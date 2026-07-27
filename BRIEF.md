# Brief: Groundwater Monitoring Viz

We support an environmental-justice publication with data-driven visuals. A reporter is
writing a story about a closed low-level radioactive waste site and the decades of
groundwater monitoring that followed. (The dataset here is a synthetic stand-in for the
real records — treat it exactly as you would real reporting data.)

## The ask

Produce **one publication-ready chart** (PNG) showing how tritium levels in the
monitoring wells evolved over time, and how they compare to the **EPA drinking-water
standard of 20,000 pCi/L**.

Requirements from the reporter:

1. Show the contrast between the contaminated wells and the background wells — the
   story is that a few wells near the trench spiked badly while the rest stayed clean.
2. Mark the EPA standard clearly so a non-technical reader instantly sees "safe vs. not."
3. Annotate the peak contamination — when and how high.
4. Add a callout with the **most recent (2024) reading** for the well nearest the
   trench, so readers know where things stand today.
5. Include a short caption (1–2 sentences) and a data-attribution line, per `STYLE.md`.

## Deliverable

- `output/tritium_chart.png` — the chart
- A caption + attribution line (in the PNG or a small text file next to it)

Follow the design guide in `STYLE.md`. The dataset is in `data/`, documented in
`SOURCES.json`.
