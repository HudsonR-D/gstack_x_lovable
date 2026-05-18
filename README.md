# gstack × Lovable

Turn [Lovable](https://lovable.dev) into **Garry Tan’s virtual engineering team** using his proven gstack methodology.

This repo gives you a ready-to-use Lovable Skill that brings the full `Think → Plan → Build → Review → Test → Ship → Reflect` workflow + role-based reviews (CEO, Eng Manager, Designer, QA, Security, Release Manager) directly into Lovable.

## Quick Start (Easiest)

### Import the Skill into Lovable

1. Open Lovable
2. Go to **Settings → Skills → Import → GitHub**
3. Paste this repo URL:  
   `https://github.com/HudsonR-D/gstack_x_lovable`
4. Lovable will import the skill as `gstack`

Once imported, just type things like:
- `use gstack`
- `gstack office-hours: build a waitlist page`
- `gstack plan`
- `gstack review`
- `gstack qa`
- `gstack ship`
- `gstack learn [insight]`

The skill will automatically activate and guide you through the full structured process.

## What This Gives You

- Full gstack workflow adapted specifically for Lovable
- Strong safety guardrails and "careful mode"
- Role switching (CEO/Product, Engineering Manager, Designer, QA Lead, etc.)
- Structured artifacts (Product Vision, Architecture, QA reports, etc.)
- **GBrain-style learning capture** via `gstack learn`
- Regular safety & update hygiene reminders

## GBrain-style Memory (LEARNINGS.md)

This repo also supports lightweight persistent memory similar to Garry Tan’s GBrain.

### How to use it

1. Create a file called `LEARNINGS.md` in your project root (or let the skill create it).
2. Use commands like:
   - `gstack learn [your insight or decision]`
   - `gstack remember this`
   - `gstack learn from this session`

The skill will extract the learning, propose a clean entry, and ask for confirmation before saving it.

This gives you accumulating project knowledge that survives across sessions.

### Recommended LEARNINGS.md Template

```markdown
# LEARNINGS.md — Project Learnings & Patterns

> Captured insights, decisions, patterns, and gotchas.  
> Updated via `gstack learn`. This file acts as lightweight persistent memory.

## Recent Learnings
- **[YYYY-MM-DD]** — [Clear, specific learning + why it mattered]

## Patterns That Work Well Here
- 

## Things That Didn't Work / Anti-Patterns
- 

## Decisions We Regret or Reversed
- 

## Useful Snippets, Gotchas & Context
- 
```

## Recommended: Add GSTACK.md to Your Project

For best long-term results, also add a `GSTACK.md` file to your project root. This gives the AI persistent memory about your project’s decisions, conventions, and status.

### Fastest way
Just paste this into chat:

```
Create a file called GSTACK.md in the root of this project with the following content:
```

Then paste the GSTACK.md template.

### GSTACK.md Template

```markdown
# GSTACK.md — Project Memory & Conventions

> This file helps the gstack virtual team (and future you) maintain consistent context, decisions, and patterns.

## Project Overview
One or two paragraphs describing what this project is, who it's for, and the core value it delivers.

## Key Decisions & Rationale
- **Auth approach**: We chose X because... (date: YYYY-MM-DD)
- **Database / data model**: ...
- **UI / component strategy**: ...
- **Deployment & hosting**: ...

## Current Status
- **Active phase**: (e.g. Planning / Building feature X / QA / Post-ship)
- **Current focus**: ...
- **Last major milestone**: ...

## Coding & Process Conventions (for AI)
- Always follow the full gstack pipeline on non-trivial work.
- Preferred patterns / libraries: ...
- Things we deliberately avoid: ...
- Naming / file organization rules: ...
- Testing expectations: ...

## Open Risks, Assumptions & TODOs
- Risks:
- Assumptions we're making:
- Known technical debt / future work:

## Useful Context for Future Sessions
- Key user flows to protect:
- Performance or UX constraints:
- Things that surprised us / important learnings:

## Last Updated
[Date] — Updated by: [you or gstack]
```

## How to Update the Skill Later

If you want to improve the prompt, just edit `SKILL.md` in this repo. Then re-import the skill in Lovable.

## Credits

- Original gstack by [Garry Tan](https://github.com/garrytan/gstack)
- Adapted for Lovable by Hudson R&D

## License

MIT License — see [LICENSE](LICENSE) file.