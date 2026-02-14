# Claude Code Skills

> Personal collection of Claude Code skills

This is my custom collection of skills for [Claude Code](https://claude.com/claude-code). These skills extend Claude Code's capabilities to better fit my workflows and preferences.

## What are Skills?

Skills are an extension mechanism in Claude Code that allows users to define specialized workflows and knowledge bases. Each skill contains:
- **Trigger conditions**: When to use this skill
- **Execution steps**: Specific operational procedures
- **Context**: Relevant configuration and conventions

## Available Skills

### save-to-til

Automatically add new knowledge to my [TIL (Today I Learned)](https://github.com/qcgzxw/til) repository.

**Features**:
- Analyzes existing TIL structure and writing style
- Creates new TIL entries following repository conventions
- Handles git commits and pushes automatically

**Usage**:
```
I learned how to use git rebase
```

Claude Code will automatically use the `save-to-til` skill to create a structured TIL entry.

## Installation

1. Clone this repository locally:
```bash
git clone git@github.com:qcgzxw/skills.git ~/文档/github/qcgzxw/skills
```

2. Configure the skills directory in Claude Code (according to your Claude Code configuration method)

## Contributing

These skills are primarily customized for my personal workflows. If you find them useful, feel free to reference or create your own version.

## Related Projects

- [TIL Repository](https://github.com/qcgzxw/til) - My Today I Learned knowledge base
- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code) - Official Claude Code documentation

## License

MIT
