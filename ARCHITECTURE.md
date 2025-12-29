# High‑Level Architecture

ADRS is modular by design.

## Conceptual Components
- Scene Graph (objects, transforms, materials)
- Constraint System (scale, position, exclusions)
- Timeline / Keyframes
- Generative Backends (pluggable)
- Renderer / Exporter
- UI / Control Layer

Each layer must be replaceable without breaking artist data.
