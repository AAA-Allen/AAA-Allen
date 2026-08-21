# 🤖 Skills / 给 Agent 的 Skills

这里收纳**可复用的 Agent / Skill 定义**——把我在开发中沉淀的工作流（脚手架生成、改名、功能瘦身、文档核查等）固化成 Skill，供 Claude Code 等 Agent 直接调用。
This folder collects **reusable Agent / Skill definitions** — turning the workflows I've distilled (scaffold generation, renaming, feature-slimming, doc audit…) into Skills callable by agents like Claude Code.

## 设计原则 / Design principles

- 一个 Skill 解决一类明确任务，含 `SKILL.md` 说明 + 必要的 `scripts/`、`references/`。
- 避免把敏感信息、个人文件写进 Skill。

## 当前状态 / Status

> 🚧 专属 Skills 整理中 / Dedicated skills are being organized (coming soon).

计划首批沉淀的 Skills（草案）：
- `scaffold-slim` — 从 ContiNew 类 monorepo 按 prd 做功能瘦身并改名。
- `repo-rename` — 跨包名 / artifactId / 类名 / 种子数据 / Logo 的全量改名。
- `profile-readme` — 生成双语 GitHub profile 导航页（即本仓库的来由）。

## SKILL.md 模板 / Template

```markdown
---
name: <skill-name>
description: <何时使用该 skill 的一句话触发描述 / one-line trigger>
---

# <Skill 名称>

## 适用场景 / When to use
<什么情况下调用本 skill>

## 步骤 / Steps
1. ...
2. ...

## 注意事项 / Caveats
- ...
```

> 每个 Skill 放在独立子目录：`skills/<skill-name>/SKILL.md`。

---

← 返回导航首页 / Back to [home](../README.md)
