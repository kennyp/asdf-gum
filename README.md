<div align="center">

# asdf-gum [![Build](https://github.com/kennyp/asdf-gum/actions/workflows/build.yml/badge.svg)](https://github.com/kennyp/asdf-gum/actions/workflows/build.yml) [![Lint](https://github.com/kennyp/asdf-gum/actions/workflows/lint.yml/badge.svg)](https://github.com/kennyp/asdf-gum/actions/workflows/lint.yml)

[gum](https://github.com/charmbracelet/gum) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add gum
# or
asdf plugin add gum https://github.com/kennyp/asdf-gum.git
```

gum:

```shell
# Show all installable versions
asdf list-all gum

# Install specific version
asdf install gum latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gum latest

# Now gum commands are available
gum --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kennyp/asdf-gum/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Kenny Parnell](https://github.com/kennyp/)
