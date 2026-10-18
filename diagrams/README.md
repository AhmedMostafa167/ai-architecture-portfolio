# Diagrams

- `src/` — editable source files (e.g. `.drawio`, `.excalidraw`, `.mmd`, `.puml`)
- `export/` — rendered PNG/SVG files referenced from docs and ADRs

Keep the same base name for a source and its exports, e.g.
`src/context.drawio` → `export/context.svg`. Re-export whenever the source changes.
