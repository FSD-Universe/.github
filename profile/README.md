# **FSD Universe**

## **构建下一代飞行模拟基础设施**

FSD Universe 是一个专注于飞行模拟联机服务端及其生态系统的开源组织。

我们通过现代化的技术栈，推动飞行模拟联机技术向高性能、高可用性架构演进。

这里是以 SimpleFSD 项目为核心的开发阵地，我们正在构建一个模块化、可扩展的飞行模拟后端生态系统。

---

## 🎯 **项目列表**

### **1. SimpleFSD - 现代化的全功能FSD服务器**
[![SimpleFSD](https://img.shields.io/github/v/release/FSD-Universe/SimpleFSD?label=SimpleFSD&logo=go)](https://github.com/FSD-Universe/SimpleFSD)

组织的旗舰项目，采用 Go 语言编写的高性能飞行模拟联机服务器。

- 全面协议支持：完整实现 FSD Version 3.000 Draft 9，兼容 VATSIM(TOKEN) 及 VATSIM2022 协议
- 专业级特性：智能计划同步与锁定、增强的管制员信息、高频率 VisualPosition 更新（支持0.2秒/次）
- 多协议网关：集成传统TCP FSD、全功能HTTP API服务器和 WebSocket，为现代应用提供无缝连接
- 持续架构演进：处于快速迭代期，为追求卓越性能而不懈重构

### **2. SimpleFSD-Lite - 极致精简的核心FSD**
[![Lite](https://img.shields.io/github/v/release/FSD-Universe/SimpleFSD-Lite?label=SimpleFSD-Lite&logo=go)](https://github.com/FSD-Universe/SimpleFSD-Lite)

专为轻量与稳定部署设计的版本，保留核心FSD协议实现，是纯联飞服务器的理想选择。

### **3. MetarService - METAR和TAF数据融合服务**
[![METAR](https://img.shields.io/github/v/release/FSD-Universe/metar-service?label=MetarService&logo=go)](https://github.com/FSD-Universe/metar-service)

---

## 🚀 **技术哲学**

*   **性能为先**: 利用 Go 语言的原生高并发特性，旨在支撑大规模联飞活动。
*   **模块化设计**: 我们坚信微服务与模块化是构建复杂且稳定系统的基础。SimpleFSD 的全功能设计是其起点，未来我们将把更多功能拆分为独立的微服务。
*   **开放与透明**: 所有项目均采用宽松的 **MIT 协议**，无任何附加条款，鼓励社区自由使用、修改和分发。
*   **实践驱动**: 我们的特性来源于实际运营需求，确保每一个功能都切实有用。

## 🌱 **生态与未来**

当前，我们正专注于夯实 **SimpleFSD** 核心。以此为基础，FSD Universe 的蓝图正在徐徐展开：

*   **微服务生态**: 规划中的独立服务包括但不限于：专用的语音中继、数据持久化与分析、AI交通生成等。
*   **衍生工具**: 基于强大的HTTP API和WebSocket，开发现代化的Web雷达客户端等。

## 👥 **加入我们**

我们不是一个只有规划的组织，而是一个有**活跃代码产出**的社区。如果你：

*  是一名**Go开发者**，对高并发网络服务感兴趣。
*  是一名**飞行模拟爱好者**，了解联飞协议并有改进想法。
*  或者只是觉得：“哇，这实在是太酷了”。

我们诚挚邀请你参与进来。你可以通过以下方式开始：

1.  **试用与反馈**: 下载 [SimpleFSD](https://github.com/Flyleague-Collection/SimpleFSD/releases/latest) 的最新版本进行测试。
2.  **报告问题**: 在 GitHub 上提交你遇到的 Bug 或功能建议。
3.  **贡献代码**: 欢迎提交 Pull Request。

**让我们一起，从重构一个FSD开始，共同构建飞行模拟的未来。**

## 💝 支持我们
### ✨ 项目初心
FSD Universe 是一个完全免费、开源的技术共享项目

我们坚信：

开源共享能让模拟飞行社区更加繁荣

我们承诺：

所有的代码、文档、方案都永久免费开放，这份初心永远不会改变

### 🤔 为什么开通赞助？
有些热心的朋友询问：“你们的项目帮了我很多，能不能赞助支持一下？”

经过考虑，我们开通了这个渠道，但需要明确：

🚫 赞助 ≠ 购买服务
✅ 赞助 = 请开发者喝杯咖啡，说声谢谢

### ☕ 赞助将用于什么？
如果你的赞助让我们惊喜，我们会用于：

维持项目活力：服务器、域名等基础费用

改善开发体验：换个更舒服的键盘，买更多咖啡

激励贡献者：给核心贡献者发个小红包，表达感谢

社区活动：偶尔组织个线上分享会什么的

### 🎯 如何赞助？
如果你真的觉得这个项目对你有帮助，并且想鼓励我们继续下去：

[爱发电链接](https://afdian.com/a/half_nothing)

任何金额都是一份珍贵的心意 ❤️

### 🌟 其他支持方式
如果你暂时不方便赞助，这些方式同样能给我们巨大动力：

给项目点个 Star ⭐ - 这是最好的“点赞”

分享给更多飞友 📢 - 让更多人受益

反馈使用体验 💬 - 帮助我们改进

参与贡献 🔧 - 提交PR、完善文档、帮助新手

### 💌 最后想说
无论你是否赞助，我们都衷心感谢你使用这个项目。看到我们的工作能帮助到其他飞行爱好者，这就是最大的成就感。

保持热爱，一起飞行！ 🛫✨

---
**组织关键词:** `flight-simulation` `fsd` `vatsim` `golang` `high-performance` `open-source` `atc` `multi-protocol` `websocket` `api-server`
