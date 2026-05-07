# DESIGN.md Quality Control

This document tracks whether the SNUPI Lab Tech Indigo `DESIGN.md` is rich enough to guide AI agents without relying on external references.

## Benchmark

Professional DESIGN.md collections such as getdesign.md emphasize production-grade depth, project-root installation, and direct use by coding agents. The comparable quality bar is not visual polish alone; it is how much design decision-making can be delegated safely to the file.

## QC Rubric

| Area | Target | Status |
| --- | --- | --- |
| Self-contained identity | DESIGN.md works without opening image/PDF references | Pass |
| Token completeness | Colors, type, spacing, radius, components lint cleanly | Pass |
| Artifact specificity | Slides, paper figures, diagrams, posters, equations, tables have rules | Pass |
| Color semantics | Each major color has a role and misuse guidance | Pass |
| Data visualization | Charts, heatmaps, uncertainty, tables, baselines covered | Pass |
| Layout recipes | 16:9 slides, figure panels, diagrams, responsive previews covered | Pass |
| Accessibility | Contrast, grayscale, print, projection, export checks covered | Pass |
| Agent usability | Prompt snippets and iteration guide included | Pass |
| Known limits | Gaps are explicitly named | Pass |

## Current Assessment

The theme is now closer to a professional DESIGN.md than a simple palette handoff. Its strongest areas are research-specific artifact guidance, slide discipline, and portable self-containment. It is less website-oriented than many getdesign.md examples by design, because the primary use case is lab communication rather than product landing pages.

## Maintenance Checklist

Run this after major changes:

```bash
npm run design:lint
```

Then inspect:

- Did new tokens introduce contrast warnings?
- Are new colors assigned clear semantic roles?
- Did any guidance make reference assets mandatory again?
- Are slide, paper figure, and infographic workflows still covered?
- Are prompt snippets still short enough to paste into an agent task?

