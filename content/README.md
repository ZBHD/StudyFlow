# Content Layer

The content layer stores your learning materials: notes, mistakes, and practice records.

## Components

### Notes (`notes/`)
- `templates/note.md` - Note template
- `subjects/` - Your notes organized by subject

### Mistakes (`mistakes/`)
- `templates/mistake.md` - Mistake template
- Subject-specific mistake files

### Practice (`practice/`)
- `templates/writeup.md` - Practice/project template
- `entries/` - Your practice records

## Usage

### Taking Notes

After learning something new:
1. Use the note template to organize your understanding
2. Save in `notes/subjects/[subject-name]/`
3. Link to related mistakes if applicable

### Recording Mistakes

When you make a mistake:
1. Use the mistake template to analyze it
2. Add to the mistake index (`workflow/review/mistake-index.md`)
3. If repeated 2-3 times, upgrade to weak point

### Practice Records

After completing a project or practice:
1. Use the writeup template to document it
2. Save in `practice/entries/`
3. Include what you learned and what was challenging
