---
version: alpha
name: SNUPI Lab Tech Indigo
description: "A reusable visual identity for SNU PI Lab research communication. The theme combines the existing SNUPI slide template's white academic canvas, royal-blue structural bands, lower-right lab mark, and large single-figure discipline with a newer Tech Indigo palette for AI, robotics, HCI, and mobile agent research. It should feel precise, bright, readable, and technical rather than decorative or marketing-heavy."

colors:
  primary: "#5B6CFF"
  on-primary: "#FFFFFF"
  primary-legacy: "#4169E1"
  primary-deep: "#2F46D9"
  secondary: "#8E97FF"
  secondary-soft: "#E9ECFF"
  accent: "#A855F7"
  accent-soft: "#EAD7FF"
  neutral: "#232833"
  neutral-muted: "#667085"
  neutral-subtle: "#9AA4B2"
  canvas: "#F7F8FF"
  canvas-white: "#FFFFFF"
  surface: "#FFFFFF"
  surface-tint: "#F2F4FF"
  hairline: "#DDE3F1"
  hairline-strong: "#B9C3E2"
  figure-grid: "#E7EAF4"
  semantic-success: "#15803D"
  semantic-warning: "#F59E0B"
  semantic-error: "#DC2626"

typography:
  display:
    fontFamily: "Inter, Pretendard, Aptos, Arial, sans-serif"
    fontSize: 56px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: 0px
  slide-title:
    fontFamily: "Georgia, Times New Roman, serif"
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: 0px
  slide-title-sans:
    fontFamily: "Inter, Pretendard, Aptos, Arial, sans-serif"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: 0px
  section-title:
    fontFamily: "Inter, Pretendard, Aptos, Arial, sans-serif"
    fontSize: 36px
    fontWeight: 700
    lineHeight: 1.18
    letterSpacing: 0px
  figure-title:
    fontFamily: "Inter, Pretendard, Aptos, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0px
  body-lg:
    fontFamily: "Inter, Pretendard, Aptos, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.35
    letterSpacing: 0px
  body:
    fontFamily: "Inter, Pretendard, Aptos, Arial, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0px
  body-sm:
    fontFamily: "Inter, Pretendard, Aptos, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0px
  caption:
    fontFamily: "Inter, Pretendard, Aptos, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0px
  label:
    fontFamily: "Inter, Pretendard, Aptos, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0px
  mono:
    fontFamily: "JetBrains Mono, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.45
    letterSpacing: 0px
  math:
    fontFamily: "Latin Modern Math, Cambria Math, STIX Two Math, serif"
    fontSize: 32px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: 0px

rounded:
  none: 0px
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  slide-band-height: 40px
  slide-margin-x: 80px
  slide-margin-y: 64px
  slide-footer-gap: 20px
  figure-gap: 18px

components:
  slide-band:
    backgroundColor: "{colors.primary-legacy}"
    textColor: "{colors.on-primary}"
    typography: "{typography.caption}"
    rounded: "{rounded.none}"
    height: 40px
    width: 100%
  slide-title-frame:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.neutral}"
    typography: "{typography.slide-title}"
    rounded: "{rounded.none}"
    padding: 0px
  slide-title-accent-bar:
    backgroundColor: "{colors.primary}"
    rounded: "{rounded.none}"
    width: 20px
    height: 96px
  slide-content-canvas:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.neutral}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: 0px
  slide-footer:
    backgroundColor: "{colors.primary-legacy}"
    textColor: "{colors.on-primary}"
    typography: "{typography.caption}"
    rounded: "{rounded.none}"
    padding: 0px 16px
    height: 40px
  figure-panel:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.neutral}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 24px
  figure-caption:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.neutral-muted}"
    typography: "{typography.caption}"
    rounded: "{rounded.none}"
    padding: 8px 0px
  callout-primary:
    backgroundColor: "{colors.secondary-soft}"
    textColor: "{colors.neutral}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 16px 20px
  callout-accent:
    backgroundColor: "{colors.accent-soft}"
    textColor: "{colors.neutral}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 16px 20px
  button-primary-hover:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 10px 14px
  metric-tile:
    backgroundColor: "{colors.surface-tint}"
    textColor: "{colors.neutral}"
    typography: "{typography.figure-title}"
    rounded: "{rounded.md}"
    padding: 18px
  muted-note:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.neutral-muted}"
    typography: "{typography.caption}"
    rounded: "{rounded.none}"
    padding: 4px 0px
  subtle-marker:
    backgroundColor: "{colors.neutral-subtle}"
    rounded: "{rounded.pill}"
    width: 8px
    height: 8px
  chart-line-primary:
    backgroundColor: "{colors.primary}"
    rounded: "{rounded.pill}"
    height: 4px
  chart-line-secondary:
    backgroundColor: "{colors.secondary}"
    rounded: "{rounded.pill}"
    height: 4px
  chart-line-accent:
    backgroundColor: "{colors.accent}"
    rounded: "{rounded.pill}"
    height: 4px
  chart-gridline:
    backgroundColor: "{colors.figure-grid}"
    rounded: "{rounded.none}"
    height: 1px
  divider:
    backgroundColor: "{colors.hairline}"
    rounded: "{rounded.none}"
    height: 1px
  divider-strong:
    backgroundColor: "{colors.hairline-strong}"
    rounded: "{rounded.none}"
    height: 1px
  status-success:
    backgroundColor: "{colors.semantic-success}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 4px 10px
  status-warning:
    backgroundColor: "{colors.semantic-warning}"
    textColor: "{colors.neutral}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 4px 10px
  status-error:
    backgroundColor: "{colors.semantic-error}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 4px 10px
  table-header:
    backgroundColor: "{colors.surface-tint}"
    textColor: "{colors.neutral}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: 10px 12px
  table-cell:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.neutral}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.none}"
    padding: 10px 12px
---

# SNUPI Lab Tech Indigo

## Overview

SNUPI Lab visual work should communicate research clearly before it tries to impress. The family is built for presentation slides, paper figures, posters, and lightweight infographics about AI, robotics, HCI, and mobile agents.

This file is self-contained. Agents should be able to reproduce the SNUPI Lab Tech Indigo visual family from the tokens and written rules here without opening any image or PDF. Reference assets may be inspected for extra visual confidence, but they are not required.

The default mood is bright technical clarity: white or near-white canvas, exact blue-violet accents, generous figure space, restrained typography, blue outline iconography, hairline dividers, and soft lavender-tinted surfaces.

The slide heritage matters. The existing template uses top and bottom royal-blue bands, a lower-right SNUPI logo, large academic title type, and a strong rule: one large figure, table, or equation per slide whenever possible. Preserve that discipline even when using the newer Tech Indigo palette.

The original palette board used a white/mist canvas, a blue SNUPI triangular mark, a large "Selected Paper Series Color Palette" heading, and a central rounded palette card. Its five essential colors are encoded above: Primary `#5B6CFF`, Secondary `#8E97FF`, Accent `#A855F7`, Neutral `#232833`, and Background `#F7F8FF`.

The original slide template used 16:9 pages with full-width royal-blue top and bottom bands, a lower-right SNUPI logo region, footer date/page text, serif title treatment, and a vertical blue accent bar on content slides. Title slides center the title and metadata. Content slides reserve most of the canvas for one large figure, table, or equation.

## Colors

- **Primary Tech Indigo (#5B6CFF):** main brand color for key figures, section highlights, selected nodes, and primary chart series.
- **Primary Legacy Royal (#4169E1):** preserve for slide top and bottom bands, footer pagination, and compatibility with existing SNUPI slide decks.
- **Secondary Lavender Blue (#8E97FF):** supporting chart series, secondary UI blocks, subtle connectors, grouped regions, and hover-like emphasis.
- **Accent Violet (#A855F7):** callouts, exceptional states, contrast groups, and the one "pay attention here" element. Do not use it as broad background.
- **Neutral Ink (#232833):** text, outlines, axis labels, table rules, and diagrams requiring authority.
- **Canvas Mist (#F7F8FF):** slide and paper figure backgrounds when pure white feels too stark. Use white for dense slides and publication figures unless a tinted surface helps hierarchy.

For charts, order categorical colors as primary, secondary, accent, primary-deep, neutral-muted. Avoid rainbow palettes unless the data truly requires many categories. For heatmaps, prefer a single sequential ramp from canvas-white to primary-deep, with accent reserved for annotations.

## Typography

Use `Inter`, `Pretendard`, `Aptos`, or `Arial` for most digital and figure work. They match the clean technical mood of the palette family and handle Korean/English mixed labels well.

For legacy SNUPI presentation slides, `slide-title` may use a serif stack to match the existing PDF. If a new deck is meant to feel more modern or closer to the selected palette image, use `slide-title-sans` instead.

Slide text must stay large. Titles should be at least 35 pt. Body text should be at least 25 pt. Avoid more than six lines of small text on one slide. In figures, axis labels and legends must remain readable after insertion into a paper column or slide.

Use `mono` only for code, model names, dataset ids, metrics, and exact command snippets. Use `math` for displayed equations and keep equations visually central, not embedded in paragraphs.

## Layout

Use a 16:9 slide canvas for presentations. The canonical slide has:

- top band: full width, 40 px on a 1920 x 1080 export.
- bottom band: full width, 40 px on a 1920 x 1080 export.
- content margin: about 80 px left/right and 64 px top after the band.
- title accent bar: vertical primary block at the left of the title area.
- footer: lower-right lab mark, date, and page number on the bottom band.

For research slides, favor one central artifact. A figure, table, diagram, or equation should occupy roughly two-thirds of the usable page when it is the main point. Captions should be short and placed near the artifact, not as a paragraph wall.

For paper figures, prefer compact but breathable panels: consistent gutters, aligned axes, no heavy border boxes, and direct labels where possible. When composing multi-panel figures, use lettered panel labels in neutral ink with primary as a small anchor, not a large badge.

## Elevation & Depth

Stay mostly flat. Use hairline borders, tinted surfaces, and small shadows only for UI preview cards or explanatory infographics. Publication figures and academic slides should not rely on shadows to separate meaning.

Recommended surfaces:

- White canvas for slides, paper figures, and tables.
- Canvas Mist for palette pages, overview infographics, and background bands.
- Surface Tint for metric tiles, grouped regions, or subtle component blocks.
- Hairline borders for panels, tables, and diagram containers.

## Shapes

The family uses precise, low-radius geometry. Use square or lightly rounded rectangles; `md` radius is the default maximum for charts, tables, and cards. Use pill radius only for legends, small status chips, or progress marks.

Logo-adjacent motifs may use triangular or node-link geometry inspired by the SNUPI mark, but keep them sparse. Do not turn the theme into decorative triangle wallpaper.

## Components

**Slides:** combine a royal-blue structural band with Tech Indigo highlights inside the content area. Use the SNUPI logo in the lower-right footer area. Put the title at the upper-left and align content to the same left edge. For title slides, center the title vertically and keep metadata below it.

**Large Figure Slide:** title, one large figure/table/equation, one short caption or takeaway. The figure should dominate the slide. Use primary for the single most important annotation and neutral ink for labels.

**Avoid-This Slide:** if demonstrating a bad example, use neutral text and only one warning cue. Avoid using red as the main theme color; red is reserved for true errors.

**Paper Figure:** white background, neutral ink text, primary first series, secondary second series, accent only for a critical comparison or callout. Prefer direct labels over crowded legends.

**Benchmark Chart:** lines or bars should use thick enough strokes for slide projection. Primary series must be the method or result under discussion. Baselines should use neutral-muted or dashed neutral strokes.

**Diagram or Pipeline:** primary marks the current contribution, secondary marks context modules, accent marks an intervention, user action, or novel component. Hairline arrows and connectors should be neutral-subtle unless they carry semantic emphasis.

**Infographic Card:** use surface white on canvas mist, thin hairline border, md radius, and no nested cards. Use icons as blue outline symbols when helpful, matching the line-art tone of the palette board.

## Do's and Don'ts

Do:

- Treat this DESIGN.md as the portable source of truth for palette, layout, and visual behavior.
- Preserve the slide template's top/bottom band, lower-right logo, footer date, and page number for SNUPI decks.
- Keep slides readable from the back of a room.
- Let figures, equations, and tables be visually large.
- Use primary blue for the main contribution or selected result.
- Use accent violet only when something genuinely needs extra attention.
- Keep diagrams aligned, sparse, and easy to scan.
- Prefer direct labels and minimal legends.

Don't:

- Do not fill slides with continuous text.
- Do not place many unrelated images on one slide unless comparison is the point.
- Do not use rainbow colors as a default chart palette.
- Do not use heavy shadows, dark cinematic backgrounds, or glossy gradients.
- Do not overuse purple; the lab theme is indigo-first with violet accents.
- Do not make paper figures depend on low-contrast lavender text.
- Do not shrink figure labels below readability just to fit more panels.

## Optional Reference Assets

If this repository is available, the original source references live at:

- `assets/reference/theme.png`
- `assets/reference/snupi_slide_template.pdf`
- `assets/reference/pdf-pages/`

These files are useful for visual QA and onboarding, but downstream projects should not require them. If only one file can travel with a paper, slide deck, or code repository, copy `DESIGN.md`.
