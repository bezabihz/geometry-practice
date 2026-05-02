---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 11
## Areas of Polygons & Circles

McGraw Hill Glencoe Geometry · Texas Edition

---

## Area Formula Reference

| Shape | Formula | Key measurement |
|-------|---------|----------------|
| Rectangle | $A = bh$ | base × height |
| Square | $A = s^2$ | side squared |
| Parallelogram | $A = bh$ | height ⊥ to base |
| Triangle | $A = \frac{1}{2}bh$ | height ⊥ to base |
| Trapezoid | $A = \frac{1}{2}h(b_1+b_2)$ | average base × height |
| Rhombus/Kite | $A = \frac{1}{2}d_1 d_2$ | product of diagonals |
| Regular polygon | $A = \frac{1}{2}Pa$ | perimeter × apothem |
| Circle | $A = \pi r^2$ | radius squared |
| Sector | $A = \frac{x}{360}\pi r^2$ | fraction of circle |

> **Height** must always be **perpendicular** to the base — not the slant side.

---

## Parallelogram & Triangle Areas

<div class="columns">
<div>

**Theorem 11-1 (Parallelogram):**
$$A = bh$$

The height $h$ is perpendicular to the base — it is not the slant side.

**Theorem 11-2 (Triangle):**
$$A = \frac{1}{2}bh$$

A triangle is half a parallelogram (any triangle can be doubled into a parallelogram).

**Heron's Formula** (when only sides are known):
$$s = \frac{a+b+c}{2}, \qquad A = \sqrt{s(s-a)(s-b)(s-c)}$$

> **Example:** Triangle with base 10, height 6.
> $A = \frac{1}{2}(10)(6) = \mathbf{30}$

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Parallelogram -->
  <polygon points="30,100 180,100 210,40 60,40" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Height -->
  <line x1="60" y1="40" x2="60" y2="100" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
  <rect x="60" y="85" width="14" height="14" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="65" y="76" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">h</text>
  <text x="100" y="125" font-size="13" fill="#1a3a5c" font-family="Arial">base b</text>
  <text x="215" y="75" font-size="13" fill="#1a3a5c" font-family="Arial">A = bh</text>

  <!-- Triangle -->
  <polygon points="30,230 210,230 110,160" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Height -->
  <line x1="110" y1="160" x2="110" y2="230" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
  <rect x="110" y="215" width="14" height="14" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="115" y="200" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">h</text>
  <text x="95" y="248" font-size="13" fill="#1a3a5c" font-family="Arial">base b</text>
  <text x="222" y="200" font-size="13" fill="#1a3a5c" font-family="Arial">A = ½bh</text>
</svg>

</div>
</div>

---

## Trapezoid & Rhombus Areas

<div class="columns">
<div>

**Theorem 11-3 (Trapezoid):**
$$A = \frac{1}{2}h(b_1 + b_2)$$

Think of it as: height × (average of the two bases).

**Theorem 11-4 (Rhombus or Kite):**
$$A = \frac{1}{2}d_1 d_2$$

Works because the diagonals divide the figure into 4 triangles.

> **Example 1 (Trapezoid):** $b_1 = 6$, $b_2 = 10$, $h = 4$.
> $A = \frac{1}{2}(4)(6+10) = 2(16) = \mathbf{32}$

> **Example 2 (Rhombus):** $d_1 = 8$, $d_2 = 6$.
> $A = \frac{1}{2}(8)(6) = \mathbf{24}$

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Trapezoid -->
  <polygon points="60,40 200,40 230,120 30,120" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="60" y1="40" x2="60" y2="120" stroke="#e05c1a" stroke-width="2" stroke-dasharray="5,3"/>
  <rect x="60" y="103" width="14" height="14" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="65" y="88" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">h=4</text>
  <text x="110" y="30" font-size="13" fill="#1a3a5c" font-family="Arial">b₁=6</text>
  <text x="100" y="140" font-size="13" fill="#1a3a5c" font-family="Arial">b₂=10</text>
  <text x="190" y="90" font-size="12" fill="#555" font-family="Arial">A=32</text>

  <!-- Rhombus -->
  <polygon points="145,165 205,210 145,255 85,210" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Diagonals -->
  <line x1="85" y1="210" x2="205" y2="210" stroke="#1a3a5c" stroke-width="2" stroke-dasharray="5,3"/>
  <line x1="145" y1="165" x2="145" y2="255" stroke="#1a3a5c" stroke-width="2" stroke-dasharray="5,3"/>
  <rect x="137" y="202" width="16" height="16" fill="none" stroke="#555" stroke-width="1.5"/>
  <text x="140" y="200" font-size="12" fill="#1a3a5c" font-family="Arial">d₁=8</text>
  <text x="150" y="215" font-size="12" fill="#1a3a5c" font-family="Arial">d₂=6</text>
  <text x="210" y="215" font-size="12" fill="#555" font-family="Arial">A=24</text>
</svg>

</div>
</div>

---

## Regular Polygons & Apothem

<div class="columns">
<div>

In a **regular polygon** (all sides and angles equal):
- **Apothem** ($a$) = perpendicular distance from center to a side
- **Perimeter** = $P = ns$ (number of sides × side length)
- **Central angle** = $\frac{360°}{n}$

**Theorem 11-5:**
$$A = \frac{1}{2}Pa$$

Think of it as: the apothem splits the polygon into $n$ congruent triangles, each with area $\frac{1}{2} \cdot s \cdot a$.

> **Example (Regular Hexagon):** Side $s = 6$, apothem $a = 3\sqrt{3}$
> $P = 6 \times 6 = 36$
> $A = \frac{1}{2}(36)(3\sqrt{3}) = 54\sqrt{3} \approx 93.5$

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Regular hexagon -->
  <polygon points="145,30 220,72 220,158 145,200 70,158 70,72" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Center -->
  <circle cx="145" cy="115" r="4" fill="#1a3a5c"/>
  <text x="150" y="113" font-size="12" fill="#1a3a5c" font-family="Arial" font-weight="bold">O</text>
  <!-- Apothem to bottom side -->
  <line x1="145" y1="115" x2="145" y2="200" stroke="#e05c1a" stroke-width="2.5"/>
  <rect x="137" y="184" width="16" height="16" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="150" y="162" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">a</text>
  <!-- Radius to vertex -->
  <line x1="145" y1="115" x2="220" y2="72" stroke="#555" stroke-width="1.5" stroke-dasharray="4,3"/>
  <text x="180" y="88" font-size="12" fill="#555" font-family="Arial">r</text>
  <!-- One triangle shaded -->
  <polygon points="145,115 70,158 145,200" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5" fill-opacity="0.5"/>
  <!-- Side label -->
  <text x="85" y="188" font-size="13" fill="#1a3a5c" font-family="Arial">s = 6</text>
  <text x="55" y="240" font-size="12" fill="#555" font-family="Arial">n triangles, each area = ½ · s · a</text>
</svg>

</div>
</div>

---

## Circles: Circumference, Area, Arc Length & Sector

<div class="columns">
<div>

**Theorem 11-6 (Circumference):**
$$C = 2\pi r = \pi d$$

**Theorem 11-7 (Area):**
$$A = \pi r^2$$

**Arc Length** (fraction of circumference):
$$\ell = \frac{x}{360} \cdot 2\pi r$$

**Sector Area** (fraction of circle area):
$$A_{\text{sector}} = \frac{x}{360} \cdot \pi r^2$$

where $x$ = central angle in degrees.

> **Example:** $r = 10$, $x = 72°$
> $A_{\text{sector}} = \frac{72}{360}\pi(100) = \frac{1}{5}(100\pi) = 20\pi \approx 62.8$

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Full circle -->
  <circle cx="145" cy="130" r="100" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Sector (72°/360° = 1/5 of circle, from 0° to 72°) -->
  <path d="M145,130 L245,130 A100,100 0 0,1 176,35 Z" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Radius labels -->
  <line x1="145" y1="130" x2="245" y2="130" stroke="#e05c1a" stroke-width="2"/>
  <line x1="145" y1="130" x2="176" y2="35" stroke="#e05c1a" stroke-width="2"/>
  <text x="190" y="125" font-size="12" fill="#e05c1a" font-family="Arial">r</text>
  <!-- Angle label -->
  <path d="M185,130 A40,40 0 0,1 169,92" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="192" y="105" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">72°</text>
  <!-- Arc label -->
  <text x="230" y="72" font-size="12" fill="#e05c1a" font-family="Arial">arc</text>
  <!-- Circumference arrow -->
  <path d="M245,135 A102,102 0 0,1 42,135" fill="none" stroke="#1a3a5c" stroke-width="2" stroke-dasharray="5,3"/>
  <text x="30" y="175" font-size="12" fill="#1a3a5c" font-family="Arial">C = 2πr</text>
  <!-- Center -->
  <circle cx="145" cy="130" r="4" fill="#1a3a5c"/>
  <text x="150" y="145" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">O</text>
  <text x="40" y="248" font-size="12" fill="#555" font-family="Arial">Sector = (x/360) × πr²</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example — Composite Figure

**Find the area of the figure: a rectangle 12 × 8 with a semicircle on top (diameter = 12).**

<div class="columns">
<div>

**Part 1: Rectangle**
$$A_{\text{rect}} = 12 \times 8 = 96$$

**Part 2: Semicircle** (radius = 6)
$$A_{\text{semi}} = \frac{1}{2}\pi r^2 = \frac{1}{2}\pi(36) = 18\pi \approx 56.5$$

**Total Area:**
$$A = 96 + 18\pi \approx 96 + 56.5 = \mathbf{152.5}$$

**Perimeter (if needed):**
Rectangle bottom + 2 sides + semicircle arc
$$P = 12 + 8 + 8 + \pi(6) = 28 + 6\pi \approx 46.8$$

</div>
<div>

<svg width="270" height="230" viewBox="0 0 270 230" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle -->
  <rect x="55" y="105" width="160" height="110" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Semicircle on top -->
  <path d="M55,105 A80,80 0 0,1 215,105" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Dimensions -->
  <text x="120" y="225" font-size="13" fill="#1a3a5c" font-family="Arial">12</text>
  <text x="223" y="165" font-size="13" fill="#1a3a5c" font-family="Arial">8</text>
  <text x="125" y="70" font-size="13" fill="#e05c1a" font-family="Arial">r = 6</text>
  <!-- Center of semicircle -->
  <circle cx="135" cy="105" r="4" fill="#e05c1a"/>
  <line x1="135" y1="105" x2="215" y2="105" stroke="#e05c1a" stroke-width="2" stroke-dasharray="4,3"/>
  <!-- Area labels -->
  <text x="100" y="165" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">96</text>
  <text x="108" y="82" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">18π</text>
</svg>

</div>
</div>

---

## Chapter 11 — Summary

| Shape | Area Formula |
|-------|-------------|
| Rectangle/Parallelogram | $A = bh$ |
| Triangle | $A = \frac{1}{2}bh$ |
| Trapezoid | $A = \frac{1}{2}h(b_1+b_2)$ |
| Rhombus/Kite | $A = \frac{1}{2}d_1d_2$ |
| Regular polygon | $A = \frac{1}{2}Pa$ |
| Circle | $A = \pi r^2$ |
| Sector | $A = \frac{x}{360}\pi r^2$ |
| Arc length | $\ell = \frac{x}{360}(2\pi r)$ |

> **Key insight:** All area formulas reduce to base × height. The trapezoid uses the *average* base; the circle can be thought of as a regular polygon with infinitely many tiny sides, and $\frac{1}{2}Pa$ becomes $\frac{1}{2}(2\pi r)(r) = \pi r^2$.
