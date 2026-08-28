# 14 · Search, and being found by AI

*Written 28 August 2026, against the built site in
`content/website/export/6D-website.html`.*

---

## 1. The honest headline

**Branded search: won on day one. Non-branded search: nowhere for eighteen
months. Answer engines: better than either, and nobody in this market is
trying.**

Those three sentences are the whole assessment. The rest of this document is
why, and what to do about it.

The critical thing is that **only one of the three jobs
(`10-the-three-jobs.md`) depends on search at all.** Verify is somebody typing
the company name. Nudge is an existing client on a page we sent them. Only
**cold** needs ranking, and cold was always the slow one.

So a site that performs badly on `event production company london` and
perfectly on `6D Group` is doing exactly what it was built to do. Judge it on
that, not on a rankings report.

---

## 2. Branded search

Somebody meets us, or is handed our name, and types it. Today they find
nothing, which is the entire reason this project exists.

**This is won almost immediately.** There's no competition for the exact
company name, the domain matches, and a real site with a phone number and
company details will rank first within weeks of going live. No skill required.

⛔ **One check before launch: search "6D Group" now.** If there's an unrelated
company with the same name ranking, we need to know. Common enough with
two-character-plus-word names, and it changes whether we need `6D Group
production` in titles to disambiguate.

**What makes branded search work is not the site alone.** Someone verifying us
looks at the first screen of results, not just the first link. That screen
should have:

- The website
- A Google Business Profile with the unit address, phone and photos
- LinkedIn company page
- Both director profiles
- Companies House

Four of those five are free and take an afternoon. **The Google Business
Profile is the highest-value hour on this entire list** and it isn't a website
job at all.

---

## 3. Non-branded search, and why it won't work yet

`event production company london` and its relatives are contested by companies
with fifteen years of domain age, hundreds of earned links, and budget. We have
a domain with no history and no links.

**Realistic:** nothing meaningful on head terms for 12 to 18 months, and
possibly never on the biggest ones. That's not a failure of the copy. It's
arithmetic.

Anyone promising otherwise is selling something.

### Where we can actually win

The long tail, and the copy is accidentally very good at it. The service pages
are full of things almost nobody else writes down:

| Kind of search | Why we can win it |
|---|---|
| `bs7909 electrician event power` | Named standard, and most suppliers don't mention it |
| `stock panel system event set reuse` | Specific, and tied to a real sustainability answer |
| `speaker preview room conference` | Almost nothing written about this anywhere |
| `event power logging carbon reporting` | An emerging procurement requirement with thin content |
| `conference set cabaret round tables screens` | Real problem, specific answer already written |
| `analog way switcher fibre led london` | Kit-level, and it's how technical buyers actually search |

Low volume, high intent. Somebody searching `bs7909 electrician event` is not
browsing.

**This is the argument for the technical depth in the service pages.** Every
competitor writes "full service event production, delivered seamlessly". That
copy ranks for nothing because it's identical to everyone else's. Panel sizes
in 300mm increments rank for something because they're ours.

---

## 4. Answer engines, which is the more interesting half

People increasingly ask ChatGPT, Claude, Perplexity or Google's AI summaries
rather than clicking blue links. *"Who can build a 40-stand exhibition in
London?"* is now a question people put to an assistant.

**This is a much better opportunity for us than Google, for three reasons:**

1. **The authority barrier is far lower.** Google ranks on links and domain
   age, which we don't have and can't shortcut. Answer engines pull from
   whatever most specifically answers the question, and a ten-year-old site
   full of generic copy answers nothing
2. **They reward exactly what we've written.** Checkable specifics, named
   standards, real numbers, direct statements. Vagueness is invisible to them
3. **Nobody in this market is trying.** Every competitor site is written to
   impress a human skim-reader. None of them are structured to be quoted

### What we have that works

Panel dimensions. Deck sizes. BS7909. d&b. Analog Way. Fibre. RCBOs
throughout. "30cm to 30m." "Digital radio mics because the analogue spectrum
keeps shrinking." Each of those is an extractable fact attached to a company
name.

### What's missing, in order of cost

**1. The FAQ sections are empty, and this is the single biggest miss on the
site.** Every service page ends with "Questions we get asked" and a ⛔. A
direct question with a direct answer underneath is the most quotable structure
that exists, for Google's featured snippets and for every answer engine.

Six pages, three questions each, eighteen answers of two or three sentences.
It is the cheapest, highest-return writing left in this project, and it needs
half an hour of the two of you rather than any research.

**2. No schema markup.** `Organization`, `LocalBusiness`, `Service` per
department, and `FAQPage` on the question blocks. This is how a machine knows
what the company is rather than guessing. Developer job, an hour.

**3. Nothing is dated.** Answer engines strongly prefer content with a visible
date. Blog posts need publication dates; the case studies should carry a year.

**4. No entity connections.** This is the big structural one, and it's covered
in §5.

---

## 5. The naming permissions are an SEO decision as well as a credibility one

This wasn't obvious until the photographs arrived, and it changes how urgent
those six emails are.

Search engines and language models both work on **entities and the
relationships between them**. "6D Group" is currently an entity connected to
nothing. No client names, no venues, no named events. That is a real
disadvantage in both systems and no amount of good copy fixes it.

**Naming venues is the easy half.** The QEII Centre, the Barbican and the rest
are established entities that already exist in every index and every model.
Naming a venue we've worked in connects us to it, and **venues are usually much
easier to get permission to name than clients**, because we're not implying
anything about their business.

⛔ **Worth asking for explicitly in the permission emails:** not just "may we
use this photograph" but "may we say this was at [venue] for [client]". The
second half is where the search value is, and it's the same email.

---

## 6. The blog is the engine, not the site

The site is a fixed asset. It gets built, it proves we exist, and then it sits
there. It will never rank for much on its own because it's eight pages.

**Fifty blog posts is a different proposition.** One a week for a year, each on
one specific thing, is fifty long-tail entry points and fifty dated, quotable
documents. That's the cold job, and it's the only realistic route to it.

The four posts already drafted are the right shape. `202608-blog-01` on how
crew get booked is exactly the kind of thing that gets cited, because it
answers a question nobody else answers in public.

**Expect a 3 to 6 month lag** before any of it shows in search
(`06-analytics-framework.md` already says this). Do not judge the blog at three
months.

---

## 7. Scoring the site as built

| | Score | Why |
|---|---|---|
| **Branded search** | 9/10 | Wins on launch. Only gap is the Google Business Profile |
| **Non-branded head terms** | 2/10 | No authority, no links, brutal competition. Expected |
| **Long-tail technical** | 7/10 | Genuinely strong copy. Held back by no FAQs and no blog live |
| **Answer engines** | 6/10 | Good raw material, no schema, no FAQs, no entity connections |
| **Technical build** | ⛔ | Depends entirely on what Will builds. §8 is the spec |

**The gap between 6/10 and 8/10 on answer engines is eighteen FAQ answers and
an hour of schema markup.** That's the whole difference.

---

## 8. What Will needs to build

Beyond the copy:

- **One H1 per page**, matching the page's job. Already structured that way
- **Unique title and meta description per page.** Only the home page has one
  drafted. Six more to write, and they should read like sentences rather than
  keyword strings
- **Schema markup**: `Organization` and `LocalBusiness` sitewide, `Service` on
  each department page, `FAQPage` on the question blocks once they exist
- **Real URLs per department**, not tabs or accordions on one page.
  `/services/set-and-staging` and so on
- **Internal links between the service pages.** The set page should link to
  video and power in the body copy where it mentions them, because that's how
  both Google and an assistant understand that the six are one offer
- **Descriptive alt text on all six photographs**, saying what's in the frame
  rather than repeating the company name
- **Fast, and clean Core Web Vitals.** Compress the photographs properly;
  they're the only heavy thing on the site
- **XML sitemap, and Search Console verified on day one**, so we have a
  baseline from the start rather than from whenever someone remembers

---

## 9. What to actually do, in order

1. **Google Business Profile.** Free, an hour, and it's the biggest single win
   for the urgent job
2. **Eighteen FAQ answers**, three per service page. Half an hour of the two of
   you. Highest-return writing left
3. **Add "may we name the venue" to the six permission emails.** Same email,
   large search benefit
4. **Search "6D Group" and check nothing else owns it**
5. **Schema markup and Search Console at launch**, not later
6. **Blog live from week one** and weekly after that

Numbers 1, 2 and 3 are worth more than everything else on this list combined,
and none of them is a website job.

---

*Measurement and what to review monthly: `06-analytics-framework.md`.
Build requirements: `11-developer-brief.md`.*
