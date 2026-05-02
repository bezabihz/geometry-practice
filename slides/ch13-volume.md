---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 13
## Volume

McGraw Hill Glencoe Geometry · Texas Edition

---

## Volume Formulas — Overview

| Solid | Formula | Key idea |
|-------|---------|---------|
| Prism | $V = Bh$ | Base area × height |
| Cylinder | $V = \pi r^2 h$ | Circle area × height |
| Pyramid | $V = \frac{1}{3}Bh$ | $\frac{1}{3}$ × prism |
| Cone | $V = \frac{1}{3}\pi r^2 h$ | $\frac{1}{3}$ × cylinder |
| Sphere | $V = \frac{4}{3}\pi r^3$ | Unique formula |

**Cavalieri's Principle:** If two solids have the same height and equal cross-sectional areas at every level, they have the same volume.

<svg width="700" height="130" viewBox="0 0 700 130" xmlns="http://www.w3.org/2000/svg">
  <!-- 5 3D solids side by side (simplified) -->
  <!-- Rectangular prism -->
  <polygon points="40,90 140,90 160,60 60,60" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="40,90 40,30 60,0 60,60" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="40,30 140,30 160,0 60,0" fill="#b5cee8" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="140" y1="30" x2="140" y2="90" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="140" y1="30" x2="160" y2="0" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="140" y1="90" x2="160" y2="60" stroke="#1a3a5c" stroke-width="2"/>
  <text x="90" y="115" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle">Prism V=Bh</text>
  <!-- Cylinder -->
  <ellipse cx="250" cy="85" rx="45" ry="14" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="205" y1="85" x2="205" y2="25" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="295" y1="85" x2="295" y2="25" stroke="#1a3a5c" stroke-width="2"/>
  <ellipse cx="250" cy="25" rx="45" ry="14" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <text x="250" y="115" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle">Cyl V=πr²h</text>
  <!-- Pyramid -->
  <polygon points="360,90 460,90 480,60 340,60" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="360,90 340,60 410,5 410,5" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="460,90 480,60 410,5" fill="#b5cee8" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="360,90 460,90 410,5" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <text x="410" y="115" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle">Pyr V=⅓Bh</text>
  <!-- Cone -->
  <ellipse cx="560" cy="85" rx="40" ry="12" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="520" y1="85" x2="560" y2="10" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="600" y1="85" x2="560" y2="10" stroke="#1a3a5c" stroke-width="2"/>
  <text x="560" y="115" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle">Cone V=⅓πr²h</text>
  <!-- Sphere -->
  <circle cx="660" cy="55" r="45" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <ellipse cx="660" cy="55" rx="45" ry="12" fill="none" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <text x="660" y="115" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle">Sphere V=⁴⁄₃πr³</text>
</svg>

---

## Prisms & Cylinders

<div class="columns">
<div>

**Theorem 13-1 (Prism):**
$$V = Bh$$

where $B$ = area of the base, $h$ = height.

For a **rectangular prism**: $V = lwh$

> **Example:** $l = 8$, $w = 5$, $h = 3$
> $V = 8 \times 5 \times 3 = \mathbf{120}$

---

**Theorem 13-2 (Cylinder):**
$$V = \pi r^2 h$$

> **Example:** $r = 4$, $h = 9$
> $V = \pi(16)(9) = \mathbf{144\pi} \approx 452.4$

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangular prism -->
  <polygon points="20,130 130,130 150,100 40,100" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="20,130 20,50 40,20 40,100" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="20,50 130,50 150,20 40,20" fill="#b5cee8" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="130" y1="50" x2="130" y2="130" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="130" y1="50" x2="150" y2="20" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="130" y1="130" x2="150" y2="100" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Dimension labels -->
  <text x="68" y="145" font-size="13" fill="#e05c1a" font-family="Arial">l=8</text>
  <text x="2" y="94" font-size="13" fill="#e05c1a" font-family="Arial">h=3</text>
  <text x="152" y="118" font-size="13" fill="#e05c1a" font-family="Arial">w=5</text>
  <text x="30" y="165" font-size="13" fill="#555" font-family="Arial">V = 8×5×3 = 120</text>

  <!-- Cylinder -->
  <ellipse cx="215" cy="245" rx="60" ry="18" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="155" y1="245" x2="155" y2="185" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="275" y1="245" x2="275" y2="185" stroke="#1a3a5c" stroke-width="2.5"/>
  <ellipse cx="215" cy="185" rx="60" ry="18" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="215" y1="185" x2="275" y2="185" stroke="#e05c1a" stroke-width="2"/>
  <text x="238" y="179" font-size="12" fill="#e05c1a" font-family="Arial">r=4</text>
  <line x1="280" y1="185" x2="280" y2="245" stroke="#e05c1a" stroke-width="2"/>
  <text x="283" y="218" font-size="12" fill="#e05c1a" font-family="Arial">h=9</text>
</svg>

</div>
</div>

---

## Pyramids & Cones

<div class="columns">
<div>

**Theorem 13-3 (Pyramid):**
$$V = \frac{1}{3}Bh$$

> **Why ⅓?** Three congruent pyramids fit exactly inside one prism of the same base and height (Cavalieri's principle demonstrates this).

> **Example:** Square pyramid, base $6 \times 6$, $h = 10$
> $B = 36,\quad V = \frac{1}{3}(36)(10) = \mathbf{120}$

---

**Theorem 13-4 (Cone):**
$$V = \frac{1}{3}\pi r^2 h$$

> **Example:** $r = 3$, $h = 7$
> $V = \frac{1}{3}\pi(9)(7) = 21\pi \approx \mathbf{66.0}$

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Pyramid -->
  <polygon points="20,210 140,210 170,180 50,180" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="20,210 50,180 90,50" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="140,210 170,180 90,50" fill="#b5cee8" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="20,210 140,210 90,50" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <!-- Height dashed -->
  <line x1="90" y1="50" x2="90" y2="195" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
  <text x="93" y="130" font-size="13" fill="#e05c1a" font-family="Arial">h=10</text>
  <text x="65" y="228" font-size="13" fill="#555" font-family="Arial">V=⅓(36)(10)=120</text>

  <!-- Cone -->
  <ellipse cx="220" cy="220" rx="50" ry="15" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="170" y1="220" x2="220" y2="100" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="270" y1="220" x2="220" y2="100" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Height dashed -->
  <line x1="220" y1="100" x2="220" y2="220" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
  <line x1="220" y1="220" x2="270" y2="220" stroke="#e05c1a" stroke-width="2"/>
  <text x="243" y="218" font-size="12" fill="#e05c1a" font-family="Arial">r=3</text>
  <text x="224" y="165" font-size="12" fill="#e05c1a" font-family="Arial">h=7</text>
  <text x="165" y="250" font-size="12" fill="#555" font-family="Arial">V=⅓π(9)(7)=21π</text>
</svg>

</div>
</div>

---

## Sphere Volume

<div class="columns">
<div>

**Theorem 13-5 (Sphere):**
$$V = \frac{4}{3}\pi r^3$$

> **Where does this come from?** Archimedes showed that a sphere + cone fits exactly inside a cylinder, where sphere volume = cylinder − cone.

**Hemisphere volume:**
$$V_{\text{hemi}} = \frac{2}{3}\pi r^3$$

> **Example:** $r = 6$
> $V = \frac{4}{3}\pi(216) = 288\pi \approx \mathbf{904.8}$

> **Comparison (same $r$):**
> $V_{\text{cone}} : V_{\text{sphere}} : V_{\text{cyl}} = 1 : 2 : 3$

This beautiful ratio (1:2:3) was inscribed on Archimedes' tombstone.

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Sphere -->
  <circle cx="145" cy="130" r="100" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Equator (great circle) -->
  <ellipse cx="145" cy="130" rx="100" ry="28" fill="none" stroke="#e05c1a" stroke-width="2" stroke-dasharray="6,3"/>
  <!-- Radius -->
  <line x1="145" y1="130" x2="245" y2="130" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="188" y="122" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">r = 6</text>
  <!-- Center -->
  <circle cx="145" cy="130" r="5" fill="#1a3a5c"/>
  <text x="150" y="148" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">O</text>
  <!-- Hemisphere divider -->
  <line x1="45" y1="130" x2="245" y2="130" stroke="#1a3a5c" stroke-width="1.5" stroke-dasharray="4,3"/>
  <!-- Label halves -->
  <text x="90" y="100" font-size="13" fill="#1a3a5c" font-family="Arial">Upper</text>
  <text x="90" y="165" font-size="13" fill="#1a3a5c" font-family="Arial">Lower</text>
  <!-- Volume label -->
  <rect x="20" y="240" width="250" height="25" rx="6" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="145" y="257" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold" text-anchor="middle">V = 4/3 π r³ = 288π ≈ 904.8</text>
</svg>

</div>
</div>

---

## Similar Solids & Scale Factor

<div class="columns">
<div>

If two solids are similar with scale factor $k$:

| Measurement | Ratio |
|-------------|-------|
| Linear (lengths, radii) | $k$ |
| Surface area | $k^2$ |
| Volume | $k^3$ |

> **Example:** Two similar cylinders. Smaller has $r = 3$, $h = 5$. Larger has $r = 6$, $h = 10$.
>
> Scale factor: $k = \frac{6}{3} = 2$
>
> $\frac{SA_{\text{large}}}{SA_{\text{small}}} = k^2 = 4$
>
> $\frac{V_{\text{large}}}{V_{\text{small}}} = k^3 = 8$
>
> If $V_{\text{small}} = 45\pi$, then $V_{\text{large}} = 8 \times 45\pi = 360\pi$.

</div>
<div>

<svg width="280" height="240" viewBox="0 0 280 240" xmlns="http://www.w3.org/2000/svg">
  <!-- Small cylinder -->
  <ellipse cx="70" cy="170" rx="35" ry="11" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="35" y1="170" x2="35" y2="110" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="105" y1="170" x2="105" y2="110" stroke="#1a3a5c" stroke-width="2"/>
  <ellipse cx="70" cy="110" rx="35" ry="11" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <text x="55" y="196" font-size="12" fill="#1a3a5c" font-family="Arial">r=3,h=5</text>
  <!-- Large cylinder -->
  <ellipse cx="210" cy="210" rx="60" ry="18" fill="#c8ddf0" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="150" y1="210" x2="150" y2="90" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="270" y1="210" x2="270" y2="90" stroke="#e05c1a" stroke-width="2.5"/>
  <ellipse cx="210" cy="90" rx="60" ry="18" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="175" y="238" font-size="12" fill="#e05c1a" font-family="Arial">r=6,h=10</text>
  <!-- Scale factor label -->
  <rect x="90" y="15" width="100" height="45" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="140" y="33" font-size="13" fill="#1a3a5c" font-family="Arial" text-anchor="middle" font-weight="bold">k = 2</text>
  <text x="140" y="52" font-size="12" fill="#555" font-family="Arial" text-anchor="middle">V ratio = k³= 8</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example — Composite Solid

**A grain silo = cylinder (r=5, h=12) + cone on top (r=5, h=4). Find total volume.**

<div class="columns">
<div>

**Volume of cylinder:**
$$V_{\text{cyl}} = \pi r^2 h = \pi(25)(12) = 300\pi$$

**Volume of cone:**
$$V_{\text{cone}} = \frac{1}{3}\pi r^2 h = \frac{1}{3}\pi(25)(4) = \frac{100\pi}{3}$$

**Total:**
$$V = 300\pi + \frac{100\pi}{3} = \frac{900\pi + 100\pi}{3} = \frac{1000\pi}{3} \approx \mathbf{1047.2}$$

</div>
<div>

<svg width="230" height="250" viewBox="0 0 230 250" xmlns="http://www.w3.org/2000/svg">
  <!-- Cylinder -->
  <ellipse cx="115" cy="225" rx="65" ry="18" fill="#c8ddf0" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="50" y1="225" x2="50" y2="105" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="180" y1="225" x2="180" y2="105" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Cylinder top ellipse -->
  <ellipse cx="115" cy="105" rx="65" ry="18" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Cone on top -->
  <line x1="50" y1="105" x2="115" y2="30" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="180" y1="105" x2="115" y2="30" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Dimension labels -->
  <line x1="190" y1="105" x2="190" y2="225" stroke="#e05c1a" stroke-width="2"/>
  <text x="194" y="172" font-size="12" fill="#e05c1a" font-family="Arial">h=12</text>
  <line x1="195" y1="30" x2="195" y2="105" stroke="#e05c1a" stroke-width="2"/>
  <text x="198" y="72" font-size="12" fill="#e05c1a" font-family="Arial">h=4</text>
  <line x1="115" y1="225" x2="180" y2="225" stroke="#555" stroke-width="1.5"/>
  <text x="138" y="222" font-size="12" fill="#555" font-family="Arial">r=5</text>
  <text x="20" y="20" font-size="12" fill="#555" font-family="Arial">V = 300π + 100π/3 = 1000π/3</text>
</svg>

</div>
</div>

---

## Chapter 13 — Summary

| Solid | Volume |
|-------|--------|
| Prism / Cylinder | $V = Bh$ |
| Pyramid / Cone | $V = \frac{1}{3}Bh$ |
| Sphere | $V = \frac{4}{3}\pi r^3$ |
| Hemisphere | $V = \frac{2}{3}\pi r^3$ |

**Similar solids with scale factor $k$:** areas scale by $k^2$, volumes by $k^3$.

**Ratio (same $r$ and $h$):** $V_{\text{cone}} : V_{\text{sphere}} : V_{\text{cylinder}} = 1 : 2 : 3$

> **Key insight:** Every volume formula is $V = Bh$ or $V = \frac{1}{3}Bh$. The $\frac{1}{3}$ appears for any solid that tapers to a point — pyramid or cone — because their cross-sections shrink as you move away from the base, whereas prisms and cylinders have constant cross-sections.
