---
name: FranVisuals
description: A dual-theme portfolio for a graphic designer working in streaming, sports, and finance broadcast graphics.
colors:
  bg-dark: "#05090f"
  bg-elevated-dark: "#0a1220"
  panel-dark: "#0c1424"
  text-dark: "#eaf2fb"
  text-dim-dark: "#8ea3bd"
  accent-dark: "#38bdf8"
  accent-bright-dark: "#7dd3fc"
  on-accent-dark: "#04121f"
  available-dark: "#2ee06f"
  veil-dark: "rgba(3, 8, 16, 0.94)"
  bg-light: "#eef1f7"
  bg-elevated-light: "#ffffff"
  panel-light: "#ffffff"
  text-light: "#0a1220"
  text-dim-light: "#4d5f7a"
  accent-light: "#0b6fa8"
  accent-bright-light: "#095b8b"
  on-accent-light: "#ffffff"
  available-light: "#0f9d4f"
  veil-light: "rgba(10, 18, 32, 0.9)"
  logo-navy: "#0d1b33"
  caption-ink: "#f4f9ff"
typography:
  display:
    fontFamily: "Bebas Neue, Archivo, sans-serif"
    fontSize: "clamp(2.8rem, 8.5vw, 6rem)"
    fontWeight: 400
    lineHeight: 0.94
    letterSpacing: "0.01em"
  stat-lead:
    fontFamily: "Bebas Neue, Archivo, sans-serif"
    fontSize: "clamp(3.2rem, 8vw, 4.6rem)"
    fontWeight: 400
    lineHeight: 0.9
    letterSpacing: "0.01em"
  headline:
    fontFamily: "Bebas Neue, Archivo, sans-serif"
    fontSize: "clamp(2.2rem, 5vw, 3.4rem)"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.01em"
  title:
    fontFamily: "Bebas Neue, Archivo, sans-serif"
    fontSize: "1.75rem"
    fontWeight: 400
    lineHeight: 1
  wordmark:
    fontFamily: "Bebas Neue, Archivo, sans-serif"
    fontSize: "1.6rem"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.03em"
  wordmark-sm:
    fontFamily: "Bebas Neue, Archivo, sans-serif"
    fontSize: "1.3rem"
    fontWeight: 400
    lineHeight: 1
  ticker:
    fontFamily: "Bebas Neue, Archivo, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 400
    letterSpacing: "0.06em"
  counter:
    fontFamily: "Bebas Neue, Archivo, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    letterSpacing: "0.06em"
  body:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(1rem, 1.5vw, 1.12rem)"
    fontWeight: 400
    lineHeight: 1.5
  action-lg:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 700
    letterSpacing: "0.02em"
  action:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.92rem"
    fontWeight: 700
    letterSpacing: "0.02em"
  action-md:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.9rem"
    fontWeight: 700
  action-sm:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.85rem"
    fontWeight: 700
    letterSpacing: "0.02em"
  link:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.88rem"
    fontWeight: 400
  prompt:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.84rem"
    fontWeight: 600
    letterSpacing: "0.04em"
  caption:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.8rem"
    fontWeight: 600
  fine:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.78rem"
    fontWeight: 400
  label:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.76rem"
    fontWeight: 700
    letterSpacing: "0.09em"
  label-sm:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.72rem"
    fontWeight: 700
    letterSpacing: "0.12em"
  label-xs:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.7rem"
    fontWeight: 700
    letterSpacing: "0.13em"
  label-2xs:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.66rem"
    fontWeight: 600
    letterSpacing: "0.09em"
  tag:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.64rem"
    fontWeight: 800
    letterSpacing: "0.07em"
rounded:
  none: "0px"
spacing:
  xs: "0.42rem"
  sm: "0.6rem"
  md: "1.1rem"
  lg: "2rem"
  xl: "clamp(3rem, 8vw, 5.5rem)"
components:
  button-primary:
    backgroundColor: "{colors.accent-dark}"
    textColor: "{colors.on-accent-dark}"
    typography: "{typography.action}"
    rounded: "{rounded.none}"
    padding: "0.72rem 1.25rem"
  button-primary-hover:
    backgroundColor: "{colors.accent-bright-dark}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.text-dark}"
    typography: "{typography.action}"
    rounded: "{rounded.none}"
    padding: "0.72rem 1.25rem"
  filter-pill:
    backgroundColor: "transparent"
    textColor: "{colors.text-dim-dark}"
    typography: "{typography.action-sm}"
    rounded: "{rounded.none}"
    padding: "0.55rem 1rem"
  filter-pill-active:
    backgroundColor: "{colors.accent-dark}"
    textColor: "{colors.on-accent-dark}"
  category-tag:
    backgroundColor: "{colors.accent-dark}"
    textColor: "{colors.on-accent-dark}"
    typography: "{typography.tag}"
    rounded: "{rounded.none}"
    padding: "0.2rem 0.42rem"
  theme-toggle:
    backgroundColor: "{colors.bg-elevated-dark}"
    rounded: "{rounded.none}"
    width: "3.9rem"
    height: "2.2rem"
---

# Design System: FranVisuals

## Overview

**Creative North Star: "The Cut-Corner Broadcast Kit"**

FranVisuals designs the graphics that run underneath live streams, match broadcasts, and trading calls. The site is built out of the brand's own logo — an angular navy chevron sliced by a lightning bolt — rather than out of generic landing-page furniture. Every container in the system repeats the logo's cut corner: a notch taken out of the top-right and bottom-left of buttons, pills, cards, and the theme toggle. Nothing is rounded, because nothing in the logo is rounded.

The system ships in two themes of equal standing. **Night** is a near-black navy control room where a bright celeste (`#38bdf8`) is the only lit color. **Day** is the near-white sheet from FranVisuals' own brand banners, where the logo returns to its navy and the accent deepens to `#0b6fa8` so it keeps its contrast against paper. The theme is not a preference toggle bolted on — the brand kit itself exists in both, so the site does too.

Type is a two-voice pairing: Bebas Neue for anything shouted (headline, stat figures, wordmark, ticker) and Archivo for anything read or clicked. This is a **Persuade** surface: prove range and volume fast through the work itself — a three-up carousel of live pieces, then a filterable archive — and hand the visitor a one-tap WhatsApp line.

Confirmed rejections: no cream/paper-serif editorial treatment, no rounded friendly-SaaS card language, and no green *accent* — an earlier green broadcast palette was replaced at the client's direction with the logo's navy/celeste identity. Green survives in exactly one place, the availability dot, where it carries meaning rather than brand.

**Key Characteristics:**
- Dual navy/near-white theming with a single celeste accent that re-tunes per theme
- The logo's cut corner as the universal container shape; zero border-radius
- Condensed broadcast caps over a grotesk workhorse
- The logo itself as a recolorable CSS mask — one asset, both themes
- Flat, hairline-bordered depth; no shadows anywhere

## Colors

A navy-to-paper ground with exactly one accent hue, which shifts lightness (not identity) between themes so it stays legible on both.

### Primary
- **Signal Celeste** (`#38bdf8` night / `#0b6fa8` day): buttons, active filters, stat figures, links on hover, corner brackets, category tags, ticker bullets. The day value is deepened purely for contrast — it is the same brand blue.
- **Signal Celeste — Pressed** (`#7dd3fc` night / `#095b8b` day): hover state of the primary button only.

### Neutral
- **Control-Room Black** (`#05090f`) / **Brand Paper** (`#eef1f7`): page ground.
- **Elevated** (`#0a1220` / `#ffffff`): ticker strip, theme-toggle track, footer.
- **Panel** (`#0c1424` / `#ffffff`): card and slide fill.
- **Ink** (`#eaf2fb` / `#0a1220`): primary text.
- **Ink Dim** (`#8ea3bd` / `#4d5f7a`): secondary text, captions, inactive labels.
- **Hairline** (`rgba(125,211,252,0.14)` / `rgba(13,27,51,0.14)`): default borders.
- **Hairline Strong** (`rgba(125,211,252,0.32)` / `rgba(13,27,51,0.34)`): hovered borders, ghost-button strokes, pill outlines.

### Tertiary
- **Availability Green** (`#2ee06f` night / `#0f9d4f` day): the availability dot only. It never appears anywhere else. Green, not red — the dot sits beside "Disponible para nuevos proyectos", and a red dot read as the opposite of the sentence next to it.
- **Logo Navy** (`#0d1b33`): the logo mark in day theme. In night theme the same mask renders pure white.

### Named Rules
**The One Voice Rule.** The celeste is reserved for things that are live, actionable, or numeric — a button, an active state, a count, a framing bracket. It never colors a paragraph or fills a full-bleed region.

**The Two-Value Accent Rule.** The accent has exactly one night value and one day value. A new state borrows one of them or stays neutral; it never introduces a third blue.

**The Caption Ink Exception.** Text sitting on a photograph (`#f4f9ff` over the caption veil) is theme-independent, because the image underneath is the same in both themes.

## Typography

**Display Font:** Bebas Neue (with Archivo, sans-serif fallback)
**Body Font:** Archivo (with system-ui fallback)

**Character:** Bebas Neue is the broadcast lower-third and scoreboard voice — condensed, all-caps, single weight (400), used for anything the page shouts. Archivo is the grotesk workhorse carrying everything that has to be read at length or clicked. A single-weight display face is the point: hierarchy at the top of the page comes from scale, not from bolding.

A Helvetica-only version was trialled and rejected by the client; the condensed pairing is the committed direction.

### Hierarchy
- **Display** (400, `clamp(2.8rem, 8.5vw, 6rem)`, line-height 0.94, uppercase): hero headline only.
- **Stat Lead** (400, `clamp(3.2rem, 8vw, 4.6rem)`, accent): the headline figure in the stat band.
- **Headline** (400, `clamp(2.2rem, 5vw, 3.4rem)`, uppercase): section headings and the closing CTA.
- **Title** (400, `1.75rem`): secondary stat figures.
- **Wordmark** (400, `1.6rem` header / `1.3rem` footer, tracking `0.03em`).
- **Ticker** (400, `1.05rem`, tracking `0.06em`).
- **Counter** (400, `1rem`, tracking `0.06em`): the lightbox `n / total`.
- **Body** (400, `clamp(1rem, 1.5vw, 1.12rem)`, line-height 1.5): hero subhead, section intros.
- **Action** (700, `1.05rem` large CTA / `0.92rem` buttons / `0.9rem` footer button / `0.85rem` filters, tracking `0.02em`).
- **Link** (400, `0.88rem`): footer navigation.
- **Prompt** (600, `0.84rem`, tracking `0.04em`): the carousel's "Deslizá para conocerlos" line.
- **Caption** (600, `0.8rem`): project titles on image captions.
- **Fine** (400, `0.78rem`): footer note and copyright.
- **Label** (700, `0.76rem` pills / `0.72rem` stat-lead label / `0.7rem` footer headings, tracking `0.09em`–`0.13em`, uppercase).
- **Label 2XS** (600, `0.66rem`, tracking `0.09em`, uppercase): secondary stat labels.
- **Tag** (800, `0.64rem`, tracking `0.07em`, uppercase): category tags on images.

### Named Rules
**The Shout/Talk Rule.** Bebas Neue shouts (headlines, stat figures, wordmark, ticker, counter); Archivo talks (everything else). A single string never mixes both faces.

**The Single Weight Rule.** Bebas Neue ships one weight (400). Display elements are `<h1>`/`<h2>`, which browsers default to `font-weight: 700`, so the headings currently render as a *synthesised* bold — slightly thicker strokes than the true face. This is the incumbent, client-approved appearance and is left as-is deliberately. If it is ever tightened, set `font-weight: 400` on the display steps rather than adding a bolder family.

## Layout

Full-bleed single-column sections stacked vertically: sticky header → hero → carousel → ticker → archive → closing CTA → footer. Section padding is `clamp(1.25rem, 4vw, 3rem)` horizontal.

The hero is **centred**, not left-aligned: `.hero-inner` is `max-width: 52rem; margin: 0 auto; text-align: center`, so the logo mark, headline, subhead, actions, and stat band share one vertical axis.

The stat band is a three-figure hierarchy, not a grid of equal cells: a lead figure (`+1000 proyectos realizados`) at display scale in accent, then two hairline-separated secondary figures (`+7 años`, `+200 clientes`) at `1.75rem`.

The archive uses CSS multi-column masonry (`columns: 4 16rem`, dropping to `2 12rem` under 720px) rather than a fixed-aspect grid, because the source pieces mix 16:9 broadcast overlays and 9:16 story formats — cropping either to a uniform tile would falsify the work.

The carousel stage is `aspect-ratio: 16/7.4` on desktop and `16/10` under 720px, with the centre slide at 64% width (78% on mobile).

## Elevation & Depth

Flat by design — there are no box-shadows in the system. Depth comes from three stacked background values (ground → elevated → panel) plus hairline borders. The carousel is the one place depth is dramatized, and it does so with scale, rotation, blur, and opacity rather than shadow: side slides sit at `scale(0.78) rotate(±6deg)`, `blur(2px)`, `opacity 0.45`.

### Named Rules
**The Flat-By-Default Rule.** Nothing casts a shadow. Interactive surfaces signal state through border brightening, a 2–3px lift, or the corner brackets appearing — never through elevation.

## Shapes

Every corner in the system is square, and the system's one signature shape is the **cut corner**, taken directly from the logo's chamfered chevron:

```css
clip-path: polygon(0 0, calc(100% - Npx) 0, 100% Npx, 100% 100%, Npx 100%, 0 calc(100% - Npx));
```

The notch scales with the component: `6px` on the toggle knob, `7px` on icon buttons and arrows, `8px` on pills and filters, `10px` on buttons, `14px` on archive cards, `18px` on carousel slides.

The second recurring shape is the **corner bracket**: four independent 2px L-strokes pinned to an archive tile's corners, invisible at rest and drawn in on hover/focus as a viewfinder locking onto the piece.

The hero carries three thin **shards** — 1–2px hairlines rotated `-14deg` — echoing the diagonal slashes in the FranVisuals brand banners.

## Components

### Buttons
- **Shape:** cut corner at 10px; no radius.
- **Primary:** accent fill, `on-accent` text, padding `0.72rem 1.25rem` (`1rem 1.8rem` for the large CTA).
- **Hover / Focus:** fill shifts to the pressed accent and the button lifts 2px; `focus-visible` draws a 2px accent outline at 3px offset.
- **Ghost:** transparent, hairline-strong border, ink text; hover turns border and text accent.

### Chips / Pills
- **Filter pill:** transparent with hairline-strong border and dim text; active state fills accent with `on-accent` text. Carries a dimmed inline count.
- **Availability pill:** hairline-strong border, uppercase label, and a `0.5rem` green dot with a pulsing ring (disabled under `prefers-reduced-motion`).
- **Category tag:** solid accent fill, `on-accent` text, no border, uppercase — always paired with a project title inside an image caption.

### Cards / Containers (archive tiles)
- **Corner Style:** cut corner at 14px, plus the corner-bracket motif.
- **Background:** panel, 1px hairline border.
- **Shadow Strategy:** none — see Elevation & Depth.
- **Hover / Focus:** border brightens, tile lifts 3px, brackets and the caption fade in. Under `hover: none` both are shown at rest instead.
- **Internal Padding:** image is edge-to-edge; caption bar `0.75rem 0.9rem`.

### Navigation
Sticky header on a `color-mix` translucent ground with 12px backdrop blur and a hairline bottom border. The wordmark pairs the masked logo glyph with "FRAN" in ink and "VISUALS" in accent. Social icons are `2.2rem` cut-corner hairline squares that turn accent on hover. The header CTA is hidden below 560px.

### Theme Toggle (signature component)
A `3.9rem × 2.2rem` cut-corner track holding a sun and a moon glyph with a sliding accent knob. The knob sits left in day and slides `1.68rem` right in night on a `cubic-bezier(0.16, 1, 0.3, 1)` ease; whichever glyph the knob covers renders in `on-accent`, the other in dim ink at 50% opacity. Hover blooms a 5px accent glow ring. Exposes `aria-pressed` and honours `prefers-reduced-motion`. The chosen theme persists to `localStorage` under `fv-theme` and is re-applied by a blocking inline script before first paint so the page never flashes the wrong mode.

### Carousel (signature component)
Introduced by a centred `showcase-head` — an uppercase display heading with a hairline-flanked prompt line beneath it.

A three-up stage: the current slide centred at full scale, the previous and next slides pushed `±64%` laterally, rotated `±6deg`, scaled to `0.78`, blurred `2px` and dropped to `0.45` opacity. Transitions run `0.75s cubic-bezier(0.16, 1, 0.3, 1)`. Advances every 3.8s, pausing on hover, on focus, and when the tab is hidden. Off-stage slides are marked `inert` and `aria-hidden` so they never receive focus.

**Direct manipulation.** The stage is draggable via pointer events (one path covering mouse, touch and pen) with a 45px threshold. A gesture whose vertical travel exceeds its horizontal travel is ignored, and `touch-action: pan-y` keeps the page scrollable through the carousel on a phone. The stage carries `tabindex="0"`, `role="group"`, and left/right arrow-key handling so the swipe has keyboard parity. Cursor is `grab` / `grabbing`.

Controls are cut-corner arrows plus a row of `1.5rem × 3px` dot bars; the active bar fills accent and scales `1.8` vertically. Below 720px the dots take their own wrapping row (a full-width row of twelve bars otherwise outruns a phone and shoves the arrows off screen). Autoplay is suppressed entirely under `prefers-reduced-motion`.

### Lightbox
Archive tiles carry a transparent full-bleed `card-open` button with a `zoom-in` cursor and an accent zoom badge that fades in on hover (shown at rest under `hover: none`). Activating it opens a modal dialog over an `rgba(2,6,12,0.86)` blurred scrim.

The panel is a cut-corner (20px) figure holding a 1600w rendition of the piece — the 760w gallery variant goes soft at full size — capped at `calc(100vh - 12rem)`, over a caption bar carrying the category tag, the title, and an `n / total` counter in display type. The image element is created in script rather than shipped in markup, because an image tag with an empty `src` makes some browsers re-request the page URL.

Navigation is scoped to the **currently filtered** set, so paging through under "Empresa" walks four pieces, not twenty-four. Supports arrow keys, `Escape`, a focus trap across the dialog's buttons, focus restoration to the originating tile, and a body scroll lock. The open transition is triggered by a forced reflow rather than `requestAnimationFrame`, so a throttled frame callback can never leave the panel transparent but click-blocking. Below 860px the controls move inside the panel and overlay the image on a translucent blurred fill, since there is no room to hang them off the edge.

### Ticker
Full-width strip between the carousel and the archive, on the elevated ground with hairline top and bottom borders. Two identical item groups translate `-50%` over 34s, which is seamless only because each group is padded out to exceed the widest expected viewport — a group narrower than the viewport is what makes a marquee visibly cut. Each item is prefixed by a 45°-rotated accent square. Pauses on hover; collapses to a single static wrapped row under `prefers-reduced-motion`.

### Footer
A four-column grid — brand block (logo lockup, tagline, availability pill) at `1.6fr`, then Explorar / Seguime / Contacto at `1fr` each — collapsing to two columns under 900px (brand spanning full width) and one under 520px. Column headings are `0.7rem` uppercase at `0.13em` tracking; links nudge `2px` right and turn accent on hover.

**Seguime** carries social entries as a cut-corner icon badge plus a two-line label (platform over handle); the badge inverts to a solid accent fill on hover. **Contacto** carries a primary button with the phone number, and that button must be excluded from the column's generic link styling — see the Don'ts. A hairline `footer-bar` closes the page with the copyright and origin line.

The logo mark is repeated as a large `min(30rem, 62vw)` watermark bled off the bottom-right corner at 6% opacity, rendered through the same CSS mask so it recolors with the theme.

## Do's and Don'ts

### Do:
- **Do** keep the accent rare — buttons, active states, figures, brackets, ticker bullets — per the One Voice Rule.
- **Do** apply the cut corner to every new container, sized to the component (6–18px).
- **Do** render the logo through the CSS mask (`--logo-src` + `background: var(--logo)`) so it inherits the theme instead of shipping two image files.
- **Do** keep both themes at WCAG AA or better; the day accent is deepened specifically to hold contrast on paper.
- **Do** let the archive's aspect ratios stay mixed; never force-crop a 9:16 piece into a 16:9 tile.
- **Do** gate the ticker, the carousel autoplay, and the live-dot pulse behind `prefers-reduced-motion`.
- **Do** scope lightbox navigation to the active filter, so the counter matches what the visitor can actually see.
- **Do** check a new rule against later same-specificity rules: `.header-cta { display: none }` inside a media query loses to a plain `.btn { display: inline-flex }` declared further down. Scope it (`.site-header .header-cta`).
- **Do** exclude buttons from container link styling with `:not(.btn)`. A bare `.footer-col a` outranks `.btn-primary` and silently repaints the button's label to dim grey on the accent fill — a real contrast failure that shipped once.
- **Do** reach for scale, not weight, when a display element needs more presence — Bebas Neue has no real bold to reach for.

### Don't:
- **Don't** add a drop-shadow or scale a card up on hover — depth comes from borders, layering, and the carousel's own transform language.
- **Don't** introduce a third accent value or a second hue; the accent has exactly one night and one day value.
- **Don't** round any corner, anywhere, for any component.
- **Don't** let a marquee group be narrower than the viewport — that is what makes the loop cut.
- **Don't** leave off-stage carousel slides focusable; they must stay `inert`.
- **Don't** ship an image element with an empty `src` as a placeholder; build it in script when the content is known.
- **Don't** gate a modal's entrance on `requestAnimationFrame` — a throttled frame leaves it invisible but click-blocking. Force a reflow instead.
