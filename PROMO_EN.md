# StudyFlow — Turn AI into Your Learning Partner, Not an Answer Machine

> A pure Markdown AI learning collaboration system. Zero dependencies, zero barriers, works with any AI tool.

---

## Do You Have These Problems?

- No learning plan — study when you feel like it, skip when you don't
- Forget what you learned — review depends on luck
- AI answers your questions, but doesn't know you
- Ask AI for a plan, get generic advice
- Use learning apps, but your data is locked in their platform

**StudyFlow solves all of these.**

---

## What Is It?

StudyFlow is a **pure Markdown file** system for AI learning collaboration.

Not an app. Not a SaaS. Not a platform that requires signup.

Just `.md` files on your computer. Feed them to any AI tool, and the AI can:

- Know who you are, what you've learned, where you're weak
- Help you plan, supervise execution, and review progress
- Manage your mistakes and schedule spaced repetition
- Teach you in your preferred style, not generic scripts

**Your data is always yours.** Switch AI tools? Just send your files to the new one.

---

## Why Markdown?

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

---

## How Does It Work?

### 1. Build Your Profile

Through conversation with AI, it collects your info and generates a structured profile:

```markdown
## Background
- Role: University Student
- Major: Computer Science
- Goals: Graduate school entrance exam + technical skills

## Time Budget
- Available: 20 hours/week
- Preferred: 8am-12pm

## Current Level
- Programming: Python basics, C beginner
- Math: Calculus in progress
- Courses: Data structures starting
```

### 2. AI Gets Context

Next time you talk to AI, send your profile. Now it knows:

- Your goals
- Your progress
- Your weak points
- Your time budget

**No need to reintroduce yourself every time.**

### 3. Role Division

StudyFlow defines two AI roles:

**Leader**
- Plans, supervises, reviews
- Strict but respectful
- Criticizes behavior, not personality

**Teacher**
- Explains, answers questions
- Uses analogies and guidance, not direct answers
- Gives hints, lets you think first

**You're not asking AI a question — you're collaborating on a learning project.**

### 4. Spaced Repetition

After learning something new, StudyFlow automatically schedules reviews:

- D+1: First review
- D+3: Second review
- D+7: Third review
- D+14: Fourth review

**It's not that you can't remember — no one helped you review.**

---

## Who Is It For?

| Audience | How to Use |
|----------|------------|
| **Students** | Track multi-subject progress, manage exam prep |
| **Graduate Exam Takers** | Long-term planning, phased execution, mistake tracking |
| **Self-learners** | Skill building, project practice, knowledge organization |
| **Professionals** | Fragmented learning, knowledge system building |

---

## Comparison with Other Solutions

| Feature | StudyFlow | Learning Apps | Manual |
|---------|-----------|---------------|--------|
| Data Ownership | ✅ Your files | ❌ Locked in | ✅ Yours |
| AI Compatibility | ✅ Any AI | ❌ Bound | ❌ No AI |
| Learning Curve | Low | Low | High |
| Collaboration | ✅ Git | Limited | ❌ |
| Price | Free | Paid | Free |
| Customization | ✅ Fully | Limited | ✅ |

---

## Quick Start

**5 minutes. Zero dependencies.**

```bash
# Clone the repo
git clone https://github.com/ZBHD/StudyFlow.git

# Copy core files to your study directory
cp -r StudyFlow/core ~/my-study/
cp -r StudyFlow/workflow ~/my-study/
```

Then open your AI tool and say:

```
Read core/user/profile.md, then help me build my learning profile.
```

**That's it.** Your AI learning partner is ready.

---

## Technical Details

- **File Format**: Pure Markdown (`.md`)
- **Dependencies**: None (no Git, Node.js, or Python required)
- **AI Tools**: ChatGPT, Claude Code, Copilot, or any AI
- **Version Control**: Git recommended, not required
- **License**: MIT (do whatever you want)

---

## Why Open Source?

Learning should not be proprietary.

Your learning methods, your notes, your review plans — these are your intellectual assets. They shouldn't be locked in any platform.

StudyFlow uses the most open format (Markdown), the most open workflow (Git), and the most open license (MIT) to give you full control over your learning data.

**If you share this vision, welcome to Star, Fork, and PR.**

---

## Links

- **Repository**: https://github.com/ZBHD/StudyFlow
- **Quick Start**: [5-Minute Setup](setup/quick-start.md)
- **Full Docs**: [README](README.md)
- **License**: MIT

---

## Acknowledgments

Thanks to the [Linux.do](https://linux.do) community for support and feedback.

---

**Learning is something AI can help with, but can't do for you.**

**StudyFlow makes AI your partner, not your answer machine.**
