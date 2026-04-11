# 🦞 OpenClaw 教程

> 基于 OpenClaw 开源项目的中文学习教程，帮助你快速了解、安装、配置和高效使用 OpenClaw 个人 AI 助手。

## 📖 教程目录

| 序号 | 文档 | 内容简介 |
|------|------|----------|
| 01 | [什么是 OpenClaw](./01-what-is-openclaw.md) | 项目概览、核心理念、功能亮点和适用人群 |
| 02 | [系统架构与核心原理](./02-architecture.md) | Gateway 架构、组件关系、Wire Protocol 和数据流 |
| 03 | [快速上手指南](./03-getting-started.md) | 安装、Onboard 向导、首次对话全流程 |
| 04 | [openclaw.json 配置详解](./04-configuration.md) | 配置文件格式、常用配置项含义与默认值 |
| 05 | [安全配置与最佳实践](./05-security.md) | 信任模型、DM 策略、工具沙箱和安全审计 |
| 06 | [模型与 Provider 配置](./06-models-and-providers.md) | 模型选择、Fallback 链、Provider 配置和切换 |
| 07 | [工具与 Skills 使用指南](./07-tools-and-skills.md) | 内置工具清单、Skills 加载机制和常用 Skills 推荐 |
| 08 | [Token 节省与上下文管理](./08-token-saving.md) | 上下文构成、Compaction 原理和节省 Token 实用技巧 |
| 09 | [Agent 配置与多 Agent 实践](./09-agent-config.md) | 单 Agent 配置、多 Agent 路由和实战案例 |
| 10 | [消息渠道接入指南](./10-channels.md) | 内置渠道、插件渠道和典型配置示例 |
| 11 | [不同用户场景最佳配置推荐](./11-best-practices.md) | 个人开发者、团队、安全敏感场景配置参考 |
| 12 | [多 Agent 软件开发团队实施方案](./12-multi-agent-dev-team.md) | 6 Agent 团队结构、Lead 编排模式、完整配置和 Skill 实现 |

## 🎯 适合谁阅读

- **想了解 OpenClaw 是什么** → 从 [01-什么是 OpenClaw](./01-what-is-openclaw.md) 开始
- **想快速跑起来** → 直达 [03-快速上手指南](./03-getting-started.md)
- **想深入配置** → 阅读 [04-配置详解](./04-configuration.md) + [05-安全配置](./05-security.md)
- **想节省 Token 费用** → 必读 [08-Token 节省](./08-token-saving.md)
- **想搭建多 Agent 系统** → 参见 [09-Agent 配置](./09-agent-config.md) 和 [12-多 Agent 开发团队](./12-multi-agent-dev-team.md)
- **想连接各种聊天平台** → 参见 [10-渠道接入](./10-channels.md)

## 📋 前置要求

- **Node.js**：推荐 Node 24，也支持 Node 22 LTS（22.14+）
- **操作系统**：macOS / Linux / Windows（推荐使用 WSL2）
- **模型 API Key**：至少一个来自 Anthropic、OpenAI、Google 等 Provider 的 API Key

## 🔗 官方资源

| 资源 | 链接 |
|------|------|
| 官网 | <https://openclaw.ai> |
| 文档 | <https://docs.openclaw.ai> |
| GitHub | <https://github.com/openclaw/openclaw> |
| Discord | <https://discord.gg/clawd> |
| DeepWiki | <https://deepwiki.com/openclaw/openclaw> |

## ⚠️ 声明

本教程内容完全基于 OpenClaw 开源仓库的源代码和官方文档编写，所有描述均来自项目实际代码和文档事实，不含臆想内容。如有出入，请以 [官方文档](https://docs.openclaw.ai) 为准。
