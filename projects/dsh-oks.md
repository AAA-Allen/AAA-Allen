# dsh-oks

> DeepSeek Harness 插件：在 DSH Web UI 中连接本地 Open Knowledge Studio（OKS）知识库，提供召回、知识库浏览与可视化设置。

- 🌐 仓库 / Repo：<https://github.com/AAA-Allen/dsh-oks> · ![stars](https://img.shields.io/github/stars/AAA-Allen/dsh-oks?style=social)
- 🗓 状态 / Status：活跃开发中 / Active

## 技术栈 / Stack

`TypeScript` · `Node.js ≥ 22` · DSH `0.1.0-rc.8` · OKS CLI

## 功能 / Features

- **自动召回**：每轮 Agent 对话开始前按配置进行 OKS 召回，可在面板中关闭
- **工具集**：`oks_recall` · `oks_status` · `oks_wiki_use` · `oks_metrics` · `oks_inject_stats` · `oks_inject_feedback`
- **设置面板**：在 DSH Web 中提供中文 OKS 卡片，并把设置写回 OKS 配置
- **知识浏览**：浏览本地知识库的 Wiki、待审核 Draft 与 Raw Bundle，支持筛选、搜索、详情查看与刷新
- **诊断**：对未安装 OKS、未配置知识库、目录结构不完整等情况给出明确提示，不静默创建或迁移知识库

## 说明 / Notes

- 不复制或托管知识数据：调用本机 `oks` CLI，读取已配置的本地 OKS 目录。
- 可选搭配 `dsh-better-sidebar` 获得可停靠侧边栏与 Wiki / Raw 浏览器入口；生产环境建议固定 tag 或 commit 版本。

---

← 返回 [项目索引](README.md) · 返回 [导航首页](../README.md)
