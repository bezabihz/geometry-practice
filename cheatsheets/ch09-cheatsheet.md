---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 9 Cheatsheet
# Transformations

---

<div style="text-align:center;">

<svg width="680" height="280" viewBox="0 0 680 280" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <defs>
    <marker id="arr" markerWidth="8" markerHeight="6" refX="8" refY="3" orient="auto">
      <polygon points="0 0, 8 3, 0 6" fill="#e05c1a"/>
    </marker>
  </defs>
  <text x="340" y="18" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Four Types of Transformations</text>

  <!-- TRANSLATION -->
  <g transform="translate(10,30)">
    <rect x="0" y="0" width="155" height="230" rx="6" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
    <text x="78" y="20" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Translation</text>
    <!-- Preimage triangle -->
    <polygon points="20,90 60,90 40,50" fill="none" stroke="#1a3a5c" stroke-width="2"/>
    <text x="15" y="100" font-size="10" fill="#1a3a5c">A</text>
    <text x="61" y="100" font-size="10" fill="#1a3a5c">B</text>
    <text x="39" y="45" font-size="10" fill="#1a3a5c">C</text>
    <!-- Arrow -->
    <line x1="75" y1="72" x2="95" y2="72" stroke="#e05c1a" stroke-width="2" marker-end="url(#arr)"/>
    <!-- Image triangle -->
    <polygon points="100,90 140,90 120,50" fill="none" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
    <text x="95" y="100" font-size="10" fill="#e05c1a">A'</text>
    <text x="141" y="100" font-size="10" fill="#e05c1a">B'</text>
    <text x="119" y="45" font-size="10" fill="#e05c1a">C'</text>
    <!-- Rule -->
    <text x="78" y="120" text-anchor="middle" font-size="11" fill="#333">$(x,y)→(x+a,y+b)$</text>
    <text x="78" y="138" text-anchor="middle" font-size="11" fill="#333">Isometry ✓</text>
    <text x="78" y="154" text-anchor="middle" font-size="11" fill="#333">Preserves:</text>
    <text x="78" y="168" text-anchor="middle" font-size="10" fill="#555">size, shape,</text>
    <text x="78" y="180" text-anchor="middle" font-size="10" fill="#555">orientation</text>
  </g>

  <!-- REFLECTION -->
  <g transform="translate(175,30)">
    <rect x="0" y="0" width="155" height="230" rx="6" fill="#f0ffe0" stroke="#2a7a2a" stroke-width="1.5"/>
    <text x="78" y="20" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">Reflection</text>
    <!-- Line of reflection (y-axis style) -->
    <line x1="78" y1="32" x2="78" y2="115" stroke="#2a7a2a" stroke-width="2" stroke-dasharray="4,2"/>
    <!-- Preimage -->
    <polygon points="20,100 60,100 50,55" fill="none" stroke="#1a3a5c" stroke-width="2"/>
    <!-- Image (mirrored) -->
    <polygon points="136,100 96,100 106,55" fill="none" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
    <text x="78" y="120" text-anchor="middle" font-size="10" fill="#2a7a2a">← mirror line →</text>
    <text x="78" y="138" text-anchor="middle" font-size="11" fill="#333">Isometry ✓</text>
    <text x="78" y="154" text-anchor="middle" font-size="10" fill="#555">y-axis: (x,y)→(−x,y)</text>
    <text x="78" y="168" text-anchor="middle" font-size="10" fill="#555">x-axis: (x,y)→(x,−y)</text>
    <text x="78" y="182" text-anchor="middle" font-size="10" fill="#555">y=x: (x,y)→(y,x)</text>
  </g>

  <!-- ROTATION -->
  <g transform="translate(340,30)">
    <rect x="0" y="0" width="155" height="230" rx="6" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
    <text x="78" y="20" text-anchor="middle" font-size="13" font-weight="bold" fill="#e05c1a">Rotation</text>
    <!-- Center of rotation -->
    <circle cx="78" cy="80" r="4" fill="#e05c1a"/>
    <text x="84" y="78" font-size="10" fill="#e05c1a">O</text>
    <!-- Preimage -->
    <polygon points="90,80 120,60 115,90" fill="none" stroke="#1a3a5c" stroke-width="2"/>
    <!-- Arc showing rotation -->
    <path d="M 118,63 A 42,42 0 0 0 80,38" stroke="#e05c1a" fill="none" stroke-width="1.5" stroke-dasharray="4,2"/>
    <!-- Image (rotated) -->
    <polygon points="78,38 56,66 86,68" fill="none" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
    <text x="78" y="120" text-anchor="middle" font-size="11" fill="#333">Isometry ✓</text>
    <text x="78" y="136" text-anchor="middle" font-size="10" fill="#555">90° CCW: (x,y)→(−y,x)</text>
    <text x="78" y="150" text-anchor="middle" font-size="10" fill="#555">180°: (x,y)→(−x,−y)</text>
    <text x="78" y="164" text-anchor="middle" font-size="10" fill="#555">270° CCW: (x,y)→(y,−x)</text>
  </g>

  <!-- DILATION -->
  <g transform="translate(505,30)">
    <rect x="0" y="0" width="165" height="230" rx="6" fill="#fdecea" stroke="#cc2200" stroke-width="1.5"/>
    <text x="83" y="20" text-anchor="middle" font-size="13" font-weight="bold" fill="#cc2200">Dilation</text>
    <!-- Center of dilation -->
    <circle cx="28" cy="100" r="4" fill="#cc2200"/>
    <text x="14" y="98" font-size="10" fill="#cc2200">C</text>
    <!-- Preimage (small triangle) -->
    <polygon points="60,90 80,90 70,70" fill="none" stroke="#1a3a5c" stroke-width="2"/>
    <text x="70" y="65" font-size="9" fill="#1a3a5c">△</text>
    <!-- Image (large triangle) -->
    <polygon points="105,110 145,110 125,70" fill="none" stroke="#cc2200" stroke-width="2" stroke-dasharray="5,3"/>
    <text x="125" y="65" font-size="9" fill="#cc2200">△'</text>
    <!-- Lines from center -->
    <line x1="28" y1="100" x2="145" y2="110" stroke="#cc2200" stroke-width="1" stroke-dasharray="3,3" opacity="0.6"/>
    <line x1="28" y1="100" x2="125" y2="70" stroke="#cc2200" stroke-width="1" stroke-dasharray="3,3" opacity="0.6"/>
    <text x="83" y="130" text-anchor="middle" font-size="11" fill="#333">NOT isometry</text>
    <text x="83" y="146" text-anchor="middle" font-size="10" fill="#555">(x,y)→(kx, ky)</text>
    <text x="83" y="162" text-anchor="middle" font-size="10" fill="#555">k&gt;1: enlarge</text>
    <text x="83" y="176" text-anchor="middle" font-size="10" fill="#555">0&lt;k&lt;1: reduce</text>
  </g>
</svg>

</div>

---

## Composition Theorems & Key Rules

<div style="display:flex; gap:24px;">
<div style="flex:1;">

| Transformation Rule | Coordinate Change |
|--------------------|------------------|
| Translate $\langle a,b \rangle$ | $(x+a,\ y+b)$ |
| Reflect over $x$-axis | $(x,\ -y)$ |
| Reflect over $y$-axis | $(-x,\ y)$ |
| Reflect over $y = x$ | $(y,\ x)$ |
| Rotate 90° CCW | $(-y,\ x)$ |
| Rotate 180° | $(-x,\ -y)$ |
| Rotate 270° CCW | $(y,\ -x)$ |
| Dilate by $k$ (origin) | $(kx,\ ky)$ |

</div>
<div style="flex:1;">

## Composition Theorems

> **2 parallel lines** → Translation  
> Distance $= 2 \times d(\ell_1, \ell_2)$

> **2 intersecting lines** → Rotation  
> Angle $= 2 \times \theta$

## Symmetry
- **Line symmetry:** reflection onto itself
- **Rotational:** maps to itself at angle $< 360°$
- **Order $n$:** $n$ rotational positions

**Regular hexagon:** 6 lines of sym., order 6 (every 60°)

</div>
</div>
