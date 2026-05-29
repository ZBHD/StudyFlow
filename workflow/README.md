# Workflow Layer

The workflow layer manages your learning process: planning, tracking, reviewing, and improving.

## Components

### Planning (`planning/`)
- `current-stage.md` - Current phase goals and principles
- `weekly-plan.md` - This week's plan
- `goals.md` - Long-term goals and milestones

### Diary (`diary/`)
- `templates/daily.md` - Daily journal template
- `templates/weekly-review.md` - Weekly review template
- `entries/` - Your daily journal entries

### Review (`review/`)
- `review-queue.md` - Spaced repetition queue
- `weak-points.md` - Weak points summary
- `mistake-index.md` - Mistake index

## Usage

### Daily Workflow

1. **Morning**: Check today's tasks in `weekly-plan.md`
2. **During learning**: Take notes, record mistakes
3. **Evening**: Write daily journal in `diary/entries/YYYY-MM-DD.md`
4. **Before sleep**: AI reviews and sets tomorrow's tasks

### Weekly Workflow

1. **Monday**: Review last week, set this week's plan
2. **Daily**: Follow the daily workflow
3. **Sunday**: Weekly review in `diary/entries/weekly/`

## For AI Tools

1. Always check `planning/current-stage.md` for context
2. Read `review/review-queue.md` before making plans
3. Update `review/weak-points.md` when patterns emerge
