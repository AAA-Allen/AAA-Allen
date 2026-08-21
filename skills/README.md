# 🤖 Skills / 给 Agent 的 Skills

> ✅ 我沉淀的 Skill 已迁至**独立仓库**：[AAA-Allen/FIH-skills](https://github.com/AAA-Allen/FIH-skills)
> Dedicated skills now live in their own repo: [AAA-Allen/FIH-skills](https://github.com/AAA-Allen/FIH-skills).

本页面仅作导航索引，实际 Skill 定义以独立仓库为准。
This page is just a pointer; the actual skill definitions live in the repo above.

## 已收录的 Skills / Included skills

| Skill | 说明 / What | 入口 |
| --- | --- | --- |
| `continew-add-filetype` | 给 ContiNew-Admin 新增文件类型 / 追加后缀映射 | [SKILL.md →](https://github.com/AAA-Allen/FIH-skills/blob/main/continew-add-filetype/SKILL.md) |
| `continew-remove-app` | 一键移除 ContiNew-Admin 「开放平台-应用管理」模块（可回滚） | [SKILL.md →](https://github.com/AAA-Allen/FIH-skills/blob/main/continew-remove-app/SKILL.md) |
| `yunxiao-devops` | 云效（阿里云 DevOps）全流程自动化 | [SKILL.md →](https://github.com/AAA-Allen/FIH-skills/blob/main/yunxiao-devops/SKILL.md) |

## 结构约定 / Convention

每个 Skill 独立目录：`SKILL.md`（frontmatter 触发描述 + 步骤）+ `scripts/` + `references/`。
Agent 通过 `SKILL.md` 的 `description` 触发调用。可克隆仓库或通过 URL 直接加载。

---
← 返回导航首页 / Back to [home](../README.md)