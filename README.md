# GenExtend & GenMorph – Demo Page

Companion demo page for the ICASSP 2026 paper **"GenExtend & GenMorph: Generative Audio Extension and Morphing"** by Prem Seetharaman*, Oriol Nieto*, and Justin Salamon (Adobe Research).

## Overview

The page showcases audio/video examples for:

- **GenExtend** – seamlessly extends an audio prompt forward or backward for a specified duration.
- **GenMorph** – blends two audio prompts into a smooth transition of the desired length.
- **Baselines** – Convolutional Noise Matching (CNM), a non-generative comparison.

## Project Structure

```
index.html      — Main HTML page
styles.css      — All CSS styles
img/            — Static images (architecture diagram, etc.)
videos/         — Example audio/video clips (.mp4)
```

## Running Locally

Open `index.html` in any modern browser, or serve the directory with a simple HTTP server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
