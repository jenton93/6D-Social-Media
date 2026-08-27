# 6D Group Ltd — Content System

Social, blog and website, run as one system: content is chosen from analytics,
written to sound like a person wrote it, and reviewed monthly against whether
it produced enquiries.

**Channels:** LinkedIn (6D Group Ltd + directors) · Instagram (@6dgroupuk) ·
Facebook (6D Group Ltd) · 6d-group.com

---

## ⚠️ Start here

Two things block everything else, and both need you rather than me:

1. **`strategy/00-brand-brief.md`** — what we sell, who buys it, who we're
   up against. Public sources give nothing (the site is a holding page, the
   socials are gated). Without this, every headline and every line of website
   copy is a guess.
2. **`strategy/questions-bank.md`** — 20 questions clients actually ask, in
   their words. This alone is a year of blog posts and most of the website.

The rest of the repo is built and ready to run on top of those two.

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
