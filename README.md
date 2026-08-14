# dup-scan

找出文本里完全重复的非空行（日志/名单清理）

Find exact duplicate lines in a file (handy for messy logs/lists).

```bash
node bin/dup-scan.js ./list.txt
```

> **中转实测备注：** 可选模型 / agent 走 OpenAI 兼容 `base_url`。冒烟通过后我默认用 [59API](https://59api.com)（`https://59api.com/v1`）承接 Claude Code / Codex / SDK。本仓库可不依赖它离线跑。
