---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 5
## Relationships in Triangles

McGraw Hill Glencoe Geometry · Texas Edition

---

## Triangle Centers — Overview

Every triangle has four classical centers, each built from a different set of special lines.

| Center | Built from | Special property | Location |
|--------|-----------|-----------------|----------|
| **Circumcenter** | Perpendicular bisectors | Equidistant from vertices | Can be outside obtuse △ |
| **Incenter** | Angle bisectors | Equidistant from sides | Always inside |
| **Centroid** | Medians | Center of gravity | Always inside |
| **Orthocenter** | Altitudes | — | Can be outside obtuse △ |

<svg width="700" height="160" viewBox="0 0 700 160" xmlns="http://www.w3.org/2000/svg">
  <!-- Circumcenter -->
  <polygon points="90,20 20,140 160,140" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="90" cy="92" r="52" fill="none" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <circle cx="90" cy="92" r="4" fill="#e05c1a"/>
  <text x="62" y="155" font-size="11" fill="#1a3a5c" font-family="Arial">Circumcenter</text>
  <!-- Incenter -->
  <polygon points="265,20 195,140 335,140" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="265" cy="105" r="30" fill="none" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <circle cx="265" cy="105" r="4" fill="#e05c1a"/>
  <text x="242" y="155" font-size="11" fill="#1a3a5c" font-family="Arial">Incenter</text>
  <!-- Centroid -->
  <polygon points="440,20 370,140 510,140" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="440" y1="20" x2="440" y2="140" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="370" y1="140" x2="475" y2="80" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="510" y1="140" x2="405" y2="80" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <circle cx="440" cy="100" r="4" fill="#e05c1a"/>
  <text x="420" y="155" font-size="11" fill="#1a3a5c" font-family="Arial">Centroid</text>
  <!-- Orthocenter -->
  <polygon points="615,20 545,140 685,140" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="615" y1="20" x2="615" y2="140" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="545" y1="140" x2="645" y2="80" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="685" y1="140" x2="585" y2="80" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <circle cx="615" cy="88" r="4" fill="#e05c1a"/>
  <text x="590" y="155" font-size="11" fill="#1a3a5c" font-family="Arial">Orthocenter</text>
</svg>

---

## Perpendicular Bisector Theorems

<div class="columns">
<div>

A **perpendicular bisector** of a segment is a line that is perpendicular to the segment at its midpoint.

**Theorem 5-1:** If a point is on the perpendicular bisector of a segment, it is equidistant from the endpoints.

$$PA = PB$$

**Theorem 5-2 (Converse):** If a point is equidistant from the endpoints of a segment, it lies on the perpendicular bisector.

**Theorem 5-5 (Circumcenter):** The circumcenter of a triangle is equidistant from all three vertices.
$$CA = CB = CC$$

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Segment AB -->
  <line x1="60" y1="200" x2="230" y2="200" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="60" cy="200" r="6" fill="#1a3a5c"/>
  <circle cx="230" cy="200" r="6" fill="#1a3a5c"/>
  <text x="48" y="220" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="228" y="220" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <!-- Midpoint M -->
  <circle cx="145" cy="200" r="5" fill="#e05c1a"/>
  <text x="140" y="220" font-size="13" fill="#e05c1a" font-family="Arial">M</text>
  <!-- Perpendicular bisector -->
  <line x1="145" y1="240" x2="145" y2="20" stroke="#e05c1a" stroke-width="2" stroke-dasharray="6,3"/>
  <rect x="145" y="192" width="12" height="12" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <!-- Point P on bisector -->
  <circle cx="145" cy="80" r="6" fill="#1a3a5c"/>
  <text x="152" y="80" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">P</text>
  <!-- Lines PA and PB -->
  <line x1="145" y1="80" x2="60" y2="200" stroke="#555" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="145" y1="80" x2="230" y2="200" stroke="#555" stroke-width="1.5" stroke-dasharray="5,3"/>
  <!-- Equal distance marks -->
  <text x="82" y="135" font-size="12" fill="#555" font-family="Arial">PA</text>
  <text x="188" y="135" font-size="12" fill="#555" font-family="Arial">PB</text>
  <text x="90" y="240" font-size="12" fill="#e05c1a" font-family="Arial">PA = PB  ✓</text>
</svg>

</div>
</div>

---

## Angle Bisector & Incenter Theorems

<div class="columns">
<div>

An **angle bisector** divides an angle into two congruent angles.

**Theorem 5-3:** A point on the angle bisector of an angle is equidistant from the two sides of the angle.

**Theorem 5-4 (Converse):** A point equidistant from the two sides of an angle lies on the angle bisector.

**Theorem 5-6 (Incenter):** The incenter is equidistant from all three sides.
The distance from the incenter to each side is the **inradius** ($r$).

> The incenter is always inside the triangle.

</div>
<div>

<svg width="290" height="250" viewBox="0 0 290 250" xmlns="http://www.w3.org/2000/svg">
  <polygon points="145,20 20,220 270,220" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Angle bisectors from each vertex -->
  <line x1="145" y1="20" x2="145" y2="185" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="20" y1="220" x2="210" y2="136" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="270" y1="220" x2="82" y2="136" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <!-- Incenter -->
  <circle cx="145" cy="165" r="5" fill="#e05c1a"/>
  <text x="152" y="165" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">I</text>
  <!-- Inscribed circle -->
  <circle cx="145" cy="165" r="42" fill="none" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <!-- Inradius label -->
  <line x1="145" y1="165" x2="145" y2="207" stroke="#555" stroke-width="1.5"/>
  <text x="150" y="195" font-size="12" fill="#555" font-family="Arial">r</text>
  <text x="35" y="242" font-size="12" fill="#555" font-family="Arial">Incenter equidistant from all 3 sides</text>
</svg>

</div>
</div>

---

## Centroid Theorem

<div class="columns">
<div>

A **median** connects a vertex to the midpoint of the opposite side. Every triangle has three medians.

**Theorem 5-7 (Centroid):** The centroid divides each median in a **2:1 ratio** from vertex to midpoint.

$$BG = \frac{2}{3} \cdot BD \qquad GD = \frac{1}{3} \cdot BD$$

The centroid is the triangle's **center of gravity** — it balances on this point.

> **Example:** Median $\overline{BD} = 18$. Find $BG$ and $GD$.
> $BG = \frac{2}{3}(18) = 12$
> $GD = \frac{1}{3}(18) = 6$

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <polygon points="145,20 20,230 270,230" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Midpoints -->
  <circle cx="145" cy="230" r="5" fill="#1a3a5c"/>
  <circle cx="83" cy="125" r="5" fill="#1a3a5c"/>
  <circle cx="207" cy="125" r="5" fill="#1a3a5c"/>
  <!-- Medians -->
  <line x1="145" y1="20" x2="145" y2="230" stroke="#e05c1a" stroke-width="2"/>
  <line x1="20" y1="230" x2="207" y2="125" stroke="#e05c1a" stroke-width="2"/>
  <line x1="270" y1="230" x2="83" y2="125" stroke="#e05c1a" stroke-width="2"/>
  <!-- Centroid G -->
  <circle cx="145" cy="157" r="7" fill="#e05c1a"/>
  <text x="152" y="157" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">G</text>
  <!-- 2:1 labels on vertical median -->
  <line x1="135" y1="20" x2="135" y2="157" stroke="#555" stroke-width="1" stroke-dasharray="3,3"/>
  <text x="115" y="95" font-size="12" fill="#555" font-family="Arial">BG</text>
  <text x="108" y="92" font-size="12" fill="#e05c1a" font-family="Arial">= ²⁄₃</text>
  <line x1="135" y1="157" x2="135" y2="230" stroke="#555" stroke-width="1" stroke-dasharray="3,3"/>
  <text x="115" y="200" font-size="12" fill="#555" font-family="Arial">GD = ¹⁄₃</text>
  <!-- Vertex labels -->
  <text x="139" y="14" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="140" y="248" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">D</text>
  <text x="6" y="244" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="272" y="244" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
</svg>

</div>
</div>

---

## Triangle Inequality Theorem

<div class="columns">
<div>

**Theorem 5-11 (Triangle Inequality):**
The sum of the lengths of any two sides of a triangle must be **greater than** the length of the third side.

$$a + b > c, \quad a + c > b, \quad b + c > a$$

**Why:** The straight-line distance between two points is always the shortest path — if a side were too long, you couldn't "close" the triangle.

> **Example 1:** Can 3, 5, 9 form a triangle?
> $3 + 5 = 8 < 9$ ✗ — **Cannot** form a triangle.

> **Example 2:** Can 6, 8, 10 form a triangle?
> $6 + 8 = 14 > 10$ ✓, $6 + 10 = 16 > 8$ ✓, $8 + 10 = 18 > 6$ ✓ — **Yes!**

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Valid triangle -->
  <polygon points="70,50 20,200 200,200" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="30" y="135" font-size="13" fill="#1a3a5c" font-family="Arial">6</text>
  <text x="105" y="220" font-size="13" fill="#1a3a5c" font-family="Arial">8</text>
  <text x="145" y="120" font-size="13" fill="#1a3a5c" font-family="Arial">10</text>
  <text x="25" y="240" font-size="12" fill="#1a3a5c" font-family="Arial">6+8=14 > 10 ✓</text>
  <!-- Invalid attempt -->
  <line x1="210" y1="200" x2="260" y2="200" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="210" y1="200" x2="218" y2="150" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="260" y1="200" x2="252" y2="150" stroke="#555" stroke-width="2" stroke-dasharray="5,3"/>
  <text x="225" y="220" font-size="13" fill="#e05c1a" font-family="Arial">5</text>
  <text x="208" y="172" font-size="13" fill="#e05c1a" font-family="Arial">3</text>
  <text x="248" y="172" font-size="13" fill="#555" font-family="Arial">9</text>
  <text x="205" y="240" font-size="11" fill="#e05c1a" font-family="Arial">3+5=8 < 9 ✗</text>
  <text x="148" y="260" font-size="11" fill="#555" font-family="Arial">Sides don't meet!</text>
</svg>

</div>
</div>

---

## Angle-Side Relationships

<div class="columns">
<div>

**Theorem 5-9:** In a triangle, the side opposite the larger angle is longer.
$$m\angle A > m\angle B \;\Rightarrow\; BC > AC$$

**Theorem 5-10 (Converse):** The angle opposite the longer side is larger.

**Theorem 5-8 (Exterior Angle Inequality):** An exterior angle is greater than either non-adjacent interior angle.

> **Example:** In $\triangle ABC$, $\angle A = 90°$, $\angle B = 60°$, $\angle C = 30°$.
>
> Order the sides from shortest to longest:
>
> $\angle C < \angle B < \angle A \;\Rightarrow\; AB < AC < BC$

</div>
<div>

<svg width="290" height="230" viewBox="0 0 290 230" xmlns="http://www.w3.org/2000/svg">
  <polygon points="20,200 270,200 20,40" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <rect x="20" y="188" width="14" height="14" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M260,200 A28,28 0 0,1 250,174" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M20,56 A20,20 0 0,1 36,50" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="6" y="226" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="271" y="220" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="6" y="38" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="8" y="188" font-size="13" fill="#e05c1a" font-family="Arial">90°</text>
  <text x="244" y="188" font-size="13" fill="#e05c1a" font-family="Arial">60°</text>
  <text x="28" y="58" font-size="13" fill="#e05c1a" font-family="Arial">30°</text>
  <!-- Side labels -->
  <text x="130" y="218" font-size="13" fill="#1a3a5c" font-family="Arial">AB (medium)</text>
  <text x="2" y="128" font-size="12" fill="#1a3a5c" font-family="Arial">AC</text>
  <text x="148" y="128" font-size="12" fill="#1a3a5c" font-family="Arial">BC (longest)</text>
  <text x="18" y="248" font-size="12" fill="#555" font-family="Arial">Largest ∠ → longest opposite side</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example — Centroid & Inequality

**Part A:** The centroid $G$ divides median $\overline{AE}$. If $AG = 14$, find $AE$ and $GE$.

> $AG = \frac{2}{3} AE \;\Rightarrow\; 14 = \frac{2}{3} AE \;\Rightarrow\; AE = 21$
>
> $GE = AE - AG = 21 - 14 = 7$
>
> Check: $AG : GE = 14 : 7 = 2:1$ ✓

**Part B:** Can a triangle have sides of length 4, 7, and 12?

> $4 + 7 = 11 < 12$ ✗ — **No**, the two shorter sides don't reach each other.

**Part C:** In $\triangle PQR$, $PQ = 9$, $QR = 6$, $PR = 11$. Order the angles from smallest to largest.

> Smallest side $QR = 6$ → smallest $\angle P$
> Middle side $PQ = 9$ → middle $\angle R$
> Longest side $PR = 11$ → largest $\angle Q$
>
> Answer: $\angle P < \angle R < \angle Q$

---

## Chapter 5 — Summary

| Theorem | Statement |
|---------|-----------|
| **Perp. Bisector (5-1)** | Point on bisector ↔ equidistant from endpoints |
| **Angle Bisector (5-3)** | Point on bisector ↔ equidistant from sides |
| **Circumcenter (5-5)** | Equidistant from all 3 vertices; on perp. bisectors |
| **Incenter (5-6)** | Equidistant from all 3 sides; on angle bisectors |
| **Centroid (5-7)** | Divides each median 2:1 from vertex |
| **Angle-Side (5-9/10)** | Larger angle ↔ longer opposite side |
| **Triangle Inequality (5-11)** | Sum of any two sides > third side |
| **Hinge Theorem (5-12)** | Larger included angle → longer opposite side |

> **Key insight:** The centroid's 2:1 ratio means the vertex-to-centroid distance is always *twice* the centroid-to-midpoint distance.
