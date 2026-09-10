# argo-rollouts

[English version](./README.md)

Progressive Delivery for Kubernetes

![argo-rollouts](https://repo.x-cmd.io/argo-rollouts.svg?lang=zh)

## 安装

```sh
x install argo-rollouts
```

## 代码规模

合计: **333,291** 行代码（覆盖前 5 种语言、共 **751** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 162,974 | 8,868 | 15,243 | 402 |
| Yaml | 120,784 | 316 | 1,962 | 290 |
| Json | 39,090 | 0 | 1 | 8 |
| TypeScript | 3,648 | 7,442 | 207 | 15 |
| Tsx | 3,422 | 26 | 336 | 36 |

## OpenSSF Scorecard 评分

总评分: **7.2 / 10**

评分最低的几项:

- **Security-Policy** (3/10) — security policy file detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed

## 源代码

- **上游仓库**: <https://github.com/argoproj/argo-rollouts>
- **官网**: <https://argo-rollouts.readthedocs.io/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.10.0` (2026-08-27)
- **最近提交**: 2026-09-10
- **Release 含资产**: 15 个

## 流行度

- **Star**: 3,575 · **Fork**: 1,211 · **开放 issue**: 1,513 · **贡献者**: 462

## 累计统计

- **发布数**: 84 · **已合并 PR**: 2124 · **开放 PR**: 162 · **已关闭 issue**: 1018 · **开放 issue**: 495 · **提交数**: 2258

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 1 | 24 | 20 | 1 | 4 | 30 |
| last60d | 2026-07-12 | 2 | 86 | 48 | 10 | 17 | 95 |
| 90d | 2026-06-12 | 3 | 108 | 55 | 16 | 25 | 120 |
| last180d | 2026-03-14 | 4 | 152 | 71 | 30 | 51 | 156 |
| 360d | 2025-09-15 | 7 | 231 | 89 | 46 | 86 | 230 |
| last720d | 2024-09-20 | 13 | 473 | 119 | 111 | 174 | 464 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
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

## 发行版状态

在 [repology.org](https://repology.org/project/argo-rollouts) 上共有 **7** 个发行版报告此项目。**1** 个 ✅ 已是最新上游版本，**6** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Nix unstable | `1.10.0` | ✅ latest |

## 改进这些数据

argo-rollouts 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `argo-rollouts` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/argo-rollouts.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T21:42:02Z._
