# 6D Group Ltd — Content System

Social, blog and website, run as one system: content is chosen from analytics,
written to sound like a person wrote it, and reviewed monthly against whether
it produced work.

**It's doing three jobs, not one** (`strategy/10-the-three-jobs.md`):

| | Job | Audience | Speed |
|---|---|---|---|
| **1** | **Nudge** — show existing clients the departments they aren't buying | Dozens | Weeks |
| **2** | **Cold** — become known to agencies nobody has recommended us to | Hundreds | 6–12 months |
| **3** | **Verify** — prove we're real to someone mid-decision, and get us past their finance team | Dozens | **Immediate** |

Every page and post declares its job. They succeed on different timescales and
judging one by another's yardstick is how content plans get abandoned.

**Channels:** LinkedIn (6D Group Ltd + directors) · Instagram (@6dgroupuk) ·
Facebook (6D Group Ltd) · 6d-group.com

---

## ⚠️ Start here — and it isn't the content

**Job 3 first.** Clients who experience the service at the QEII Centre ask us
to support them at other venues, and their event manager can't get us past
finance because there's nothing to point at. That's work already won on merit
and lost on paperwork.

1. **Assemble the credentials pack** — company number, VAT, public and
   employers' liability certificates, H&S policy, RAMS, accreditations, T&Cs.
   Highest-value task in the plan. A blog post can't get a supplier through
   procurement; an insurance certificate can
2. **Build `/credentials` and the phase-1 site** (`strategy/04-website-plan.md`)
3. **Ask ten years of clients for reviews.** Never been done, easiest win
   available, and reviews matter competitively in this niche

Then the content, which still needs two things only you can supply:

4. **`strategy/00-brand-brief.md`** — the remaining ⛔ sections
5. **`strategy/questions-bank.md`** — 20 questions clients actually ask, in
   their words. A year of blog posts and most of the website

---

## The weekly rhythm

| Day | What happens |
|---|---|
| **Mon** | Capture last week's metrics → `analytics/metrics-log.csv` (20 min). Edit the week's blog draft. Director post A |
| **Tue** | Blog internal review. Company LinkedIn post (Slot B) |
| **Wed** | Blog formatting, meta, images, UTMs. Director post B |
| **Thu** | **Blog publishes.** Social cut-downs go out — LinkedIn + Facebook + Instagram (Slot A). Director post C. Next week's topic confirmed |
| **Fri** | Draft next week's post. Instagram visual post (Slot C) |

Monthly: fill in `analytics/monthly-review.md`, then build next month's
calendar from what it says — 60% proven, 30% iteration, 10% bets.

---

## Repo map

```
strategy/
  00-brand-brief.md        ⛔ INCOMPLETE — the blocker
  01-voice-and-tone.md     How copy avoids sounding machine-written
  02-channel-strategy.md   What each channel is for, and the cadence
  03-content-pillars.md    Four pillars and their allocation
  04-website-plan.md       Sitemap, page-by-page, SEO, technical
  05-blog-plan.md          Weekly blog: types, topics, workflow
  06-analytics-framework.md  What we measure and how it decides the calendar
  07-90-day-roadmap.md     Sequenced plan with honest expectations
  08-profile-buildout.md   Filling in the LinkedIn/IG/Facebook pages properly
  09-director-linkedin.md  Director posts — the biggest reach lever we have
  10-the-three-jobs.md     Nudge / Cold / Verify — the organising framework

calendar/content-calendar.csv   The schedule
templates/                      Front-matter templates for every content type
analytics/                      Metrics log, scoring, monthly reviews
content/social|blog|website/    The finished pieces
```

---

## Two rules

**Nothing publishes without a voice check.** `01-voice-and-tone.md` §6, six
questions, logged as `voice_check: pass` in the piece's front matter. The
banned-phrase list in §2 is not a stylistic preference — it's the difference
between copy that reads as ours and copy that reads as generated.

**Nothing gets scheduled without evidence.** After month two, every slot in
the calendar traces back to a row in `metrics-log.csv` or to an explicit,
falsifiable bet. Ideas are welcome; they just have to go in the 10%.
