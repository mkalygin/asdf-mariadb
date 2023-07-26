<div align="center">

# asdf-mariadb [![Build](https://github.com/mkalygin/asdf-mariadb/actions/workflows/build.yml/badge.svg)](https://github.com/mkalygin/asdf-mariadb/actions/workflows/build.yml) [![Lint](https://github.com/mkalygin/asdf-mariadb/actions/workflows/lint.yml/badge.svg)](https://github.com/mkalygin/asdf-mariadb/actions/workflows/lint.yml)

[mariadb](https://mariadb.org/documentation) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add mariadb
# or
asdf plugin add mariadb https://github.com/mkalygin/asdf-mariadb.git
```

mariadb:

```shell
# Show all installable versions
asdf list-all mariadb

# Install specific version
asdf install mariadb latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mariadb latest

# Now mariadb commands are available
mariadb --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mkalygin/asdf-mariadb/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Michael Kalygin](https://github.com/mkalygin/)
