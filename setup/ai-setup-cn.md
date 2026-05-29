# AI 工具配置指南

> StudyFlow 是 AI 无关的——任何能读 Markdown 的 AI 都能用。
> 这里列出不同工具的最佳配置方式。
>
> [English](ai-setup.md)

---

## ChatGPT

### 方式 1：Codex 项目（推荐）

1. 打开 [chat.openai.com](https://chat.openai.com)
2. 创建新项目，命名为 "我的学习"
3. 把 `core/` 和 `workflow/` 目录上传到项目
4. 开始对话，它会自动读取你的文件

### 方式 2：对话式

1. 直接开始新对话
2. 把 `core/user/profile.md` 的内容发给它
3. 告诉它："读这个文件，然后帮我建立学习画像"

---

## Claude Code

### 方式 1：Agent（推荐）

StudyFlow 内置两个 Claude Code agent：

1. 复制 `agents/` 目录到你的项目的 `.claude/agents/`
2. 在 Claude Code 中输入 `@agent-leader` 或 `@agent-teacher`
3. 开始对话

**Leader** 负责规划和监督，**Teacher** 负责答疑和讲解。

### 方式 2：直接对话

```bash
cd your-study-folder
claude
```

然后把 `core/user/profile.md` 的内容发给它。

---

## GitHub Copilot

### VS Code 集成

1. 用 VS Code 打开你的学习文件夹
2. 安装 Copilot 扩展
3. 打开任意 `.md` 文件
4. 用 `Ctrl+I` 或 `Cmd+I` 唤起 Copilot
5. 开始对话

> Copilot 会自动读取工作区中的所有文件。

---

## 通义千问 / 文心一言 / 其他国产 AI

### 方式：对话式

1. 直接开始新对话
2. 把 `core/user/profile.md` 的内容发给它
3. 告诉它："读这个文件，然后帮我建立学习画像"

> **提示：** 把整个 `core/` 目录的内容一次性发给它，效果更好。

---

## 通用配置建议

### 1. 让 AI 理解你的系统

第一次对话时，告诉 AI：

```
我有一个基于 Markdown 的学习管理系统。
核心文件在 core/ 目录：
- core/user/profile.md — 我的画像
- core/user/ability-map.md — 我的能力评估
- core/user/ai-rules.md — 你的行为规范

工作流在 workflow/ 目录：
- workflow/planning/ — 学习计划
- workflow/diary/ — 学习日记
- workflow/review/ — 复习记录

请先读一下这些文件，然后开始帮我。
```

### 2. 让 AI 保持上下文

每次新对话开始时，把你的画像发给它：

```
先读一下 core/user/profile.md，这是我的画像。
然后我们继续。
```

### 3. 让 AI 严格按规范执行

告诉 AI：

```
请严格按照 core/user/ai-rules.md 的规范执行。
- Leader 角色：严格要求，批评行为，不批评人格。
- Teacher 角色：引导式教学，给提示，不直接给答案。
```

---

## 常见问题

**Q: 我的 AI 不支持读文件怎么办？**
A: 直接把文件内容复制粘贴到对话里。所有 AI 都能读文本。

**Q: 多个 AI 工具可以同时用吗？**
A: 可以。只要它们读的是同一套文件。

**Q: AI 的回答不好怎么办？**
A: 告诉它哪里不好，让它调整。也可以换一个 AI 工具试试。

**Q: 需要付费吗？**
A: StudyFlow 本身免费。AI 工具的费用取决于你用哪个。
