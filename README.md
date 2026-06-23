# GKM Viewer

Interactive 3D viewers of the **GKM (moment) graph of the affine Grassmannian** for the
rank-2 root systems **A2, B2, G2**. Vertices are T-fixed points (lattice points lifted onto
the energy paraboloid, colored by energy `E = |v|²`); edges are the GKM / T-stable curves.

**Controls**
- Drag to rotate · scroll to zoom · right-drag to pan
- **Click a vertex**: cycles select → ▲ flow-up → ▼ flow-down → clear (shows simple-root
  coordinates and the Morse/flow cells)
- **Click an edge**: shows its **edge volume** `vol = …`

**Files** — open `index.html` (tabbed A2/B2/G2), or any of `a2.html` / `b2.html` / `g2.html`
directly. Each viewer is fully self-contained (three.js embedded) and works offline.

Built from `momentmap.nb` (Hausel group).

## Acknowledgement

Based on a note of **[Miguel González](https://miguelgg.com/)** (ICMAT), *Note on torus
actions on affine Grassmannians* — the GKM-graph conventions (vertices and one-dimensional orbits / edges)
and the **edge-volume formula** that this viewer displays. Clicking an edge shows
`k·B(β∨,β∨) = |d|²/k`, i.e. twice the symplectic ℙ¹ volume `(k/2)·B(β∨,β∨)` derived in
that note (which in turn uses Godinho–von Heymann–Sabatini, *12, 24 and beyond*,
Adv. Math. 319 (2017)).
