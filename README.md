# Art with Code

**Interactive generative art experiments by [Sandro Ieva](https://sandroieva.com)**

A curated collection of 20 browser-based creative coding pieces — exploring particles, organic forms, 3D geometry, pattern systems, and procedural animation. Each artwork is fully interactive with real-time controls.

---

## Live Gallery

Open `index.html` in any modern browser to explore all pieces in a unified gallery experience with:

- Sleek list overview of all 20 artworks
- Full-screen artwork viewer with live controls
- Smooth curtain transitions between pieces
- Three.js wireframe background with mouse parallax
- Keyboard navigation (← → to browse, ESC to return)

## The Collection

| # | Title | Technique |
|---|-------|-----------|
| 01 | **ASCII Rain** | Canvas · Typography · Animation |
| 02 | **Flow Field** | Particles · Curl Noise · Color |
| 03 | **Candlestick Waves** | Grid · Wave · Pattern |
| 04 | **Code Waves** | 3D Terrain · Perspective · Lines |
| 05 | **Cross Pattern** | Grid · Crosses · Cyan |
| 06 | **Dataism Flower** | Dots · Petals · HUD |
| 07 | **Fish Swarm** | Swarm · Ring · Organic |
| 08 | **Contour Blobs** | Pencil · Blobs · Hand-drawn |
| 09 | **Iridescent Terrain** | Points · Color · Terrain |
| 10 | **Facet Sculpture** | Three.js · 3D · Sculpture |
| 11 | **Particle Form** | Three.js · Points · Mandala |
| 12 | **Organic Tree** | Three.js · Tree · Botanical |
| 13 | **Particle Globe** | Sphere · Particles · Space |
| 14 | **Pinecone Wireframe** | Wireframe · Botanical · 3D |
| 15 | **Pinwheel Wave** | Shader · Radial · Segments |
| 16 | **Pixel Twist** | Pixel · Grid · Export |
| 17 | **Pinecone Particles** | Rotation · Botanical · Canvas |
| 18 | **Self Swimming** | Swimmers · Ring · Organic |
| 19 | **Spiral Cone** | Three.js · Spiral · Cone |
| 20 | **Torus Tile Builder** | Torus · 3D · Tiles |

## Tech Stack

- **HTML5 Canvas** — 2D generative pieces
- **Three.js** — 3D sculptures, particle systems, organic forms
- **Vanilla JavaScript** — no build tools, no frameworks
- **Self-contained** — each artwork is a single HTML file

## Run Locally

```bash
# Clone the repo
git clone https://github.com/SandroIeva/art-with-code.git
cd art-with-code

# Open the gallery
open index.html
```

No dependencies. No build step. Just open in a browser.

## Deploy to Vercel

```bash
# Install Vercel CLI (if needed)
npm i -g vercel

# Deploy
vercel
```

Or connect the GitHub repo directly in the [Vercel dashboard](https://vercel.com/new).

## Project Structure

```
art-with-code/
├── index.html                          # Gallery (self-contained, all artworks embedded)
├── README.md
├── artworks/                           # Individual artwork source files
│   ├── ascii_rain_v8.html
│   ├── flow_field_clean.html
│   ├── candlestick_wave_pattern.html
│   ├── CodeWaves.html
│   ├── cross_pattern_animation.html
│   ├── dataism_flower_v3.html
│   ├── fish_swarm_organic.html
│   ├── handcrafted_contour_blobs.html
│   ├── iridescent_terrain_controls.html
│   ├── organic_facet_sculpture.html
│   ├── organic_particle_form_threejs.html
│   ├── organic_tree_3d.html
│   ├── particle_globe_v2.html
│   ├── pinecone_wireframe_botanical.html
│   ├── pinwheel_wave_shader.html
│   ├── pixel_twist.html
│   ├── rotating_pinecone_particles.html
│   ├── self_swimming_abstract.html
│   ├── spiral_cone_organic.html
│   └── torus_tile_builder.html
```

> **Note:** The gallery (`index.html`) embeds all artworks inline — no external file references needed. The `artworks/` folder contains the original source files for individual use or editing.

## Browser Support

Tested on Chrome, Safari, and Firefox. Requires a browser with ES6, Canvas 2D, and WebGL support.

## License

All artworks © Sandro Ieva. All rights reserved.

---

[sandroieva.com](https://sandroieva.com)
