<div align="center">

# asdf-git-secrets [![Build](https://github.com/mrjk/asdf-git-secrets/actions/workflows/build.yml/badge.svg)](https://github.com/mrjk/asdf-git-secrets/actions/workflows/build.yml) [![Lint](https://github.com/mrjk/asdf-git-secrets/actions/workflows/lint.yml/badge.svg)](https://github.com/mrjk/asdf-git-secrets/actions/workflows/lint.yml)

[git-secrets](https://github.com/mrjk/asdf-git-secrets) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add git-secrets
# or
asdf plugin add git-secrets https://github.com/mrjk/asdf-git-secrets.git
```

git-secrets:

```shell
# Show all installable versions
asdf list-all git-secrets

# Install specific version
asdf install git-secrets latest

# Set a version globally (on your ~/.tool-versions file)
asdf global git-secrets latest

# Now git-secrets commands are available
git-secrets --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrjk/asdf-git-secrets/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mrjk](https://github.com/mrjk/)
