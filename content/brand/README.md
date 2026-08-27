# Brand assets

## The colour is cyan, not green

**#008EAA.** Sampled from the round logo, which is the only accurate source we
have. Every earlier draft in this repo called it green, on the assumption that
the unit signage was photographing cyan because of the LEDs behind it. That was
wrong. The signage is accurate and the brand colour has always been a cyan.

Anything written before 27 August 2026 that says "green" means this.

## Palette

| Token | Light | Dark | Notes |
|---|---|---|---|
| Brand | `#008EAA` | `#008EAA` | The logo colour. Fills, large display, the hero rule |
| Accent (text, links) | `#007A93` | `#00C2E8` | Slightly off the brand value so body-size text passes AA |
| Accent bright | `#008EAA` | `#3FCBE6` | Headline highlights on black |
| Ground | `#FFFFFF` | `#0A0F11` | |
| Raised | `#F4F8F9` | `#141B1D` | Cards, quiet panels |
| Ink | `#0A0F11` | `#EEF4F5` | |
| Muted | `#58686D` | `#93A3A7` | |
| Hairline | `#E1E9EB` | `#222C2E` | |
| Deep | `#000000` | `#000000` | Hero and footer. Pure black, same as the logo circle |

**Why the accent isn't just #008EAA everywhere.** #008EAA on white is a 3.85:1
contrast ratio, which fails WCAG AA for body text. #007A93 is 4.99:1 and reads
as the same colour. Use the true brand value for fills, rules and large type,
where the ratio doesn't apply, and the accent for anything set at reading size.
Buttons: white text on `#007A93` in light, `#04171C` text on `#00C2E8` in dark.

## Type

**Audiowide** for display and the logotype. **Arimo** for body. Both Google
Fonts, both free, both already in the copy pack builds.

## Files

- `logo-round-256.png` — the round mark, black circle, cyan ring and wordmark.
  Transparent outside the circle. 256px, which is enough for a favicon and for
  the copy pack, and not enough for the site
- ⛔ `logo-round.svg` — **still needed.** In SharePoint at
  `Business Info/Logo Round.svg`. Will needs the vector
- ⛔ `logo-sheet.ai` — the Illustrator master, `Business Info/Logo Sheet.ai`.
  Worth having in the repo even though it isn't web-usable, because it's where
  any future variant comes from
- ⛔ Any single-colour, reversed or horizontal lockups on that sheet

## Rule

The logo is a black circle. On a white page it needs air around it, and on
anything busy it needs the black circle rather than a knocked-out version, or
the wordmark stops reading. Never place it over show photography without the
circle.
