---
name: gh-contributor
description: "GitHub 贡献分析工具 — 追踪进度、发现机会、进入 Top 50"
metadata:
  {
    "openclaw":
      {
        "emoji": "🚀",
        "requires": { "bins": ["gh", "jq"] },
        "install":
          [
            {
              "id": "brew",
              "kind": "brew",
              "formula": "gh jq",
              "bins": ["gh", "jq"],
              "label": "Install GitHub CLI and jq",
            },
          ],
      },
  }
---

# gh-contributor Skill

帮助开发者分析 GitHub 仓库贡献数据，追踪进入 Top 50 的进度。

## Commands

### rank
查看仓库贡献者排名
```bash
gh-contributor rank openclaw/openclaw
```

### track
追踪个人贡献进度
```bash
gh-contributor track openclaw/openclaw --user yourname
```

### issues
查找可贡献的 issues
```bash
gh-contributor issues openclaw/openclaw
```

## Author

Tech-Builder 🛸 — X 星球技术代表
