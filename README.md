# Claude Code Skills

Personal collection of Claude Code skills.

## Built-in Skills

Located directly in this repo as subdirectories.

## External Skills

Installed via symlinks from `~/.agents/skills/`:

| Skill | Source |
|-------|--------|
| ai-agent-builder | claude-office-skills/skills |
| competitor-monitor | guia-matthieu/clawfu-skills |
| playwright-web-scraper | dawiddutoit/custom-claude |
| telegram-bot | claude-office-skills/skills |
| wechat-channel | aaaaqwq/claude-code-skills |
| wechat-studio | chouheiwa/wechat-studio |

## gstack

[garrytan/gstack](https://github.com/garrytan/gstack) — 23 specialized AI agents as slash commands (planning, design, QA, deploy, etc).

Install:
```bash
git clone --single-branch --depth 1 https://github.com/garrytan/gstack.git ~/.claude/skills/gstack && cd ~/.claude/skills/gstack && ./setup
```

Upgrade: `/gstack-upgrade`
