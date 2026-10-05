# hackathon-plan

Planning interview for the Agentic Society Hackathon (Oct 15-16, 2026). Run it once during prep week. You come out with one project sized for four 90-minute build sessions, a definition of done for Friday's demo, a session-by-session plan, a prep checklist, and a one-liner.

It plans. It does not build.

## Install

**Claude Code** (paste into your terminal)
```bash
mkdir -p ~/.claude/skills/hackathon-plan && curl -sL https://raw.githubusercontent.com/Agentic-Society-LLC/hackathon-plan/main/SKILL.md -o ~/.claude/skills/hackathon-plan/SKILL.md
```
Then type `/hackathon-plan` in any session. Running it inside your company brain folder is best, because it can check what you already have connected.

**Codex** (paste into your terminal)
```bash
mkdir -p ~/.codex/skills/hackathon-plan && curl -sL https://raw.githubusercontent.com/Agentic-Society-LLC/hackathon-plan/main/SKILL.md -o ~/.codex/skills/hackathon-plan/SKILL.md
```
Then ask "run the hackathon-plan skill".

**Claude.ai / Cowork**
Download [SKILL.md](https://raw.githubusercontent.com/Agentic-Society-LLC/hackathon-plan/main/SKILL.md), put it in a folder named `hackathon-plan`, zip that folder, and upload the zip in Settings > Capabilities > Skills. Then say "plan my hackathon build".

**Anything else (ChatGPT, Hermes, etc.)**
Open [SKILL.md](https://raw.githubusercontent.com/Agentic-Society-LLC/hackathon-plan/main/SKILL.md), copy all of it, paste it as your first message, then say "start".

## What you get

- `hackathon-plan-<your-name>.md`: your full plan.
- A 5-line submission card to send to the organizers before Oct 15.

## Inspiration

- Matt Pocock's `grill-me` / `grilling` skill (github.com/mattpocock/skills): the relentless interview, the rounds of numbered questions each with a recommended answer, and the split where the agent looks up facts and the human makes decisions.
- Lauren Tan's (poteto) `pstack` (github.com/cursor/plugins/tree/main/pstack): definition of done as a checkable test, riskiest unknown first, settling facts by running something instead of asking, candor over agreement, and planning without building.

## License

MIT. Use it, adapt it for your own event, share it. See [LICENSE](LICENSE).
