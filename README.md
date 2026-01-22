# pages

## 3D viewer page

This repository hosts a lightweight 3D viewer intended for embedding in SharePoint via an iframe.

### How to use

1. Add your model file as `model.glb` in the repository root.
2. Publish GitHub Pages (or other static hosting) for this repository.
3. Use the published `index.html` URL as the iframe source in SharePoint.

### Optional: load a different file name

If your model uses a different file name, keep it in the repo root and pass it in the URL:

```
https://<your-pages-domain>/index.html?model=your-file.glb
```

The page uses `<model-viewer>` from Google to render the GLB file.
