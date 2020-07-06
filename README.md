# Opinionated Nix repository template

Based on https://nix.dev/ tutorials, repository template to get you started with [Nix](https://nixos.org/):

- [niv](https://github.com/nmattia/niv) for painless dependency management (aka pinning)
- [gitignore.nix](https://github.com/hercules-ci/gitignore.nix) for respecting `.gitignore` when working on git projects
- [GitHub Actions](https://github.com/features/actions) for CI
- [pre-commit-hooks.nix](https://github.com/cachix/pre-commit-hooks.nix) for running linters during committing and CI
- [direnv](https://direnv.net/) for automatically loading your developer environment

# Getting started

1. Follow tutorial for [creating a binary cache](TODO)
2. Replace ``mycache`` in ``.github/workflows/test.yml`` with the name of your binary cache
3. Run `direnv allow`

# Future work

- niv + dependabot integration
- bump niv via cronjob