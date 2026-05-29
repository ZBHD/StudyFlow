# Habits Collection

## Purpose

Understand user's learning habits, schedule, and common distractions. Generate habit-related parts of profile.md and weak-points.md.

## Conversation Template

AI: Let's talk about your learning habits. This helps me create a realistic plan for you.

    How much time can you dedicate to learning each day?
    Be honest - it's better to plan for 1 hour and succeed than plan for 3 hours and fail.

[Wait for user response]

AI: When do you learn best? Morning, afternoon, evening, or late night?

[Wait for user response]

AI: What typically distracts you from learning?
    Common examples: phone, social media, games, TV, fatigue, etc.

[Wait for user response]

AI: When you can't start studying or get stuck, what's usually the reason?
    For example: don't know where to start, task too vague, too tired, etc.

[Wait for user response]

AI: What strategies have worked for you in the past to stay focused?

[Wait for user response]

## Output Format

Write to `core/user/profile.md`:
- Section 3: Learning State
- Section 4: Procrastination & Execution Issues

Write to `workflow/review/weak-points.md` (if applicable):
- Common weak points based on user's answers

## Notes

- Don't judge user's schedule or habits
- Help user be realistic about available time
- Common distractions are universal, not personal failures
- Focus on actionable strategies, not guilt
