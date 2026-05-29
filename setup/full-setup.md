# Full Setup Guide

Complete configuration guide for StudyFlow.

## Directory Structure

After setup, your StudyFlow directory should look like this:

```
studyflow/
├── README.md
├── LICENSE
├── .gitignore
├── setup/
├── collect/
├── core/
│   └── user/
│       ├── profile.md          # Your profile (generated)
│       ├── ability-map.md      # Your abilities (generated)
│       └── ai-rules.md         # AI collaboration rules
├── workflow/
│   ├── planning/
│   │   ├── current-stage.md    # Current learning phase
│   │   ├── weekly-plan.md      # This week's plan
│   │   └── goals.md            # Your goals (generated)
│   ├── diary/
│   │   ├── templates/
│   │   └── entries/            # Your daily journals
│   └── review/
│       ├── review-queue.md     # Spaced repetition queue
│       ├── weak-points.md      # Your weak points
│       └── mistake-index.md    # Your mistake index
├── content/
│   ├── notes/
│   │   └── subjects/           # Your notes by subject
│   ├── mistakes/
│   └── practice/
│       └── entries/            # Your practice records
├── roles/
├── agents/
└── scenes/
```

## Initial Setup

### Step 1: Clone or Download

```bash
git clone https://github.com/ZBHD/StudyFlow.git
cd studyflow
```

### Step 2: Run Information Collection

Use your AI tool to run the collection process:

```
Read collect/README.md and guide me through the information collection process.
```

This will generate:
- `core/user/profile.md`
- `core/user/ability-map.md`
- `workflow/planning/goals.md`

### Step 3: Customize AI Rules

Edit `core/user/ai-rules.md` to match your preferred:
- Communication style
- Strictness level
- Feedback preferences

### Step 4: Set Up First Plan

Use your AI tool to create your first plan:

```
Read my profile and goals, then help me create my first weekly plan.
```

## Daily Usage

### Morning Routine

1. Open your AI tool
2. Say: "Let me check today's tasks"
3. AI reads your plan and gives you today's tasks

### During Learning

1. Take notes in `content/notes/subjects/`
2. Record mistakes in `content/mistakes/`
3. Ask AI for help when stuck

### Evening Routine

1. Say: "Let me report today's progress"
2. AI guides you through daily journal
3. AI updates review queue and weak points

## Weekly Usage

### Monday Planning

1. Say: "Let's plan this week"
2. AI reviews last week and creates new plan

### Sunday Review

1. Say: "Let's do weekly review"
2. AI guides you through weekly review
3. AI updates ability map if needed

## Maintenance

### Regular Updates

- **Daily**: Journal entries, mistake records
- **Weekly**: Plans, reviews, ability map
- **Monthly**: Goals, weak points, AI rules

### File Management

- Keep journal entries organized by date
- Archive completed plans
- Review and clean up old notes

## Troubleshooting

### AI Doesn't Understand My Context

Solution: Make sure to share your profile at the start of each conversation.

### Plans Are Too Ambitious

Solution: Adjust `core/user/ai-rules.md` to emphasize medium intensity.

### Forgetting to Update

Solution: Set daily reminders for journal entries.

## Advanced Usage

### Custom Scenes

Create your own scene package in `scenes/`:
1. Create a new directory
2. Add README.md with setup instructions
3. Include templates as needed

### Multiple Subjects

Organize notes by subject in `content/notes/subjects/`:
```
content/notes/subjects/
├── mathematics/
├── programming/
├── language/
└── ...
```

### Integration with Other Tools

StudyFlow is pure Markdown, so it works with:
- Obsidian
- Notion (import)
- VS Code
- Any Markdown editor
