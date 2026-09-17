# argo-rollouts

[中文版本](./README.cn.md)

Progressive Delivery for Kubernetes

![argo-rollouts](https://repo.x-cmd.io/argo-rollouts.svg)

## Install

```sh
x install argo-rollouts
```

## Code insight

Total: **334,211** lines of code across **751** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 163,616 | 8,895 | 15,281 | 402 |
| Yaml | 120,938 | 316 | 1,962 | 290 |
| Json | 39,200 | 0 | 1 | 8 |
| TypeScript | 3,653 | 7,462 | 207 | 15 |
| Tsx | 3,422 | 26 | 336 | 36 |

## OpenSSF Scorecard

Overall score: **7.2 / 10**

Lowest-scoring checks:

- **Security-Policy** (3/10) — security policy file detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/argoproj/argo-rollouts>
- **Homepage**: <https://argo-rollouts.readthedocs.io/>
- **License**: Apache-2.0

## Release

- **Latest**: `v1.10.0` (2026-08-27)
- **Last commit**: 2026-09-16
- **Assets in release**: 15

## Popularity

- **Stars**: 3,582 · **Forks**: 1,210 · **Open issues**: 1,514 · **Contributors**: 468

## Totals (cumulative)

- **Releases**: 84 · **Merged PRs**: 2137 · **Open PRs**: 151 · **Closed issues**: 1019 · **Open issues**: 495 · **Commits**: 2271

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-18 | 1 | 26 | 18 | 1 | 2 | 40 |
| last60d | 2026-07-19 | 1 | 63 | 39 | 8 | 10 | 73 |
| 90d | 2026-06-19 | 3 | 107 | 53 | 17 | 25 | 123 |
| last180d | 2026-03-21 | 3 | 150 | 67 | 31 | 49 | 160 |
| 360d | 2025-09-22 | 7 | 232 | 82 | 44 | 84 | 243 |
| last720d | 2024-09-27 | 13 | 475 | 113 | 110 | 171 | 475 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [argo-rollouts-checksums.txt](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/argo-rollouts-checksums.txt) | 504 B | `other` |
| [argo-rollouts.intoto.jsonl](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/argo-rollouts.intoto.jsonl) | 24.1 KiB | `other` |
| [dashboard-install.yaml](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/dashboard-install.yaml) | 2.7 KiB | `other` |
| [install.yaml](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/install.yaml) | 2.9 MiB | `other` |
| [kubectl-argo-rollouts-darwin-amd64](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/kubectl-argo-rollouts-darwin-amd64) | 139.1 MiB | `native/darwin/x64` |
| [kubectl-argo-rollouts-darwin-arm64](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/kubectl-argo-rollouts-darwin-arm64) | 133.8 MiB | `native/darwin/arm64` |
| [kubectl-argo-rollouts-linux-amd64](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/kubectl-argo-rollouts-linux-amd64) | 135.1 MiB | `native/linux/x64` |
| [kubectl-argo-rollouts-linux-arm64](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/kubectl-argo-rollouts-linux-arm64) | 128.7 MiB | `native/linux/arm64` |
| [kubectl-argo-rollouts-windows-amd64](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/kubectl-argo-rollouts-windows-amd64) | 136.4 MiB | `native/win/x64` |
| [namespace-install.yaml](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/namespace-install.yaml) | 7.5 KiB | `other` |
| [notifications-install.yaml](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/notifications-install.yaml) | 9.4 KiB | `other` |
| [rollout_cr_schema.json](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/rollout_cr_schema.json) | 3.8 MiB | `other` |
| [sbom.tar.gz](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/sbom.tar.gz) | 73.7 KiB | `native/unknown` |
| [sbom.tar.gz.pem](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/sbom.tar.gz.pem) | 3.3 KiB | `other` |
| [sbom.tar.gz.sig](https://github.com/argoproj/argo-rollouts/releases/download/v1.10.0/sbom.tar.gz.sig) | 96 B | `other` |

## Improve this data

Install metadata for argo-rollouts lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `argo-rollouts` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/argo-rollouts.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260917.yml` · 2026-09-17T05:21:13Z._
