# 3d-cell

An interactive 3D model of the inside of an animal (eukaryotic) cell, built with [three.js](https://threejs.org/).

**Run it:** open `index.html` in a modern browser (it loads three.js from a CDN, so an internet connection is needed). Or serve the folder, e.g. `python3 -m http.server` and visit http://localhost:8000.

## What's inside

Plasma membrane (with membrane proteins) · nucleus (double envelope + nuclear pores) · chromatin · nucleolus · rough ER with bound ribosomes · smooth ER · Golgi apparatus · mitochondria (with cristae) · lysosomes · peroxisomes · free ribosomes · transport vesicles · centrosome (two centrioles of 9 microtubule triplets) · microtubules.

## Controls

- **Drag** to rotate, **scroll / pinch** to zoom, right-drag to pan.
- **Hover** to identify, **click** a structure (or its name in the list) to fly to it and read about it.
- **◉** hides/shows a structure; **Isolate** shows one on its own.
- **Cutaway** opens a wedge in the membrane and nucleus; **Labels** names everything; **Motion** toggles vesicle traffic and organelle drift.
- **Quiz me** asks you to find structures by clicking them.

The model is schematic — sizes and counts are not to scale.
