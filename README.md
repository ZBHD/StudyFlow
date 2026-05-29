# StudyFlow

[中文版](README_CN.md)

> This project actively participates in and recognizes the [Linux.do](https://linux.do) community.

> An open-source AI learning collaboration system that works with any AI tool.

StudyFlow helps you plan, track, and improve your learning with AI assistance. It's a pure Markdown system — no software to install, no accounts to create. Just files and an AI tool of your choice.

## Features

- **AI Collaboration**: Let AI quickly understand your background and provide personalized help
- **Learning Tracking**: Daily journals, plans, reviews, and spaced repetition queues
- **Knowledge Management**: Notes, mistake tracking, and practice records
- **Habit Building**: Statistics, weak point tracking, and progress visualization
- **Universal Design**: Works for students, professionals, self-learners, and anyone who wants to learn systematically

## Why StudyFlow?

### The Problem

- No learning plan — study when you feel like it, skip when you don't
- Forget what you learned — review depends on luck
- AI answers your questions, but doesn't know you
- Ask AI for a plan, get generic advice
- Learning apps lock your data in their platform

### The Solution

**Your data is always yours.** Switch AI tools? Just send your files to the new one.

| Approach | Pros | Cons |
|----------|------|------|
| Learning Apps | Nice UI | Data locked in, lose everything when switching |
| Databases | Structured | Needs deployment, maintenance |
| **Markdown** | **Universal, readable, version-controllable** | Manage files yourself |

Markdown is the only format that satisfies all of these:
1. **Human-readable** — Open and see
2. **AI-readable** — All AI tools support it
3. **Git-manageable** — Version control, history, collaboration
4. **Tool-agnostic** — VS Code, Obsidian, Notepad all work

### Comparison

| Feature | StudyFlow | Learning Apps | Manual |
|---------|-----------|---------------|--------|
| Data Ownership | ✅ Your files | ❌ Locked in | ✅ Yours |
| AI Compatibility | ✅ Any AI | ❌ Bound | ❌ No AI |
| Learning Curve | Low | Low | High |
| Collaboration | ✅ Git | Limited | ❌ |
| Price | Free | Paid | Free |
| Customization | ✅ Fully | Limited | ✅ |

## Quick Start

### 1. Get the System

```bash
git clone https://github.com/yourusername/studyflow.git
```

Or download the ZIP and extract it.

### 2. Choose Your AI Tool

StudyFlow works with any AI tool:
- ChatGPT Codex
- Claude Code
- Any other AI tool

### 3. Initialize Your Profile

Open your AI tool and paste this prompt:

```
I want to use the StudyFlow learning system. Please read the files in the studyflow/collect/prompts/ directory and guide me through the information collection process. Start with basic.md.
```

The AI will ask you questions and automatically create your profile files.

### 4. Start Learning

Once your profile is set up, use these prompts:

**For planning and review:**
```
Read my profile in core/user/profile.md and help me create a weekly plan.
```

**For learning help:**
```
I'm learning [topic]. Read my ability map in core/user/ability-map.md and explain [concept] from the basics.
```

**For daily check-in:**
```
Let me report today's progress. Read my current plan in workflow/planning/current-stage.md.
```

**For Claude Code users:**

StudyFlow includes two pre-built agents. Copy the `agents/` directory to your project's `.claude/agents/` to enable them:
- `@agent-leader` — Planning, supervision, progress tracking, and review
- `@agent-teacher` — Q&A, explanation, and note organization

## Documentation

- [Quick Start Guide](setup/quick-start.md) / [快速开始](setup/quick-start-cn.md) - 5-minute setup
- [AI Tool Setup](setup/ai-setup.md) / [AI 工具配置](setup/ai-setup-cn.md) - Configure your AI tool
- [Full Setup Guide](setup/full-setup.md) / [完整设置](setup/full-setup-cn.md) - Complete configuration
- [Information Collection](collect/README.md) - How the collection process works

## Architecture

StudyFlow uses a layered architecture:

| Layer | Required | Components | Purpose |
|-------|----------|------------|---------|
| **Scenes** | Optional | Exam Prep / Skill Building / Language Learning | Pre-built templates for specific use cases |
| **Content** | Optional | Notes / Mistakes / Practice Records | Knowledge management |
| **Workflow** | Core | Plans / Journals / Reviews / Queues | Learning process management |
| **Core** | Required | User Profile / AI Rules / Collection | Foundation for AI collaboration |

- **Core (Required)**: User profile, AI collaboration rules, information collection
- **Workflow (Core)**: Plans, journals, reviews, spaced repetition queues
- **Content (Optional)**: Notes, mistake tracking, practice records
- **Scenes (Optional)**: Pre-built templates for specific use cases

## Directory Structure

```
studyflow/
├── README.md              # This file
├── LICENSE                # MIT License
├── .gitignore
├── setup/                 # Setup guides
├── collect/               # Information collection module
├── core/                  # Core layer (required)
├── workflow/              # Workflow layer (core)
├── content/               # Content layer (optional)
├── roles/                 # AI role definitions
├── agents/                # Claude Code agents (optional)
└── scenes/                # Scene packages (optional)
```

## Use Cases

### For Students
- Track study progress across multiple subjects
- Manage exam preparation with spaced repetition
- Get AI help with difficult concepts

### For Professionals
- Plan skill development alongside work
- Track learning progress for career advancement
- Maintain work-life-learning balance

### For Self-Learners
- Structure self-directed learning
- Build consistent learning habits
- Get AI guidance without a teacher

## Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Why Open Source?

Learning should not be proprietary.

Your learning methods, your notes, your review plans — these are your intellectual assets. They shouldn't be locked in any platform.

StudyFlow uses the most open format (Markdown), the most open workflow (Git), and the most open license (MIT) to give you full control over your learning data.

**If you share this vision, welcome to Star, Fork, and PR.**

## Acknowledgments

- Built with the belief that learning should be systematic, not chaotic
- Designed for humans, powered by AI
- Inspired by spaced repetition, active recall, and deliberate practice
- Thanks to the [Linux.do](https://linux.do) community for support and feedback
