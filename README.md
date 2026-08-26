# Frame Studio

A frame-by-frame animated GIF editor that runs entirely in the browser.
No build step, no dependencies, no server, no uploads — one static HTML file.

- Draw with brush, eraser, line, rectangle, ellipse and flood fill
- Shapes and text stay editable: select, move, resize, rotate and restyle them
- Import a GIF to edit it, or images as frames; export a real GIF
- Reference image for tracing, which is never included in the export
- Crop the canvas by hand, or trim straight to the artwork
- Layers per frame, with opacity, lock, hide and merge down
- Tween between frames: position, size, rotation, opacity and colour, with easing
- Zoom, pan, onion skinning, per-frame delays, undo/redo
- Autosaves to IndexedDB and offers your work back after a crash
- Exports only the region that changed between frames, so files stay small

The GIF encoder and decoder are both written from scratch in the page.

## Deploy (Render Static Site)

- Build command: *(leave empty)*
- Publish directory: `.`
