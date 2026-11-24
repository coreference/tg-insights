# Agent skill pack — The Neurodivergent Friendly Workbook of DBT Skills

`agent-kb/` is a ready-made skill (`kb-nd-friendly-dbt-workbook`): `SKILL.md` = book profile + domain list, `domains/` = one routing table per domain, `references/` = one full knowledge file per topic.

It is regenerated automatically whenever the knowledge base changes, so a symlinked install never goes stale.

Install for Claude Code (symlink keeps it current):

Run in the library root (the folder holding `KNOWLEDGE_INDEX.md`):

```bash
mkdir -p ~/.claude/skills && ln -s "$PWD/sources/books/nd-friendly-dbt-workbook/agent-kb" ~/.claude/skills/kb-nd-friendly-dbt-workbook
```

or copy the folder into a project's `.claude/skills/kb-nd-friendly-dbt-workbook/`. For claude.ai, zip the folder and upload it as a skill (re-upload after updates). For other agents, load `SKILL.md` as instructions and give file access to the folder.
