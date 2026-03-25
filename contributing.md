# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test kubeswitch https://github.com/chrisjohnson/asdf-kubeswitch --asdf-tool-version 0.9.3 "switch --help"
```

Tests are automatically run in GitHub Actions on push and PR.
