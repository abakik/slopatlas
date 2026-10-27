# Sloplab

An interactive specimen bench for the default look of AI-generated interfaces ("slop"), 2023–2026, with a toy forecast for 2027.

Open `index.html` in a browser. It is a single static file with no build step; fonts load from Google Fonts.

## What it does

- **Year presets (2023–2026).** Each renders a full fictional landing page ("Nova") assembled from that year's typical traits.
- **Recipe (mix & match).** Pick a year per dimension: colour, typography, component, composition, imagery, motion, interaction, plus copy as an extra dimension. "Shuffle" draws a random recipe.
- **Fine-tune.** Sliders and toggles per dimension (gradient and glow, hue, grain, headline scale, tracking, gradient text, radius, shadow, emoji density, spacing, image saturation, warm cast, dither, motion speed, number of AI entry points).
- **2027 forecast.** Five drivers (absorption of 2025–26 taste, agentic UI share, authenticity signalling, maximalist rebound, provenance labelling). Four scenarios compete per dimension, and the winner is the one with the highest driver × affinity score. The readout shows the weights, the signals behind them, and what would show the forecast is wrong.
- **Atlas.** A dimension × year matrix with a mini specimen, tells and a "load into bench" button for every trait.
- **Tell salience.** A 0–3 heatmap of how visible each tell was per year. The 2027 column is computed from the drivers.
- **Tells on the bench** lists every trait in the current specimen with its catalogue code (`C·24` = colour, 2024; `X·27C` = interaction, 2027 scenario C). **Copy recipe** exports the current configuration as JSON.

## Caveats

The trait descriptions and salience scores are qualitative estimates drawn from design-community discussion, tool defaults and generated samples. They are not measurements. 2026 covers part of a year. The 2027 model is deliberately simple so its assumptions stay visible and open to argument.
