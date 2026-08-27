# Analytics Framework — How Data Decides What We Publish Next

The point of this repo is that content isn't guessed. Every cycle, what we
publish is chosen from evidence about what the last cycle did.

---

## 1. The loop

```
   ┌─────────────────────────────────────────────────────────┐
   │                                                         │
   ▼                                                         │
CAPTURE  →  SCORE  →  DIAGNOSE  →  BRIEF  →  PUBLISH  ───────┘
(weekly)   (weekly)   (monthly)   (monthly)  (continuous)
```

- **Capture** — pull raw numbers into `analytics/metrics-log.csv`. Weekly,
  same day, no exceptions. Sparse data breaks the whole model.
- **Score** — every published piece gets a Performance Score (§3).
- **Diagnose** — monthly, work out *why* the top and bottom performers landed
  where they did (§4). This is the step people skip; it's the only one that
  creates learning.
- **Brief** — next month's calendar is generated from the diagnosis (§5), not
  from a brainstorm.
- **Publish** — ship, tag, and feed back in.

---

## 2. What we measure

Three tiers. Don't confuse them — the top tier is the only one that pays.

**Tier 1 — Business outcomes** (the only ones that matter to the P&L)
| Metric | Source | Target |
|---|---|---|
| Qualified enquiries from content | CRM, source field | *set in month 1* |
| Pipeline value attributed to content | CRM | |
| Cost per qualified enquiry | Spend ÷ enquiries | |
| Enquiry → meeting conversion | CRM | |

**Tier 2 — Intent signals** (the leading indicators — watch these weekly)
| Metric | Source |
|---|---|
| Website sessions from social / organic | GA4 |
| Contact page views + form starts | GA4 |
| Blog → contact page path completion | GA4 exploration |
| Newsletter signups | ESP |
| LinkedIn profile views + follower quality (are they our ICP?) | LinkedIn analytics |
| Branded search volume | Google Search Console |

**Tier 3 — Engagement** (diagnostic only — never a goal in itself)
Impressions, reach, likes, comments, shares, saves, watch time, CTR,
avg. time on page, scroll depth.

> A post with 40 likes from people who will never buy is worth less than a
> post with 4 comments from three decision-makers in our ICP. Score for who,
> not how many.

---

## 3. The Performance Score

Every piece gets scored 0–100 within 21 days of publishing. Formula lives in
`analytics/README.md`; the shape is:

```
Score = (0.45 × Outcome)     # enquiries / signups / attributed pipeline
      + (0.30 × Intent)      # clicks to site, saves, DMs, profile visits
      + (0.15 × ICP Reach)   # % of reach that matches our target audience
      + (0.10 × Volume)      # raw impressions, normalised to channel median
```

Each component is normalised 0–100 against the trailing 90-day median for
that channel and format, so a LinkedIn carousel is compared to other LinkedIn
carousels — not to a blog post.

**Never compare scores across jobs.** A Nudge piece reaches a few dozen
people and may sell a lighting package; a Cold piece reaches thousands and
sells nothing for six months; a Verify piece is never attributed at all
(`10-the-three-jobs.md`). Normalise within channel, format **and job** — and
when a piece underperforms, the first question is which job it was doing.

**Bands**
- **80+ — Scale it.** Repurpose to two other formats, run it as paid, write
  the sequel.
- **55–79 — Keep.** Format works. Iterate the angle.
- **30–54 — Fix once.** One deliberate change (hook, format or topic), retest.
- **<30 — Retire.** Two consecutive sub-30s in a format/pillar combination
  and we stop making it.

---

## 4. Monthly diagnosis

Fill in `analytics/monthly-review.md`. Four questions, answered with evidence:

1. **What were the top 3 and bottom 3 by score?** For each, name the single
   most likely cause. Not "good engagement" — "the first line named a
   specific £ figure, which is the only post this month that did".
2. **Which content pillar is over/under-performing** relative to how much we
   publish in it? If pillar B is 20% of output and 60% of enquiries, output
   shifts next month.
3. **Which format is winning per channel?** Track separately — the answer
   differs by channel and it changes every few months.
4. **What did the audience tell us in their own words?** Comments, DMs, reply
   emails, sales-call objections. Pull direct quotes. These become next
   month's headlines — the audience writes better hooks than we do.

Output of the review is a one-page **"Next month's bets"** list: 3–5 explicit,
falsifiable bets (e.g. *"Posts opening with a client objection will out-score
posts opening with a stat, on LinkedIn, by 20+ points"*). Each bet gets tested
by at least two posts.

---

## 5. From diagnosis to calendar

Next month's calendar is allocated:

- **60% Proven** — pillar/format/angle combinations scoring 55+
- **30% Iteration** — a scoring winner changed in exactly one variable
- **10% Bets** — genuinely new formats or angles, deliberately risky

Never let Proven go above 70% — the account goes stale and the score decays
as the audience habituates. Never let Bets go below 10% — that's how you stop
finding the next thing that works.

---

## 6. Tracking hygiene

- **UTM on everything.** `?utm_source=linkedin&utm_medium=social&utm_campaign=<pillar>&utm_content=<piece-id>`
- **Piece IDs are permanent.** Format `YYYYMM-<channel>-<nn>`, assigned at
  brief stage, carried through file name, UTM and metrics log.
- **GA4** — key events on: contact form submit, newsletter signup, phone/email
  click, >75% scroll on a blog post, case-study PDF download.
- **Search Console** — connected on day 1; blog scoring needs 90 days of
  impression/position data before it means anything.
- **CRM source field is mandatory** on every enquiry. Without it Tier 1 is
  fiction and the whole score collapses into vanity metrics.

---

## 7. Honest caveats

- Organic social attribution is lossy. Dark social (someone copies a link into
  WhatsApp) is real and invisible. Treat Tier 1 as directional, and always
  cross-check against the "how did you hear about us?" field on the form.
- Blog content has a 3–6 month lag before organic search performance is
  readable. Don't retire a blog post on 30-day data.
- Below roughly 20 posts per channel there isn't enough data for the median
  normalisation to be stable. For the first two months, score manually and
  note that scores are provisional.
