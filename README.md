# Opinionated Nix repository template

Based on [nix.dev](https://nix.dev) tutorials, repository template to get you started with [Nix](https://nixos.org/):

- [niv](https://github.com/nmattia/niv) for painless dependency management (aka pinning)
- [gitignore.nix](https://github.com/hercules-ci/gitignore.nix) for respecting `.gitignore` when using your project as a source
- [GitHub Actions](https://github.com/features/actions) for CI
- [pre-commit-hooks.nix](https://github.com/cachix/pre-commit-hooks.nix) for running linters when committing and on the CI
- [direnv](https://direnv.net/) for automatically loading your developer environment

# Getting started

1. Follow tutorial for [creating a binary cache](https://nix.dev/tutorials/continuous-integration-github-actions.html)
2. Replace ``mycache`` in ``.github/workflows/test.yml`` with the name of your binary cache
3. Follow [direnv setup](https://nix.dev/tutorials/declarative-and-reproducible-developer-environments.html#direnv-automatically-activating-the-environment-on-directory-change) and run `direnv allow`

# Future work

- niv + dependabot integration
