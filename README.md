<div align="center">

# asdf-packetbeat [![Build](https://github.com/NeoHsu/asdf-packetbeat/actions/workflows/build.yml/badge.svg)](https://github.com/NeoHsu/asdf-packetbeat/actions/workflows/build.yml) [![Lint](https://github.com/NeoHsu/asdf-packetbeat/actions/workflows/lint.yml/badge.svg)](https://github.com/NeoHsu/asdf-packetbeat/actions/workflows/lint.yml)


[packetbeat](https://www.elastic.co/guide/en/beats/packetbeat/current/index.html) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add packetbeat
# or
asdf plugin add packetbeat https://github.com/NeoHsu/asdf-packetbeat.git
```

packetbeat:

```shell
# Show all installable versions
asdf list-all packetbeat

# Install specific version
asdf install packetbeat latest

# Set a version globally (on your ~/.tool-versions file)
asdf global packetbeat latest

# Now packetbeat commands are available
packetbeat --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/NeoHsu/asdf-packetbeat/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Neo Hsu](https://github.com/NeoHsu/)
