# third_party/norma — 上游归档

[`github.com/Autumn-27/norma`](https://github.com/Autumn-27/norma) 是 ARTEX 的 agent 能力 SDK（`agentcore` / `tool` / `permission` / `harness` / `memory` / `transcript` 等，详见仓库根 `go.mod`）。上游仓库已从 GitHub 消失（404），本目录是**从 Go module proxy（proxy.golang.org）缓存取回的官方源码快照**，按原始 git tag 归档。

| 目录 | tag | tag 时间 | git commit | proxy zip SHA-256 |
|---|---|---|---|---|
| `norma-v0.4.4/` | `refs/tags/v0.4.4` | 2026-10-13T12:46:07Z | `70d12d96de11030137b968e7637385fb09529109` | `616e1056bff366d8cc2b95bf5761435f740c559cf7b133df8216bab59d1f5d86` |
| `norma-v0.4.3/` | `refs/tags/v0.4.3` | 2026-09-30T01:12:52Z | `320ae32989da97dd91469bb89164cbfe87d83d5d` | `e464eb14f05f7fe6d74f19d745a13309369e9e402175061458f1a44ae61ca270` |

两个 tag 均为原作者（Autumn-27）在其仓库 `github.com/autumn-27/norma` 上所打；上表 commit 哈希来自 proxy.golang.org 的 `@v/<ver>.info` 溯源响应。ARTEX v0.3.15 定版依赖的是 `norma v0.4.3`（与根 `go.mod` / `go.sum` 一致）；`v0.4.4` 是上游最后一个 tag，主要变更为 Gemini thought_signature 回传、Anthropic usage 去重（`Usage.MergeEcho`）、harness 事件路由修复、子进程非交互环境加固、shell 会话环缓冲 UTF-8 边界修复。

源码 zip 亦可随时重新获取：

```
https://proxy.golang.org/github.com/autumn-27/norma/@v/v0.4.3.zip
https://proxy.golang.org/github.com/autumn-27/norma/@v/v0.4.4.zip
```

归档内容为解包后的完整模块源码（未做任何改动），仅用于备份与离线 `go mod vendor` / replace 场景。
