# Norman's Skills

A collection of Claude Skills for various workflows.

## Installation

### Option 1: OpenSkills (Recommended)
```bash
npx openskills install NewmanXBT/normans-skills
```

### Option 2: Manual Installation
Clone this repo and copy the skills you need to `~/.claude/skills/`

```bash
git clone https://github.com/NewmanXBT/normans-skills.git
cp -r normans-skills/skills/content/* ~/.claude/skills/
```

## Skills

### Content

| Skill | Description | Command |
|-------|-------------|---------|
| [x-content-optimizer](skills/content/x-content-optimizer/) | Audit and optimize tweets, X articles, and threads for X's recommendation algorithm | `/x-content-optimizer` |

## Structure

```
normans-skills/
├── skills/
│   └── content/
│       └── x-content-optimizer/
│           ├── SKILL.md
│           └── references/
└── README.md
```

## License

MIT
