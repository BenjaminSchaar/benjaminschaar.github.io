# Benjamin Schaar — Personal Site / CV

## register
**brand** — single-page personal portfolio. Design IS the product.

## Product purpose
Introduce Benjamin Schaar as a technical generalist working across data, audio, and visual practices, to potential collaborators and employers across all three domains. Stand in for a traditional CV (with print parity for PDF export).

## Users
1. **Hiring managers / collaborators** in data/ML, creative-tech studios, audio/music-tech companies, and design-engineering teams. They must be able to read his range in 30 seconds without forming a single-domain mental model.
2. **Music / creative-tech contacts** in Vienna who already know him casually and want a clean reference.
3. **Academic peers** evaluating his computational work (secondary; he is not job-hunting in academia).
4. **Recruiters** who will print this to PDF and circulate it.

## Core positioning
**Technical generalist.** Three current practices:
- **Data & Science** — Python pipelines, HPC workflows, statistical modelling, computer vision (PhD work; his day job)
- **Music & Audio** — 15 years of electronic music production, audio DSP, custom audio tooling
- **Visual & Spatial** — projection mapping, shader work, immersive events (Tohuwabohu collective, Vienna)

Built on the formal foundation of a five-year IT & Media Technology diploma. Sustained by a tendency to identify the next computational problem and pick the cleanest tool. AI has shifted the bottleneck — the generalist's strength is now framing the problem and choosing the approach, both more valuable than ever.

The previous attempt at this site collapsed all three practices into a "computational scientist" frame because every visual cue (dark navy, oscilloscope readouts, mono data labels, neural-traces banner) read as the neuroscience category. The new design must avoid that reflex.

## Tone
Confident, considered, restrained. Editorial magazine more than developer portfolio. Personality through typography and material quality, not through copy. Dry irony is fine; sincere "passion" copy is not.

## Brand references (new direction — "Crossfade")
- **Modern editorial portfolios**: typography-led, asymmetric magazine layouts, generous whitespace, ONE bold accent.
- **Linear, Vercel, Things, Raycast** — clean modern dark UI but elevated; warm-toned, not cold-blue.
- **A24, Wallpaper, Kinfolk** for photography mood: dark editorial, warm raking light, material textures.
- **Instrument Serif (italic) + Inter** as the typographic spine. Big confident serif italic display, sober sans body.

## Brand anti-references
- The previous v1 of this site (`redesign/functn-inspired` branch). The whole direction. Do not re-import.
- Cold-blue dark-mode developer portfolios with mono captions everywhere.
- SaaS landing pages — hero-metric blocks, gradient buttons, "trusted by" sections, testimonial carousels.
- Generic "scientist who codes" tropes — oscilloscope traces, neural network animations, signal grids.
- AI-generated portraits replacing the real `profile.png`.
- Em dashes used as decorative punctuation (use commas, colons, periods).
- Side-stripe `border-left` accents on cards and callouts.
- Card grids of identical-sized tiles.

## Strategic principles
1. **Generalist framing is structural, not just claimed.** A "Domains" section that names three practices side-by-side, and a "Catalog" that mixes them chronologically, do the heavy lifting before the prose.
2. **Typography is the design.** No canvas decoration. No image hero overlay. The hero is the name and a single thesis sentence; the page leads with confident type.
3. **One image moment, not many.** A single editorial image (generated via nano-banana) sits as a deliberate mid-page beat. The accent color is pulled from the image so the design and image share a palette.
4. **One accent. Not blue.** A warm rust/amber pulled from the image. Used sparingly (~10% of surface): year tags, marks, hovers, a single underline.
5. **Modern dark, warm-toned.** Near-black with a warm undertone, never cold navy. Cream-warm text, not blue-grey.
6. **Print parity is non-negotiable.** Anything added must collapse gracefully under `@media print` so the PDF stays clean.

## Constraints
- Single static `index.html`. No build step. No React.
- Inline CSS and JS are fine. File should stay around 30-50KB before image assets.
- Hosted on GitHub Pages from `main`.
- The real `profile.png` is the headshot; do not replace.
- Hero image is `assets/hero.jpg` — generated via nano-banana, optimized to ≤500KB.
