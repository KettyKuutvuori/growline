<img src="sprites/logo-light.webp" alt="Growline" width="490">

A procedural botanical drawing tool. Draw a path and flowers, grasses, leaves and stems grow along it.

**Live:** https://kettykuutvuori.github.io/growline/

## What you can do
- Draw open or closed paths, select a stretch and regrow it, reshape or move paths
- Styles: Photo, Basic, Minimal, Metallic, Cross-stitch
- Seasons and botanical sets: Wild meadow, Nordic, Alpine, Japanese
- Palette, density, scale, variation, orientation and seed
- Upload an image and draw over it; select it to move, resize from the corners, or delete it
- Play the growth animation on the canvas (G), then export it as MP4
- Export PNG, layered SVG, or the growing animation as MP4

## Run locally
It is a static site with no build step:

```
python3 -m http.server
```

then open http://localhost:8000.

## Files
- `index.html`: the whole app (HTML, CSS and JavaScript)
- `sprites/`: cut-out flower images used by the Photo style
