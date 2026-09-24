# Positioning & Messaging — a Claude skill

A rigorous B2B positioning and messaging skill that runs a four-stage sequence built on the published methods of four practitioners, each covering the others' blind spots. It turns evidence into a decision, the decision into copy, and the copy into a story — in that order — and produces one messaging framework document a salesperson who missed the workshop can open and use in five minutes.

**Positioning is a decision. Messaging is the expression of that decision.** Most bad messaging isn't a writing problem; it's an undecided or unevidenced positioning problem papered over with adjectives. The sequence is the method.

| Stage | Question | Source | Output |
|---|---|---|---|
| 0. Evidence | Why did people actually switch — and what stopped the ones who didn't? | Bob Moesta | Demand brief |
| 1. Decision | Where do we compete, and what can only we claim? | April Dunford | Positioning decision |
| 2. Expression | Can a stranger tell what this is in five seconds? | Fletch PMM | Messaging & homepage copy |
| 3. Narrative | What changed in the world that makes this urgent? | Andy Raskin | Strategic narrative |

## What's in here

```
SKILL.md            the sequence, the gates, the guardrails
GETTING-STARTED.md  what inputs you need, and what to do if you have none
references/         one file per stage, pulled in only when that stage is active
```

## How to get it

- **Download:** click the green **Code** button → **Download ZIP**, or grab the latest [release](../../releases).
- **Clone:** `git clone https://github.com/chrisrodde-build/positioning-and-messaging-skill.git`

## How to use it

**Claude Code / Claude (Cowork):** put these files in a folder named `positioning-and-messaging` inside your skills directory, so you end up with `~/.claude/skills/positioning-and-messaging/SKILL.md`. If you downloaded the ZIP, just rename the unzipped folder to `positioning-and-messaging` and drop it in `~/.claude/skills/`. Restart your session and it triggers automatically when you describe positioning or messaging work.

**Cursor or any other capable agent:** point the agent at `SKILL.md` and let it pull in the reference files as each stage becomes active. `GETTING-STARTED.md` is written for you, the human — read it once before you begin.

You don't invoke it by keyword. Just describe the work: *"Help me rebuild our messaging framework,"* *"Our positioning isn't landing,"* or *"Review our homepage against our actual differentiation."*

## What it needs from you

The output is only as good as the evidence you bring. Ideally: 6–12 transcribed customer conversations weighted toward losses and stalls, live web access for the competitive table-stakes check, your current homepage and decks with their dates, and your loss/stall reasons. No transcripts? `GETTING-STARTED.md` has fallbacks that still work. Treat the output as strong, well-grounded hypotheses — not a finished decision you can skip owning.

## Attribution

This skill synthesizes publicly published methods. It is **not affiliated with, endorsed by, or reviewed by** any of the practitioners named; any errors in the summaries are the skill's, not theirs. Their work goes far deeper than any summary — go to the sources, buy their books, and hire them:

- **April Dunford** — *Obviously Awesome*, *Sales Pitch*, and the *Positioning* podcast — [aprildunford.com](https://www.aprildunford.com/)
- **Bob Moesta** — *Demand-Side Sales 101*; the Four Forces developed with Chris Spiek — [demandsidesales.com](https://www.demandsidesales.com/)
- **Anthony Pierri & Rob Kaminski** — Fletch PMM — [fletchpmm.com](https://www.fletchpmm.com/)
- **Andy Raskin** — ["The Greatest Sales Deck I've Ever Seen"](https://medium.com/the-mission/the-greatest-sales-deck-ive-ever-seen-4f4ef3391ba0) and subsequent writing

The sequencing, the gates, and the deliverable spec are how the method has been assembled here.

## License

MIT — see [LICENSE](LICENSE). Free to use, adapt, and share.

Built by Chris Rodde, [Two Spruce Partners](https://twospruce.co). If you build something with it or improve it, I'd love to hear about it.
