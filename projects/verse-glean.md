# Verse-Glean（影海拾光）

> 视频平台知识胶囊提取系统：把泛知识短视频的「线性观看」变成「结构化留存」。

- 🌐 仓库 / Repo：<https://github.com/AAA-Allen/Verse-Glean> · ![stars](https://img.shields.io/github/stars/AAA-Allen/Verse-Glean?style=social)
- 🗓 状态 / Status：进行中（2026.05 – 2027.05，大学生创新训练计划项目）

## 技术栈 / Stack

`Python` · `FastAPI` · `MySQL` · `Redis` · `Docker Compose` · `Vue 3 + Vant` · `Kotlin + Jetpack Compose` · LLM / ASR / Embedding

## 功能 / Features

- **一键触发**：在抖音 / B 站看视频时通过分享或悬浮球触发
- **处理链路**：元数据解析 → 字幕 / ASR 转写 → 大模型提炼
- **知识胶囊**：可编辑、可语义关联的结构化产物
- **知识图谱**：胶囊汇聚为个人 3D 知识图谱
- **多端**：Android 端（分享接收、悬浮球、胶囊管理）+ Web H5 管理端

## 说明 / Notes

- monorepo 结构：`docs/`（PRD / 技术设计 / 数据库 / API / 开发计划 / 测试计划）、`backend/`（FastAPI）、`android/`（Kotlin + Compose）、`web/`（Vue 3 + Vant）
- 文档即基线：需求与接口先落 `docs/`，再进入实现。

---

← 返回 [项目索引](README.md) · 返回 [导航首页](../README.md)
