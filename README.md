# MODFORGE — Eurorack Synthesizer Prototyper

An interactive web-based tool for designing and testing custom Eurorack synthesizer modules.

## Features

- **12 Module Types** — VCO, VCF, VCA, ADSR, LFO, Mixer, Noise, S&H, Stereo, Sequencer, Tuner, Clock
- **Real-Time Audio** — Web Audio synthesis with live patching
- **Visual Patch Cables** — Click ports to connect, animated wire-drawing UX
- **Module Designer** — Combine subcircuits into custom modules with the Design tab
- **Random Module Generator** — One-click inspiration for new designs
- **Save/Load** — Persist designs and custom modules in localStorage
- **BOM & Schematics** — Auto-generated bill of materials and circuit diagrams
- **Send to Patch** — Test your custom designs with live audio

## Hosting on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch**, select `main` and `/ (root)`
4. Your app will be live at `https://yourusername.github.io/modforge/`

## Embedding in Squarespace

Add a **Code Block** to your Squarespace page with:

```html
<iframe 
  src="https://yourusername.github.io/modforge/" 
  width="100%" 
  height="900" 
  style="border:none; border-radius:8px;"
  allow="autoplay"
></iframe>
```

> The `allow="autoplay"` attribute is needed for Web Audio to work inside the iframe.

## Development

The app is a single `index.html` file with no build step — React and Babel load from CDN. Just edit and push.

## License

MIT
