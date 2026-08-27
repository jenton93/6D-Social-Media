# Website Plan

6d-group.com is currently a "coming soon" page. Every social post we publish
before that changes sends interested people to a dead end — which is why the
site is the first build in the roadmap, ahead of the content calendar.

---

## What the site has to do

One job: turn someone who has heard of us into someone who contacts us.

That's it. Not "communicate our brand values". A visitor should be able to
answer four questions inside 30 seconds:

1. What do they do?
2. Is it for someone like me?
3. Are they any good?
4. What happens if I get in touch?

Any page that doesn't help answer one of those is a page we don't need yet.

---

## Sitemap — phase 1 (launch)

```
/                      Home
/services              Overview + links to each
  /services/<service>  One page per core service   ← the money pages
/about                 Who we are, why we exist
/work                  Case studies index
  /work/<project>      Individual case studies
/blog                  Index
  /blog/<post>         Posts
/contact               Form + direct details
```

Phase 2 (month 3+, only if the data justifies it): sector landing pages,
resources/downloads, careers, FAQ hub, pricing.

Don't build phase 2 first. An eight-page site that's finished beats a
thirty-page site that's half-written, and half-written is what always happens.

---

## Page-by-page

### Home
- **Above the fold:** a plain sentence saying what we do and who for. No
  slogan. If someone read only this line they should understand the business.
- Proof immediately after — logos, a number, a named result. Before any
  description of our process.
- Three services, one line each, linking out. **Set & Staging and Video lead**
  — they're the front door and where the business is strongest. Lighting,
  Sound, Power and Content follow, and the page should make clear they can be
  taken separately or together (pick and mix) rather than as a fixed bundle.
- One case study, in full, on the homepage.
- A short "how it works" — 3 steps, what actually happens.
- Contact block. Repeated at the bottom.

### Service pages *(the most commercially important pages on the site)*

Six pages, one per department. **Set & Staging and Video get built and written
first** — they carry the SEO and win the first job. The other four still get
proper pages, because they're the second sale and existing clients land on
them.

Every service page needs a line making the pick-and-mix explicit: this can be
taken on its own, or with any of the other five, on one contract.

Structure:
1. What this is, in one sentence
2. The problem it solves — described so precisely the reader thinks "that's us"
3. What you get — deliverables, concrete
4. How it runs — timeline, stages, who's involved
5. What it costs, or how pricing works. **Say something.** A range, a "from",
   a "typical projects run £X–£Y". Refusing to discuss price is the single
   biggest cause of drop-off on B2B service sites
6. Proof specific to this service
7. FAQ — the real objections, answered honestly
8. Contact

### About
Not a history — but the origin belongs here. **6D started as a lighting
company**, and that's the kind of specific, unfakeable detail that earns
trust with a technical reader. Say it plainly.

Then: who runs it, what we believe about how big shows should be resourced,
and photos of actual people. This page is read almost entirely by producers
deciding whether to trust us with their reputation, so the senior team being
visible and named matters more here than anywhere else on the site.

### Work / case studies
Format for each: context → the problem → what we did → what happened, with
numbers → a quote. 400–800 words. Three at launch is enough; zero is not.

**Most of these will be anonymised**, because trade work is white-label. Write
them as *"a 1,600-delegate financial services conference, three halls, 11-hour
get-in"*. For this audience the numbers and the constraints are the proof —
the logo never was. Where a client has agreed to be named, name them.

### Contact
Form with the fewest possible fields (name, email, one message box, and a
"how did you hear about us?" dropdown — that field feeds the analytics loop
and it's the only reliable attribution we'll get). Plus phone, email and a
sentence saying who replies and how quickly.

---

## Technical requirements

- **Analytics before launch, not after.** GA4 with key events configured
  (form submit, phone click, email click, 75% blog scroll), Search Console
  verified, sitemap submitted. Launching without these loses data that can't
  be recovered retrospectively.
- Mobile first — most social traffic is mobile and it'll be the majority of
  everything we send.
- Core Web Vitals in the green. Compress every image; it's the usual culprit.
- **Open Graph tags on every page** — title, description, and a 1200×630
  image. Without them, links shared to LinkedIn and Facebook render as a grey
  box, and that alone measurably suppresses clicks.
- Schema markup: Organization on every page, Article on blog posts,
  LocalBusiness if we're pursuing local search.
- SSL, redirects mapped, 404 page that points somewhere useful.
- Blog CMS the team can post to without a developer. If publishing needs a
  ticket, the weekly cadence will not survive month two.

---

## SEO foundations

- One target keyword per service page, chosen for buying intent over volume.
  "commercial X in Lincolnshire" beats "what is X" every time.
- Title tags under 60 chars, meta descriptions under 155, both written as
  copy rather than keyword strings.
- One H1 per page, descriptive H2s.
- Internal links: every blog post links to at least one service page; every
  service page links to at least one case study.
- Google Business Profile claimed and completed — it's often the highest-
  converting "page" a small UK business has, and it isn't on their website.
