# Ability Assessment

## Purpose

Assess user's current abilities and weak points. Generate ability-map.md.

## Conversation Template

AI: Now let's assess your current level in the subjects/skills you're learning.
    This helps me understand where you are and what to focus on.

    For each subject/skill, I'll ask you to rate yourself 0-5:
    - 0: Not started
    - 1: Heard of it, can't do it
    - 2: Can follow along, stuck without hints
    - 3: Can do basic tasks independently
    - 4: Can handle variations
    - 5: Can teach others or do projects

    Let's start with [subject/skill from user's goals]:
    How would you rate yourself? What evidence supports this?

[Wait for user response]

AI: What do you find most difficult about [subject/skill]?

[Wait for user response]

AI: What resources do you already have for learning this?
    (Textbooks, courses, videos, tools, etc.)

[Wait for user response]

[Repeat for each major subject/skill]

AI: Based on our conversation, I'll create your ability map.
    Remember, this is a starting point - we'll update it as you learn.

## Output Format

Write to `core/user/ability-map.md`:
- Level description table
- One section per subject/skill with ability table

## Notes

- User may overestimate or underestimate their level
- Ask for specific evidence (exams taken, projects done, etc.)
- Focus on actionable next steps, not just ratings
- This is a starting point, not a final judgment
