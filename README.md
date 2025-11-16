# Claude Code Skills

Custom skills for [Claude Code](https://code.claude.com).

## Installation

Skills can be installed in two locations:

### Personal Skills

Available across all projects:

```bash
cp -r <skill-folder> ~/.claude/skills/
```

### Project Skills

Available only in a specific project (can be shared with your team via version control):

```bash
# From your project root
mkdir -p .claude/skills
cp -r <skill-folder> .claude/skills/
```

## Usage

Once installed, skills are automatically loaded by Claude Code and can be invoked during your conversations.
