# Agent skill pack — Human Gazing Upon Machine

`agent-kb/` is a ready-made skill (`kb-human-gazing-upon-machine`): `SKILL.md` = channel profile + domain list, `domains/` = one routing table per domain, `references/` = one full knowledge file per topic.

It is regenerated automatically whenever the knowledge base changes, so a symlinked install never goes stale.

Install for Claude Code (symlink keeps it current):

```bash
mkdir -p ~/.claude/skills && ln -s "/Users/coreference/projects/tg insights/sources/tg-channels/human-machine/agent-kb" ~/.claude/skills/kb-human-gazing-upon-machine
```

or copy the folder into a project's `.claude/skills/kb-human-gazing-upon-machine/`. For claude.ai, zip the folder and upload it as a skill (re-upload after updates). For other agents, load `SKILL.md` as instructions and give file access to the folder.
