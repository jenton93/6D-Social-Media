# 6D Group — content repo

Read this before doing anything. It's the context and the rules; the detail
lives in `strategy/`.

## The business

**6D Group Ltd** — technical production for large-scale events. Six
departments: **Set & Staging · Lighting · Sound · Video · Power · Content**.
Strapline: *Design · Produce · Create*.

Directors: **Jenton Hollingum**, **Christian Murphy**.
Phone 0204 583 8080 · Info@6d-group.com · 6d-group.com

The specialism is **production management for large-scale events** — judgement,
not kit. Clients buy departments **pick and mix**: one or all six, one contract.

**90% of work comes from agencies and in-house AV teams**, usually when a show
has outgrown what they can deliver themselves. 10% direct end clients. Main
event type: corporate conferences and awards.

Ten years, ~£1m turnover, ~50% growth a year since 2020, and **no website or
marketing to date** — every job came from a recommendation. Marketing's job is
to continue that growth.

## The three jobs (`strategy/10-the-three-jobs.md`)

Every page and post declares one in front matter:

- **`verify`** — prove we're real to someone mid-decision. **The urgent one.**
  Work already won is being lost because searching the name finds nothing
- **`nudge`** — show existing clients the departments they aren't buying
- **`cold`** — reach agencies nobody has recommended us to. The slow one

They succeed on different timescales. Never compare their metrics.

## Hard rules — these are expensive to get wrong

1. **Never state or imply headcount.** Perceived capacity is a screening
   criterion. Never invent a bigger team either — silence, not fiction
2. **Never publish an annual crew figure.** ~100 freelance names a year reads
   as a pool, which argues our opponents' case. **Scale is per show**:
   "crew of 40 on site"
3. **Never name a competitor** in public content — not Aztec, Encore, 4Wall,
   White, Red, Lux. Aztec is also a client. Attack the model, never the names
4. **Never brief against other suppliers from the company page.** Producers
   distrust it. The point-of-view argument belongs on **Jenton's or
   Christian's personal LinkedIn**, in first person, as personal experience
5. **Never publish prices.** Agencies and direct clients pay different rates.
   Explain *how* pricing works instead
6. **Never name a client without written permission.** Trade work is
   white-label. Check Boomtown and BGT contracts before either is used
7. **Never use stock photography.** Real shows only

## Voice (`strategy/01-voice-and-tone.md` — read it in full before writing)

UK English. First person. Contractions. Specific numbers and real nouns.

Banned: "in today's…", "it's not just X, it's Y", delve, leverage, seamless,
robust, elevate, unlock, "that's where we come in", "here's the thing",
rule-of-three with three equal-length items, emoji bullets.

**Every piece is read aloud before publishing** and logged `voice_check: pass`.

## The method that makes this work

Directors are busy. **Content comes from voice notes**, not writing — 60–90
seconds, transcribed, edited keeping their phrasing, approved before posting.
See `templates/director-voice-note-brief.md`.

The 27 Aug note produced a cornerstone blog post, four social cut-downs,
website copy for three pages and four queued posts. Raw transcripts go in
`content/raw/` with unused material indexed.

## Where things are

```
strategy/     00 brand brief · 01 voice · 02 channels · 03 pillars
              04 website · 05 blog · 06 analytics · 07 roadmap
              08 profiles · 09 director LinkedIn · 10 three jobs
              11 developer brief · questions-bank.md
content/      website/ (copy pack + HANDOVER) · blog/ · social/ · raw/
calendar/     content-calendar.csv
analytics/    metrics-log.csv · monthly-review.md
```

## Current state

- Website copy drafted, waiting on: crew/show numbers, company registration
  details, insurance levels, client permissions, a photo of the directors.
  See `content/website/HANDOVER.md`
- Will at K9 Systems has been engaged since January, waiting on copy
- First blog post and its four cut-downs are approved and ready to schedule
- `strategy/questions-bank.md` is still empty — it's a year of content

## Working conventions

- Branch: `claude/social-blog-content-strategy-yimpq5`
- Repositories are moving from `jenton93/` to a **6D Group organisation**. If
  access fails, it's the org authorisation step (see `START-HERE.md`), not a
  broken repo
- Commit whenever meaningful work is done; keep messages factual
- Mark assumptions `‹ASSUMED›` and hard gaps `⛔`. **Never hand back a blank
  template** — copy stalled for eight months that way. Write it through and
  let them correct
