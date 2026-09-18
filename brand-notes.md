# Brand notes — mAIn human

## Name usage

- **Exact casing:** `mAIn human` — lowercase **m**, capital **A** and **I**, lowercase **n**, then lowercase **human**.
- Never write "Main Human", "MAIN HUMAN", "Mainhuman", "Main AI Human", or any title-cased variant.
- Treat it as a single wordmark, always with the space between "mAIn" and "human".
- At the start of a sentence the name still starts lowercase (this is intentional, like "iPhone"). Where that reads awkwardly, rewrite the sentence so the name isn't the first word, rather than capitalizing it.
- The character name is **Ed** — normal proper-noun capitalization, no special styling.
- A second character, **Norm**, may only be referenced as "coming later" — no capabilities, appearance, or timing details.
- Tagline is exact, including the period: **"Your favorite digital person."**

## What we do not claim

Carried over from the approved identity brief — keep enforcing this on every future page or post:

- Not an "AI crew," not a coding-only assistant, not a memory product with a decorative head.
- No measured accuracy or efficiency numbers.
- No phone or watch apps presented as available (roadmap-only, and only Windows desktop is real today).
- No claim of character choice or voice choice.
- No mention of bundled AI usage/allowances or pricing (FAQ answer is fixed: "Pricing will be announced at launch.").
- Never say "works offline" or "fully local" — speech recognition uses a cloud service; only voice output, face, and memory layer are local. Task work goes to the user's own Claude account.
- No security-certification language (no "encrypted," "SOC 2," "enterprise-grade," etc. — none of that has been verified).

## Color

Warm, human, slightly analog — avoids the cold blue/purple "AI product" palette on purpose.

| Token | Light mode | Dark mode | Use |
|---|---|---|---|
| `--bg` | `#FAF7F2` | `#17140F` | Page background |
| `--bg-alt` | `#F0EAE0` | `#211C15` | Alternating section stripes |
| `--text` | `#211D19` | `#F3EDE3` | Primary text |
| `--text-muted` | `#5B534A` | `#B8AC9A` | Secondary text, ledes |
| `--accent` | `#B25B25` | `#E08A4B` | Copper/amber — links, buttons, tagline |
| `--border` | `#DED4C4` | `#3A3227` | Hairlines, card borders |
| `--card-bg` | `#FFFFFF` | `#1F1A13` | Form fields, video placeholder card |

Dark mode is driven by `prefers-color-scheme: dark` in `style.css`; no toggle UI yet.

## Type

- **Headings:** [Fraunces](https://fonts.google.com/specimen/Fraunces) (variable, weights 500/600/700) — a warm serif with some character, matches Ed's "older, warm, dry humor" personality without looking corporate.
- **Body/UI:** [Inter](https://fonts.google.com/specimen/Inter) (weights 400/500/600) — plain, highly legible, gets out of the way for the actual copy.
- Both loaded from Google Fonts via `<link>` in `index.html`; no other external scripts or fonts.

## Open items

- **Real Ed hero image** — `assets/ed-hero.png` is referenced but not present; page currently has no image at that path. Needs the real render before launch.
- **Demo video** — `#demo` section is a static placeholder box; no video file or embed yet.
- **Waitlist backend** — the form on the page (`action="#"`) does not submit anywhere; needs a real endpoint (and privacy copy) before it goes live.
- **Pricing** — not decided; FAQ intentionally punts with "Pricing will be announced at launch."
- **Legal pages** — no privacy policy, terms, or cookie notice yet; none are linked from the footer.
