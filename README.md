# SNUPI Lab Visual Theme

This repository is a reusable design context pack for SNU PI Lab research visuals. It is meant to be dropped into future slide, paper-figure, poster, and infographic projects so agents can produce work in the same visual family.

Start with [DESIGN.md](DESIGN.md). It follows the Google Stitch DESIGN.md pattern: YAML design tokens first, then human-readable guidance. It is self-contained: agents can use it without opening the reference image or PDF. The original palette board and slide PDF remain in [assets/reference](assets/reference) for visual QA and onboarding.

## Files

- [DESIGN.md](DESIGN.md): canonical, portable SNUPI Lab theme for agents.
- [assets/reference/theme.png](assets/reference/theme.png): optional palette and mood reference.
- [assets/reference/snupi_slide_template.pdf](assets/reference/snupi_slide_template.pdf): optional SNUPI slide layout reference.
- [brief-prompts/agent-context.md](brief-prompts/agent-context.md): short prompt block to paste into visual-generation tasks.
- [brief-prompts/slide-brief.md](brief-prompts/slide-brief.md): reusable brief for SNUPI presentation slides.
- [brief-prompts/paper-figure-brief.md](brief-prompts/paper-figure-brief.md): reusable brief for paper figures.
- [brief-prompts/infographic-brief.md](brief-prompts/infographic-brief.md): reusable brief for diagrams and infographics.
- [preview.html](preview.html): static visual catalog of the palette and common patterns.
- [tokens/snupi-theme.css](tokens/snupi-theme.css): CSS custom properties for quick prototyping.
- [assets/reference/pdf-pages](assets/reference/pdf-pages): PNG renders of the PDF slide template used during theme extraction.

## Use In A New Project

Copy `DESIGN.md` and any relevant brief from `brief-prompts/` into the target project. Then tell the agent:

```text
Read DESIGN.md first and follow the SNUPI Lab Tech Indigo theme. Use the selected brief template for the artifact type.
```

For high-stakes slide work, optionally provide `assets/reference/snupi_slide_template.pdf` or the rendered reference pages so the agent can visually QA the lab footer and band structure. It is not required for normal use because the essential layout rules are already in `DESIGN.md`.

## Validate

The DESIGN.md format is alpha. When the Google CLI is available, run:

```bash
npx @google/design.md lint DESIGN.md
```

Warnings about orphaned tokens can be acceptable for this repository because the theme intentionally exposes extra colors for future figures and infographics.
