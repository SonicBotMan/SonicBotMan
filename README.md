<h1 align="center">Hi, I'm Orion <a href="https://pmparker.net/">(PM Parker)</a></h1>

<p align="center">
  <a href="https://pmparker.net/"><img src="https://img.shields.io/badge/Blog-pmparker.net-3FD97F?style=flat-square&logo=aboutdotme&logoColor=white" alt="Blog"/></a>
  <a href="https://wen.pmparker.net/"><img src="https://img.shields.io/badge/Live-观澜态势看板-2563EB?style=flat-square" alt="观澜"/></a>
  <a href="https://xagent.icu/"><img src="https://img.shields.io/badge/Site-xagent.icu-FF4D4D?style=flat-square" alt="xagent.icu"/></a>
  <img src="https://img.shields.io/badge/Role-PM→AI Builder-8B5CF6?style=flat-square" alt="Role"/>
</p>

**Product Manager. Open Source Engineer. AI Workflow Architect.**

十年产品经理（百度系：安全 / 本地生活 / 内容生态 / 移动端），现在 All in AI——把 AI 当团队用，一个人跑出一条完整产品线。从下载内核（Rust）到 Agent 中间件（工作流 / 记忆 / 运维）再到应用层（情报看板 / 自动视频产线），**每个项目都是活的：有线上地址、有真实数据、有踩坑复盘。**

> What separates a compelling AI demo from a reliable AI product is an unsexy layer of engineering discipline. That's exactly what I build.

---

## 🏗️ The System — 我在搭什么

不是一堆孤立 repo，而是一个自下而上的系统：

```
📡 应用层   观澜 GUANLAN（情报看板 · 12期/日全自动视频）   ClawICU Site（运维知识库）
─────────────────────────────────────────────────
🧠 中间件   SoloFlow（工作流引擎）  LobsterPress（认知记忆）  ClawICU（急救系统）
─────────────────────────────────────────────────
⚙️ 基础层   Peregrine（下载内核）   OpenClaw Portable（便携运行时）
```

---

## ⚡ Featured Projects

### [🦅 Peregrine](https://github.com/SonicBotMan/peregrine) `Rust` `Tauri 2` — *最新*

**Linux 下载器：IDM 级多段加速内核 + AI Agent 原生 MCP 调度。**

- 自研 Rust 内核：分段下载 + 动态重平衡，慢链路实测 **3.1× 加速**；`kill -9` 级断点续传
- **MCP 一等公民**：Claude / 任意 Agent 直接管理下载任务（10 工具 · 3 类资源 · 实时事件）
- 一个 headless daemon，CLI / GUI / MCP 三端薄客户端同构——协议即插件

<br/>

### [⚡ SoloFlow](https://github.com/SonicBotMan/SoloFlow) ![Stars](https://img.shields.io/github/stars/SonicBotMan/SoloFlow?style=flat-square&color=yellow) `Python`

**AI Agent 的 DAG 工作流引擎——让多步任务结构化、可观测、可重试，再自动进化成技能。**

- DAG + FSM 双引擎：依赖排序、并行执行、状态机校验
- 三层记忆：Working (LRU) / Episodic (SQLite FTS5) / Semantic（模板）
- **Skill Evolution**：观察 → 检测重复模式 → 打包 → 评分 → 安装
- **96 tests passing，零运行时依赖**

<br/>

### [🦞 LobsterPress](https://github.com/SonicBotMan/lobster-press) ![Stars](https://img.shields.io/github/stars/SonicBotMan/lobster-press?style=flat-square&color=yellow) ![npm](https://img.shields.io/npm/v/@sonicbotman/lobster-press?style=flat-square&color=cb3837) `Python`

**AI Agent 认知记忆引擎：SQLite 单文件，零向量库依赖。**

- 滑动窗口会永久丢上下文，LobsterPress 把每轮对话存进本地 SQLite
- 认知科学策略：DAG 无损压缩 + 遗忘曲线 + 语义笔记
- 原始消息永不删除，任何摘要都可回溯

<br/>

### [🏥 ClawICU](https://github.com/SonicBotMan/clawicu) ![Stars](https://img.shields.io/github/stars/SonicBotMan/clawicu?style=flat-square&color=yellow) `Shell` → [xagent.icu](https://xagent.icu/)

**OpenClaw 急救系统：一条命令，诊断、修复、复活。**

- **20** 项诊断检查 · **6** 阶段救援协议 · **25** 篇线上故障指南
- Next.js 静态站 + SEO + SOS 分享页，支持 `curl | sh` 一键救援

<br/>

### [🔌 openclaw-portable](https://github.com/SonicBotMan/openclaw-portable) ![Stars](https://img.shields.io/github/stars/SonicBotMan/openclaw-portable?style=flat-square&color=yellow) `Batchfile`

**即插即用的便携式 OpenClaw**——插在 Windows / Linux / Mac 上就能用，开箱即跑。

---

## 📡 Live: 观澜 GUANLAN

<p align="left">
  <a href="https://wen.pmparker.net/"><img src="https://img.shields.io/badge/🌐_wen.pmparker.net-进入看板-2563EB?style=for-the-badge" alt="观澜"/></a>
</p>

不是 repo，是**跑在自己 NAS 上的生产系统**：

| 模块 | 现状 |
|------|------|
| 📰 信源聚合 | **560+ 信源**，20 分钟周期，事件聚类 + 三级分级 |
| 🎬 视频产线 | **12 期/日 全自动**：选稿 → LLM 文案 → GPU 配图 → TTS → 渲染 → 发布 |
| 🖼️ AI 配图 | 4090 本地推理，**3.2 秒/张**，0.024 元/张 |
| 🤖 具身智能频道 | 竖版独立频道，编辑思维选稿，GPU 配图 + 双音色 |

从新闻入库到视频发布**全程无人值守**——这条产线本身的架构复盘写在博客里。

---

## ✍️ Writing — 深度长文 @ [pmparker.net](https://pmparker.net/)

没有编造的通用方法论，只有亲手做过、测过、翻过车的东西：

| 文章 | 讲什么 |
|------|--------|
| [我让 AI 建了条视频产线，它把我首页覆盖了](https://pmparker.net/blog/pulse-engine-video-pipeline.html) | 12期/日全自动产线：三次鬼、8.18GB 无限混音、尾斜杠覆盖首页 |
| [从新闻标题到封面图：3.2 秒的 AI 配图管线](https://pmparker.net/blog/ai-cover-pipeline.html) | 九段式 Prompt 工程 + GPU 容器农场调度 + 成本分析 |
| [最可怕的不是报错，是你的 AI 悄悄换了个人](https://pmparker.net/blog/silent-degradation.html) | 静默降级：配置里的模型不是跑着的模型 |
| [4090 大战 Jetson Thor](https://pmparker.net/blog/gpu-benchmark-4090-thor.html) | 同 seed 生图基准测试，差距没想到 |
| [我的第二大脑终于能用了](https://pmparker.net/blog/second-brain-engineering.html) | 把记忆系统当产品做：写入纪律、受控词表、分层召回 |

**[全部 29 篇 →](https://pmparker.net/blog/)**

---

## 🛠️ Other Projects

| Project | Description |
|---------|-------------|
| [dsv4-dual-thor-tuning](https://github.com/SonicBotMan/dsv4-dual-thor-tuning) | DeepSeek-V4-Flash 双 Jetson Thor 生产级调优 |
| [dsv4-vision-thor-port](https://github.com/SonicBotMan/dsv4-vision-thor-port) | DeepSeek-V4 Vision 在 Thor (SM110) 上的适配 |
| [dating-skills](https://github.com/SonicBotMan/dating-skills) | 恋爱方法论蒸馏技能包 😄 |
| [labor-rights-defense](https://github.com/SonicBotMan/labor-rights-defense) | 劳动维权方法论 AI Agent 技能包（2025 司法解释二 + 2026 判例） |
| [resume-forge](https://github.com/SonicBotMan/resume-forge) | AI 简历锻造工坊——产品经理专属 |

---

## ⚡ GitHub Stats

<p align="left">
  <img src="https://img.shields.io/github/stars/SonicBotMan?style=for-the-badge&label=Total+Stars&color=yellow" alt="Stars"/>
  <img src="https://img.shields.io/github/followers/SonicBotMan?style=for-the-badge&color=2563eb" alt="Followers"/>
  <a href="https://github.com/SonicBotMan?tab=repositories"><img src="https://img.shields.io/badge/Repos-20%2B-8B5CF6?style=for-the-badge" alt="Repos"/></a>
</p>

---

## 🤝 Connect

<p align="left">
  <a href="https://pmparker.net/"><img src="https://img.shields.io/badge/Blog-pmparker.net-3FD97F?style=for-the-badge&logo=aboutdotme&logoColor=white" alt="Blog"/></a>
  <a href="https://wen.pmparker.net/"><img src="https://img.shields.io/badge/观澜-GUANLAN-2563EB?style=for-the-badge" alt="观澜"/></a>
  <a href="https://xagent.icu/"><img src="https://img.shields.io/badge/ClawICU-xagent.icu-FF4D4D?style=for-the-badge" alt="xagent.icu"/></a>
  <a href="mailto:yunjiemi@agent.qq.com"><img src="https://img.shields.io/badge/Email-yunjiemi@agent.qq.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

<details>
<summary>🌐 English Summary</summary>

Ten-year product manager (Baidu alum: security / local life / content ecosystem), now building AI products full-time — treating AI as the team. The portfolio spans the full stack: **Peregrine** (Rust multi-segment download kernel with native MCP agent scheduling, 3.1× acceleration), **SoloFlow** (DAG+FSM workflow engine with three-tier memory and automatic skill evolution), **LobsterPress** (cognitive memory engine for LLM agents — single SQLite file, zero vector DB), **ClawICU** (OpenClaw emergency rescue: 20 checks, 6 phases, 25 guides), and **观澜 GUANLAN** — a live intelligence dashboard on my home NAS tracking 560+ sources with a fully automated video pipeline producing 12 AI-narrated episodes per day. I write deep-dive articles (in Chinese) about everything I build and break at [pmparker.net](https://pmparker.net/).

</details>
