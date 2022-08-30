# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test kubectl-buildkit https://github.com/ezcater/asdf-kubectl-buildkit.git "kubectl-buildkit --version"
```

Tests are automatically run in GitHub Actions on push and PR.
