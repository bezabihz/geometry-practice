---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 8
## Quadrilaterals

McGraw Hill Glencoe Geometry · Texas Edition

---

## Quadrilateral Family Tree

Every quadrilateral belongs to a hierarchy — each shape inherits all properties of its parent.

<svg width="760" height="180" viewBox="0 0 760 180" xmlns="http://www.w3.org/2000/svg">
  <!-- Quadrilateral (top) -->
  <rect x="300" y="5" width="160" height="36" rx="8" fill="#1a3a5c"/>
  <text x="380" y="28" font-size="13" fill="#fff" font-family="Arial" font-weight="bold" text-anchor="middle">Quadrilateral</text>
  <!-- Branches -->
  <line x1="380" y1="41" x2="180" y2="75" stroke="#555" stroke-width="1.5"/>
  <line x1="380" y1="41" x2="380" y2="75" stroke="#555" stroke-width="1.5"/>
  <line x1="380" y1="41" x2="580" y2="75" stroke="#555" stroke-width="1.5"/>
  <!-- Parallelogram -->
  <rect x="295" y="75" width="170" height="36" rx="8" fill="#1a3a5c"/>
  <text x="380" y="98" font-size="13" fill="#fff" font-family="Arial" font-weight="bold" text-anchor="middle">Parallelogram</text>
  <!-- Trapezoid -->
  <rect x="510" y="75" width="140" height="36" rx="8" fill="#2a5080"/>
  <text x="580" y="98" font-size="13" fill="#fff" font-family="Arial" text-anchor="middle">Trapezoid</text>
  <!-- Kite -->
  <rect x="100" y="75" width="120" height="36" rx="8" fill="#2a5080"/>
  <text x="160" y="98" font-size="13" fill="#fff" font-family="Arial" text-anchor="middle">Kite</text>
  <!-- Sub-branches from Parallelogram -->
  <line x1="380" y1="111" x2="240" y2="145" stroke="#555" stroke-width="1.5"/>
  <line x1="380" y1="111" x2="380" y2="145" stroke="#555" stroke-width="1.5"/>
  <line x1="380" y1="111" x2="520" y2="145" stroke="#555" stroke-width="1.5"/>
  <!-- Rectangle -->
  <rect x="165" y="145" width="140" height="30" rx="8" fill="#e05c1a"/>
  <text x="235" y="165" font-size="13" fill="#fff" font-family="Arial" text-anchor="middle">Rectangle</text>
  <!-- Rhombus -->
  <rect x="310" y="145" width="140" height="30" rx="8" fill="#e05c1a"/>
  <text x="380" y="165" font-size="13" fill="#fff" font-family="Arial" text-anchor="middle">Rhombus</text>
  <!-- Square -->
  <rect x="455" y="145" width="140" height="30" rx="8" fill="#c03a00"/>
  <text x="525" y="165" font-size="13" fill="#fff" font-family="Arial" font-weight="bold" text-anchor="middle">Square</text>
  <!-- Isosceles Trapezoid -->
  <line x1="580" y1="111" x2="680" y2="145" stroke="#555" stroke-width="1.5"/>
  <rect x="620" y="145" width="120" height="30" rx="8" fill="#2a5080"/>
  <text x="680" y="165" font-size="11" fill="#fff" font-family="Arial" text-anchor="middle">Isosc. Trapezoid</text>
</svg>

> **Square** has ALL properties of rectangle, rhombus, and parallelogram.

---

## Parallelogram Properties

<div class="columns">
<div>

A **parallelogram** ($\square ABCD$) has two pairs of parallel sides.

| Theorem | Property |
|---------|----------|
| **8-1** | Opposite sides are congruent |
| **8-2** | Opposite angles are congruent |
| **8-3** | Consecutive angles are supplementary |
| **8-4** | Diagonals bisect each other |

> **Theorem 8-4 explained:** The diagonals intersect at their shared midpoint — each diagonal is cut in half by the other.

> **Example:** $ABCD$ is a $\square$. $AB = 5x-2$, $CD = 3x+8$. Find $AB$.
> $5x-2 = 3x+8 \;\Rightarrow\; x = 5 \;\Rightarrow\; AB = \mathbf{23}$

</div>
<div>

<svg width="290" height="240" viewBox="0 0 290 240" xmlns="http://www.w3.org/2000/svg">
  <!-- Parallelogram -->
  <polygon points="40,200 230,200 260,60 70,60" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Diagonals -->
  <line x1="40" y1="200" x2="260" y2="60" stroke="#e05c1a" stroke-width="2" stroke-dasharray="6,3"/>
  <line x1="230" y1="200" x2="70" y2="60" stroke="#e05c1a" stroke-width="2" stroke-dasharray="6,3"/>
  <!-- Midpoint -->
  <circle cx="150" cy="130" r="6" fill="#e05c1a"/>
  <!-- Equal diagonal halves marks -->
  <line x1="90" y1="98" x2="97" y2="93" stroke="#e05c1a" stroke-width="2"/>
  <line x1="205" y1="162" x2="212" y2="157" stroke="#e05c1a" stroke-width="2"/>
  <line x1="192" y1="98" x2="185" y2="93" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="107" y1="162" x2="100" y2="157" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Labels -->
  <text x="26" y="218" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="231" y="218" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="262" y="55" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="58" y="55" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">D</text>
  <!-- Opposite side marks -->
  <line x1="128" y1="203" x2="136" y2="203" stroke="#555" stroke-width="2.5"/>
  <line x1="155" y1="57" x2="163" y2="57" stroke="#555" stroke-width="2.5"/>
  <text x="35" y="140" font-size="12" fill="#555" font-family="Arial">∥</text>
  <text x="260" y="140" font-size="12" fill="#555" font-family="Arial">∥</text>
  <text x="50" y="230" font-size="12" fill="#e05c1a" font-family="Arial">Diagonals bisect each other</text>
</svg>

</div>
</div>

---

## Proving a Quadrilateral is a Parallelogram

A quadrilateral is a parallelogram if **any one** of these conditions holds:

| Theorem | Condition |
|---------|-----------|
| **8-5** | Both pairs of opposite sides are congruent |
| **8-6** | Both pairs of opposite angles are congruent |
| **8-7** | Diagonals bisect each other |
| **8-8** | One pair of sides is both parallel and congruent |

<div class="columns">
<div>

> **Example:** Show that $PQRS$ is a parallelogram.
> Given: $PQ = RS = 10$ and $PQ \parallel RS$
>
> By **Theorem 8-8**, $PQRS$ is a parallelogram.

</div>
<div>

<svg width="260" height="150" viewBox="0 0 260 150" xmlns="http://www.w3.org/2000/svg">
  <polygon points="20,130 190,130 230,30 60,30" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="58" y1="27" x2="66" y2="27" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="186" y1="127" x2="194" y2="127" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="10" y="148" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">P</text>
  <text x="193" y="148" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">Q</text>
  <text x="233" y="27" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">R</text>
  <text x="48" y="27" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">S</text>
  <text x="100" y="140" font-size="12" fill="#555" font-family="Arial">PQ ∥ SR  and  PQ = SR</text>
</svg>

</div>
</div>

---

## Rectangle, Rhombus & Square

<div class="columns">
<div>

**Rectangle** — parallelogram with 4 right angles
> **Theorem 8-9:** Diagonals of a rectangle are **congruent**.

**Rhombus** — parallelogram with 4 congruent sides
> **Theorem 8-10:** Diagonals of a rhombus are **perpendicular**.
> **Theorem 8-11:** Each diagonal of a rhombus **bisects** its vertex angles.

**Square** — both a rectangle and a rhombus
> Has ALL properties of both.

| Shape | Diag. ≅? | Diag. ⊥? | All sides ≅? | All ∠ = 90°? |
|-------|-----------|-----------|--------------|--------------|
| Rectangle | ✓ | ✗ | ✗ | ✓ |
| Rhombus | ✗ | ✓ | ✓ | ✗ |
| Square | ✓ | ✓ | ✓ | ✓ |

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle -->
  <rect x="15" y="15" width="120" height="70" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <rect x="15" y="15" width="16" height="16" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <line x1="15" y1="15" x2="135" y2="85" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="135" y1="15" x2="15" y2="85" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <text x="60" y="108" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle">Rectangle (diag ≅)</text>

  <!-- Rhombus -->
  <polygon points="220,15 265,50 220,85 175,50" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <line x1="175" y1="50" x2="265" y2="50" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="220" y1="15" x2="220" y2="85" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <rect x="213" y="43" width="14" height="14" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="220" y="108" font-size="12" fill="#e05c1a" font-family="Arial" text-anchor="middle">Rhombus (diag ⊥)</text>

  <!-- Square -->
  <rect x="80" y="145" width="90" height="90" fill="#fff3e0" stroke="#1a3a5c" stroke-width="2.5"/>
  <rect x="80" y="145" width="14" height="14" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <rect x="156" y="145" width="14" height="14" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <rect x="80" y="221" width="14" height="14" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <rect x="156" y="221" width="14" height="14" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <line x1="80" y1="145" x2="170" y2="235" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="170" y1="145" x2="80" y2="235" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <rect x="118" y="183" width="14" height="14" transform="rotate(45,125,190)" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="125" y="252" font-size="13" fill="#1a3a5c" font-family="Arial" text-anchor="middle" font-weight="bold">Square</text>
</svg>

</div>
</div>

---

## Trapezoids & Kites

<div class="columns">
<div>

**Trapezoid** — exactly one pair of parallel sides (bases $b_1$ and $b_2$)
**Isosceles trapezoid** — legs are congruent

| Theorem | Property |
|---------|----------|
| **8-14** | Isosceles trap.: base angles congruent |
| **8-15** | Isosceles trap.: diagonals congruent |
| **8-16** | Midsegment $= \frac{b_1 + b_2}{2}$ |

**Kite** — two pairs of consecutive congruent sides

| Theorem | Property |
|---------|----------|
| **8-19** | Diagonals perpendicular |
| **8-20** | One diagonal bisects vertex angles |

> **Example (Midsegment):** $b_1 = 8$, $b_2 = 14$.
> $MN = \frac{8+14}{2} = \mathbf{11}$

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Trapezoid -->
  <polygon points="70,30 210,30 250,140 30,140" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="136" y="25" font-size="13" fill="#1a3a5c" font-family="Arial">b₁ = 8</text>
  <text x="118" y="158" font-size="13" fill="#1a3a5c" font-family="Arial">b₂ = 14</text>
  <!-- Midsegment -->
  <line x1="50" y1="85" x2="230" y2="85" stroke="#e05c1a" stroke-width="2.5"/>
  <circle cx="50" cy="85" r="5" fill="#e05c1a"/>
  <circle cx="230" cy="85" r="5" fill="#e05c1a"/>
  <text x="115" y="79" font-size="13" fill="#e05c1a" font-family="Arial">MN = 11</text>
  <!-- Kite below -->
  <polygon points="145,175 100,215 145,255 190,215" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <line x1="100" y1="215" x2="190" y2="215" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="145" y1="175" x2="145" y2="255" stroke="#1a3a5c" stroke-width="1.5" stroke-dasharray="5,3"/>
  <rect x="137" y="207" width="16" height="16" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <!-- Congruence marks on kite sides -->
  <line x1="116" y1="192" x2="121" y2="188" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="170" y1="188" x2="175" y2="192" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="116" y1="237" x2="121" y2="242" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="170" y1="242" x2="175" y2="237" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="148" y="265" font-size="11" fill="#555" font-family="Arial">Kite: diag ⊥</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example — Parallelogram & Midsegment

**Part A:** $WXYZ$ is a parallelogram. $WX = 2x+3$, $YZ = x+11$, $\angle W = (3y-5)°$, $\angle X = (y+15)°$. Find $WX$, $YZ$, and $\angle W$.

<div class="columns">
<div>

**Opposite sides equal (Thm 8-1):**
$$2x+3 = x+11 \;\Rightarrow\; x = 8$$
$$WX = YZ = 2(8)+3 = \mathbf{19}$$

**Consecutive angles supplementary (Thm 8-3):**
$$3y-5 + y+15 = 180$$
$$4y + 10 = 180 \;\Rightarrow\; y = 42.5$$
$$\angle W = 3(42.5)-5 = \mathbf{122.5°}$$

</div>
<div>

**Part B:** A trapezoid has bases 13 and 7. Find the midsegment.

$$MN = \frac{b_1 + b_2}{2} = \frac{13+7}{2} = \mathbf{10}$$

<svg width="240" height="130" viewBox="0 0 240 130" xmlns="http://www.w3.org/2000/svg">
  <polygon points="55,20 185,20 220,110 20,110" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <text x="100" y="15" font-size="12" fill="#1a3a5c" font-family="Arial">b₁ = 7</text>
  <text x="100" y="126" font-size="12" fill="#1a3a5c" font-family="Arial">b₂ = 13</text>
  <line x1="38" y1="65" x2="202" y2="65" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="100" y="59" font-size="12" fill="#e05c1a" font-family="Arial">MN = 10</text>
</svg>

</div>
</div>

---

## Chapter 8 — Summary

| Shape | Key Properties |
|-------|---------------|
| **Parallelogram** | Opp. sides ∥ & ≅; opp. ∠ ≅; consec. ∠ supp.; diag. bisect each other |
| **Rectangle** | Parallelogram + 4 right angles + diag. ≅ |
| **Rhombus** | Parallelogram + 4 ≅ sides + diag. ⊥ + diag. bisect angles |
| **Square** | Rectangle + rhombus (all properties) |
| **Trapezoid** | Exactly 1 pair ∥ sides; midseg $= \frac{b_1+b_2}{2}$ |
| **Isosc. Trap.** | Legs ≅, base ∠ ≅, diag. ≅ |
| **Kite** | 2 pairs consec. ≅ sides; diag. ⊥; 1 diag. bisects vertex ∠ |

> **Key insight:** A square is the "most special" quadrilateral — it satisfies every parallelogram, rectangle, and rhombus property simultaneously.
