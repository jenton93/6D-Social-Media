# Developer Brief — WordPress Build

For whoever builds it. Everything here is a requirement, not a preference —
each line traces back to a decision in `04-website-plan.md` or
`10-the-three-jobs.md`.

---

## Status

**Will at K9 Systems has been engaged since January. He is waiting on copy.**

That's been the blocker for eight months, and it's worth naming why, because
it changes how this gets handed over.

Copy hasn't happened because writing it requires a long, uninterrupted sitting
from the person with the least available time in the business — the same
constraint that shows up everywhere else in this plan. Handing back a template
with twelve blanks to fill in would produce the same result again.

**So the approach is: everything gets written, including the parts I have to
assume.** Assumptions are marked `‹ASSUMED›` and stated plainly. Correcting a
wrong sentence takes thirty seconds; composing a right one from a blank page
takes an afternoon that never comes.

Anything still marked ⛔ is a fact I genuinely cannot invent — a company
number, an insurance figure. Those are the only things needed before Will can
start, and each is a lookup rather than a piece of writing.

---

## Scope — recommended for launch

Eight pages, not the fourteen in the January brief. Copy is the bottleneck and
a half-finished site recreates the exact problem we're solving. Six thin pages
also rank worse than one strong one.

```
/                     Home
/what-we-do           Six event types as sections on one page
/services             Six departments as sections on one page
/how-we-work          The six steps
/work                 Case studies
/about                ← add this. Missing from the January brief
/contact
/credentials          Footer link
```

**Build the navigation with room for phase 2** — individual event-type pages,
individual service pages, and trade hire — so none of it is retro-fitted.

**Build the event-type pages first** if anything has to wait. That's how
buyers search — a producer looks for "conference production company", not
"lighting hire". Service pages serve the existing client discovering the other
departments, and the technical reader checking depth.

**Trade hire** comes later — build the navigation with room for it now.

**Brand:** green and black on white. **Audiowide** for display/logo, **Arimo**
for body. Both Google Fonts.
⛔ *Exact green hex needed — the unit signage photographs as cyan under its
LEDs, so I can't sample it reliably.*

**Contact:** +44 20 4583 8080 · Info@6d-group.com

**Note on the reference sites** (whitepd.com, redeventproduction.co.uk): take
the structure, not the styling. Both are direct competitors, and a site that
looks like a third version of the same thing makes the choice between them
feel arbitrary. The black/green/Audiowide combination is already more
distinctive than either — lean on it.

---

## Non-negotiable requirements

**Publishing**
- The blog must be postable by the team **without a developer**. If publishing
  needs a ticket, the weekly cadence dies in month two. This is the single
  most important technical requirement on the page
- Simple block editing on standard pages too — copy will change often in the
  first three months

**Findability** *(the site exists to solve an absence problem)*
- Searching "6D Group" must return this site. Verify before sign-off
- Google Search Console verified, sitemap submitted, at launch
- Google Business Profile claimed and linked
- Schema markup: `Organization` sitewide, `Article` on posts,
  `LocalBusiness` if we pursue local search
- Company name, address and phone identical to LinkedIn, Facebook, Google
  Business Profile and Companies House. Mismatches are a trust signal in the
  wrong direction

**Sharing**
- **Open Graph tags on every page** — title, description, 1200×630 image.
  Without them, links shared to LinkedIn and Facebook render as a grey box and
  clicks drop measurably. Test with LinkedIn's Post Inspector before launch

**Measurement** — must be live *before* launch, not after
- GA4 with key events: contact form submit, phone click, email click,
  credentials pack download, 75% blog scroll
- UTM parameters preserved through any redirects
- Contact form includes a **"how did you hear about us?"** field. Non-negotiable
  — without it a business that has always grown by word of mouth can't tell
  word of mouth from marketing, and every number in the monthly review becomes
  an opinion

**Performance and presentation**
- Mobile first. Most social traffic is mobile
- Core Web Vitals green. Compress every image — show photography is always the
  culprit
- Real photographs of real shows throughout. No stock imagery of any kind:
  the site's job is proving a working company exists, and stock does the
  opposite
- Brand: black ground, single cyan accent, white type, per the unit signage.
  Disciplined and high-contrast — no second accent colour needed

**Credentials page**
- Every document a **direct PDF link**. The event manager's task is forwarding
  them; anything behind a form or login gets abandoned rather than forwarded
- One combined "Supplier information pack" PDF

**Housekeeping**
- SSL, 404 page pointing somewhere useful, redirects mapped from the holding
  page
- Two admin accounts minimum. Sole access to a live site is a painful problem
- Backups configured before launch

---

## What we supply to the developer

- Copy — `content/website/` (in progress)
- Photography — real show photos, sized and captioned
- Logo as SVG with transparency, plus exact brand hex values
- Credentials documents as PDFs
- Google Analytics and Search Console access

## Sign-off checklist

- [ ] Searching the company name returns the site
- [ ] Every page has a working OG preview (test in LinkedIn Post Inspector)
- [ ] A test form submission arrives, and appears in GA4
- [ ] "How did you hear about us?" field present and captured in the CRM
- [ ] Credentials PDFs download in one click
- [ ] NAP consistent across all five listings
- [ ] Someone non-technical publishes a test blog post unaided
- [ ] Mobile check on a real phone, not a simulator
