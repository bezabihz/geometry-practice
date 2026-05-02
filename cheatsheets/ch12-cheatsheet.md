---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 12 Cheatsheet
# Surface Area

---

<div style="text-align:center;">

<svg width="680" height="270" viewBox="0 0 680 270" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="340" y="18" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Surface Area — All Solids</text>

  <!-- PRISM -->
  <g transform="translate(10,35)">
    <rect x="0" y="0" width="118" height="220" rx="6" fill="#d0e8ff" stroke="#1565C0" stroke-width="1.5"/>
    <text x="59" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#1565C0">Prism</text>
    <!-- 3D box drawing -->
    <rect x="14" y="26" width="60" height="50" fill="#e8f4ff" stroke="#1565C0" stroke-width="1.5"/>
    <polygon points="14,26 26,16 86,16 74,26" fill="#c0d8f0" stroke="#1565C0" stroke-width="1.5"/>
    <polygon points="74,26 86,16 86,66 74,76" fill="#b0ccec" stroke="#1565C0" stroke-width="1.5"/>
    <!-- dimension labels -->
    <text x="44" y="55" text-anchor="middle" font-size="10" fill="#1565C0">l</text>
    <text x="6" y="54" font-size="10" fill="#1565C0">w</text>
    <text x="81" y="50" font-size="10" fill="#1565C0">h</text>
    <!-- Formulas -->
    <text x="59" y="104" text-anchor="middle" font-size="11" font-weight="bold" fill="#1565C0">LA = Ph</text>
    <text x="59" y="120" text-anchor="middle" font-size="11" fill="#1565C0">SA = Ph + 2B</text>
    <text x="59" y="140" text-anchor="middle" font-size="10" fill="#555">P = perimeter of base</text>
    <text x="59" y="155" text-anchor="middle" font-size="10" fill="#555">B = area of base</text>
    <text x="59" y="170" text-anchor="middle" font-size="10" fill="#555">h = height</text>
    <rect x="10" y="182" width="98" height="30" rx="3" fill="#f0f8ff" stroke="#1565C0" stroke-width="1"/>
    <text x="59" y="197" text-anchor="middle" font-size="10" fill="#1565C0">Box: SA=2(lw+lh+wh)</text>
  </g>

  <!-- CYLINDER -->
  <g transform="translate(140,35)">
    <rect x="0" y="0" width="118" height="220" rx="6" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="1.5"/>
    <text x="59" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#2a7a2a">Cylinder</text>
    <!-- Cylinder drawing -->
    <ellipse cx="59" cy="46" rx="38" ry="12" fill="#b0e0b0" stroke="#2a7a2a" stroke-width="1.5"/>
    <rect x="21" y="46" width="76" height="50" fill="#c8ecc8" stroke="#2a7a2a" stroke-width="1.5"/>
    <ellipse cx="59" cy="96" rx="38" ry="12" fill="#a0d8a0" stroke="#2a7a2a" stroke-width="1.5"/>
    <text x="62" y="72" font-size="10" fill="#2a7a2a">h</text>
    <text x="59" y="40" text-anchor="middle" font-size="10" fill="#2a7a2a">r</text>
    <line x1="59" y1="34" x2="97" y2="34" stroke="#2a7a2a" stroke-width="1" stroke-dasharray="3,2"/>
    <!-- Formulas -->
    <text x="59" y="124" text-anchor="middle" font-size="11" font-weight="bold" fill="#2a7a2a">LA = 2πrh</text>
    <text x="59" y="140" text-anchor="middle" font-size="11" fill="#2a7a2a">SA = 2πrh + 2πr²</text>
    <rect x="10" y="182" width="98" height="30" rx="3" fill="#f0fff0" stroke="#2a7a2a" stroke-width="1"/>
    <text x="59" y="197" text-anchor="middle" font-size="10" fill="#2a7a2a">C = 2πr (circumference)</text>
  </g>

  <!-- PYRAMID -->
  <g transform="translate(270,35)">
    <rect x="0" y="0" width="118" height="220" rx="6" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
    <text x="59" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#e05c1a">Pyramid</text>
    <!-- Pyramid drawing -->
    <polygon points="59,24 14,96 104,96" fill="#ffe0b0" stroke="#e05c1a" stroke-width="1.5"/>
    <polygon points="104,96 59,24 104,60" fill="#ffd090" stroke="#e05c1a" stroke-width="1.5" opacity="0.6"/>
    <line x1="59" y1="24" x2="59" y2="96" stroke="#555" stroke-width="1.2" stroke-dasharray="3,2"/>
    <text x="63" y="63" font-size="10" fill="#555">ℓ</text>
    <text x="45" y="108" font-size="10" fill="#e05c1a">B</text>
    <!-- Formulas -->
    <text x="59" y="128" text-anchor="middle" font-size="11" font-weight="bold" fill="#e05c1a">LA = ½Pℓ</text>
    <text x="59" y="144" text-anchor="middle" font-size="11" fill="#e05c1a">SA = ½Pℓ + B</text>
    <text x="59" y="164" text-anchor="middle" font-size="10" fill="#555">ℓ = slant height</text>
    <text x="59" y="178" text-anchor="middle" font-size="10" fill="#555">P = base perimeter</text>
  </g>

  <!-- CONE -->
  <g transform="translate(400,35)">
    <rect x="0" y="0" width="118" height="220" rx="6" fill="#fdecea" stroke="#cc2200" stroke-width="1.5"/>
    <text x="59" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#cc2200">Cone</text>
    <!-- Cone drawing -->
    <polygon points="59,24 14,96 104,96" fill="#ffcccc" stroke="#cc2200" stroke-width="1.5"/>
    <ellipse cx="59" cy="96" rx="45" ry="12" fill="#ff9999" stroke="#cc2200" stroke-width="1.5"/>
    <line x1="59" y1="24" x2="104" y2="96" stroke="#555" stroke-width="1.2"/>
    <text x="90" y="63" font-size="10" fill="#555">ℓ</text>
    <line x1="59" y1="24" x2="59" y2="96" stroke="#555" stroke-width="1.2" stroke-dasharray="3,2"/>
    <text x="63" y="65" font-size="10" fill="#555">h</text>
    <line x1="59" y1="96" x2="104" y2="96" stroke="#555" stroke-width="1.2" stroke-dasharray="3,2"/>
    <text x="80" y="108" font-size="10" fill="#555">r</text>
    <!-- Formulas -->
    <text x="59" y="128" text-anchor="middle" font-size="11" font-weight="bold" fill="#cc2200">LA = πrℓ</text>
    <text x="59" y="144" text-anchor="middle" font-size="11" fill="#cc2200">SA = πrℓ + πr²</text>
    <text x="59" y="164" text-anchor="middle" font-size="10" fill="#555">ℓ = √(r²+h²)</text>
    <rect x="10" y="182" width="98" height="30" rx="3" fill="#fff0ee" stroke="#cc2200" stroke-width="1"/>
    <text x="59" y="197" text-anchor="middle" font-size="10" fill="#cc2200">slant: ℓ² = r² + h²</text>
  </g>

  <!-- SPHERE -->
  <g transform="translate(530,35)">
    <rect x="0" y="0" width="138" height="220" rx="6" fill="#f0e0f8" stroke="#880088" stroke-width="1.5"/>
    <text x="69" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#880088">Sphere</text>
    <!-- Sphere drawing -->
    <circle cx="69" cy="72" r="46" fill="#e0c0f0" stroke="#880088" stroke-width="1.5"/>
    <ellipse cx="69" cy="72" rx="46" ry="14" fill="none" stroke="#880088" stroke-width="1" stroke-dasharray="4,2"/>
    <line x1="69" y1="72" x2="115" y2="72" stroke="#555" stroke-width="1.2" stroke-dasharray="3,2"/>
    <text x="91" y="68" font-size="11" fill="#555" font-weight="bold">r</text>
    <!-- Formulas -->
    <text x="69" y="140" text-anchor="middle" font-size="11" font-weight="bold" fill="#880088">SA = 4πr²</text>
    <text x="69" y="160" text-anchor="middle" font-size="10" fill="#555">(no lateral area)</text>
    <rect x="10" y="182" width="118" height="30" rx="3" fill="#f8f0fc" stroke="#880088" stroke-width="1"/>
    <text x="69" y="197" text-anchor="middle" font-size="10" fill="#880088">Vol = (4/3)πr³</text>
  </g>
</svg>

</div>

---

## Euler's Formula & Cross Sections

<div style="display:flex; gap:24px;">
<div style="flex:1;">

$$F + V - E = 2$$

| Solid | F | V | E | Check |
|-------|---|---|---|-------|
| Cube | 6 | 8 | 12 | ✓ |
| Triangular prism | 5 | 6 | 9 | ✓ |
| Square pyramid | 5 | 5 | 8 | ✓ |
| Tetrahedron | 4 | 4 | 6 | ✓ |

</div>
<div style="flex:1;">

## Quick Reference

| Solid | SA Formula |
|-------|-----------|
| Rectangular prism | $2(lw + lh + wh)$ |
| Cylinder | $2\pi rh + 2\pi r^2$ |
| Regular pyramid | $\frac{1}{2}P\ell + B$ |
| Cone | $\pi r\ell + \pi r^2$ |
| Sphere | $4\pi r^2$ |

**Slant height:** $\ell = \sqrt{r^2 + h^2}$

</div>
</div>
