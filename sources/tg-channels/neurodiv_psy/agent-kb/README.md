# Agent skill pack — (нейро)разнообразная психология

`agent-kb/` is a ready-made skill (`kb-neurodiv-psy`): `SKILL.md` = channel profile + domain list, `domains/` = one routing table per domain, `references/` = one full knowledge file per topic.

It is regenerated automatically whenever the knowledge base changes, so a symlinked install never goes stale.

Install for Claude Code (symlink keeps it current):

```bash
mkdir -p ~/.claude/skills && ln -s "/Users/coreference/projects/tg insights/sources/tg-channels/neurodiv_psy/agent-kb" ~/.claude/skills/kb-neurodiv-psy
```

or copy the folder into a project's `.claude/skills/kb-neurodiv-psy/`. For claude.ai, zip the folder and upload it as a skill (re-upload after updates). For other agents, load `SKILL.md` as instructions and give file access to the folder.
