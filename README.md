<div align="center">

# asdf-air [![Build](https://github.com/localdee/asdf-air/actions/workflows/build.yml/badge.svg)](https://github.com/localdee/asdf-air/actions/workflows/build.yml) [![Lint](https://github.com/localdee/asdf-air/actions/workflows/lint.yml/badge.svg)](https://github.com/localdee/asdf-air/actions/workflows/lint.yml)

[air](https://github.com/air-verse/air) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add locald-air https://github.com/localdee/asdf-air.git
```

locald-air:

```shell
# Show all installable versions
asdf list-all locald-air

# Install specific version
asdf install locald-air latest

# Set a version globally (on your ~/.tool-versions file)
asdf global locald-air latest

# Now air commands are available
air -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/localdee/asdf-air/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [locald.sh](https://github.com/localdee/)
