# Developer Brief — WordPress Build

For whoever builds it. Everything here is a requirement, not a preference —
each line traces back to a decision in `04-website-plan.md` or
`10-the-three-jobs.md`.

---

## In-house or Will at K9 Systems?

**Use Will.** The reasoning is capacity, not capability.

The scarcest resource in this business is senior time, and it's the same
resource that delivers high-margin production work, services the growth
target, and records the voice notes the content plan runs on. Spending it on
WordPress is the most expensive way to save money available.

There's a worse risk than cost. Building in-house means the site gets picked
up between shows and put down again when September arrives — and a site that's
perpetually 70% finished is *precisely* what "they don't really exist" looks
like. The problem being solved here is absence. A half-built site doesn't fix
it; in some ways it confirms it.

Build it once, properly, with someone whose job it is. Keep the in-house
effort for the copy, the photos and the blog — which are the parts nobody
external can do anyway.

---

## Scope — phase 1

Eight pages. Finished beats extensive.

```
/                      Home
/services              Overview
  /services/<six>      Set & Staging · Lighting · Sound · Video · Power · Content
/about                 Who we are
/work                  Case studies index + individual case studies
/blog                  Index + posts
/contact               Form + details
/credentials           Company info, insurance, policies  (footer link)
```

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
