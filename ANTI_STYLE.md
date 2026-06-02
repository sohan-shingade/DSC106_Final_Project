# Anti-Style Rules — "Don't look vibecoded"

A working blocklist of AI-generated design fingerprints, and the rules we use instead.
Grounded in 2026 critiques of "AI slop" / "vibecoded" interfaces (see Sources).

## Why this exists
LLMs draw the *statistical center* of their training data. Underspecified design defaults
to the same median look: Inter, blue→purple gradients, rounded cards, drop shadows, an eyebrow
kicker over a giant centered headline, a three-up stat strip, Lucide icons, glassmorphism.
The result is *homogenization* — every page looks like every other AI page. Avoiding it is not
about taste polish; it is about refusing the defaults and making specific, opinionated choices.

## Fingerprints we BAN (if it appears, it's wrong)
1. **Eyebrow kicker** — tiny UPPERCASE letter-spaced label / pill chip sitting above a big headline. The single most obvious tell.
2. **Stat cards / stat strip** — 3 evenly-spaced "big number + small label" boxes. The "hero metric" template.
3. **Card-everything** — rounded rectangles with subtle drop shadows; cards nested in cards; identical card grids; bento grids.
4. **Centered hero** — large vague headline centered, supporting line under, CTA pair.
5. **Hairline-rule + small-caps figure label** — the "editorial" version of the same templated reflex.
6. **Left-border accent pull-quote / "callout" aside.**
7. **Decoration**: gradients, gradient text, glassmorphism/blur, glow borders, neon-on-dark.
8. **Dark mode + one accent + serif** — once distinctive, now its own AI template. Don't let the palette do the design's job.
9. **Fonts**: Inter, Roboto, Open Sans, Lato, Arial, system-ui as the *design choice*. Monospace used as lazy "techy" shorthand.
10. **Icons/emoji** above headings; Lucide peppered into every section.
11. **Even, metronomic vertical rhythm**; everything in one tidy centered column.
12. **Em dashes** as default connective tissue. Prose reads AI.

## Rules we FOLLOW instead
- **Print, not product.** Model the page on a field report / broadsheet, not a SaaS landing page. Conventions a person uses on purpose: masthead, folio/running header, dateline, ruled tables, figure numbers, marginalia, colophon.
- **A real, asymmetric grid.** Flush-left, ragged-right. A narrow left margin-rail carries section numerals and notes; the main measure sits beside it; plates bleed wider. Never center the hero.
- **Numbers live in a TABLE**, not cards. Tabular figures, right-aligned, ruled rows, change shown in the one accent. (Kills tell #2.)
- **Section markers are large marginal numerals** (01 / 02 / 03) set in the rail — structural, not an eyebrow tag. (Kills tell #1.)
- **Figures are plates.** Dark inset panels with a thin keyline and a mono "FIG. n" + caption, like plates in a journal. No rounded cards, no shadows. (Kills #3, #5.)
- **Two functional colors + one mark color.** Warm newsprint paper, near-black ink, a single fire red used *only* on data marks and change figures — never as decorative fill or gradient.
- **Type with a point of view.** Display: a high-contrast idiosyncratic serif (Instrument Serif). Reading: a quality text serif (Newsreader). Labels/figures/folio: a mono used *specifically* for data and report furniture (IBM Plex Mono) — a deliberate logbook texture, not generic "techy."
- **Rhythm with tension.** Tight in the masthead and table; generous around plates. Vary it.
- **Prose like a human.** No em dashes. Short declaratives. Specific nouns and numbers.

## The test
If someone could say "an AI made this" on sight, it failed. The page should read as made by a
person with opinions: a printed wildfire dossier, not a generated web page.

## Sources
- AI slop fingerprints / eyebrow kicker / stat cards — https://www.developersdigest.tech/blog/ai-design-slop-and-how-to-spot-it , https://impeccable.style/slop/
- Claude-specific defaults (Inter, three-card grids, blue-purple, shadcn) — https://www.mindstudio.ai/blog/claude-design-avoid-generic-ai-aesthetics
- Anti-vibe-coding / anti-sameness — https://medium.com/@Rythmuxdesigner/the-anti-vibe-coding-movement-why-designers-are-rejecting-ai-generated-mediocrity-in-2026-b241ce60a369
- "Why every AI landing page looks the same" — https://dev.to/_46ea277e677b888e0cd13/why-every-ai-generated-landing-page-looks-the-same-and-how-to-fix-it-1kmo
