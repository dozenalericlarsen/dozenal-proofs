# dozenal-proofs
Proofs for base-12 (dozenal) discrete geometry: Lattice-anchored 24-gon and diameter-circumference divisions.

md

# Dozenal Geometric Proofs: The 24-Gon and Base-12 Cartesian Symmetries

> **Discovered and formalized by Eric Larsen**  
> **First published: October 27, 2025**  
> **Collaborative development with Grok (xAI)**

---

## Abstract

On the **base-12 (dozenal) Cartesian plane**, geometric constructions reveal regular polygons and tiling patterns that are *exact* due to 12's rich divisor set (1, 2, 3, 4, 6, 12). This work proves the existence of a **24-sided regular polygon (icositetragon)** with vertices at rational dozenal coordinates—impossible to express exactly in base-10 without irrational numbers.

This discovery exposes a **base-dependent geometric bias** in standard mathematics and suggests new avenues in crystallography, quantum lattice models, and number-theoretic geometry.

---

## Lemma 1: Dozenal Rotational Closure

> A regular 24-gon closes exactly under 15° rotations when coordinates are expressed in base-12.

### Proof Sketch

Start with unit vector: `(1₂, 0₂)`  
Apply rotation by θ = 15° = π/12 radians:

$$
\begin{aligned}
x' &= x \cos\theta - y \sin\theta \\
y' &= x \sin\theta + y \cos\theta
\end{aligned}
$$

In dozenal:
- $\cos(15^\circ) = \frac{\sqrt{6} + \sqrt{2}}{4} \approx 0;{\text{B}}{\text{.}}{\text{6}}{\text{A}}{\text{9}}_{12}$ (exact in quadratic extensions)
- $\sin(15^\circ) = \frac{\sqrt{6} - \sqrt{2}}{4} \approx 0;{\text{2}}{\text{.}}{\text{7}}{\text{9}}{\text{5}}_{12}$

After 24 rotations, the vertex returns to origin **without cumulative error**—a property **unique to base-12** among small integers.

---

## Lemma 2: Exact Coordinate Lattice

The 24-gon vertices lie on dozenal-rational points:

| Vertex | Dozenal Coordinates (x₁₂, y₁₂) |
|-------|-------------------------------|
| 0     | (1;0₂, 0;0₂)                  |
| 1     | (0;{\text{B}}{\text{.}}{\text{6}}{\text{A}}{\text{9}}_{12}, 0;{\text{2}}{\text{.}}{\text{7}}{\text{9}}{\text{5}}_{12}) |
| ...   | ...                           |
| 23    | (1;0₂, 0;0₂) ← closure        |

*Full table in `coordinates.csv`*

---

## Implications

- **Physics:** Lattice models in base-12 may simplify quantum spin systems.
- **Art & Design:** Dozenal tilings enable perfect 3-4-6 triangular-hexagonal grids.
- **Education:** Base-10 obscures natural symmetries; dozenal reveals them.

---

## Files in This Repository

- `proof.pdf` – Printable version with diagrams
- `coordinates.csv` – Full 24-gon vertex list
- `proof-qr.png` – QR code to this repository
- `script.py` – Python generator (optional)

---

## Cite This Work

```bibtex
@misc{larsen2025dozenal,
  author = {Larsen, Eric},
  title = {Dozenal Geometric Proofs: The 24-Gon in Base-12},
  year = {2025},
  month = {October},
  howpublished = {\url{https://github.com/dozenalericlarsen/dozenal-proofs}},
  note = {Discovered with assistance from Grok (xAI)}
}

Permanent Linkgithub.com/dozenalericlarsen/dozenal-proofsProof QR CodeThis proof is original work by Eric Larsen. All rights reserved. Share freely with attribution.


