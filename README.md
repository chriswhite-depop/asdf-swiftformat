<div align="center">

# asdf-swiftformat [![Build](https://github.com/chriswhite-depop/asdf-swiftformat/actions/workflows/build.yml/badge.svg)](https://github.com/chriswhite-depop/asdf-swiftformat/actions/workflows/build.yml) [![Lint](https://github.com/chriswhite-depop/asdf-swiftformat/actions/workflows/lint.yml/badge.svg)](https://github.com/chriswhite-depop/asdf-swiftformat/actions/workflows/lint.yml)

[swiftformat](https://github.com/chriswhite-depop/swiftformat) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add swiftformat
# or
asdf plugin add swiftformat https://github.com/chriswhite-depop/asdf-swiftformat.git
```

swiftformat:

```shell
# Show all installable versions
asdf list-all swiftformat

# Install specific version
asdf install swiftformat latest

# Set a version globally (on your ~/.tool-versions file)
asdf global swiftformat latest

# Now swiftformat commands are available
swiftformat --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chriswhite-depop/asdf-swiftformat/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris White](https://github.com/chriswhite-depop/)
