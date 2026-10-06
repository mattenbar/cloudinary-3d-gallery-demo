# Cloudinary 3D Product Gallery Demo

A single-page Cloudinary demonstration combining:

- Product images and video
- A tagged 360-degree spin set
- An interactive 3D Product Gallery model
- Live Carbon Black, Silver, and Crimson texture replacement
- JPG, animated WebP, MP4, GLB, and USDZ delivery examples
- Camera, lighting, exposure, and Draco compression controls
- An interactive 3D model over switchable campaign backgrounds

## Run locally

Serve the repository over HTTP:

```bash
python3 -m http.server 8765
```

Then open `http://127.0.0.1:8765/`.

## Deployment

The repository is designed to publish directly from the root of the `main`
branch with GitHub Pages.

## Cloudinary configuration

The default demo uses the `doxfstysv` product environment. Tag-based gallery
assets require client-side Resource Lists to be enabled, and transformations on
zipped 3D sources require PDF/ZIP delivery to be allowed in Cloudinary security
settings.
