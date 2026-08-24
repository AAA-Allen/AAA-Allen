# Boat

> 一站式管理自己名下的**项目**与**运维资产**：项目任务 + 服务器/服务/域名/凭据台账统一收纳，支持一键 SSH 自动部署。

- 🌐 仓库 / Repo：<https://github.com/AAA-Allen/Boat> · ![stars](https://img.shields.io/github/stars/AAA-Allen/Boat?style=social)
- 🗓 状态 / Status：活跃开发中 / Active

## 技术栈 / Stack

`NestJS` · `TypeORM` · `MySQL 8` · `Node.js ≥ 18` · `Vue 3` · `Vite` · `TypeScript` · `Element Plus` · `Pinia` · `SSH2`

## 功能 / Features

- **项目管理**：项目、任务、里程碑、状态与进度看板
- **运维台账**：服务器、应用/服务、域名、环境、凭据的信息化管理
- **自动上线**：为应用配置 Git 仓库，一键 SSH 部署到自有服务器，PM2 运行并留痕实时日志
- **仪表盘**：全局统计概览，一屏看清所有资产
- **认证**：管理员登录、JWT 鉴权、密码加密

## 说明 / Notes

- 运维侧分两部分：台账式管理（不做真实服务器 CPU/内存状态采集）+ 针对自有应用的 SSH 自动部署（拉代码 → 构建 → PM2）。
- 服务器监控采集后续可扩展 Agent/SSH。
- 默认管理员 `admin / admin123`，登录后请及时修改密码。

---

← 返回 [项目索引](README.md) · 返回 [导航首页](../README.md)