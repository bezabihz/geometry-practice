---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 12
## Surface Area

McGraw Hill Glencoe Geometry · Texas Edition

---

## Key Vocabulary & Euler's Formula

<div class="columns">
<div>

| Term | Definition |
|------|-----------|
| **Polyhedron** | 3-D solid with flat polygon faces |
| **Face** | Flat surface |
| **Edge** | Segment where two faces meet |
| **Vertex** | Point where edges meet |
| **Lateral face** | Non-base face |
| **Lateral area (LA)** | Sum of lateral face areas |
| **Surface area (SA)** | Total area of all faces |
| **Slant height** $\ell$ | Height of lateral face (pyramid/cone) |

**Euler's Formula:**
$$F + V - E = 2$$

> **Example:** A cube: $F = 6$, $V = 8$, $E = 12$.
> $6 + 8 - 12 = 2$ ✓

</div>
<div>

<svg width="290" height="250" viewBox="0 0 290 250" xmlns="http://www.w3.org/2000/svg">
  <!-- Cube front face -->
  <polygon points="40,90 160,90 160,210 40,210" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Cube back face (top/right) -->
  <polygon points="80,50 200,50 200,170 80,170" fill="#f0f5fc" stroke="#1a3a5c" stroke-width="1.5"/>
  <!-- Connecting edges -->
  <line x1="40" y1="90" x2="80" y2="50" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="160" y1="90" x2="200" y2="50" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="160" y1="210" x2="200" y2="170" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="40" y1="210" x2="80" y2="170" stroke="#1a3a5c" stroke-width="1.5" stroke-dasharray="5,3"/>
  <!-- Vertex dots -->
  <circle cx="40" cy="90" r="5" fill="#e05c1a"/>
  <circle cx="160" cy="90" r="5" fill="#e05c1a"/>
  <circle cx="200" cy="50" r="5" fill="#e05c1a"/>
  <circle cx="80" cy="50" r="5" fill="#e05c1a"/>
  <!-- Labels -->
  <text x="90" y="160" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">Face</text>
  <text x="156" y="148" font-size="12" fill="#e05c1a" font-family="Arial">Edge</text>
  <text x="30" y="85" font-size="12" fill="#e05c1a" font-family="Arial">V</text>
  <!-- Euler -->
  <rect x="10" y="218" width="270" height="28" rx="6" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="145" y="237" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold" text-anchor="middle">F + V − E = 2  (Euler)</text>
</svg>

</div>
</div>

---

## Prisms

<div class="columns">
<div>

A **right prism** has rectangular lateral faces perpendicular to the bases.

**Theorem 12-1:**
$$LA = Ph \qquad SA = Ph + 2B$$

where $P$ = perimeter of base, $h$ = height, $B$ = area of base.

**Rectangular prism** ($l \times w \times h$):
$$SA = 2(lw + lh + wh)$$

> **Example:** $l = 5$, $w = 3$, $h = 4$
> $SA = 2(5 \cdot 3 + 5 \cdot 4 + 3 \cdot 4)$
> $= 2(15 + 20 + 12) = 2(47) = \mathbf{94}$

**Triangular prism** — base is a triangle; lateral faces are 3 rectangles.

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangular prism -->
  <!-- Front face -->
  <polygon points="40,110 160,110 160,220 40,220" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Top face -->
  <polygon points="40,110 80,60 200,60 160,110" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Right face -->
  <polygon points="160,110 200,60 200,170 160,220" fill="#b5cee8" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Height arrow -->
  <line x1="215" y1="60" x2="215" y2="170" stroke="#e05c1a" stroke-width="2.5"/>
  <polygon points="215,170 210,158 220,158" fill="#e05c1a"/>
  <polygon points="215,60 210,72 220,72" fill="#e05c1a"/>
  <text x="220" y="120" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">h=4</text>
  <!-- Width label -->
  <text x="80" y="240" font-size="13" fill="#1a3a5c" font-family="Arial">l=5</text>
  <!-- Depth label -->
  <text x="165" y="200" font-size="13" fill="#1a3a5c" font-family="Arial">w=3</text>
  <!-- Net hint -->
  <text x="20" y="20" font-size="13" fill="#555" font-family="Arial" font-weight="bold">SA = 2(lw+lh+wh) = 94</text>
</svg>

</div>
</div>

---

## Cylinders

<div class="columns">
<div>

A **right cylinder** has two circular bases connected by a curved lateral surface.

**Theorem 12-2:**
$$LA = 2\pi r h \qquad SA = 2\pi r h + 2\pi r^2$$

**Think of the net:** Unroll the cylinder — the lateral surface becomes a rectangle with width $h$ and length $= 2\pi r$ (circumference).

$$SA = \underbrace{2\pi r h}_{\text{lateral}} + \underbrace{2\pi r^2}_{\text{2 circles}}$$

> **Example:** $r = 3$, $h = 7$
> $LA = 2\pi(3)(7) = 42\pi$
> $SA = 42\pi + 2\pi(9) = 42\pi + 18\pi = \mathbf{60\pi} \approx 188.5$

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Cylinder -->
  <!-- Bottom ellipse -->
  <ellipse cx="145" cy="200" rx="80" ry="25" fill="#b5cee8" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Sides -->
  <line x1="65" y1="90" x2="65" y2="200" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="225" y1="90" x2="225" y2="200" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Top ellipse -->
  <ellipse cx="145" cy="90" rx="80" ry="25" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Radius arrow -->
  <line x1="145" y1="90" x2="225" y2="90" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="178" y="82" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">r=3</text>
  <!-- Height arrow -->
  <line x1="240" y1="90" x2="240" y2="200" stroke="#e05c1a" stroke-width="2.5"/>
  <polygon points="240,200 235,188 245,188" fill="#e05c1a"/>
  <polygon points="240,90 235,102 245,102" fill="#e05c1a"/>
  <text x="245" y="150" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">h=7</text>
  <!-- Net rectangle below -->
  <rect x="15" y="235" width="180" height="28" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <text x="105" y="252" font-size="12" fill="#e05c1a" font-family="Arial" text-anchor="middle">Unrolled: 2πr × h</text>
</svg>

</div>
</div>

---

## Pyramids

<div class="columns">
<div>

A **regular pyramid** has a regular polygon base; lateral faces are congruent isosceles triangles.

**Slant height** $\ell$ = height of each triangular lateral face (measured from apex to base edge midpoint).

**Theorem 12-3:**
$$LA = \frac{1}{2}P\ell \qquad SA = \frac{1}{2}P\ell + B$$

> **Example (Square pyramid):** base = 6, slant height $\ell = 5$
> $P = 4 \times 6 = 24$
> $LA = \frac{1}{2}(24)(5) = 60$
> $B = 6^2 = 36$
> $SA = 60 + 36 = \mathbf{96}$

**Finding slant height:** Use Pythagorean theorem: $\ell = \sqrt{h^2 + (s/2)^2}$

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Square base of pyramid -->
  <polygon points="60,220 220,220 260,170 100,170" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Lateral faces -->
  <polygon points="60,220 100,170 160,50" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="100,170 260,170 160,50" fill="#b5cee8" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="220,220 260,170 160,50" fill="#a8c8e0" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Apex -->
  <circle cx="160" cy="50" r="5" fill="#e05c1a"/>
  <text x="163" y="46" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">Apex</text>
  <!-- Slant height -->
  <line x1="160" y1="50" x2="140" y2="220" stroke="#e05c1a" stroke-width="2.5" stroke-dasharray="6,3"/>
  <text x="120" y="140" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">ℓ = 5</text>
  <!-- Base label -->
  <text x="125" y="246" font-size="13" fill="#1a3a5c" font-family="Arial">s = 6</text>
  <!-- Height (dashed) -->
  <line x1="160" y1="50" x2="160" y2="195" stroke="#555" stroke-width="1.5" stroke-dasharray="4,3"/>
  <text x="164" y="128" font-size="12" fill="#555" font-family="Arial">h</text>
  <text x="180" y="270" font-size="12" fill="#555" font-family="Arial">SA = ½Pℓ + B = 96</text>
</svg>

</div>
</div>

---

## Cones & Spheres

<div class="columns">
<div>

**Theorem 12-4 (Cone):**
$$LA = \pi r \ell \qquad SA = \pi r \ell + \pi r^2$$

Slant height: $\ell = \sqrt{r^2 + h^2}$

> **Example:** $r = 5$, $h = 12$
> $\ell = \sqrt{25+144} = \sqrt{169} = 13$
> $SA = \pi(5)(13) + \pi(25) = 65\pi + 25\pi = \mathbf{90\pi} \approx 282.7$

---

**Sphere (Theorem 12-5):**
$$SA = 4\pi r^2$$

A sphere's surface area equals exactly 4 times the area of its great circle — a remarkable result discovered by Archimedes.

> **Example:** $r = 6$
> $SA = 4\pi(36) = \mathbf{144\pi} \approx 452.4$

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Cone -->
  <!-- Base ellipse -->
  <ellipse cx="90" cy="200" rx="60" ry="18" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Lateral surface -->
  <line x1="30" y1="200" x2="90" y2="70" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="150" y1="200" x2="90" y2="70" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Radius -->
  <line x1="90" y1="200" x2="150" y2="200" stroke="#e05c1a" stroke-width="2"/>
  <text x="115" y="196" font-size="12" fill="#e05c1a" font-family="Arial">r=5</text>
  <!-- Height -->
  <line x1="90" y1="70" x2="90" y2="200" stroke="#e05c1a" stroke-width="2" stroke-dasharray="4,3"/>
  <text x="94" y="138" font-size="12" fill="#e05c1a" font-family="Arial">h=12</text>
  <!-- Slant height -->
  <text x="46" y="140" font-size="12" fill="#555" font-family="Arial">ℓ=13</text>
  <text x="30" y="228" font-size="12" fill="#555" font-family="Arial">SA=90π</text>

  <!-- Sphere -->
  <circle cx="215" cy="140" r="80" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Great circle -->
  <ellipse cx="215" cy="140" rx="80" ry="20" fill="none" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <!-- Radius -->
  <line x1="215" y1="140" x2="295" y2="140" stroke="#e05c1a" stroke-width="2"/>
  <text x="248" y="133" font-size="12" fill="#e05c1a" font-family="Arial">r=6</text>
  <text x="168" y="248" font-size="12" fill="#555" font-family="Arial">SA=4πr²=144π</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example — Composite Solid

**A silo is a cylinder topped with a hemisphere. $r = 8$ ft, cylinder height = 20 ft. Find the total surface area (excluding the floor).**

<div class="columns">
<div>

**Cylinder lateral surface** (no top):
$$LA = 2\pi r h = 2\pi(8)(20) = 320\pi$$

**Hemisphere** (half of $4\pi r^2$):
$$SA_{\text{hemi}} = \frac{1}{2}(4\pi r^2) = 2\pi r^2 = 2\pi(64) = 128\pi$$

**Total:**
$$SA = 320\pi + 128\pi = \mathbf{448\pi} \approx 1407.4 \text{ ft}^2$$

Note: we exclude the floor (bottom circle of cylinder).

</div>
<div>

<svg width="240" height="250" viewBox="0 0 240 250" xmlns="http://www.w3.org/2000/svg">
  <!-- Cylinder body -->
  <line x1="40" y1="120" x2="40" y2="230" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="200" y1="120" x2="200" y2="230" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Bottom ellipse (floor) -->
  <ellipse cx="120" cy="230" rx="80" ry="20" fill="#ddd" stroke="#888" stroke-width="1.5" stroke-dasharray="5,3"/>
  <!-- Hemisphere on top -->
  <path d="M40,120 A80,80 0 0,1 200,120" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Cylinder visible fill -->
  <rect x="40" y="120" width="160" height="110" fill="#c8ddf0" stroke="none"/>
  <line x1="40" y1="120" x2="40" y2="230" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="200" y1="120" x2="200" y2="230" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Radius label -->
  <line x1="120" y1="120" x2="200" y2="120" stroke="#e05c1a" stroke-width="2"/>
  <text x="153" y="115" font-size="12" fill="#e05c1a" font-family="Arial">r=8</text>
  <!-- Height label -->
  <line x1="215" y1="120" x2="215" y2="230" stroke="#e05c1a" stroke-width="2"/>
  <text x="218" y="180" font-size="12" fill="#e05c1a" font-family="Arial">h=20</text>
  <text x="30" y="14" font-size="12" fill="#555" font-family="Arial">SA = 320π + 128π = 448π ft²</text>
</svg>

</div>
</div>

---

## Chapter 12 — Summary

| Solid | Lateral Area | Surface Area |
|-------|-------------|-------------|
| Right prism | $Ph$ | $Ph + 2B$ |
| Cylinder | $2\pi r h$ | $2\pi r h + 2\pi r^2$ |
| Regular pyramid | $\frac{1}{2}P\ell$ | $\frac{1}{2}P\ell + B$ |
| Cone | $\pi r\ell$ | $\pi r\ell + \pi r^2$ |
| Sphere | — | $4\pi r^2$ |

> **Key insight:** Every surface area formula = lateral area + bases. The lateral area of a prism unrolls to a rectangle; a cylinder unrolls to a rectangle of width $h$ and length $2\pi r$; a pyramid/cone unrolls to a sector of a circle.
