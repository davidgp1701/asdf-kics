<div align="center">

# asdf-kics [![Build](https://github.com/davidgp1701/asdf-kics/actions/workflows/build.yml/badge.svg)](https://github.com/davidgp1701/asdf-kics/actions/workflows/build.yml) [![Lint](https://github.com/davidgp1701/asdf-kics/actions/workflows/lint.yml/badge.svg)](https://github.com/davidgp1701/asdf-kics/actions/workflows/lint.yml)


[kics](https://github.com/anchore/kics) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.
- `tar`: generic POSIX utility for Linux/Mac environments.

# Install

Plugin:

```shell
asdf plugin add kics
# or
asdf plugin add kics https://github.com/davidgp1701/asdf-kics.git
```

kics:

```shell
# Show all installable versions
asdf list-all kics

# Install specific version
asdf install kics latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kics latest

# Now kics commands are available
kics version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/davidgp1701/asdf-kics/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David Garcia Perez](https://github.com/davidgp1701/)
