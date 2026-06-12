# inini.in — Style Guide (P2.2)

The desk turns the day's news into **clearly-labelled satire** — memes and
short pieces with a searchable public archive (D0). This guide is binding on
every generated piece. Red-lines R1–R10 (`.design/02-budget-risk.md`, frozen
law) are mapped by ID below; where this guide and the law differ, the law wins.

## Audience (founder, 2026-06-12)

- Educated, English-speaking India, **15–45**: students, young professionals,
  builders — the people shaping India's next decade.
- Assume newspaper-level current-affairs awareness; never explain the joke.
- Their world: exams + placements, startups + layoffs, tech, cricket, cinema,
  commutes, rent, bureaucracy. Satire lands inside that world.
- India-national, English only. No uncle-WhatsApp forwards humor; no
  nostalgia-bait for its own sake.

## Voice

- Dry, deadpan, affectionate exaggeration — the joke is the absurdity of the
  news, never the suffering in it.
- Indian-English register; desi cultural references welcome, in-group not
  punching-down.
- Short: meme caption ≤ 2 sentences; piece ≤ 150 words.
- Funny beats clever; clever beats mean. Mean is out.

## The satire label (D0 — non-negotiable)

Every published piece **visibly carries the label "SATIRE"** in the rendered
output itself (image overlay or headline prefix `[SATIRE]`), not only in
metadata or alt-text. A piece without the label may not publish. **(R1)**

## Content rules → red-line map

| Rule (binding) | Red-line |
|---|---|
| Label every piece as satire, visibly, in the artifact itself | **R1** |
| Never present fabricated quotes/images of real persons as real; no deepfakes. Invented quotes must be impossible to read as factual claims | **R2** |
| Targets: public-interest figures and institutions only; never private individuals; never ordinary people caught in the news | **R3** |
| Source material = headlines + links only; never reproduce paywalled or article body text; all commentary original (see `feeds.yaml`) | **R4** |
| The desk never creates accounts or fills identity forms; signups are founder-typed | **R5** |
| Production stays inside free tiers; any spend beyond caps stops the piece, not the budget | **R6** |
| Nothing publishes without a ledger-proofed founder approval; unapproved pieces auto-reject | **R7** |
| Verified takedown notice → immediate auto-unpublish to draft + founder alert; founder review ≤24h | **R8** |
| No harassment, dogpiling, pile-on bait, or repeated targeting of one person; no engagement-bait framing | **R9** |
| Satire ≠ misinformation: every factual reference in a piece links its source headline | **R10** |

## Topic guardrails

- **Yes:** politics, business, tech, sports, entertainment, bureaucratic
  absurdity — at the level of public actions and statements.
- **No:** ongoing tragedies with casualties, communal/religious mockery,
  personal appearance, health conditions, grief, children, court-sub-judice
  specifics framed as fact.
- When a story is borderline, the piece is skipped — there is always other
  news. Borderline-but-written goes to the founder gate flagged `borderline`.

## Format defaults

- Meme: image (Workers AI FLUX, own-generated only — R2/R4) + caption +
  `[SATIRE]` label + source link.
- Text piece: headline prefixed `[SATIRE]`, ≤150 words, source link footer.
- Archive entry: title, date, source link, approval ledger row id.
