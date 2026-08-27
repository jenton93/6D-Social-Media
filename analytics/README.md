# Analytics — Working Files

Framework and reasoning live in `strategy/06-analytics-framework.md`. This
folder is the doing.

## Weekly — every Monday, 20 minutes

Append one row per live piece to `metrics-log.csv`. Pull from:

| Channel | Where |
|---|---|
| LinkedIn company | Page admin → Analytics → Content |
| LinkedIn director | Post → "View analytics" on each post |
| Instagram | Professional dashboard → Insights (requires a Business account) |
| Facebook | Meta Business Suite → Insights |
| Website | GA4 → Reports → Engagement → Pages, filtered by UTM |
| Search | Search Console → Performance → Pages |
| Enquiries | CRM, `source` field |

Capture at **7, 21 and 90 days** after publishing. Social plateaus by day 21;
blog posts don't mean anything until day 90.

**Don't backfill from memory.** A gap in the log is better than a guess — a
guessed row corrupts the median that every future score is normalised against.

## The score

```
Score = 0.45×Outcome + 0.30×Intent + 0.15×ICP Reach + 0.10×Volume
```

Each component normalised 0–100 against the trailing 90-day median for **that
channel and format**. A LinkedIn carousel is only ever compared to other
LinkedIn carousels.

| Component | Built from |
|---|---|
| Outcome | enquiries, newsletter signups, attributed pipeline |
| Intent | link clicks, saves, shares, DMs, profile visits, sessions |
| ICP Reach | % of reach matching our target audience (LinkedIn demographics; estimate elsewhere) |
| Volume | impressions ÷ channel-format median |

**Bands:** 80+ scale it · 55–79 keep · 30–54 fix once · <30 retire.

Under ~20 posts per channel the medians aren't stable. For the first two
months score by hand and mark scores provisional. Don't retire anything on
provisional data.

## Monthly

Copy `monthly-review.md` to `analytics/reviews/YYYY-MM.md`, fill it in, and
build next month's calendar from its output. The review is what makes this a
system rather than a spreadsheet.
