# nikhil5562.github.io

Personal portfolio of **Nikhil K Shaji**, AI/ML engineer, live at
**<https://nikhil5562.github.io>**.

It covers my work on AI tools for Kerala's monsoon and climate: Gemini apps,
a live climate projection dashboard, and deep-learning radar nowcasting.

## How it's built

A single static page (`index.html`) with inline CSS and JavaScript, plus
Google Fonts. It has no build step and no dependencies. The radar sweep in the
header is drawn on a `<canvas>` using the standard dBZ reflectivity colour
scale. It's an illustration, not live radar data.

## Updating

Edit `index.html` and push to `main`. GitHub Pages redeploys automatically
within a minute or two.
