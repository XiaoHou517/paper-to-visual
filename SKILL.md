---
name: paper-to-visual
description: Turn a research paper into an editable presentation and a matching poster cover with vintage paper textures, muted sage greens, and ink-wash collage. Use for paper presentations, journal clubs, research briefings, and standalone covers with a reusable personal style.
---

# Paper to Visual

Default deliverables: a complete editable PPTX and a matching poster cover based on one research paper. Explicit instructions for the current task take precedence. When the task is to edit or package this skill, work on the skill files rather than automatically producing artifacts for an example paper.

## Read and execute

Before authoring, read [the personal style profile](references/personal-style.md) and [visual authoring and review](references/visual-authoring.md). These files travel with the skill. Do not depend on a particular paper, local machine path, previous conversation, or temporary screenshot.

This is an instruction-based skill, not a bundled generation service. Use the host's actual capabilities for reading papers, generating images, authoring editable PPTX files, and rendering previews. Follow relevant PDF, presentation, and image skills when available. Otherwise use suitable available tools; never call nonexistent tools or hardcode another skill's installation path.

Use image generation for the illustrated ink-wash artwork. Suitable user-provided textures and artwork can substitute when that capability is unavailable. Do not imitate the style with random programmatic dots or gradient rectangles. If neither generation nor suitable artwork is available, explain that limitation and complete only the supported analysis or outline; do not describe those as finished artifacts. Disclose any missing visual verification if a PPTX renderer is unavailable.

## Inputs and evidence

Accept a PDF, full text, accessible paper URL, or DOI. Read the full text and relevant figures where possible. If only an abstract is available, state the coverage and do not invent methods or findings. If the identifier cannot be resolved, request the source.

Write a concise `paper-notes.md` in the task output directory. Record bibliographic metadata, research questions, methods, findings, limitations, and page, section, or figure locations for key claims. Check numbers, units, sample sizes, comparison conditions, and statistical definitions. Do not fabricate missing authors, affiliations, dates, data, or identifiers.

Distinguish the paper's claims from presenter commentary. Rebuild charts only from reliable data; otherwise preserve a clear original figure. Do not manufacture precise values from blurry plots. Cite original and adapted evidence on the relevant slide. Decorative illustrations must not masquerade as experimental evidence, device photographs, or accurate engineering drawings.

## Narrative and topic-specific imagery

Determine the paper type, audience, and central contribution before choosing slides. Empirical papers may follow question, method, results, and limitations; reviews may use themes and disagreements; theoretical papers may use arguments and derivations. Do not force every paper into an experiment template.

Choose one central visual subject and a small set of supporting motifs from the current paper. Record these choices, palette, typography, and composition in `design-notes.md`. Subjects may be research objects, apparatus, materials, or settings. Choose them afresh for each paper rather than fixing every cover to robotics, radar, medicine, campuses, or people.

Integrate the subject, supporting scenes, paper grain, and irregular ink-wash boundaries into a coherent vintage collage. An abstract paint splash with a title pasted on top is insufficient.

## Presentation

Working defaults: Chinese presentation text, 16:9, and approximately 10-15 slides. Adjust the count to the actual substance of the paper instead of padding. Retain the original title and necessary technical terms. Use English or another language when requested; English skill documentation does not determine the output language.

- Make the title a clear reading entry point on the cover. Use topic-specific collage and a deliberate text hierarchy. Section pages may reuse selected visual motifs.
- On content slides, retain paper texture, sage tones, and restrained ink details while giving text and scientific evidence priority.
- Keep titles, body text, annotations, tables, and reliably reconstructed charts editable. Raster artwork and original evidence figures are acceptable; a full-slide image is not a substitute for an editable deck.
- Give each slide a clear purpose. Use evidence-based takeaway titles where useful, while retaining units, legends, uncertainty, and sources.
- Build information density through explanation, evidence, and relationships. Do not fix sparse pages merely by enlarging fonts or spreading sentences apart. Apply the linked layout guidance.

## Matching poster cover

The default is a thematic paper poster cover, not a full conference poster containing every method and result. Unless specified otherwise, use portrait 3:4 and export PNG, targeting at least 1800 x 2400 pixels. Report actual dimensions; upscaling does not create native illustration detail. Handle print specifications separately when requested.

Design the portrait composition independently. Include a recognizable central subject, a few meaningful supporting scenes, visible ink diffusion, broken brush edges, and paper grain. Let the illustration dissolve naturally into the paper. Do not place a small hard-edged image on an otherwise empty page or stretch a landscape cover into portrait.

Keep copy focused on the title, a short thematic statement, and the paper citation. Do not invent a presenter, institution, or logo. Do not import identities or brands from reference artwork. Add long titles and citations with editable typography rather than trusting generated lettering.

## Review and deliver

Render every slide and the poster. Inspect full-size views and thumbnails using [the visual review criteria](references/visual-authoring.md#visual-review). Fix factual, composition, density, typography, and contrast issues. A successful export is not proof of visual quality.

Deliver the actual `.pptx`, poster `.png`, viewable previews, `paper-notes.md`, and `design-notes.md`. Provide file links and disclose slide count, dimensions, and material limitations. Only promise an editable poster source when it has actually been created. Publish externally only when requested.
