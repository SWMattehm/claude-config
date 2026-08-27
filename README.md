# claude-config

CLAUDE.md templates + cursor rules that actually help

## Install

```bash
# pick a template
cp templates/CLAUDE.api.md your-project/CLAUDE.md
```

## How to use

```bash
# Claude Code reads CLAUDE.md from the repo root automatically
```

## What it does

- Global coding-style rules in rules/
- Per-archetype CLAUDE.md templates (api / cli / lib)
- Review checklist baked into instructions
- Kept short: agents read every token every time

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── rules/
│   ├── review.md
│   └── style.md
├── templates/
│   ├── CLAUDE.api.md
│   └── CLAUDE.cli.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
└── SECURITY.md
```

## Known issues

- none reported yet (surprisingly)

## License

MIT licensed, see LICENSE.
