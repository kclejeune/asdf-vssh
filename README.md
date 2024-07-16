<div align="center">

# asdf-vssh [![Build](https://github.com/kclejeune/asdf-vssh/actions/workflows/build.yml/badge.svg)](https://github.com/kclejeune/asdf-vssh/actions/workflows/build.yml) [![Lint](https://github.com/kclejeune/asdf-vssh/actions/workflows/lint.yml/badge.svg)](https://github.com/kclejeune/asdf-vssh/actions/workflows/lint.yml)

[vssh](https://github.com/isometry/vault-ssh-plus) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add vssh
# or
asdf plugin add vssh https://github.com/kclejeune/asdf-vssh.git
```

vssh:

```shell
# Show all installable versions
asdf list-all vssh

# Install specific version
asdf install vssh latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vssh latest

# Now vssh commands are available
vssh --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kclejeune/asdf-vssh/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Kennan LeJeune](https://github.com/kclejeune/)
