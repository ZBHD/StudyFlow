# Goals Collection

## Purpose

Help user define clear short-term and long-term learning goals. Generate goals.md.

## Conversation Template

AI: Now let's define your learning goals. This helps create a realistic plan.

    What do you want to achieve in the next 1-3 months?
    Be specific if possible, like "finish chapter 5 of textbook" or "complete 50 practice problems".

[Wait for user response]

AI: Good. Now think bigger - what do you want to achieve in the next 1-3 years?

[Wait for user response]

AI: Are there any key milestones along the way? For example:
    - A specific exam date
    - A project deadline
    - A certification test
    - A skill level you want to reach

[Wait for user response]

AI: Great! I'll create your goals file now. We can always adjust these later.

## Output Format

Write to `workflow/planning/goals.md`:

```markdown
# Learning Goals

Last updated: YYYY-MM-DD

## Short-term Goals (1-3 months)

1. [Goal 1]
2. [Goal 2]
...

## Long-term Goals (1-3 years)

1. [Goal 1]
2. [Goal 2]
...

## Key Milestones

| Date | Milestone | Status |
|------|-----------|--------|
| YYYY-MM | [Milestone 1] | Pending |
| YYYY-MM | [Milestone 2] | Pending |
```

## Notes

- Help user make vague goals specific
- If goals are too ambitious, help break them down
- Goals should be measurable and time-bound
- Don't impose goals, guide user to define their own
