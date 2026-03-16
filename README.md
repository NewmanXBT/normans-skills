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

| Skill | Description | Install |
|-------|-------------|---------|
| [x-content-optimizer](skills/content/x-content-optimizer/) | Audit and optimize tweets, X articles, and threads for X's recommendation algorithm | `npx openskills install NewmanXBT/normans-skills/skills/content/x-content-optimizer` |

### Security

| Skill | Description | Install |
|-------|-------------|---------|
| [audit-report-generator](skills/security/audit-report-generator/) | Generate professional PDF audit reports from markdown findings | `npx openskills install NewmanXBT/normans-skills/skills/security/audit-report-generator` |
| [contract-maturity-issue-writer](skills/security/contract-maturity-issue-writer/) | Turn smart contract code maturity findings into structured GitHub issues with file paths, code locations, and acceptance criteria | `npx openskills install NewmanXBT/normans-skills/skills/security/contract-maturity-issue-writer` |

## Structure

```
normans-skills/
├── skills/
│   ├── content/
│   │   └── x-content-optimizer/
│   │       ├── SKILL.md
│   │       └── references/
│   └── security/
│       └── audit-report-generator/
│           ├── SKILL.md
│           ├── assets/
│           ├── references/
│           └── scripts/
│       └── contract-maturity-issue-writer/
│           └── SKILL.md
└── README.md
```

## License

MIT
