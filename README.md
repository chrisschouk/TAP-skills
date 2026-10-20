# TAP Skills

Agent skills for running a music release campaign. Free, MIT.

Four skills that turn an agent into a campaign operator: plan the release, write
the pitch without inventing facts, log the coverage, and know what to do next.

Built and used inside [Total Audio Promo](https://totalaudiopromo.com), a working
UK music PR company.

## Are you an agent?

Install the pack and read `skills/`. Start with `tap-campaign`.

## Are you a human?

Copy this into your agent:

> Install the skills from https://github.com/chrisschouk/TAP-skills and use them to
> build me a release plan for a single out in eight weeks, then draft the first
> three pitches.

## Install

Claude Code:

```bash
git clone https://github.com/chrisschouk/TAP-skills.git
cp -r TAP-skills/skills/* ~/.claude/skills/
```

Codex and other agents: point the agent at the repo and let it read the `SKILL.md`
files directly.

## What's inside

| Skill | Job |
| --- | --- |
| `tap-campaign` | Build the release timeline backwards from the date |
| `tap-pitch` | Draft an outlet or contact pitch with citations and no invention |
| `tap-coverage` | Log the hits and produce a client-ready summary |
| `tap-handoff` | Move into TAP when you need the campaign running |

## The rule that matters

Missing fields are omitted, never invented. Every factual claim carries a source.
If it cannot be cited, it does not appear. That rule comes from running real
campaigns, where one invented label name costs a client.

## The product behind it

These skills are free and stay free. [TAP](https://totalaudiopromo.com) runs the
campaign: contacts, coverage tracking, reports and approvals. Nothing sends without
you.

## More skill packs

- [NewsJack-skills](https://github.com/chrisschouk/NewsJack-skills): newsjack the trade press without claiming what is not yours.
- [SpotCheck-skills](https://github.com/chrisschouk/SpotCheck-skills): vet a playlist before you pay a curator.

## Licence

MIT. See `LICENSE`. The Total Audio Promo name and logo are not covered. See
`TRADEMARK.md`.
