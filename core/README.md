# Core Layer

The core layer is the foundation of StudyFlow. It contains the user profile, ability map, and AI collaboration rules.

## Files

- `user/profile.md` - Stable user profile (personality, goals, habits)
- `user/ability-map.md` - Dynamic ability assessment (updated regularly)
- `user/ai-rules.md` - Rules for AI collaboration

## Usage

This layer is **required**. All other layers depend on it.

### For Users

1. Run the information collection process (`collect/README.md`)
2. Review and customize your profile
3. Update your ability map as you learn

### For AI Tools

1. Always read `user/profile.md` before starting a conversation
2. Check `user/ability-map.md` for context on user's current level
3. Follow `user/ai-rules.md` for collaboration style

## Maintenance

- `profile.md`: Update when goals or circumstances change
- `ability-map.md`: Update weekly or after significant learning milestones
- `ai-rules.md`: Customize to your preferred AI interaction style
