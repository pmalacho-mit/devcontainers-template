# devcontainers-template

This repository is intended to be used as a GitHub template for projects that rely on Dev Containers.

It includes the [devcontainers-suede](https://github.com/pmalacho-mit/devcontainers-suede) utility pre-installed so new repositories can quickly adopt a consistent, ready-to-use devcontainer setup.

By default, the [`devcontainers-suede/common.json`](./devcontainers-suede/common.json) devcontainer configuration is used.

If you want to refresh or change that configuration, run:

```bash
devcontainers-suede/install.sh --force
```