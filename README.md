# Master Meta Prompting

A Claude skill. Creates, audits, and improves reusable master prompts using four engineering layers: prompt, context, harness, and loop engineering. Use when the user asks for a master meta prompt, prompt improvement, a reusable AI workflow, or explicitly requests these four layers. Converts rough requests into executable briefs with evidence rules, tool boundaries, evaluation criteria, and bounded revision loops. Supports prompt-only and explicitly requested execution modes across research, publishing, marketing, coding, learning, and business planning.

## What's inside

- `master-meta-prompting/SKILL.md`

## Install

### Claude app (claude.ai, desktop, mobile)

1. Download this repo as a ZIP (**Code > Download ZIP**) and unzip it.
2. Zip the `master-meta-prompting` folder on its own, so the ZIP contains `master-meta-prompting/SKILL.md`.
3. In Claude's settings, open the Skills section, upload that ZIP, and turn the skill on.

### Claude Code

```bash
git clone https://github.com/bogsdav/master-meta-prompting.git
mkdir -p ~/.claude/skills
cp -r master-meta-prompting/master-meta-prompting ~/.claude/skills/
```

Restart Claude Code. The skill loads automatically when a request matches its description.

## Try it

- "Turn this rough request into a master prompt I can reuse."
- "Audit my prompt across the prompt, context, harness and loop layers."
- "Build a reusable research workflow prompt with evidence rules."

## License

MIT. See [LICENSE](LICENSE).
