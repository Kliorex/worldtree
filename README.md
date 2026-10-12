# WorldTree

A local-first, monochrome spatial knowledge prototype based on PRD v1.0.

## Run

Open `index.html` in a modern desktop browser. No build tools, login, or external dependencies are required.

## Features

- Perspective Canvas scene with draggable knowledge spheres and nested spaces
- Shared knowledge content with independent instance annotations
- Explicit orbit membership, links, and independent wormhole canvases
- Markdown preview, input autosave, and Markdown export
- Text, code, formula text, image/file blocks, live knowledge references, and endpoint reconnection
- Local attachments (8 MB per file, 30 MB total), included in JSON backups
- Explicit cross-space relationships, validated instance migration, and pinned positions
- Mobile knowledge-library drawer and keyboard-accessible modal controls
- IndexedDB persistence, search, JSON backup/restore, undo/redo, and recycle bin

This is v0.2 of a concept prototype, not a complete implementation of the PRD. Full rich text, typeset mathematics, whole-entity deletion, WebGL rendering, and large-scale performance optimization are not included. Existing v1 JSON backups remain compatible. Markdown exports embed attachments as data URLs; use JSON backups for full restoration.

## GitHub Pages

In repository Settings → Pages, select **Deploy from a branch**, then **main / (root)** and save.

Knowledge remains in each visitor's browser. Export JSON backups regularly. Local-file and hosted-site storage are separate; transfer knowledge with export/import.
