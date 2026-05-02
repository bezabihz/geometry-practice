---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 9
## Transformations

McGraw Hill Glencoe Geometry · Texas Edition

---

## Types of Transformations

A **transformation** moves or resizes a figure. The original is the **preimage**; the result is the **image**.

<div class="columns">
<div>

| Type | Motion | Isometry? |
|------|--------|-----------|
| **Translation** | Slide | Yes ✓ |
| **Reflection** | Flip | Yes ✓ |
| **Rotation** | Turn | Yes ✓ |
| **Dilation** | Resize | No (unless $k=1$) |

**Isometry** (rigid motion) — preserves side lengths and angle measures. Shape and size unchanged.

> Translations, reflections, and rotations are all isometries.
> Dilations preserve shape (similar) but not necessarily size.

</div>
<div>

<svg width="300" height="250" viewBox="0 0 300 250" xmlns="http://www.w3.org/2000/svg">
  <!-- Translation -->
  <polygon points="15,50 55,50 35,20" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="70,50 110,50 90,20" fill="#fff3e0" stroke="#e05c1a" stroke-width="2" stroke-dasharray="4,2"/>
  <line x1="35" y1="35" x2="65" y2="35" stroke="#555" stroke-width="1.5" stroke-dasharray="3,2"/>
  <polygon points="65,35 57,31 57,39" fill="#555"/>
  <text x="20" y="70" font-size="11" fill="#1a3a5c" font-family="Arial">Translation →</text>

  <!-- Reflection -->
  <polygon points="140,50 180,50 160,20" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="200" y1="10" x2="200" y2="70" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
  <polygon points="220,50 260,50 240,20" fill="#fff3e0" stroke="#e05c1a" stroke-width="2" stroke-dasharray="4,2"/>
  <text x="142" y="70" font-size="11" fill="#1a3a5c" font-family="Arial">Reflection ↔</text>

  <!-- Rotation -->
  <polygon points="30,155 70,155 50,120" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="50" cy="155" r="3" fill="#e05c1a"/>
  <path d="M55,140 A25,25 0 0,1 75,155" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <polygon points="75,155 67,147 65,157" fill="#e05c1a"/>
  <polygon points="55,175 95,175 75,145" fill="#fff3e0" stroke="#e05c1a" stroke-width="2" stroke-dasharray="4,2"/>
  <text x="20" y="198" font-size="11" fill="#1a3a5c" font-family="Arial">Rotation ↺</text>

  <!-- Dilation -->
  <polygon points="160,130 190,130 175,110" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="145,180 220,180 182,130" fill="#fff3e0" stroke="#e05c1a" stroke-width="2" stroke-dasharray="4,2"/>
  <circle cx="183" cy="180" r="3" fill="#e05c1a"/>
  <text x="148" y="200" font-size="11" fill="#1a3a5c" font-family="Arial">Dilation (scale k)</text>
</svg>

</div>
</div>

---

## Translations

A **translation** slides every point the same distance in the same direction, described by a **vector** $\langle a, b \rangle$.

$$T_{\langle a,b \rangle}(x, y) = (x+a,\; y+b)$$

<div class="columns">
<div>

> **Example:** Translate $A(3, 2)$ by vector $\langle -1, 4 \rangle$.
>
> $A' = (3 + (-1),\; 2 + 4) = (2, 6)$

**Key properties of translations:**
- All points move the same vector
- Preimage and image are congruent ($\cong$)
- Corresponding sides are parallel
- Translation by $\langle 0, 0 \rangle$ is the identity

</div>
<div>

<svg width="290" height="250" viewBox="0 0 290 250" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="230" x2="270" y2="230" stroke="#bbb" stroke-width="1.5"/>
  <line x1="20" y1="230" x2="20" y2="20" stroke="#bbb" stroke-width="1.5"/>
  <polygon points="20,230 270,230 270,20" fill="none"/>
  <text x="272" y="234" font-size="11" fill="#888" font-family="Arial">x</text>
  <text x="12" y="18" font-size="11" fill="#888" font-family="Arial">y</text>
  <!-- Grid lines faint -->
  <line x1="70" y1="20" x2="70" y2="230" stroke="#eee" stroke-width="1"/>
  <line x1="120" y1="20" x2="120" y2="230" stroke="#eee" stroke-width="1"/>
  <line x1="170" y1="20" x2="170" y2="230" stroke="#eee" stroke-width="1"/>
  <line x1="220" y1="20" x2="220" y2="230" stroke="#eee" stroke-width="1"/>
  <line x1="20" y1="80" x2="270" y2="80" stroke="#eee" stroke-width="1"/>
  <line x1="20" y1="130" x2="270" y2="130" stroke="#eee" stroke-width="1"/>
  <line x1="20" y1="180" x2="270" y2="180" stroke="#eee" stroke-width="1"/>
  <!-- Original triangle A(3,2), B(6,2), C(5,5) mapped to coords -->
  <!-- scale: x→(x-0)*45+20, y→230-(y-0)*45 = 5→(5)*45, 3→155, 6→290 -->
  <!-- Simplified: let 1 unit = 40px, origin at (20,230) -->
  <!-- A(3,2)→(140,150), B(6,2)→(260,150), C(5,5)→(220,30) -->
  <polygon points="140,150 220,150 200,90" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="130" y="170" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="222" y="170" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="202" y="84" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <!-- Translated by <-2,1>: A'(1,3)→(60,110), B'(4,3)→(180,110), C'(3,6)→(140,50) -->
  <polygon points="60,110 140,110 120,50" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5" stroke-dasharray="6,3"/>
  <text x="40" y="128" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">A'</text>
  <text x="142" y="128" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">B'</text>
  <text x="122" y="44" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">C'</text>
  <!-- Translation vectors (arrows) -->
  <line x1="140" y1="150" x2="60" y2="110" stroke="#555" stroke-width="1.5" stroke-dasharray="4,3"/>
  <polygon points="60,110 68,114 70,104" fill="#555"/>
  <text x="82" y="128" font-size="12" fill="#555" font-family="Arial">⟨−2,1⟩</text>
</svg>

</div>
</div>

---

## Reflections

A **reflection** flips a figure over a **line of reflection**. Each point maps to its mirror image.

<div class="columns">
<div>

| Line | Rule |
|------|------|
| $x$-axis | $(x, y) \to (x, -y)$ |
| $y$-axis | $(x, y) \to (-x, y)$ |
| $y = x$ | $(x, y) \to (y, x)$ |
| $y = -x$ | $(x, y) \to (-y, -x)$ |

**Properties:**
- Each reflected point is the same distance from the line as the original
- The line of reflection is the **perpendicular bisector** of each segment joining a point to its image

> **Example:** Reflect $P(4, -3)$ over the $y$-axis.
> $P' = (-4, -3)$

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Axes -->
  <line x1="20" y1="130" x2="270" y2="130" stroke="#bbb" stroke-width="1.5"/>
  <line x1="145" y1="20" x2="145" y2="250" stroke="#e05c1a" stroke-width="2.5" stroke-dasharray="6,3"/>
  <text x="272" y="134" font-size="12" fill="#888" font-family="Arial">x</text>
  <text x="148" y="18" font-size="12" fill="#e05c1a" font-family="Arial" font-weight="bold">y-axis (mirror)</text>
  <!-- Original triangle (right side) -->
  <polygon points="175,60 235,120 175,120" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="238" y="128" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="176" y="55" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="160" y="128" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <!-- Reflected triangle (left side) -->
  <polygon points="115,60 55,120 115,120" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5" stroke-dasharray="6,3"/>
  <text x="38" y="128" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">A'</text>
  <text x="116" y="55" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">B'</text>
  <text x="117" y="128" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">C'</text>
  <!-- Dashed perpendicular lines showing equal distance -->
  <line x1="175" y1="60" x2="115" y2="60" stroke="#ccc" stroke-width="1" stroke-dasharray="3,3"/>
  <line x1="235" y1="120" x2="55" y2="120" stroke="#ccc" stroke-width="1" stroke-dasharray="3,3"/>
  <text x="50" y="218" font-size="12" fill="#555" font-family="Arial">(x,y) → (−x,y)  over the y-axis</text>
</svg>

</div>
</div>

---

## Rotations

A **rotation** turns a figure by angle $\theta$ about a **center of rotation**.

<div class="columns">
<div>

Rules for rotations about the **origin**:

| Rotation | Rule |
|----------|------|
| 90° CCW | $(x, y) \to (-y, x)$ |
| 180° | $(x, y) \to (-x, -y)$ |
| 270° CCW (= 90° CW) | $(x, y) \to (y, -x)$ |
| 360° | $(x, y) \to (x, y)$ (identity) |

> **Example:** Rotate $P(4, -2)$ by 90° CCW.
> $P' = (-(-2), 4) = (2, 4)$

**Rotational symmetry:** A figure has rotational symmetry of order $n$ if a rotation by $\frac{360°}{n}$ maps it to itself.

</div>
<div>

<svg width="280" height="260" viewBox="0 0 280 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Axes -->
  <line x1="20" y1="130" x2="260" y2="130" stroke="#bbb" stroke-width="1.5"/>
  <line x1="140" y1="20" x2="140" y2="250" stroke="#bbb" stroke-width="1.5"/>
  <polygon points="260,130 248,124 248,136" fill="#bbb"/>
  <polygon points="140,20 134,32 146,32" fill="#bbb"/>
  <text x="262" y="134" font-size="11" fill="#888" font-family="Arial">x</text>
  <text x="133" y="18" font-size="11" fill="#888" font-family="Arial">y</text>
  <!-- Original point A(3,1) → pixel (182,110) and triangle -->
  <polygon points="182,110 222,110 182,70" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="186" y="106" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <!-- Rotated 90° CCW: (3,1)→(-1,3): (-1,3)→pixel(100,70); (5,1)→(-1,5)→(100,50); (3,3)→(-3,3)→(80,70) -->
  <polygon points="100,70 100,110 60,70" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5" stroke-dasharray="5,3"/>
  <text x="55" y="68" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">A'</text>
  <!-- Rotation arc -->
  <path d="M182,110 A55,55 0 0,0 100,75" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <polygon points="100,75 107,82 112,72" fill="#e05c1a"/>
  <text x="138" y="90" font-size="12" fill="#e05c1a" font-family="Arial">90°</text>
  <!-- Center -->
  <circle cx="140" cy="130" r="5" fill="#1a3a5c"/>
  <text x="143" y="148" font-size="11" fill="#1a3a5c" font-family="Arial">O</text>
  <text x="25" y="248" font-size="12" fill="#555" font-family="Arial">90° CCW: (x,y) → (−y, x)</text>
</svg>

</div>
</div>

---

## Dilations

A **dilation** with center $C$ and **scale factor** $k$ maps each point $P$ to $P'$ such that $CP' = k \cdot CP$.

$$D_{C,k}(x, y) = (kx, ky) \quad \text{(if center is origin)}$$

<div class="columns">
<div>

**If $k > 1$:** enlargement
**If $0 < k < 1$:** reduction
**If $k = 1$:** identity

Dilations preserve **shape** (angles) but not **size**.
The image is similar to the preimage: $k$ = scale factor.

> **Example:** Dilate $\triangle ABC$ with $k = 2$, center at origin.
> $A(1, 2) \to A'(2, 4)$
> $B(3, 1) \to B'(6, 2)$
> $C(2, 3) \to C'(4, 6)$

</div>
<div>

<svg width="280" height="260" viewBox="0 0 280 260" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="240" x2="270" y2="240" stroke="#bbb" stroke-width="1.5"/>
  <line x1="20" y1="240" x2="20" y2="20" stroke="#bbb" stroke-width="1.5"/>
  <polygon points="270,240 258,234 258,246" fill="#bbb"/>
  <polygon points="20,20 14,32 26,32" fill="#bbb"/>
  <!-- Center at (20,240) = origin, 1 unit = 35px -->
  <!-- A(1,2)→(55,170), B(3,1)→(125,205), C(2,3)→(90,135) -->
  <polygon points="55,170 125,205 90,135" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="40" y="168" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="128" y="205" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="92" y="130" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <!-- A'(2,4)→(90,100), B'(6,2)→(230,170), C'(4,6)→(160,30) -->
  <polygon points="90,100 230,170 160,30" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5" stroke-dasharray="6,3"/>
  <text x="68" y="98" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">A'</text>
  <text x="233" y="170" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">B'</text>
  <text x="162" y="26" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">C'</text>
  <!-- Lines from origin through corresponding points -->
  <line x1="20" y1="240" x2="90" y2="100" stroke="#ccc" stroke-width="1" stroke-dasharray="4,3"/>
  <line x1="20" y1="240" x2="230" y2="170" stroke="#ccc" stroke-width="1" stroke-dasharray="4,3"/>
  <circle cx="20" cy="240" r="5" fill="#e05c1a"/>
  <text x="24" y="255" font-size="12" fill="#e05c1a" font-family="Arial">O (center)</text>
  <text x="80" y="258" font-size="12" fill="#555" font-family="Arial">k = 2: every coord doubles</text>
</svg>

</div>
</div>

---

## Composition of Transformations

A **composition** applies two or more transformations in sequence.

| Theorem | Statement |
|---------|-----------|
| **9-2** | Reflecting over 2 **parallel** lines = translation by $2d$ |
| **9-3** | Reflecting over 2 **intersecting** lines = rotation by $2\theta$ |

<div class="columns">
<div>

**Glide reflection** — translation followed by a reflection over a line parallel to the translation direction.

**Symmetry types:**
- **Line symmetry** — figure maps onto itself by a reflection
- **Rotational symmetry** — figure maps onto itself by a rotation < 360°
- **Point symmetry** — 180° rotation maps figure onto itself

> **Example:** A regular hexagon has 6 lines of symmetry and rotational symmetry of order 6 (every 60°).

</div>
<div>

<svg width="280" height="230" viewBox="0 0 280 230" xmlns="http://www.w3.org/2000/svg">
  <!-- Two parallel lines -->
  <line x1="80" y1="20" x2="80" y2="210" stroke="#1a3a5c" stroke-width="2" stroke-dasharray="6,3"/>
  <line x1="180" y1="20" x2="180" y2="210" stroke="#1a3a5c" stroke-width="2" stroke-dasharray="6,3"/>
  <text x="67" y="16" font-size="11" fill="#1a3a5c" font-family="Arial">ℓ₁</text>
  <text x="167" y="16" font-size="11" fill="#1a3a5c" font-family="Arial">ℓ₂</text>
  <!-- Original triangle -->
  <polygon points="20,80 60,110 40,50" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <text x="22" y="45" font-size="12" fill="#1a3a5c" font-family="Arial">P</text>
  <!-- Reflected over ℓ₁ -->
  <polygon points="140,80 100,110 120,50" fill="#ddd" stroke="#888" stroke-width="2" stroke-dasharray="4,2"/>
  <text x="132" y="45" font-size="12" fill="#888" font-family="Arial">P'</text>
  <!-- Reflected over ℓ₂ (= translation of P) -->
  <polygon points="220,80 260,110 240,50" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="242" y="45" font-size="12" fill="#e05c1a" font-family="Arial">P''</text>
  <!-- Arrow showing net translation -->
  <line x1="40" y1="170" x2="240" y2="170" stroke="#e05c1a" stroke-width="2"/>
  <polygon points="240,170 230,165 230,175" fill="#e05c1a"/>
  <text x="110" y="190" font-size="12" fill="#e05c1a" font-family="Arial">translation = 2d</text>
  <text x="80" y="218" font-size="11" fill="#555" font-family="Arial">d = distance between ℓ₁ and ℓ₂</text>
</svg>

</div>
</div>

---

## Chapter 9 — Summary

| Transformation | Rule (about origin) | Isometry? |
|---------------|---------------------|-----------|
| Translation $\langle a,b \rangle$ | $(x,y) \to (x+a, y+b)$ | Yes |
| Reflection over $x$-axis | $(x,y) \to (x,-y)$ | Yes |
| Reflection over $y$-axis | $(x,y) \to (-x,y)$ | Yes |
| Reflection over $y=x$ | $(x,y) \to (y,x)$ | Yes |
| Rotation 90° CCW | $(x,y) \to (-y,x)$ | Yes |
| Rotation 180° | $(x,y) \to (-x,-y)$ | Yes |
| Rotation 270° CCW | $(x,y) \to (y,-x)$ | Yes |
| Dilation by $k$ | $(x,y) \to (kx,ky)$ | Only if $k=1$ |

> **Composition rule:** 2 reflections over parallel lines = translation by twice the distance. 2 reflections over intersecting lines = rotation by twice the angle between lines.
