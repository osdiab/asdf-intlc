<div align="center">

# asdf-inltc [![Build](https://github.com/osdiab/asdf-inltc/actions/workflows/build.yml/badge.svg)](https://github.com/osdiab/asdf-inltc/actions/workflows/build.yml) [![Lint](https://github.com/osdiab/asdf-inltc/actions/workflows/lint.yml/badge.svg)](https://github.com/osdiab/asdf-inltc/actions/workflows/lint.yml)

[inltc](https://github.com/unsplash/intlc) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add inltc
# or
asdf plugin add inltc https://github.com/osdiab/asdf-inltc.git
```

inltc:

```shell
# Show all installable versions
asdf list-all inltc

# Install specific version
asdf install inltc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global inltc latest

# Now inltc commands are available
intlc --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/osdiab/asdf-inltc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Omar Diab](https://github.com/osdiab/)
