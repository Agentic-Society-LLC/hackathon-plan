# hackathon-plan

Planning interview for the Agentic Society Hackathon (Oct 15-16, 2026). Run it once during prep week. You come out with one project sized for four 90-minute build sessions, a definition of done for Friday's demo, a session-by-session plan, a prep checklist, and a one-liner.

It plans. It does not build.

## Install

**Claude Code**
```
mkdir -p ~/.claude/skills/hackathon-plan
cp SKILL.md ~/.claude/skills/hackathon-plan/
```
Then type `/hackathon-plan` in any session. Running it inside your company brain folder is best, because it can check what you already have connected.

**Codex**
```
mkdir -p ~/.codex/skills/hackathon-plan
cp SKILL.md ~/.codex/skills/hackathon-plan/
```
Then ask "run the hackathon-plan skill".

**Claude.ai / Cowork**
Zip the `hackathon-plan` folder and upload it in Settings > Capabilities > Skills. Then say "plan my hackathon build".

**Anything else (ChatGPT, Hermes, etc.)**
Paste the full contents of `SKILL.md` as your first message, then say "start".

## What you get

- `hackathon-plan-<your-name>.md`: your full plan.
- A 5-line submission card to send to the organizers before Oct 15.

## Inspiration

- Matt Pocock's `grill-me` / `grilling` skill (github.com/mattpocock/skills): the relentless interview, the rounds of numbered questions each with a recommended answer, and the split where the agent looks up facts and the human makes decisions.
- Lauren Tan's (poteto) `pstack` (github.com/cursor/plugins/tree/main/pstack): definition of done as a checkable test, riskiest unknown first, settling facts by running something instead of asking, candor over agreement, and planning without building.
