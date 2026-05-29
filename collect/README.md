# Information Collection Module

This module helps AI tools collect your information through conversation and automatically generate your profile.

## How It Works

1. You start a conversation with your AI tool
2. The AI reads the prompts in order
3. The AI asks you questions based on the prompts
4. The AI generates your profile files based on your answers

## Collection Steps

| Step | File | Required | Description |
|------|------|----------|-------------|
| 1 | `prompts/basic.md` | Yes | Basic info: identity, learning content, goals |
| 2 | `prompts/goals.md` | Yes | Short-term and long-term goals |
| 3 | `prompts/habits.md` | Recommended | Learning habits, schedule, distractions |
| 4 | `prompts/ability.md` | Recommended | Current level, weak points, resources |

## Usage

### Quick Start

Paste this to your AI tool:

```
I want to use the StudyFlow learning system. Please read the files in the collect/prompts/ directory and guide me through the information collection process. Start with basic.md.
```

### Step by Step

If you prefer to do it one step at a time:

```
Read collect/prompts/basic.md and help me fill in my basic information.
```

Then:

```
Read collect/prompts/goals.md and help me define my learning goals.
```

## Output

The collection process generates:
- `core/user/profile.md` - Your stable profile
- `core/user/ability-map.md` - Your ability assessment
- `workflow/review/weak-points.md` - Initial weak points (if applicable)

## Customization

You can:
- Skip steps that don't apply to you
- Add custom questions to the prompts
- Manually edit the generated files later
