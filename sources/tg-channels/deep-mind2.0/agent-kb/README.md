# Agent skill pack — deep mind 2.0

`agent-kb/` is a ready-made skill (`kb-deep-mind-2-0`): `SKILL.md` = channel profile + domain list, `domains/` = one routing table per domain, `references/` = one full knowledge file per topic.

It is regenerated automatically whenever the knowledge base changes, so a symlinked install never goes stale.

Install for Claude Code (symlink keeps it current):

Run in the library root (the folder holding `KNOWLEDGE_INDEX.md`):

```bash
mkdir -p ~/.claude/skills && ln -s "$PWD/sources/tg-channels/deep-mind2.0/agent-kb" ~/.claude/skills/kb-deep-mind-2-0
```

or copy the folder into a project's `.claude/skills/kb-deep-mind-2-0/`. For claude.ai, zip the folder and upload it as a skill (re-upload after updates). For other agents, load `SKILL.md` as instructions and give file access to the folder.
