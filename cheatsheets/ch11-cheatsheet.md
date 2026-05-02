---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 11 Cheatsheet
# Areas of Polygons & Circles

---

<div style="text-align:center;">

<svg width="680" height="260" viewBox="0 0 680 260" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="340" y="18" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Area Formulas — Visual Reference</text>

  <!-- Rectangle -->
  <g transform="translate(10,30)">
    <rect x="0" y="0" width="100" height="70" fill="#d0e8ff" stroke="#1565C0" stroke-width="2"/>
    <text x="50" y="95" text-anchor="middle" font-size="12" font-weight="bold" fill="#1565C0">Rectangle</text>
    <text x="50" y="110" text-anchor="middle" font-size="12" fill="#1565C0">A = lw</text>
    <!-- dimension labels -->
    <text x="50" y="-4" text-anchor="middle" font-size="11" fill="#555">l</text>
    <text x="-8" y="38" font-size="11" fill="#555">w</text>
  </g>

  <!-- Parallelogram -->
  <g transform="translate(130,30)">
    <polygon points="15,70 115,70 100,0 0,0" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="2"/>
    <text x="58" y="95" text-anchor="middle" font-size="12" font-weight="bold" fill="#2a7a2a">Parallelogram</text>
    <text x="58" y="110" text-anchor="middle" font-size="12" fill="#2a7a2a">A = bh</text>
    <!-- height line -->
    <line x1="100" y1="0" x2="100" y2="70" stroke="#555" stroke-width="1.5" stroke-dasharray="3,2"/>
    <rect x="94" y="62" width="8" height="8" fill="none" stroke="#555" stroke-width="1.2"/>
    <text x="112" y="38" font-size="10" fill="#555">h</text>
    <text x="55" y="84" text-anchor="middle" font-size="10" fill="#555">b</text>
  </g>

  <!-- Triangle -->
  <g transform="translate(258,30)">
    <polygon points="55,0 0,70 110,70" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
    <text x="55" y="95" text-anchor="middle" font-size="12" font-weight="bold" fill="#e05c1a">Triangle</text>
    <text x="55" y="110" text-anchor="middle" font-size="12" fill="#e05c1a">A = ½bh</text>
    <!-- height -->
    <line x1="55" y1="0" x2="55" y2="70" stroke="#555" stroke-width="1.5" stroke-dasharray="3,2"/>
    <rect x="49" y="62" width="8" height="8" fill="none" stroke="#555" stroke-width="1.2"/>
    <text x="60" y="38" font-size="10" fill="#555">h</text>
    <text x="55" y="84" text-anchor="middle" font-size="10" fill="#555">b</text>
  </g>

  <!-- Trapezoid -->
  <g transform="translate(386,30)">
    <polygon points="20,0 90,0 110,70 0,70" fill="#fdecea" stroke="#cc2200" stroke-width="2"/>
    <text x="55" y="95" text-anchor="middle" font-size="12" font-weight="bold" fill="#cc2200">Trapezoid</text>
    <text x="55" y="110" text-anchor="middle" font-size="12" fill="#cc2200">A = ½h(b₁+b₂)</text>
    <text x="55" y="-4" text-anchor="middle" font-size="10" fill="#555">b₁</text>
    <text x="55" y="82" text-anchor="middle" font-size="10" fill="#555">b₂</text>
    <line x1="110" y1="0" x2="110" y2="70" stroke="#555" stroke-width="1.5" stroke-dasharray="3,2"/>
    <text x="116" y="38" font-size="10" fill="#555">h</text>
  </g>

  <!-- Rhombus/Kite -->
  <g transform="translate(520,10)">
    <polygon points="60,0 120,50 60,110 0,50" fill="#f0e0f8" stroke="#880088" stroke-width="2"/>
    <text x="60" y="130" text-anchor="middle" font-size="12" font-weight="bold" fill="#880088">Rhombus/Kite</text>
    <text x="60" y="145" text-anchor="middle" font-size="12" fill="#880088">A = ½d₁d₂</text>
    <!-- diagonals -->
    <line x1="0" y1="50" x2="120" y2="50" stroke="#555" stroke-width="1.5" stroke-dasharray="3,2"/>
    <line x1="60" y1="0" x2="60" y2="110" stroke="#555" stroke-width="1.5" stroke-dasharray="3,2"/>
    <text x="132" y="54" font-size="10" fill="#555">d₁</text>
    <text x="63" y="8" font-size="10" fill="#555">d₂</text>
  </g>
</svg>

</div>

---

<div style="display:flex; gap:24px;">
<div style="flex:1; text-align:center;">

<svg width="280" height="220" viewBox="0 0 280 220" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="140" y="16" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Circle: Area &amp; Sector</text>

  <!-- Full circle -->
  <circle cx="140" cy="110" r="85" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="140" cy="110" r="3" fill="#1a3a5c"/>

  <!-- Sector shaded -->
  <path d="M 140,110 L 225,110 A 85,85 0 0 1 182,40 Z" fill="#1565C0" opacity="0.3" stroke="#1565C0" stroke-width="1.5"/>

  <!-- Radius -->
  <text x="184" y="132" font-size="11" fill="#1a3a5c" font-weight="bold">r</text>

  <!-- Central angle label -->
  <path d="M 175,110 A 35,35 0 0 1 168,76" stroke="#e05c1a" fill="none" stroke-width="2"/>
  <text x="186" y="90" font-size="12" fill="#e05c1a" font-weight="bold">x°</text>

  <!-- Labels -->
  <text x="140" y="205" text-anchor="middle" font-size="11" fill="#1a3a5c" font-weight="bold">Circle: A = πr²</text>
  <text x="140" y="218" text-anchor="middle" font-size="11" fill="#1565C0">Sector: A = (x/360)·πr²</text>
</svg>

</div>
<div style="flex:1.2;">

## All Area Formulas

| Shape | Formula |
|-------|---------|
| Rectangle | $A = lw$ |
| Square | $A = s^2$ |
| Parallelogram | $A = bh$ |
| Triangle | $A = \frac{1}{2}bh$ |
| Trapezoid | $A = \frac{1}{2}h(b_1+b_2)$ |
| Rhombus/Kite | $A = \frac{1}{2}d_1d_2$ |
| Regular polygon | $A = \frac{1}{2}Pa$ |
| Circle | $A = \pi r^2$ |
| Sector ($x°$) | $A = \frac{x}{360}\pi r^2$ |
| Arc length | $\ell = \frac{x}{360} \cdot 2\pi r$ |

## Geometric Probability
$$P = \frac{\text{favorable area}}{\text{total area}}$$

</div>
</div>
