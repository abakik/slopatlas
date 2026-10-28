# Slop Atlas

*The default look of AI-generated interfaces, 2023–2027*

An interactive specimen bench for the default look of AI-generated interfaces ("slop"), 2023–2026, with a toy forecast for 2027.

Live at **https://slopatlas.vercel.app**. To run locally, open `index.html` in a browser. It is a single static file with no build step; fonts load from Google Fonts.

## What it does

- **Year presets (2023–2026).** Each renders a full fictional landing page ("Nova") assembled from that year's typical traits.
- **Recipe (mix & match).** Pick a year per dimension: colour, typography, component, composition, imagery, motion, interaction, plus copy as an extra dimension. "Shuffle" draws a random recipe.
- **Fine-tune.** Sliders and toggles per dimension (gradient and glow, hue, grain, headline scale, tracking, gradient text, radius, shadow, emoji density, spacing, image saturation, warm cast, dither, motion speed, number of AI entry points).
- **2027 forecast.** Five drivers (absorption of 2025–26 taste, agentic UI share, authenticity signalling, maximalist rebound, provenance labelling). Four scenarios compete per dimension, and the winner is the one with the highest driver × affinity score. The readout shows the weights, the signals behind them, and what would show the forecast is wrong.
- **Atlas Grid.** A dimension × year matrix with a mini specimen, tells and a "load into bench" button for every trait.
- **Tell salience.** A 0–3 heatmap of how visible each tell was per year. The 2027 column is computed from the drivers.
- **Evidence.** Every trait is tagged documented, reported, estimate or forecast, with links to the sources on the page. Hover or focus a recipe button to see a trait's tells and evidence.
- **Tells on the bench** lists every trait in the current specimen with its catalogue code (`C·24` = colour, 2024; `X·27C` = interaction, 2027 scenario C). **Copy recipe** exports the current configuration as JSON.

## Caveats

Salience scores are qualitative estimates, informed by the cited sources where they exist. They are not measurements. 2023 shows how AI products presented themselves (mostly designed by people), and 2024 shows a pre-existing style (the Linear look) as generators reproduced it. 2026 covers part of a year. The 2027 model is deliberately simple so its assumptions stay visible and open to argument.

## How to cite

Kocaballi, A. B. (2026). *Slop Atlas: The default look of AI-generated interfaces, 2023–2027* (Version 2.0) [Interactive website]. Human-AI Futures Lab, University of Technology Sydney. https://slopatlas.vercel.app

BibTeX and CFF metadata are in [`CITATION.cff`](CITATION.cff); GitHub's "Cite this repository" button reads it.

## Licence

Text, trait catalogue and salience data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Code: MIT. See [`LICENSE`](LICENSE). Built with assistance from Claude (Anthropic).
