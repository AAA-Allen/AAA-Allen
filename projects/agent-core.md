# agent-core

> 轻量、可追踪、可扩展的 Agent 工作流运行框架：不绑定模型、不绑定业务，提供统一的 Agent 运行底座。

- 🌐 仓库 / Repo：<https://github.com/AAA-Allen/agent-core> · ![stars](https://img.shields.io/github/stars/AAA-Allen/agent-core?style=social)
- 🗓 状态 / Status：活跃开发中 / Active

## 技术栈 / Stack

`Python ≥ 3.10` · OpenAI 兼容模型适配器 · 纯标准库 HTTP API（无 Web 框架依赖）· SSE · 内置浏览器工作台

## 功能 / Features

- **运行时**：顺序工作流与 Graph 图执行、条件路由、节点状态更新、子 Agent 委派；模型 / 工具 / 记忆按协议注入
- **模型与工具**：注册 Python 函数或外部业务 API，参数校验与错误原因码，模型自主工具调用循环，Harness 调用预算（限制模型轮次与工具调用次数）
- **可靠性**：`COMPLETED / BLOCKED / FAILED / CANCELED` 状态、节点级 Trace、协作式取消、节点边界超时与最大步数限制
- **可恢复**：运行结果、生命周期事件与 checkpoint 持久化，显式恢复，不把模拟结果当成真实执行证据
- **工作台**：任务提交、时间线、Trace、拓扑与结果查看；同步 / 后台运行 + SSE 事件流；运行查询、取消、恢复与会话记忆
- **双形态**：`agent_core` 完整运行时；`agent_lite` 只保留对话、历史和工具循环的极简外壳

## 说明 / Notes

- 分工清晰：模型负责理解与决策，工具负责真实业务操作，业务服务负责数据与规则，框架负责编排、状态与可观测性。
- 服务端会话记忆存放在运行目录的 `sessions/`，单实例文件存储，暂不提供跨实例共享或长期记忆治理。

---

← 返回 [项目索引](README.md) · 返回 [导航首页](../README.md)
