# 13 · Design direction

*For Will at K9 Systems, and for whoever is holding the camera on the next
three shows. Written 27 August 2026.*

---

## 1. The site is photo-led, and here's why that isn't a style choice

The urgent job is **verify** (`10-the-three-jobs.md`). Someone has met us at an
event, or been handed our name, and they search it. Right now they find
nothing, and a company with no footprint doesn't read as small or risky, it
reads as not a company.

**Photographs fix that faster than words can.** Copy can be written by anyone
in an afternoon. A photograph of a real build, in a real venue, with real crew
in it, cannot be faked and cannot be borrowed. It does the verification work in
under a second, before anyone reads a sentence.

That matters more here than it would for most businesses, because the two
things that would normally do this job are unavailable to us:

- **Testimonials** are awkward when 90% of the work is white-label. Asking an
  agency to publicly praise its subcontractor asks them to reveal they used one
- **Named case studies** need written permission per client, which we don't yet
  have

Photographs are the proof we can put up without asking anyone's permission,
provided we're careful about which ones (§3).

There's a second reason. The register is quiet (`01-voice-and-tone.md`). Quiet
copy plus a plain page reads as thin. **Quiet copy plus strong photography
reads as confident**, because the pictures carry the scale and the words don't
have to. It's the combination that lets us stop claiming things.

---

## 2. The hard constraint

> **Never use stock photography.** Real shows only. (`CLAUDE.md`, rule 8)

This is not negotiable and it is the single biggest risk to this design. A
photo-led site with four photos looks worse than a typographic site with none.
Stock is what every competitor uses and it's instantly recognisable to anyone
in this industry, which makes it worse than nothing: it says either that we
have no work of our own to show, or that we think the reader won't notice.

**So the design scales to the library.** Build it for the number of good
photographs that actually exist, and grow it. §5 is the shot list.

**Placeholders in a mockup are a different thing** and they're fine. The design
direction page uses generated abstract blocks so the layout can be judged with
something in the frame, each marked "Placeholder". They're abstract rather than
stock on purpose: stock carries a licence, and it would make the mockup look
better than the site can launch, which is a bad footing for a design decision.
They live in `content/brand/placeholders/` and that folder gets deleted once the
shot list is filled.

⛔ **The one thing I need before this can be finalised: how many usable
photographs exist right now?** Not "we've got loads on a hard drive
somewhere", an actual count of shots you'd be happy to put in front of a
producer. If it's under fifteen, the first version of the site uses fewer,
bigger images and we fill it out over the first six months.

---

## 3. Which photos we can publish

The naming rule (`CLAUDE.md`, rule 6) is usually read as a rule about text. It
isn't. **A wide shot of a branded set identifies the client as clearly as
writing their name.** So every photograph sorts into one of three tiers before
it goes anywhere near the site.

### Tier 1 · Unattributable. Use freely, no permission needed

Nothing in frame identifies whose show it is.

- Crew working a build. Truss going up, deck going down, a person on a ladder
- Rigging and structure. Truss corners, motors, bridles, points
- The back of house. Distro, cable runs, a rack, a comms position
- The workshop. CNC cutting, panels stacked, a print coming off
- A dark room from the back before doors, screens blank or showing colour bars
- Detail. A desk under worklight, a fixture, a connector panel

**This tier is the workhorse, and it happens to be the most on-brand material
we have.** Black rooms, cool light, people working. It's what the business
actually looks like, it needs no clearance, and it's the stuff nobody else
bothers to shoot because it isn't glamorous. That's exactly why it reads as
real.

### Tier 2 · Identifiable but generic. Worth a quick check

A full stage, screens lit but showing no branding or readable content. A room
full of people from behind. Recognisable venue architecture.

Usually fine. Send it to the client with a one-line "happy for us to use this?"
before publishing. Most say yes and it takes a minute.

### Tier 3 · Attributable. Written permission, same as naming

Logos, branded content on screen, a set carrying an identity, anything where a
reader could say whose show it was.

Same process as naming a client, and worth doing for two or three, because
Tier 3 shots are the ones that prove scale most convincingly.

**Practical note for whoever is shooting: a lot of Tier 3 becomes Tier 1 by
moving three feet or shooting a moment earlier.** The same stage, framed
before content goes up, or shot from the side to lose the screen, is clean.
Get in the habit of taking both.

---

## 4. What the design does

### Black is the ground

The logo is a black circle. The work happens in dark rooms. A white page with
black text is the safe corporate default and it fights the photography, because
every image becomes a bright rectangle sitting in a bright field.

**Dark sections let the photographs be the light source.** The pictures glow,
the page recedes, and the whole thing looks like the inside of a venue rather
than like a brochure about venues.

Not all dark. The pattern is: dark for the hero, the department grid and the
case studies, where photos live. Light for the reading sections, where copy
lives. The alternation gives the page rhythm without any decoration doing it.

### Photographs go full-bleed

Edge to edge, no gutter, no rounded corners, no drop shadow, no border. A
photograph in a padded card with a shadow looks like a brochure from 2014.
Full-bleed reads as confident and it makes a small library look bigger, because
each image gets more room.

### No text on top of busy images

This is where most event-supplier sites fall apart. A headline over a
photograph of a lit stage is unreadable, and the usual fix (a black gradient
over the whole picture) ruins the photograph to save the text.

**Text sits next to photographs, or on the flat black between them.** The one
exception is the hero, where a single short line over the darkest third of a
deliberately chosen image is fine, and that image gets picked for the space
rather than the space getting forced onto the image.

### Cyan is a signal, not a wash

`#008EAA` is used for eyebrows, rules, one word in a headline, and links.
Never as a background field, never as a tint over a photo. It appears rarely
enough that it means something when it does. Everything else is black, white
and the photographs.

The photography helps here: a lot of what we shoot already has cool blue-white
light in it, so the accent belongs to the pictures rather than being applied
on top of them.

### Type

**Audiowide** at display size only, for the logotype and page headings. It's a
display face and it becomes illegible below about 20px. **Arimo** for
everything else, at 17px, with generous line height.

The type scale should be wider than feels comfortable. Big headings and normal
body, with nothing in between. Middle sizes are what make a page look like a
template.

### Space

Quiet, expressed visually, is space rather than restraint in the decoration.
Generous margins, one idea per screen, and nothing competing. A page that
isn't in a hurry reads as a company that isn't in a hurry.

---

## 5. The shot list

Roughly thirty photographs makes the site work properly. Here is what they're
for, in the order they matter.

### Essential, the site is weak without these

| # | Shot | Where it goes | Tier |
|---|---|---|---|
| 1 | **The hero.** A room from the back or high side, lit, before doors. Wide, dark, with depth. The single most important image on the site | Home hero, full bleed | 1 or 2 |
| 2-4 | **Three case study leads.** The room from the audience position, or the build mid-way. One per show | Case studies | 2 or 3 |
| 5-10 | **One per department.** Close and specific, not six wide shots of stages: a distro board with the RCBOs visible · a truss corner with motors · the CNC cutting or a large print coming off · a desk under worklight · an LED wall from an angle showing the seam · the speaker preview room set up | Department grid | 1 |
| 11 | **The workshop, wide.** Proves there are premises and a build capability behind the hire | About | 1 |
| 12 | **A build in progress with crew in it.** People working, scale visible. Backs and mid-distance, no posed faces | Home or About | 1 |

### Strongly wanted

| # | Shot | Where |
|---|---|---|
| 13-18 | **A second per department**, so the service pages aren't sharing with the grid | Service pages |
| 19-22 | **Get-in and load-out.** Trucks, empty room, cases. Nobody photographs this and it's the most honest thing we do | Blog, social, How we work |
| 23-25 | **Detail shots.** Stock panel edges, a rack, a cable run dressed properly. Small, quiet, and they say "these people care" faster than a sentence can | Anywhere needing texture |
| 26-30 | **The same room, three times.** Empty, mid-build, finished. Used as a sequence this is the strongest single thing we could publish, and it's free: it's three photos from one fixed position on one job | Home or a case study |

**That last one is worth doing deliberately on the next show.** Same spot,
same phone, three times across the day. Nobody in the industry publishes it
and it explains the entire business without a word of copy.

### How to actually get these

Most of this is a phone in the right hand at the right moment, not a
photographer. Modern phones are fine in dark rooms, and a slightly grainy real
photo beats a polished stock one every time.

- **On the next three shows**, one person takes ten minutes at three points:
  empty room, mid-build, and after the room is lit before doors
- **One hour in the workshop** covers shots 5-10 and 11 in a single session
- **Shoot wider than you think**, and shoot the same thing with and without
  anything branded in frame, so a Tier 3 shot always has a Tier 1 twin

⛔ **A proper photographer for one day on one large show** is the single
highest-value spend on this whole project, and it would produce most of the
essential list at a quality nothing else gets close to. Worth pricing.

---

## 6. What happens if the photos don't arrive

Being honest about this, because it's the way this project fails.

The copy has been sitting waiting since January. If the design now waits on a
photo library, the site doesn't launch this year either.

**So the build is designed to launch at three photographs and improve.** The
layout uses fewer, larger images at low count and more, smaller ones as the
library grows, with no redesign in between. Will should build the image slots
so that adding a photograph later is a WordPress upload, not a layout change.

Launching with three real photographs and adding to it is better than waiting
for thirty. It is very much better than launching with stock.

---

## 7. What I need to finish this

- ⛔ **A count of usable photographs that exist today**, and ideally a look at
  them. It determines the layout
- ⛔ **The logo as SVG** (`content/brand/README.md`)
- ⛔ **A decision on the photographer day**, because if it's a yes the design
  should be built around what that day will produce
- ⛔ **Permission for two or three Tier 3 shots**, same conversation as the
  client naming permissions that are already outstanding

---

*Palette, type and asset rules: `content/brand/README.md`.
Page structure and copy: `content/website/`.
Build requirements: `11-developer-brief.md`.*
