<div align="center">

# asdf-upt [![Build](https://github.com/ORCID/asdf-upt/actions/workflows/build.yml/badge.svg)](https://github.com/ORCID/asdf-upt/actions/workflows/build.yml) [![Lint](https://github.com/ORCID/asdf-upt/actions/workflows/lint.yml/badge.svg)](https://github.com/ORCID/asdf-upt/actions/workflows/lint.yml)


[upt](https://github.com/sigoden/upt) plugin for the [asdf version manager](https://asdf-vm.com).

</div>


# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add upt https://github.com/ORCID/asdf-upt.git
```

upt:

```shell
# Show all installable versions
asdf list-all upt

# Install specific version
asdf install upt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global upt latest

# Now upt commands are available
upt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

