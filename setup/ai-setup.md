# AI Tool Setup Guide

StudyFlow works with any AI tool. This guide helps you configure your specific tool for the best experience.

## Universal Setup

Regardless of which AI tool you use:

1. **System prompt**: Copy the relevant role file (`roles/leader.md` or `roles/teacher.md`) as part of your system prompt
2. **Context**: Always let the AI read your profile before starting
3. **Sync**: Regularly sync your learning records

## ChatGPT Setup

### Method 1: Custom Instructions

1. Go to ChatGPT Settings → Custom Instructions
2. In "What would you like ChatGPT to know about you?", paste your `core/user/profile.md` content
3. In "How would you like ChatGPT to respond?", paste the relevant role from `roles/`

### Method 2: GPTs

1. Create a new GPT
2. In Instructions, paste the role file
3. In Knowledge, upload your profile files
4. Save and use

## Claude Setup

### Method 1: Project Knowledge

1. Create a new Project
2. In Project Knowledge, upload your profile files
3. In Custom Instructions, paste the role file
4. Start conversations from this project

### Method 2: Claude Code

1. Copy `agents/` files to your project's `.claude/agents/`
2. Restart Claude Code
3. Use `@agent-leader` or `@agent-teacher`

## Kimi Setup

### Method 1: Long Text Input

1. Start a new conversation
2. Paste the role file as the first message
3. Upload your profile files
4. Start learning

### Method 2: Prompt Engineering

1. Create a prompt template with the role
2. Include placeholders for your profile
3. Fill in before each session

## Other AI Tools

For any AI tool:

1. **System prompt**: Use the role file as a system prompt or first message
2. **Context**: Share your profile at the start of each conversation
3. **Instructions**: Tell the AI to read specific files as needed

## Tips

- Keep your profile updated for better AI assistance
- Switch between leader and teacher roles as needed
- Use natural language - the AI will understand
