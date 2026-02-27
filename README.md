# Task Manager

A project management agent that summarizes meetings, tracks action items, and syncs with external tools.

## Overview

| Component | Description |
|-----------|-------------|
| [Agent](./agent.md) | Project management agent definition |
| [Skills](./skills.md) | Reusable skill modules |
| [MCPs](./MCPs.md) | External service integrations |

## Compatibility

Built and tested on [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Also compatible with other AI coding agents that support the skills format.

### Recommended Models

| Model | Best For |
|-------|----------|
| Claude Sonnet 4.6 | Daily use — fast and cost-effective |
| Claude Opus 4.6 | Complex tasks requiring deeper reasoning |

## Quick Start

Install the meeting notes skill:

```bash
npx skills add https://github.com/yoochankim/task-manager --skill md-meeting-notes
```

Then run `/md-meeting-notes` in your agent.

## Folder Structure

```
task-manager/
├── README.md
├── agent.md
├── skills.md
├── MCPs.md
└── skills/
    └── md-meeting-notes/
        └── SKILL.md
```
