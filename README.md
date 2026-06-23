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

Built from `momentmap.nb` (Hausel group). The edge-volume formula follows M. González,
*Note on torus actions on affine Grassmannians* — the label shows `k·B(β∨,β∨) = |d|²/k`
(twice the symplectic ℙ¹ volume `(k/2)·B(β∨,β∨)`).
