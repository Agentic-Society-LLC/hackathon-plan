# hackathon-plan

Planning interview and build board for the Agentic Society Hackathon (Oct 15-16, 2026).

**Prep week:** run it once. You come out with one project sized for the four build sessions (about 7 hours of real build time), a definition of done for Friday's demo, a session-by-session plan, a prep checklist, a one-liner, and your own **build board**: `hackathon/board.html`, a single web page your AI keeps current while you build.

**Event days:** say "start session" and "close session". Your AI picks the sprint, moves tickets as it works, logs discovered work, applies the cut line at the Friday 11:30 checkpoint, and records minutes and tokens at each close.

**Friday 2:30:** say "hackathon report". The board's Report view shows what shipped, what it would have taken a person by hand (human-hours), your build time, the compression multiple, tokens, and what remains with an estimate. Copy it as text or print it to PDF.

Before Oct 15 it plans and does not build. On event days it builds against the board.

## Install

**One click:** [agenticsociety.com/downloads/ai-hackathon-planner-skill](https://agenticsociety.com/downloads/ai-hackathon-planner-skill) downloads the zip (SKILL.md + the board template) and shows the install for each tool.

**Claude Code** (paste into your terminal)
```bash
mkdir -p ~/.claude/skills/hackathon-plan/assets && curl -sL https://raw.githubusercontent.com/Agentic-Society-LLC/hackathon-plan/main/SKILL.md -o ~/.claude/skills/hackathon-plan/SKILL.md && curl -sL https://raw.githubusercontent.com/Agentic-Society-LLC/hackathon-plan/main/assets/board.html -o ~/.claude/skills/hackathon-plan/assets/board.html
```
Then type `/hackathon-plan` in any session. Running it inside your company brain folder is best, because it can check what you already have connected.

**Codex** (paste into your terminal)
```bash
mkdir -p ~/.codex/skills/hackathon-plan/assets && curl -sL https://raw.githubusercontent.com/Agentic-Society-LLC/hackathon-plan/main/SKILL.md -o ~/.codex/skills/hackathon-plan/SKILL.md && curl -sL https://raw.githubusercontent.com/Agentic-Society-LLC/hackathon-plan/main/assets/board.html -o ~/.codex/skills/hackathon-plan/assets/board.html
```
Then ask "run the hackathon-plan skill".

**Claude.ai / Cowork**
Download the zip from the link above and upload it as-is in Settings > Customize > Skills. Then say "plan my hackathon build".

**Anything else (ChatGPT, Hermes, etc.)**
Open [SKILL.md](https://raw.githubusercontent.com/Agentic-Society-LLC/hackathon-plan/main/SKILL.md), copy all of it, paste it as your first message, then say "start".

## What you get

- `hackathon-plan-<your-name>.md`: your full plan.
- A submission card to reply to Austin's prep email with, by Mon Oct 12.
- `hackathon/board.html`: your build board. Open it in a browser, turn on Auto-refresh, and watch it move while your AI works. Board, Sessions and Report views; the Report prints to PDF.

## The board

One file, no server. Your AI edits only the JSON block inside it (`<script id="hackathon-data">`); the page renders the rest. Every piece of work is a ticket with a tier (must / should / stretch / prep) and an honest **human-hours** estimate set when it is created. The Report view divides shipped human-hours by your real build time to show the compression you got from building with AI, and prices what remains the same way. The template is [assets/board.html](assets/board.html); it ships with sample data until your AI personalizes it.

## Inspiration

- Matt Pocock's `grill-me` / `grilling` skill (github.com/mattpocock/skills): the relentless interview, the rounds of numbered questions each with a recommended answer, and the split where the agent looks up facts and the human makes decisions.
- Lauren Tan's (poteto) `pstack` (github.com/cursor/plugins/tree/main/pstack): definition of done as a checkable test, riskiest unknown first, settling facts by running something instead of asking, candor over agreement, and planning without building.

## License

MIT. Use it, adapt it for your own event, share it. See [LICENSE](LICENSE).
