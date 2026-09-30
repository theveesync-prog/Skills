# vee-ai-skills

Reusable skills for Claude Code, kept in one place and installable into any project.

## Skills

| Name | Use when | Invoke |
|------|----------|--------|
| `karpathy` | Writing, reviewing or refactoring code: keeps changes simple, surgical and verifiable | `/karpathy` |

## Install in another project

```
/plugin marketplace add theveesync-prog/Skills
/plugin install vee-ai-skills@vee-ai-skills
```

## Adding a skill

Create `skills/<name>/SKILL.md` with `name` and `description` frontmatter (the description says *when* to use it), then list it in `.claude-plugin/plugin.json`.

## Credits

- `karpathy`: adapted from [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) (MIT).
