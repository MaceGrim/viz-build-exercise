# Design Guide (condensed)

Our visuals should feel native to the publication: serious, grounded, human-centered.
Data serves the story, not the other way around.

## Colors

- **Accent red:** `#c60101` — use sparingly: the threshold line, the key annotation, nothing else
- **Body text / labels:** `#474747`
- **Background:** `#EFEEED` (warm off-white)
- Keep palettes restrained — one or two distinct line/fill colors against the warm background

## Typography

- Clean sans-serif for titles and labels; readable serif for annotations is a nice touch
- Minimal chart chrome: clean lines, no heavy gridlines, sparse axis labels

## Every viz needs

- A descriptive title and a short explanatory subtitle above the chart
- A caption (1–2 sentences, plain language)
- A **data-attribution line** listing the specific sources used

## Sourcing standard (non-negotiable)

This is a journalistic publication. **Every data point, location, and number shown must
trace to a citable source** — here, that means the files in `data/` and the entries in
`SOURCES.json`. Never fabricate or approximate a value to fill a visual. If exact data
isn't available for something, note the gap and raise it with the reporter instead of
publishing it.
