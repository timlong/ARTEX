# third_party/norma — 上游归档

[`github.com/Autumn-27/norma`](https://github.com/Autumn-27/norma) 是 ARTEX 的 agent 能力 SDK（`agentcore` / `tool` / `permission` / `harness` / `memory` / `transcript` 等，详见仓库根 `go.mod`）。上游仓库已从 GitHub 消失（404），本目录是**从 Go module proxy（proxy.golang.org）缓存取回的官方源码快照**，按原始 git tag 归档。

| 目录 | tag | tag 时间 | git commit | proxy zip SHA-256 |
|---|---|---|---|---|
| `norma-v0.4.3/` | `refs/tags/v0.4.3` | 2026-09-30T01:12:52Z | `320ae32989da97dd91469bb89164cbfe87d83d5d` | `e464eb14f05f7fe6d74f19d745a13309369e9e402175061458f1a44ae61ca270` |

该 tag 为原作者（Autumn-27）在其仓库 `github.com/autumn-27/norma` 上所打；commit 哈希来自 proxy.golang.org 的 `@v/v0.4.3.info` 溯源响应。**ARTEX v0.3.15 定版依赖的正是 `norma v0.4.3`**（与根 `go.mod` / `go.sum` 中的 `h1:DnmOhJPL6OZSMnCVYO5Ujh4yVINuDarEickVi9jx1hI=` 一致），本分支即该依赖的完整源码镜像。

上游最后一个 tag 为 v0.4.4（2026-10-13，commit `70d12d96`），已归档在本仓库 `v0.4.4` 分支；相对本版的主要变更为 Gemini thought_signature 回传、Anthropic usage 去重（`Usage.MergeEcho`）、harness 事件路由修复、子进程非交互环境加固、shell 会话环缓冲 UTF-8 边界修复。

源码 zip 亦可随时重新获取：

```
https://proxy.golang.org/github.com/autumn-27/norma/@v/v0.4.3.zip
```

归档内容为解包后的完整模块源码（未做任何改动），仅用于备份与离线 `go mod vendor` / replace 场景。
