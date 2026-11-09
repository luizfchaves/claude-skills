# claude-skills

My Claude Code skills. Each folder is one skill.

## Install

Link each skill into `~/.claude/skills`:

```sh
git clone https://github.com/luizfchaves/claude-skills ~/claude-skills
for d in ~/claude-skills/*/; do ln -sfn "${d%/}" ~/.claude/skills/; done
```
