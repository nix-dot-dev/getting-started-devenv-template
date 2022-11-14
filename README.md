# Opinionated Nix repository template

Based on [devenv.sh](https://devenv.sh) and [Nix basics tutorial](https://nix.dev/tutorials/nix-language) (1-2 hour primer),
this is a simple to get started.

## Getting started

1. [Install Nix and ``devenv``](https://devenv.sh/getting-started/)
1. Follow tutorial for [creating a binary cache](https://nix.dev/tutorials/continuous-integration-github-actions.html)
2. Replace ``nix-getting-started-template`` in ``.github/workflows/test.yml`` with the name of your binary cache

## Using the project

Follow [direnv setup](https://devenv.sh/automatic-shell-activation/) and run `direnv allow`.
