---
version: alpha
name: SNUPI Lab Tech Indigo
description: "A reusable visual identity for SNU PI Lab research communication. The theme combines the existing SNUPI slide template's white academic canvas, royal-blue structural bands, lower-right lab mark, and large single-figure discipline with a newer Tech Indigo palette for AI, robotics, HCI, and mobile agent research. It should feel precise, bright, readable, and technical rather than decorative or marketing-heavy."

colors:
  primary: "#5B6CFF"
  on-primary: "#FFFFFF"
  primary-legacy: "#4169E1"
  primary-deep: "#2F46D9"
  primary-complement: "#FFEE5B"
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
  callout-complement:
    backgroundColor: "{colors.primary-complement}"
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

The original palette board used a white/mist canvas, a blue SNUPI triangular mark, a large "Selected Paper Series Color Palette" heading, and a central rounded palette card. Its five essential colors are encoded above: Primary `#5B6CFF`, Secondary `#8E97FF`, Accent `#A855F7`, Neutral `#232833`, and Background `#F7F8FF`. A sixth color, Primary Complement `#FFEE5B`, was added later as the high-contrast partner of Primary for callouts and calls to action.

The original slide template used 16:9 pages with full-width royal-blue top and bottom bands, a lower-right SNUPI logo region, footer date/page text, serif title treatment, and a vertical blue accent bar on content slides. Title slides center the title and metadata. Content slides reserve most of the canvas for one large figure, table, or equation.

## Design Intent

The theme should feel like a research lab with engineering taste: precise, calm, bright, and rigorous. It is not a consumer-product landing page, a dark cyberpunk dashboard, or a decorative tech poster. The visual language should make complex systems easier to parse.

Use these personality anchors:

- **Technical clarity:** diagrams, charts, and equations should read first.
- **Academic restraint:** hierarchy should come from scale, spacing, and color roles, not decoration.
- **Lab continuity:** SNUPI decks should still feel connected to the legacy blue-band template.
- **Modern indigo finish:** figures and infographics can use the newer Tech Indigo palette for a cleaner, more contemporary feel.
- **Cross-domain neutrality:** the theme must work for AI, robotics, HCI, mobile agents, benchmarks, user studies, and system architecture.

Use these non-goals:

- Do not imitate generic SaaS marketing pages.
- Do not make violet the dominant brand impression.
- Do not rely on visual effects that fail in print, PDF export, or projector display.
- Do not force every artifact to show the logo if the target venue is a paper figure or anonymous submission.

## Colors

- **Primary Tech Indigo (#5B6CFF):** main brand color for key figures, section highlights, selected nodes, and primary chart series.
- **Primary Complement Yellow (#FFEE5B):** the complementary color of Primary, reserved for high-contrast callouts and call-to-action emphasis such as a highlighted takeaway, a "try this" block, or the single number the audience must remember. Always pair it with neutral ink text, never with white text or as a chart series, and use it at most once per slide or panel.
- **Primary Legacy Royal (#4169E1):** preserve for slide top and bottom bands, footer pagination, and compatibility with existing SNUPI slide decks.
- **Secondary Lavender Blue (#8E97FF):** supporting chart series, secondary UI blocks, subtle connectors, grouped regions, and hover-like emphasis.
- **Accent Violet (#A855F7):** callouts, exceptional states, contrast groups, and the one "pay attention here" element. Do not use it as broad background.
- **Neutral Ink (#232833):** text, outlines, axis labels, table rules, and diagrams requiring authority.
- **Canvas Mist (#F7F8FF):** slide and paper figure backgrounds when pure white feels too stark. Use white for dense slides and publication figures unless a tinted surface helps hierarchy.

For charts, order categorical colors as primary, secondary, accent, primary-deep, neutral-muted. Avoid rainbow palettes unless the data truly requires many categories. For heatmaps, prefer a single sequential ramp from canvas-white to primary-deep, with accent reserved for annotations.

## Data Visualization

Use color semantically, not decoratively.

Recommended chart series order:

1. `primary` for the method, model, condition, or result the artifact is explaining.
2. `secondary` for the most important comparison.
3. `accent` for a critical ablation, intervention, failure mode, or selected point.
4. `primary-deep` for a stronger variant of the main series.
5. `neutral-muted` for baselines, chance, controls, and background references.

For line charts, use 3 px minimum strokes for slides and 1.5 to 2 px minimum strokes for paper figures. Use direct labels when there are three or fewer series. Use legends only when direct labels would collide with the data.

For bar charts, use primary only for the bar or group under discussion. Use secondary-soft fills or neutral-muted fills for context bars. Keep baseline and axis rules light; the data should be heavier than the frame.

For scatter plots, use neutral-subtle points for background populations and primary points for selected examples. Use accent only for outliers or qualitative callouts. Avoid translucent violet clouds unless the density itself is the point.

For heatmaps, prefer a sequential ramp from canvas-white through secondary-soft to primary-deep. Use accent marks for annotations, not as part of the scale. Always include a visible scale when absolute values matter.

For uncertainty, use thin neutral-muted error bars or soft primary bands at low opacity. Do not hide variance behind decorative glow.

For benchmark tables, use surface-tint headers, neutral ink text, and one primary highlight per row or column. Do not color every best value unless the table is explicitly a leaderboard.

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

## Artifact Recipes

### Presentation Title Slide

Use a 16:9 white canvas with full-width top and bottom royal-blue bands. Center the title vertically in the content area. Place subtitle, presenter, and date beneath the title with generous spacing. Keep the lower-right SNUPI identity region visible. Avoid decorative hero art unless the talk itself is visual or demo-driven.

### Presentation Content Slide

Use the vertical blue accent bar at the upper-left title area. Put the title on a single line when possible. The main figure, table, diagram, or equation should own the slide. Use one short caption, takeaway, or TL;DR block. If a slide needs more than six lines of body text, split it.

### Large Figure Slide

Reserve roughly two-thirds of the usable canvas for the figure. If the figure is a screenshot, crop to the relevant UI state and add direct annotations. If the figure is a chart, enlarge labels for projection. If the figure is a diagram, make the contribution path primary and context modules secondary.

### Equation Slide

Use one displayed equation or two tightly related equations. Put explanatory text below or beside the equation, not around it. Use neutral ink for the equation, primary for the one term currently being discussed, and accent for a rare contrast or error term. Avoid paragraph-level derivations on slides.

### Meeting Log Slide

Use the same title-slide structure, but allow a smaller title and a clear date. Meeting log slides should feel archival and readable, not decorative. Prefer action tables, decisions, and links over long meeting prose.

### Paper Figure

Use a white background unless the venue permits transparent output. Keep panel gutters even. Use panel labels like `a`, `b`, `c` or `A`, `B`, `C` consistently. Use primary for the proposed method, secondary for the main baseline, accent for one critical comparison. Use neutral-muted for all other baselines.

### Multi-Panel Figure

Align panels to a grid and keep their axes compatible when comparisons matter. Put labels in the same corner across panels. Use one shared legend when possible. If panels combine a pipeline and results, let the pipeline use light surfaces and the result panel carry the strongest color emphasis.

### System or Pipeline Diagram

Use left-to-right or top-to-bottom flow. Modules are lightly rounded rectangles with hairline borders. The contribution module is primary or primary-soft, context modules are surface-tint or secondary-soft, and user/model/environment elements are distinguished through labels and icons rather than extra colors. Connectors are neutral-subtle unless a path is the main story.

### Mobile Agent or HCI Diagram

Separate user, device, environment, and model/agent as distinct regions. Use primary for the active agent decision or selected interaction. Use secondary for observed context. Use accent only for intervention, feedback, correction, or risk. Avoid crowding mobile screenshots; one screenshot plus clear annotations is better than many small screens.

### Robotics Diagram

Use neutral structure for robot/environment geometry and primary for planned trajectory, selected policy, or key sensor stream. Use secondary for candidate trajectories or supporting modules. Use accent for collision, failure, correction, or intervention. Avoid decorative robot silhouettes that do not explain the method.

### Poster or Overview Infographic

Use the palette-board style: canvas mist, white panels, hairline dividers, strong section title, and blue outline icons. Keep the panel count small. Prefer one central story over many equal cards.

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

**Logo Lockup:** for internal slides, place the SNUPI identity at the lower-right, near the footer band. Keep clear space around it equal to at least the height of the triangular mark. For anonymous paper figures or submission artifacts, omit the logo.

**Legend:** use compact horizontal legends for slides and direct labels for figures when possible. Legend swatches should be simple line or filled markers using primary, secondary, accent, and neutral-muted in that order.

**Annotation:** use primary for the main annotation arrow or bracket. Use accent only when the annotation marks a surprising contrast, failure, or key intervention. Keep arrows thin and labels short.

**Table:** use surface-tint headers, neutral text, and hairline row dividers. Highlight only the values relevant to the claim. Do not turn tables into colorful heatmaps unless that is the figure's purpose.

**Iconography:** use outline icons with rounded stroke joins when possible. Keep strokes close to 2 px in UI previews and 1.25 to 1.75 pt in paper figures. Icons should explain AI, robotics, HCI, mobile, experiment, or communication concepts; avoid generic decorative symbols.

## Responsive Behavior

The theme is primarily for slides and publication artifacts, but it should adapt cleanly to web previews and dashboards.

Breakpoints:

- **Mobile:** below 640 px. Stack panels vertically, preserve chart label readability, and avoid multi-column legends.
- **Tablet:** 640 to 1024 px. Use two-column layouts only when labels remain readable.
- **Desktop:** above 1024 px. Use wider grids and preserve generous side margins.
- **Slide export:** 1920 x 1080 is the reference raster size for 16:9 preview exports.

Touch targets should be at least 44 px in interactive prototypes. Compact icon buttons may be 36 px only in dense toolbars. Do not scale type purely by viewport width; choose explicit responsive steps.

Images and plots should maintain aspect ratio. Do not crop axes, legends, or captions at mobile widths. If a figure becomes unreadable on mobile, offer a scrollable or zoomable figure area rather than shrinking text below usability.

## Accessibility & Export QA

Before delivering any artifact, run this visual QA checklist:

- Text contrast passes ordinary reading conditions. Avoid lavender text on white.
- The artifact works in grayscale or print when color is not the only encoding.
- Slide title is at least 35 pt and body text is at least 25 pt.
- Paper figure labels remain readable at the target column width.
- Primary color identifies the main claim, not incidental decoration.
- Accent violet appears at most a few times and always carries meaning.
- Axes, units, legends, and captions are present when required.
- No text overlaps, clips, or depends on tiny line breaks.
- Exported PDF or raster output preserves hairlines and does not blur labels.
- Anonymous submission figures omit lab identity when venue rules require it.

Export guidance:

- Use vector output for paper plots and diagrams when possible.
- Use 300 dpi or higher for raster paper figures.
- Use 1920 x 1080 or higher for slide PNG previews.
- Use white backgrounds for publication unless the venue explicitly supports transparency.
- Re-check color after PDF conversion because indigo and violet can shift on projectors.

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

## Agent Prompt Guide

When an agent needs to produce a visual artifact, include the artifact type and the intended venue.

Quick prompt:

```text
Read DESIGN.md first and follow the SNUPI Lab Tech Indigo theme. Create a [slide / paper figure / pipeline diagram / infographic] for [venue]. Preserve readability and use primary only for the main contribution.
```

Slide prompt:

```text
Create a 16:9 SNUPI presentation slide. Use the blue top/bottom bands, lower-right lab identity region, upper-left title with vertical accent bar, and one large central figure. Keep body text under six lines.
```

Paper figure prompt:

```text
Create a publication-ready figure using the SNUPI Lab Tech Indigo theme. Use white background, neutral labels, primary for the proposed method, secondary for the main comparison, and accent only for one critical callout. Keep labels readable at final column width.
```

Diagram prompt:

```text
Create a system diagram using SNUPI Tech Indigo. Show modules as light bordered blocks, highlight the contribution path in primary, show context modules in secondary-soft, and use neutral-subtle connectors. Avoid decorative color.
```

Iteration prompt:

```text
Audit this artifact against DESIGN.md. Report any violations in color semantics, typography size, layout density, contrast, export readability, and slide/figure conventions. Then patch the artifact.
```

## Iteration Guide

When improving an artifact, prefer these changes in order:

1. Clarify the main claim and make the main visual larger.
2. Reduce text density and split crowded slides.
3. Reassign colors so primary marks the contribution.
4. Increase label sizes and simplify legends.
5. Align panels, axes, and gutters.
6. Remove decorative effects that do not encode meaning.
7. Export and inspect the final PDF or image at target size.

If an artifact feels off-brand, ask:

- Is the canvas too dark, saturated, or decorative?
- Is violet doing too much work?
- Is the legacy slide structure missing where it should be present?
- Is the main figure too small?
- Are there too many unrelated images or panels?
- Would this still work in a paper PDF or on a projector?

## Known Gaps

This DESIGN.md intentionally defines a broad research-communication theme, not a full website product system. It does not yet include a complete logo asset policy, official Korean/English typography licensing guidance, journal-specific figure size presets, or full PowerPoint master-slide XML. Use the optional reference assets or local lab templates when those details matter.

## Optional Reference Assets

If this repository is available, the original source references live at:

- `assets/reference/theme.png`
- `assets/reference/snupi_slide_template.pdf`
- `assets/reference/pdf-pages/`

These files are useful for visual QA and onboarding, but downstream projects should not require them. If only one file can travel with a paper, slide deck, or code repository, copy `DESIGN.md`.
