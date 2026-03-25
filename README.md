<div align="center">

# asdf-kubeswitch [![Build](https://github.com/chrisjohnson/asdf-kubeswitch/actions/workflows/build.yml/badge.svg)](https://github.com/chrisjohnson/asdf-kubeswitch/actions/workflows/build.yml) [![Lint](https://github.com/chrisjohnson/asdf-kubeswitch/actions/workflows/lint.yml/badge.svg)](https://github.com/chrisjohnson/asdf-kubeswitch/actions/workflows/lint.yml)

[kubeswitch](https://github.com/danielfoehrKn/kubeswitch) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add kubeswitch https://github.com/chrisjohnson/asdf-kubeswitch.git
```

kubeswitch:

```shell
# Show all installable versions
asdf list all kubeswitch

# Install specific version
asdf install kubeswitch latest

# Set a version globally (on your ~/.tool-versions file)
asdf set -u kubeswitch latest

# Now kubeswitch commands are available
switch --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chrisjohnson/asdf-kubeswitch/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris Johnson](https://github.com/chrisjohnson/)
