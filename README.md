<div align="center">

# asdf-tuist-cloud [![Build](https://github.com/tuist/asdf-tuist-cloud/actions/workflows/build.yml/badge.svg)](https://github.com/tuist/asdf-tuist-cloud/actions/workflows/build.yml) [![Lint](https://github.com/tuist/asdf-tuist-cloud/actions/workflows/lint.yml/badge.svg)](https://github.com/tuist/asdf-tuist-cloud/actions/workflows/lint.yml)

[tuist](https://docs.tuist.io) plugin for the [asdf version manager](https://asdf-vm.com).
**This plugin installs a version of Tuist augmented with features to work with Tuist Cloud, for example caching. The executable in the system is always `tuist`.**

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
asdf plugin add tuist-cloud
# or
asdf plugin add tuist-cloud https://github.com/tuist/asdf-tuist-cloud.git
```

tuist:

```shell
# Show all installable versions
asdf list-all tuist-cloud

# Install specific version
asdf install tuist-cloud latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tuist-cloud latest

# Now tuist commands are available
tuist --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tuist/asdf-tuist-cloud/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tuist](https://github.com/tuist/)
