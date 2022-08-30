<div align="center">

# asdf-kubectl-buildkit [![Build](https://github.com/ezcater/asdf-kubectl-buildkit/actions/workflows/build.yml/badge.svg)](https://github.com/ezcater/asdf-kubectl-buildkit/actions/workflows/build.yml) [![Lint](https://github.com/ezcater/asdf-kubectl-buildkit/actions/workflows/lint.yml/badge.svg)](https://github.com/ezcater/asdf-kubectl-buildkit/actions/workflows/lint.yml)


[kubectl-buildkit](https://github.com/vmware-tanzu/buildkit-cli-for-kubectl) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kubectl-buildkit
# or
asdf plugin add kubectl-buildkit https://github.com/ezcater/asdf-kubectl-buildkit.git
```

kubectl-buildkit:

```shell
# Show all installable versions
asdf list-all kubectl-buildkit

# Install specific version
asdf install kubectl-buildkit latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubectl-buildkit latest

# Now kubectl-buildkit commands are available
kubectl-buildkit --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ezcater/asdf-kubectl-buildkit/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ezCater](https://github.com/ezcater/)
