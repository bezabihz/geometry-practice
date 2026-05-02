---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 8 Cheatsheet
# Quadrilaterals

---

<div style="text-align:center;">

<svg width="680" height="300" viewBox="0 0 680 300" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="340" y="18" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Quadrilateral Hierarchy &amp; Properties</text>

  <!-- Quadrilateral (top) -->
  <rect x="270" y="28" width="140" height="36" rx="6" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <text x="340" y="52" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Quadrilateral</text>

  <!-- Arrow to Parallelogram -->
  <line x1="340" y1="64" x2="340" y2="86" stroke="#555" stroke-width="1.5"/>
  <polygon points="340,90 335,82 345,82" fill="#555"/>

  <!-- Parallelogram -->
  <rect x="240" y="90" width="200" height="36" rx="6" fill="#d0e8ff" stroke="#1565C0" stroke-width="2"/>
  <text x="340" y="114" text-anchor="middle" font-size="13" font-weight="bold" fill="#1565C0">Parallelogram</text>

  <!-- Arrows to Rectangle and Rhombus -->
  <line x1="280" y1="126" x2="160" y2="155" stroke="#555" stroke-width="1.5"/>
  <polygon points="158,158 155,149 163,151" fill="#555"/>
  <line x1="400" y1="126" x2="520" y2="155" stroke="#555" stroke-width="1.5"/>
  <polygon points="522,158 517,151 525,149" fill="#555"/>

  <!-- Rectangle -->
  <rect x="70" y="158" width="160" height="36" rx="6" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="2"/>
  <text x="150" y="182" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">Rectangle</text>

  <!-- Rhombus -->
  <rect x="450" y="158" width="160" height="36" rx="6" fill="#ffe0cc" stroke="#e05c1a" stroke-width="2"/>
  <text x="530" y="182" text-anchor="middle" font-size="13" font-weight="bold" fill="#e05c1a">Rhombus</text>

  <!-- Arrows to Square -->
  <line x1="198" y1="194" x2="278" y2="218" stroke="#555" stroke-width="1.5"/>
  <polygon points="280,221 273,215 280,210" fill="#555"/>
  <line x1="462" y1="194" x2="382" y2="218" stroke="#555" stroke-width="1.5"/>
  <polygon points="380,221 380,210 387,215" fill="#555"/>

  <!-- Square -->
  <rect x="270" y="222" width="140" height="36" rx="6" fill="#ffd700" stroke="#cc9900" stroke-width="2"/>
  <text x="340" y="246" text-anchor="middle" font-size="13" font-weight="bold" fill="#7a5800">Square</text>

  <!-- Trapezoid (separate) -->
  <rect x="20" y="28" width="160" height="36" rx="6" fill="#f0e0f8" stroke="#880088" stroke-width="2"/>
  <text x="100" y="52" text-anchor="middle" font-size="13" font-weight="bold" fill="#880088">Trapezoid</text>
  <line x1="100" y1="64" x2="100" y2="86" stroke="#555" stroke-width="1" stroke-dasharray="4,3"/>
  <rect x="20" y="86" width="160" height="36" rx="6" fill="#f8e8f8" stroke="#880088" stroke-width="1.5"/>
  <text x="100" y="110" text-anchor="middle" font-size="12" fill="#880088">Isosceles Trapezoid</text>

  <!-- Kite (separate) -->
  <rect x="500" y="28" width="160" height="36" rx="6" fill="#f0f8e0" stroke="#4a7a00" stroke-width="2"/>
  <text x="580" y="52" text-anchor="middle" font-size="13" font-weight="bold" fill="#4a7a00">Kite</text>

  <!-- Properties at bottom -->
  <rect x="20" y="272" width="640" height="24" rx="4" fill="#e8f0fb"/>
  <text x="340" y="288" text-anchor="middle" font-size="11" fill="#1a3a5c">Square = Rectangle + Rhombus · Opp sides ∥ = Parallelogram · Exactly 1 pair ∥ = Trapezoid</text>
</svg>

</div>

---

<div style="display:flex; gap:20px;">
<div style="flex:1; text-align:center;">

<svg width="280" height="210" viewBox="0 0 280 210" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="140" y="16" text-anchor="middle" font-size="12" font-weight="bold" fill="#1a3a5c">Parallelogram Diagonals</text>

  <!-- Parallelogram -->
  <polygon points="40,170 80,50 240,50 200,170" fill="#d0e8ff" stroke="#1565C0" stroke-width="2"/>
  <text x="28" y="180" font-size="12" font-weight="bold" fill="#1565C0">A</text>
  <text x="75" y="44" font-size="12" font-weight="bold" fill="#1565C0">B</text>
  <text x="242" y="44" font-size="12" font-weight="bold" fill="#1565C0">C</text>
  <text x="200" y="184" font-size="12" font-weight="bold" fill="#1565C0">D</text>

  <!-- Diagonals -->
  <line x1="80" y1="50" x2="200" y2="170" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
  <line x1="40" y1="170" x2="240" y2="50" stroke="#2a7a2a" stroke-width="2" stroke-dasharray="5,3"/>

  <!-- Midpoint E -->
  <circle cx="140" cy="110" r="5" fill="#cc3300"/>
  <text x="146" y="107" font-size="11" font-weight="bold" fill="#cc3300">E</text>

  <!-- Equal segment ticks -->
  <line x1="107" y1="79" x2="113" y2="85" stroke="#2a7a2a" stroke-width="2"/>
  <line x1="167" y1="135" x2="173" y2="141" stroke="#2a7a2a" stroke-width="2"/>
  <line x1="107" y1="135" x2="113" y2="129" stroke="#e05c1a" stroke-width="2"/>
  <line x1="167" y1="81" x2="173" y2="87" stroke="#e05c1a" stroke-width="2"/>

  <text x="140" y="200" text-anchor="middle" font-size="11" fill="#1a3a5c">AE=CE &amp; BE=DE (bisect)</text>
</svg>

</div>
<div style="flex:1.2;">

## Properties Table

| Property | ▱ | Rect | Rhom | Sq |
|----------|:---:|:---:|:---:|:---:|
| Opp sides ∥ | ✓ | ✓ | ✓ | ✓ |
| Opp sides ≅ | ✓ | ✓ | ✓ | ✓ |
| Opp ∠s ≅ | ✓ | ✓ | ✓ | ✓ |
| Diag. bisect | ✓ | ✓ | ✓ | ✓ |
| All ∠s = 90° | — | ✓ | — | ✓ |
| All sides ≅ | — | — | ✓ | ✓ |
| Diag. ≅ | — | ✓ | — | ✓ |
| Diag. ⊥ | — | — | ✓ | ✓ |
| Diag. bisect ∠s | — | — | ✓ | ✓ |

## Trapezoid Midsegment
$$MN = \frac{b_1 + b_2}{2}$$

</div>
</div>
