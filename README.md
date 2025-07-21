# metallb

<!-- More info: https://github.com/Ileriayo/markdown-badges -->
<!-- More info: https://shields.io/badges -->
<!-- More info: https://badgesgenerator.com/ -->

[![GitLab Sync](https://img.shields.io/badge/gitlab_sync-metallb-blue?style=for-the-badge&logo=gitlab)](https://gitlab-internal.spirit-dev.net/github-mirror/helm-metallb) <!-- markdownlint-disable MD041 -->
[![GitHub Mirror](https://img.shields.io/badge/github_mirror-metallb-blue?style=for-the-badge&logo=github)](https://github.com/spirit-dev/helm-metallb)
[![App Status](https://argocd-internal.spirit-dev.net/api/badge?name=metallb-turingpi&revision=true&showAppName=true)](https://argocd-internal.spirit-dev.net/applications/metallb-turingpi)

<!--TOC-->

- [Installation process](#installation-process)

<!--TOC-->

## Installation process

The installation is entirely managed by Argocd.

A `Makefile` is present here to ease the first and one-time deployment or in case of an issue.
The installation should be done in two steps:

```shell
#> make dry-run ENV=<ENV>
#> make install ENV=<ENV>
```
