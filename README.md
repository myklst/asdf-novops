<div align="center">

# asdf-novops [![Build](https://github.com/myklst/asdf-novops/actions/workflows/build.yml/badge.svg)](https://github.com/myklst/asdf-novops/actions/workflows/build.yml) [![Lint](https://github.com/myklst/asdf-novops/actions/workflows/lint.yml/badge.svg)](https://github.com/myklst/asdf-novops/actions/workflows/lint.yml)

[novops](https://github.com/PierreBeucher/novops) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `zip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add novops
# or
asdf plugin add novops https://github.com/myklst/asdf-novops.git
```

novops:

```shell
# Show all installable versions
asdf list-all novops

# Install specific version
asdf install novops latest

# Set a version globally (on your ~/.tool-versions file)
asdf global novops latest

# Now novops commands are available
novops help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/myklst/asdf-novops/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [HaloGithub](https://github.com/myklst/)
