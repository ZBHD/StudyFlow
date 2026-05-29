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

## Documentation

- [Quick Start Guide](setup/quick-start.md) - 5-minute setup
- [AI Tool Setup](setup/ai-setup.md) - Configure your AI tool
- [Full Setup Guide](setup/full-setup.md) - Complete configuration
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

## Acknowledgments

- Built with the belief that learning should be systematic, not chaotic
- Designed for humans, powered by AI
- Inspired by spaced repetition, active recall, and deliberate practice
