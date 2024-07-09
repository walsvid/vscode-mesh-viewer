# VSCode 3D Mesh Viewer

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/kiui.mesh-viewer)](https://marketplace.visualstudio.com/items?itemName=kiui.mesh-viewer)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/kiui.mesh-viewer)

Marketplace: [kiui.mesh-viewer](https://marketplace.visualstudio.com/items?itemName=kiui.mesh-viewer)

## Description

This extension is modified from [vscode-3d-preview](https://github.com/tatsy/vscode-3d-preview) with the following features:
* Preview meshes in GLB/GLTF/OBJ/PLY formats with texture.
* Play GLB/GLTF animations.
* Default to white background.

#### Mesh preview

<video controls>
  <source src="assets/demo.mp4" type="video/mp4">
</video>

https://github.com/ashawkey/vscode-mesh-viewer/assets/25863658/f12653eb-be65-43de-9f9e-97d89b96c7f5

Credits to ["Kgirls01" (https://skfb.ly/6CIGK) by nuulbee is licensed under CC Attribution-NonCommercial-NoDerivs (http://creativecommons.org/licenses/by-nc-nd/4.0/)](https://sketchfab.com/3d-models/kgirls01-d2f946f58a8040ae993cda70c97b302c).

![mesh](assets/demo.png)

## Development
Install `Node.js` and `npm` first, then clone this repo and:

```bash
# install dependencies
npm install 

# use F5 or the dubugger panel to start debugging (will open a new VSCode window with this extension enabled.)
# Help->Toggle Developer Tools (or Shift-Control-I) to see console output.

# publish (requires vsce, a publisher as defined in package.json, and the personal access token)
# first change version in package.json
vsce publish
```

## Acknowledgements & Reference

* [vscode-3d-preview](https://github.com/tatsy/vscode-3d-preview)
* [vscode-3dviewer](https://github.com/stef-levesque/vscode-3dviewer)
* [vscode-pc-viewer](https://github.com/Obarads/vscode-pc-viewer)
* [three.js](https://threejs.org/)
