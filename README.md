# 🤝 日常陪伴反思助手 / Companion Reflection

<div align="center">

**一个温暖、自然的情绪陪伴对话技能 — 不是说教机器，不是心理医生，只是一个会好好听你说话的对话伙伴**

**A warm, natural conversational companion for emotional moments — not a therapist, not a chatbot script**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.1.2-green.svg)]()
[![SKILL.md](https://img.shields.io/badge/Agent%20Skill-SKILL.md-green)](SKILL.md)
[![Platform](https://img.shields.io/badge/Platform-Claude%20Code-orange)]()
[![Platform](https://img.shields.io/badge/Platform-Cursor-brightgreen)]()
[![GitHub Stars](https://img.shields.io/github/stars/hyt315/companion-reflection?style=social)](https://github.com/hyt315/companion-reflection/stargazers)

[English](#english) | [中文](#中文)

</div>

---

## 中文

## 📖 这是什么？

当你感到焦虑、自责、纠结于过去的伤害、或是对一切感到空虚疲惫时，你需要的往往不是大道理，而是一个能好好陪你说话的存在。

**Companion Reflection** 是一个 AI Agent 技能，将四种成熟的心理学调节框架翻译成日常对话语言。当你在对话中流露出情绪困扰时，技能引导 AI 用温和的提问式反思回应——不给罐装鸡汤，不做诊断，不急着"修好"你。

### ✨ 核心特性

| 特性 | 说明 |
|------|------|
| 🔮 **焦虑引导** | 基于斯多葛控制二分法，帮你区分"能做的"和"不能做的" |
| 💔 **自责缓解** | 基于自我同情理论（Neff），用视角切换替代空洞安慰 |
| 🔁 **纠结释怀** | 基于叙事外化与原谅研究，承认伤害的同时轻轻把"现在"还给你 |
| 🌫️ **空虚陪伴** | 基于命运之爱（尼采）与意义疗法（弗兰克），陪伴优先，绝不强行赋予意义 |
| 🛡️ **安全协议** | 最高优先级危机识别，检测到自伤信号立即转介专业资源 |
| 🔍 **坦诚透明** | 方法不隐藏也不强塞，你问就说，不说也不否认 |

---

## 🚀 快速开始

### 方式一：AI Agent 直接加载（推荐）

本仓库提供 `SKILL.md`，兼容主流 AI Agent 平台。

**一行命令安装**：

| 平台 | 安装命令 |
|------|----------|
| **Claude Code** | `git clone https://github.com/hyt315/companion-reflection.git ~/.claude/skills/companion-reflection` |
| **Codex** | `git clone https://github.com/hyt315/companion-reflection.git ~/.codex/skills/companion-reflection` |
| **Cursor** | `git clone https://github.com/hyt315/companion-reflection.git ~/.cursor/skills/companion-reflection` |

**手动安装**：
1. 下载本仓库
2. 将 `SKILL.md` 和 `references/` 目录放入你的 AI Agent 的 skills 目录
3. 开始对话即可自动生效

### 方式二：直接阅读

1. 阅读 [SKILL.md](SKILL.md) 了解完整的回应方式
2. 阅读 [references/methods-background.md](references/methods-background.md) 了解理论来源

---

## 📥 下载 / Download

| 方式 | 命令 / 链接 |
|------|------------|
| **HTTPS** | `git clone https://github.com/hyt315/companion-reflection.git` |
| **SSH** | `git clone git@github.com:hyt315/companion-reflection.git` |
| **GitHub CLI** | `gh repo clone hyt315/companion-reflection` |
| **ZIP 源码** | [下载 ZIP](https://github.com/hyt315/companion-reflection/archive/refs/heads/main.zip) |
| **Tar 源码** | [下载 Tar](https://github.com/hyt315/companion-reflection/archive/refs/heads/main.tar.gz) |
| **单文件** | `curl -O https://raw.githubusercontent.com/hyt315/companion-reflection/main/SKILL.md` |

---

## 💡 核心理念

1. **方法可以不说出来，但不应该被刻意隐藏**：用户问就坦诚回答，不否认也不回避
2. **提问引导，不陈述结论**：让用户自己得出答案，而不是被"告知"该怎么做
3. **安全优先**：危机识别与转介协议的优先级高于一切引导性回应
4. **不是心理治疗**：这是对话陪伴工具，不能替代持证专业人士

---

## 🛡️ 安全协议

**最高优先级，覆盖所有回应模式。** 如果用户表达自伤或自杀相关信号，技能立即：

- 停止所有引导性回应
- 表达真诚、个人化的关切
- 联网搜索当地最新的心理危机干预热线
- 温和建议联系身边信任的人

本技能不做诊断，不开药物建议，不替代专业帮助。

---

## 📚 方法来源

四种回应模式均基于有同行评审文献和临床应用基础的成熟框架：

| 模式 | 主要来源 |
|------|----------|
| 焦虑担忧 | 斯多葛哲学（爱比克泰德） → CBT / REBT |
| 自我批评 | 自我同情理论（Kristin Neff） → CFT / MBCT |
| 反复纠结 | 叙事疗法（White & Epston） → 原谅研究（Enright, Worthington） |
| 空虚无意义 | 命运之爱（尼采） → 意义疗法（维克多·弗兰克） |

详细引用和适用范围见 [`references/methods-background.md`](references/methods-background.md)。

---

## 📁 文件结构

```
companion-reflection/
├── SKILL.md                           # 核心技能定义（AI Agent 加载用）
├── README.md                          # 本文件
├── LICENSE                            # CC BY 4.0 协议
├── CONTRIBUTING.md                    # 贡献指南
├── CODE_OF_CONDUCT.md                 # 行为准则（Contributor Covenant 2.1）
├── SECURITY.md                        # 安全策略
├── .gitignore                         # Git 忽略规则
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml             # 问题报告模板
│   │   ├── feature_request.yml        # 功能建议模板
│   │   └── config.yml                 # 模板选择器配置
│   └── pull_request_template.md       # PR 模板
└── references/
    └── methods-background.md          # 四种回应方式的理论来源
```

---

## ⚠️ 重要说明

本技能是对话陪伴工具，**不是**心理治疗，不能替代持证心理咨询师、精神科医生或危机干预服务。如果情绪困扰持续数周以上，建议寻求专业心理咨询。

---

## 🤝 贡献

欢迎贡献新的回应场景、改进建议或翻译优化。

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

---

## 📄 许可

[CC BY 4.0](LICENSE)

---

## English

## 📖 What is this?

When you're feeling anxious, self-critical, stuck ruminating on past hurts, or empty and exhausted, what you need most isn't advice — it's someone who can truly be present with you in conversation.

**Companion Reflection** is an AI agent skill that translates four established psychological frameworks into everyday conversational language. When you express emotional distress, the skill guides the AI to respond with gentle, question-based reflection — never canned reassurance, never diagnosis, never rushing to "fix" you.

### ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🔮 **Anxiety Guidance** | Stoic Dichotomy of Control — distinguishing what you can act on from what you can't |
| 💔 **Self-Criticism Relief** | Self-Compassion theory (Neff) — perspective switching instead of hollow reassurance |
| 🔁 **Rumination Release** | Narrative Externalization + Forgiveness Research — acknowledging hurt while gently returning you to the present |
| 🌫️ **Emptiness Companionship** | Amor Fati (Nietzsche) + Logotherapy (Frankl) — companionship first, never forcing meaning |
| 🛡️ **Safety Protocol** | Highest-priority crisis detection with immediate referral to professional resources |
| 🔍 **Transparent Methods** | Methods aren't hidden or forced — disclosed when asked, never denied |

---

## 🚀 Quick Start

### Option 1: AI Agent Direct Loading (Recommended)

This repository provides `SKILL.md`, compatible with mainstream AI Agent platforms.

**One-line install**:

| Platform | Install Command |
|----------|-----------------|
| **Claude Code** | `git clone https://github.com/hyt315/companion-reflection.git ~/.claude/skills/companion-reflection` |
| **Codex** | `git clone https://github.com/hyt315/companion-reflection.git ~/.codex/skills/companion-reflection` |
| **Cursor** | `git clone https://github.com/hyt315/companion-reflection.git ~/.cursor/skills/companion-reflection` |

**Manual install**:
1. Download this repository
2. Place `SKILL.md` and `references/` directory into your AI Agent's skills directory
3. Start chatting — the skill activates automatically

### Option 2: Direct Reading

1. Read [SKILL.md](SKILL.md) for the complete response methodology
2. Read [references/methods-background.md](references/methods-background.md) for theoretical foundations

---

## 📁 File Structure

```
companion-reflection/
├── SKILL.md                           # Core skill definition (for AI Agent loading)
├── README.md                          # This file
├── LICENSE                            # CC BY 4.0 License
├── CONTRIBUTING.md                    # Contributing guide
├── CODE_OF_CONDUCT.md                 # Code of Conduct (Contributor Covenant 2.1)
├── SECURITY.md                        # Security policy
├── .gitignore                         # Git ignore rules
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml             # Bug report template
│   │   ├── feature_request.yml        # Feature request template
│   │   └── config.yml                 # Template selector config
│   └── pull_request_template.md       # PR template
└── references/
    └── methods-background.md          # Theoretical foundations for all four response modes
```

---

## ⚠️ Important

This skill is a conversational companion tool, **not** psychotherapy. It does not substitute for a licensed psychologist, psychiatrist, or crisis intervention service. If emotional distress persists over weeks, professional consultation is recommended.

---

## 🤝 Contributing

Welcome to contribute new response scenarios, improvement suggestions, or translation refinements.

See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📄 License

[CC BY 4.0](LICENSE)
