# Pressure control valves: animated cross-sections

An interactive teaching site in the same style as [hydraulic-cylinders](https://alibulentkoc.github.io/hydraulic-cylinders/). Students pick a valve from the list and watch it work in cross-section. Each valve has a short explanation, its schematic symbol, agricultural applications, a calculator (SI or US customary units) and a quiz.

Valves included:

- Check valve
- Direct-acting relief valve
- Sequence valve
- Counterbalance valve
- Pressure-reducing valve
- Unloading valve
- Pilot-operated relief valve
- Course quiz: concept questions from every valve plus calculation problems with new numbers each time

## For each valve

- **Cross-section animation** with a pressure slider, Play/Pause, slow motion, labels, live gauges and a 10-second pressure trace. Oil is coloured by function: pressure, pilot, reduced or metered, return and drain.
- **How it works**, **Used for** and **Watch for**.
- **In agriculture**: tractors, sprayers, planters, telehandlers, log splitters, combines and more, with typical settings and a class discussion question.
- **Calculator** with Quantity, Formula, Substitution and Result columns, in consistent SI or US units.
- **Quiz** with explanations; the best score is remembered in the browser.

## Lecture mode

Press **Lecture mode** (or `L`). Navigation is hidden, text is larger, and a presenter bar appears. Keys: `←` `→` change valve, `N` reveal the next point, `Space` play or pause, `S` slow motion, `F` full screen, `Esc` exit.

## Publish on GitHub Pages

Settings → Pages → Deploy from a branch → `main`, `/ (root)`. The site is served at `https://alibulentkoc.github.io/hydraulic-pressure-valves/`. Link straight to a valve with `#check`, `#relief`, `#sequence`, `#counterbalance`, `#reducing`, `#unloading`, `#pilot-relief` or `#exam`.

The site loads Google Fonts from a public CDN. Everything else is in `index.html`, with no build step.

Drawings are simplified and not to scale. Typical settings are for teaching; always use the machine manufacturer's service manual for real adjustments.
