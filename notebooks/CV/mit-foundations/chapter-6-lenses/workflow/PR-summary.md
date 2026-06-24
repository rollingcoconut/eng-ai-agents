# Chapter 6 — Lenses: companion notebook

Runnable companion notebook for Chapter 6 (Lenses) of *Foundations of Computer Vision*, reproducing the chapter's diagrammatic figures as executable PyTorch/Kornia constructions driven by physical parameters.

## Figures completed
- [x] 6.1 — Brightness/sharpness trade-off
- [x] 6.3(a) — Snell's law at a flat interface
- [x] 6.4(a) — Thin-lens geometry
- [x] 6.4(b) — Labeled thin-lens geometry
- [x] 6.5 — Relation between R and θ_S
- [x] 6.6 — Off-axis points
- [x] 6.8(a–c) — Center ray through a lens
- [x] 6.9(a–e) — Conjugate points
- [x] 6.10 — Depth of field / circle of confusion
- [x] 6.11 — Variables for the depth-of-field calculation
- [x] 6.12 — Photographic depth of field vs aperture
- [x] 6.13(a–c) — Convex and concave behavior
- [x] 6.14(a, b) — Galilean telescope

## Figures skipped (physical photos, acknowledged in prose)
- [x] 6.3(b) — straw in water
- [x] 6.7 — laser pointer
- [x] 6.15 / 6.16 — cardboard telescope + moon

## Verification
- [x] Executes top-to-bottom cleanly; all 13 figures render to `images/`
- [x] No NumPy anywhere
- [x] No stray/duplicate cells or images
- [ ] Canonical container run (`docker compose … execute_notebook.py`) + registry update

## Conventions
- [x] PyTorch + Kornia only
- [x] Figure cells expose physical knobs; derive `f`/`b`/angles via shared helpers
- [x] Single shared `COLORS` palette; shared physics + drawing helpers
- [x] Pure-plotting cells tagged `hide-input`
- [x] Markdown/comments code-first, evergreen, no toolchain references
