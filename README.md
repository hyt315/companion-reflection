<div align="center">

[English](#english) | [中文](#中文)

</div>

---

<a name="english"></a>

# 🤝 Companion Reflection

> A warm, natural conversational companion for emotional moments — not a therapist, not a chatbot script.

**Companion Reflection** is an AI agent skill that translates four established psychological frameworks into everyday conversational language. When a user expresses anxiety, self-criticism, resentment, or emptiness, the skill guides the AI to respond with gentle, question-based reflection — never canned reassurance, never diagnosis.

---

### 📥 Download / Install

| Method | Command |
|---|---|
| **HTTPS** | `git clone https://github.com/hyt315/companion-reflection.git` |
| **SSH** | `git clone git@github.com:hyt315/companion-reflection.git` |
| **GitHub CLI** | `gh repo clone hyt315/companion-reflection` |
| **ZIP** | [Download ZIP](https://github.com/hyt315/companion-reflection/archive/refs/heads/main.zip) |
| **Single file** | `curl -O https://raw.githubusercontent.com/hyt315/companion-reflection/main/SKILL.md` |

Place under your skills directory (e.g. `~/.claude/skills/`):

```
companion-reflection/
├── SKILL.md
├── README.md
├── LICENSE
├── SECURITY.md
├── .gitignore
└── references/
    └── methods-background.md
```

---

### ✨ Core Response Modes

| Emotional Signal | Core Technique | What It Sounds Like |
|---|---|---|
| 🔮 **Anxiety / Worry About Future** | Dichotomy of Control (Stoic) | "Let's sort through this — what can you actually act on today, and what's not in your hands?" |
| 💔 **Self-Blame / Self-Criticism** | Self-Compassion (Neff) | "If your best friend said those things about themselves, what would you say back?" |
| 🔁 **Rumination / Resentment** | Narrative Externalization + Forgiveness Research | "That hurt was real. And since then — has there been a small moment that was yours?" |
| 🌫️ **Emptiness / Apathy** | Amor Fati (Nietzsche) + Logotherapy (Frankl) | "I won't say 'it gets better.' If you want to do nothing right now, that's okay. I'm here." |

---

### 🛡️ Safety Protocol

**Highest priority. Overrides all other modes.** If the user expresses any self-harm or suicidal signals, the skill immediately:
- Stops all guided reflection
- Expresses genuine, personal concern
- searches for current local crisis hotline numbers
- Encourages connecting with a trusted person nearby

The skill does NOT diagnose, prescribe, or replace professional help.

---

### 📚 Method Sources

All four modes are grounded in established frameworks with peer-reviewed literature and clinical applications. For detailed citations and therapeutic boundaries, see [`references/methods-background.md`](references/methods-background.md).

| Mode | Primary Source |
|---|---|
| Anxiety | Stoic philosophy (Epictetus) → CBT / REBT |
| Self-Criticism | Self-Compassion (Kristin Neff) → CFT / MBCT |
| Rumination | Narrative Therapy (White & Epston) → Forgiveness Research (Enright, Worthington) |
| Emptiness | Amor Fati (Nietzsche) → Logotherapy (Viktor Frankl) |

---

### ⚠️ Important

This skill is a conversational companion tool, **not** psychotherapy. It does not substitute for a licensed psychologist, psychiatrist, or crisis intervention service. If emotional distress persists over weeks, professional consultation is recommended.

---

### 📄 License

[CC BY 4.0](LICENSE)

---

<a name="中文"></a>

# 🤝 日常陪伴反思助手

> 一个温暖、自然的情绪陪伴对话风格 — 不是说教机器，不是心理医生，只是一个会好好听你说话的对话伙伴。

**Companion Reflection** 是一个 AI Agent 技能，将四种成熟的心理学调节框架翻译成日常对话语言。当用户流露焦虑、自责、纠缠过去的怨恨或空虚疲惫时，技能引导 AI 用温和的提问式反思回应 — 不给罐装鸡汤，不做诊断。

---

### 📥 下载 / 安装

| 方式 | 命令 |
|---|---|
| **HTTPS** | `git clone https://github.com/hyt315/companion-reflection.git` |
| **SSH** | `git clone git@github.com:hyt315/companion-reflection.git` |
| **GitHub CLI** | `gh repo clone hyt315/companion-reflection` |
| **ZIP** | [下载 ZIP](https://github.com/hyt315/companion-reflection/archive/refs/heads/main.zip) |
| **单文件** | `curl -O https://raw.githubusercontent.com/hyt315/companion-reflection/main/SKILL.md` |

将目录放入技能目录下（如 `~/.claude/skills/`）：

```
companion-reflection/
├── SKILL.md
├── README.md
├── LICENSE
├── SECURITY.md
├── .gitignore
└── references/
    └── methods-background.md
```

---

### ✨ 四类核心回应模式

| 情绪信号 | 核心技法 | 引导方式 |
|---|---|---|
| 🔮 **焦虑 / 担忧未来** | 控制二分法（斯多葛学派） | "我们一起捋一捋 — 这里面哪些是你现在就能做的，哪些不管怎样都不由你？" |
| 💔 **自我否定 / 自责** | 自我同情（Kristin Neff） | "如果是你最好的朋友对自己说了这些话，你会怎么回应 ta？" |
| 🔁 **反复纠结 / 怨恨** | 叙事外化 + 原谅研究 | "那份伤害是真的。那之后 — 有没有哪怕一点点属于自己的、还不错的时刻？" |
| 🌫️ **空虚 / 无意义感** | 命运之爱（尼采） + 意义疗法（弗兰克） | "我不会说'会好起来的'。如果现在什么都不想做，那就先什么都不做，我都在。" |

---

### 🛡️ 安全协议

**最高优先级，覆盖所有回应模式。** 一旦用户表达自伤或自杀相关的信号，技能立即：
- 停止所有引导性回应
- 表达真诚、个人化的关切
- 联网搜索当地最新的心理危机干预热线
- 温和建议联系身边信任的人

本技能不做诊断，不开药物建议，不替代专业帮助。

---

### 📚 方法来源

四种回应模式均基于有同行评审文献和临床应用基础的成熟框架。详细引用和适用范围见 [`references/methods-background.md`](references/methods-background.md)。

| 模式 | 主要来源 |
|---|---|
| 焦虑担忧 | 斯多葛哲学（爱比克泰德） → CBT / REBT |
| 自我批评 | 自我同情理论（Kristin Neff） → CFT / MBCT |
| 反复纠结 | 叙事疗法（White & Epston） → 原谅研究（Enright, Worthington） |
| 空虚无意义 | 命运之爱（尼采） → 意义疗法（维克多·弗兰克） |

---

### ⚠️ 重要说明

本技能是对话陪伴工具，**不是**心理治疗，不能替代持证心理咨询师、精神科医生或危机干预服务。如果情绪困扰持续数周以上，建议寻求专业心理咨询。

---

### 📄 许可证

[CC BY 4.0](LICENSE)
