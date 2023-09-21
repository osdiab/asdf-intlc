<div align="center">

# asdf-intlc [![Build](https://github.com/osdiab/asdf-intlc/actions/workflows/build.yml/badge.svg)](https://github.com/osdiab/asdf-intlc/actions/workflows/build.yml) [![Lint](https://github.com/osdiab/asdf-intlc/actions/workflows/lint.yml/badge.svg)](https://github.com/osdiab/asdf-intlc/actions/workflows/lint.yml)

[intlc](https://github.com/unsplash/intlc) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add intlc https://github.com/osdiab/asdf-intlc.git
```

intlc:

```shell
# Show all installable versions
asdf list-all intlc

# Install specific version
asdf install intlc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global intlc latest

# Now intlc commands are available
intlc --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/osdiab/asdf-intlc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Omar Diab](https://github.com/osdiab/)
