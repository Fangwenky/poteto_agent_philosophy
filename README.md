# 🥔 Poteto Agent Philosophy

> Distilled agent orchestration philosophy from Lauren Tan ([@poteto](https://x.com/poteto)) — a comprehensive skill guide for disciplined AI-assisted development.

[中文](#-poteto-agent-编排哲学) | [English](#-overview)

---

## 🌏 Overview

This repository contains a structured **Skill** distilled from Lauren Tan's ([@poteto](https://x.com/poteto)) public posts on X/Twitter and her open-source projects ([pstack](https://github.com/cursor/plugins/tree/main/plugins/pstack), [noodle](https://github.com/poteto/noodle)). It captures her agent orchestration philosophy — a rigorous methodology for turning AI coding agents from sloppy code generators into disciplined engineering partners.

### What's Inside

```
skills/poteto-agent-philosophy/
└── SKILL.md          # The complete skill document
```

The `SKILL.md` contains:

| Section | Description |
|---------|-------------|
| **Three-Layer Orchestration Model** | Trigger → Router (poteto-mode) → Execution (subagents) |
| **10 Design Principles** | Laziness Protocol, Foundational Thinking, Build the Lever, etc. |
| **24 Agent Coding Rules** | Organized in 5 categories: Collaboration, Evidence, Memory, Environment, Trust |
| **Playbook-Driven Development** | 23+ structured playbooks for bug fixes, features, refactoring, etc. |
| **Subagent Orchestration** | Fearless Parallelism, Wrapper Pattern, Gated Deliverables |
| **Adversarial Review** | Multi-model cross-validation (`/interrogate`) |
| **Verification Loop** | "Prove It Works" execution templates |
| **Game Dev Orchestration** | Producer/Architect/Coder/QA multi-role workflow |
| **Ready-to-Use Templates** | Copy-paste agent behavior configurations |

### Core Philosophy in 3 Sentences

1. **"Never trust Done"** — An agent claiming completion means nothing without runtime evidence.
2. **"Structure over improvisation"** — Use Playbooks to constrain agent behavior, don't let it freestyle.
3. **"Tools are the deliverable"** — Write automation scripts instead of working by hand; the tool itself is the reviewable artifact.

### How to Use

**As a Skill for AI Agents** (Cursor / Antigravity / Claude Code):

```bash
# Copy into your project's agent skills directory
cp -r skills/poteto-agent-philosophy/ .agents/skills/poteto-agent-philosophy/
```

**As a Reference**: Read [`SKILL.md`](skills/poteto-agent-philosophy/SKILL.md) directly for principles, templates, and workflows.

**As Agent Rules**: Copy the "Agent 行为指令模板" section from SKILL.md into your project's `GEMINI.md`, `AGENTS.md`, or `.cursorrules` file.

---

## 🇨🇳 Poteto Agent 编排哲学

> 提炼自土豆姐 Lauren Tan ([@poteto](https://x.com/poteto)) 的 Agent 编排哲学 — 用于指导 AI Agent 进行纪律严明的高质量开发的完整 Skill 指南。

### 这是什么？

本仓库包含一份从 Lauren Tan（[@poteto](https://x.com/poteto)）在 X/Twitter 上的公开推文及其开源项目（[pstack](https://github.com/cursor/plugins/tree/main/plugins/pstack)、[noodle](https://github.com/poteto/noodle)）中提炼的结构化 **Skill**。它记录了她的 Agent 编排哲学——一套将 AI 编码 Agent 从"垃圾代码生成器"转变为"纪律严明的工程搭档"的严格方法论。

### 仓库内容

```
skills/poteto-agent-philosophy/
└── SKILL.md          # 完整的 Skill 文档
```

`SKILL.md` 包含以下内容：

| 章节 | 内容 |
|------|------|
| **三层编排模型** | 触发层 → 路由层（poteto-mode）→ 执行层（子代理） |
| **十大设计原则** | 懒惰协议、基础思维、穷尽设计空间、构建杠杆 等 |
| **24 条 Agent 编码准则** | 5 大类：协作 / 证据 / 记忆 / 环境 / 信任扩展 |
| **Playbook 驱动开发** | 23+ 种结构化 Playbook（Bug修复、功能开发、重构等） |
| **子代理编排** | 无畏并行、包装模式、门控交付 |
| **对抗性审查** | 多模型交叉验证（/interrogate） |
| **验证闭环** | "Prove It Works" 执行模板 |
| **游戏开发编排案例** | Producer/Architect/Coder/QA 多角色编排 |
| **即用模板** | 可直接复制使用的 Agent 行为配置 |

### 核心哲学三句话

1. **"永远不要相信 Done"** — Agent 说完成了不代表真的完成了，必须有运行时证据
2. **"结构化优于即兴"** — 用 Playbook 约束 Agent 行为，而非让其自由发挥
3. **"工具即产出"** — 写自动化工具而非手动操作，工具本身就是可审查的产出

### 如何使用

**作为 AI Agent 的 Skill**（Cursor / Antigravity / Claude Code）：

```bash
# 将 skill 复制到项目的 agent skills 目录中
cp -r skills/poteto-agent-philosophy/ .agents/skills/poteto-agent-philosophy/
```

**作为参考文档**：直接阅读 [`SKILL.md`](skills/poteto-agent-philosophy/SKILL.md) 获取原则、模板和工作流。

**作为 Agent 规则**：将 SKILL.md 中"Agent 行为指令模板"部分复制到你项目的 `GEMINI.md`、`AGENTS.md` 或 `.cursorrules` 文件中。

---

## 📌 Key References

- **pstack** (Cursor Plugin): [github.com/cursor/plugins/…/pstack](https://github.com/cursor/plugins/tree/main/plugins/pstack)
- **noodle** (Agent Orchestration Framework): [github.com/poteto/noodle](https://github.com/poteto/noodle)
- **Lauren Tan (@poteto)** on X: [x.com/poteto](https://x.com/poteto)
- Related tweet (Agent Orchestration): [x.com/poteto/status/2102050467505430555](https://x.com/poteto/status/2102050467505430555)
- Related tweet (Game Development): [x.com/poteto/status/2117043478140276847](https://x.com/poteto/status/2117043478140276847)

## 📄 License

This project is for educational and reference purposes. All original ideas and methodologies belong to Lauren Tan ([@poteto](https://x.com/poteto)). This is a community-contributed summary, not an official publication.

MIT License — see [LICENSE](LICENSE) for details.
