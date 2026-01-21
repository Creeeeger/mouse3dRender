# 3D Model Explorer

A lightweight Three.js demo viewer for exploring glTF sample models in an HDR environment. The browser loads every dependency directly, so the project does not require a build step.

## Run locally

The project contains only static files and can be served by any local web server. Two quick options are:

```bash
# Python 3
python -m http.server 8080

# npm http-server, if installed
npx http-server . -p 8080
```

Then open `http://localhost:8080` in a browser.

> [!NOTE]
> Opening `index.html` directly may fail because browsers restrict local module and asset requests. Use a local web server instead.

## Features

- Three.js 0.164.1 with orbit controls
- HDR environment lighting generated with PMREM
- Selectable glTF sample models
- Resource cleanup when switching models
- Responsive controls for desktop and touch devices

## Useful links

- [Three.js documentation](https://threejs.org/docs/)
- [glTF Sample Models](https://github.com/KhronosGroup/glTF-Sample-Models)
- [Poly Haven HDRIs](https://polyhaven.com/hdris)
