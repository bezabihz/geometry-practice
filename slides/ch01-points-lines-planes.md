---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 1
## Points, Lines, Planes & Angles

McGraw Hill Glencoe Geometry · Texas Edition

---

## Undefined Terms

These three terms are the foundation of all geometry — accepted without formal definition.

<div class="columns">
<div>

**Point** — a location, no size, no dimension
**Line** — infinite points extending in both directions
**Plane** — flat surface extending infinitely in 2-D

| Term | Notation | Dim |
|------|----------|-----|
| Point | $A$ | 0 |
| Line | $\overleftrightarrow{AB}$ | 1 |
| Plane | Plane $\mathcal{P}$ | 2 |

</div>
<div>

<svg width="330" height="240" viewBox="0 0 330 240" xmlns="http://www.w3.org/2000/svg">
  <circle cx="60" cy="36" r="6" fill="#e05c1a"/>
  <text x="74" y="41" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A — Point</text>
  <line x1="20" y1="100" x2="200" y2="100" stroke="#1a3a5c" stroke-width="2.5"/>
  <polygon points="202,100 190,94 190,106" fill="#1a3a5c"/>
  <polygon points="18,100 30,94 30,106" fill="#1a3a5c"/>
  <circle cx="80" cy="100" r="5" fill="#e05c1a"/>
  <circle cx="150" cy="100" r="5" fill="#e05c1a"/>
  <text x="76" y="118" font-size="13" fill="#1a3a5c" font-family="Arial">A</text>
  <text x="147" y="118" font-size="13" fill="#1a3a5c" font-family="Arial">B</text>
  <text x="210" y="104" font-size="14" fill="#1a3a5c" font-family="Arial">Line AB</text>
  <polygon points="30,155 190,155 260,215 100,215" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="140" y="195" font-size="14" fill="#1a3a5c" font-family="Arial" text-anchor="middle">Plane 𝒫</text>
  <circle cx="100" cy="178" r="4" fill="#e05c1a"/>
  <circle cx="150" cy="172" r="4" fill="#e05c1a"/>
  <circle cx="190" cy="182" r="4" fill="#e05c1a"/>
  <text x="28" y="148" font-size="12" fill="#555" font-family="Arial">3 non-collinear pts define a plane</text>
</svg>

</div>
</div>

---

## Collinear, Coplanar & Segment vs. Ray

<div class="columns">
<div>

**Collinear** — points on the same line
**Coplanar** — points on the same plane
**Segment** $\overline{AB}$ — two endpoints + all points between
**Ray** $\overrightarrow{AB}$ — endpoint $A$, extends through $B$
**Opposite rays** — two rays from the same point, forming a line

> **Postulate:** Through any two points there is exactly one line.

</div>
<div>

<svg width="310" height="220" viewBox="0 0 310 220" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="40" x2="180" y2="40" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="20" cy="40" r="5" fill="#e05c1a"/>
  <circle cx="180" cy="40" r="5" fill="#e05c1a"/>
  <text x="15" y="58" font-size="13" fill="#1a3a5c" font-family="Arial">A</text>
  <text x="176" y="58" font-size="13" fill="#1a3a5c" font-family="Arial">B</text>
  <text x="190" y="44" font-size="13" fill="#555" font-family="Arial">Segment AB</text>
  <line x1="20" y1="110" x2="200" y2="110" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="200,110 188,104 188,116" fill="#1a3a5c"/>
  <circle cx="20" cy="110" r="5" fill="#e05c1a"/>
  <text x="15" y="128" font-size="13" fill="#1a3a5c" font-family="Arial">A</text>
  <text x="115" y="128" font-size="13" fill="#1a3a5c" font-family="Arial">B →</text>
  <text x="207" y="114" font-size="13" fill="#555" font-family="Arial">Ray AB</text>
  <line x1="20" y1="180" x2="290" y2="180" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="290,180 278,174 278,186" fill="#1a3a5c"/>
  <polygon points="20,180 32,174 32,186" fill="#1a3a5c"/>
  <circle cx="155" cy="180" r="5" fill="#e05c1a"/>
  <text x="148" y="198" font-size="13" fill="#1a3a5c" font-family="Arial">C</text>
  <text x="50" y="172" font-size="12" fill="#e05c1a" font-family="Arial">← Ray CA</text>
  <text x="165" y="172" font-size="12" fill="#e05c1a" font-family="Arial">Ray CB →</text>
</svg>

</div>
</div>

---

## Ruler & Segment Addition Postulates

<div class="columns">
<div>

**Postulate 1-5 (Ruler):** Every point on a line has a real-number coordinate. The distance between two points equals the absolute value of the difference of their coordinates.
$$AB = |a - b|$$

**Postulate 1-6 (Segment Addition):** If $B$ is between $A$ and $C$:
$$AB + BC = AC$$

> **Example:** $A = 0,\; B = 8,\; C = 20$
> $AB = 8,\; BC = 12,\; AC = 20$ ✓

</div>
<div>

<svg width="310" height="190" viewBox="0 0 310 190" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="60" x2="290" y2="60" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="60" y1="52" x2="60" y2="68" stroke="#1a3a5c" stroke-width="1.5"/>
  <line x1="160" y1="52" x2="160" y2="68" stroke="#1a3a5c" stroke-width="1.5"/>
  <line x1="260" y1="52" x2="260" y2="68" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="56" y="83" font-size="13" fill="#1a3a5c" font-family="Arial">0</text>
  <text x="155" y="83" font-size="13" fill="#1a3a5c" font-family="Arial">8</text>
  <text x="253" y="83" font-size="13" fill="#1a3a5c" font-family="Arial">20</text>
  <circle cx="60" cy="60" r="6" fill="#e05c1a"/>
  <circle cx="160" cy="60" r="6" fill="#1a3a5c"/>
  <circle cx="260" cy="60" r="6" fill="#e05c1a"/>
  <text x="54" y="45" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">A</text>
  <text x="154" y="45" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="254" y="45" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">C</text>
  <path d="M60,96 Q110,115 160,96" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="88" y="126" font-size="13" fill="#e05c1a" font-family="Arial">AB = 8</text>
  <path d="M160,96 Q210,115 260,96" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="185" y="126" font-size="13" fill="#1a3a5c" font-family="Arial">BC = 12</text>
  <path d="M60,140 Q160,158 260,140" fill="none" stroke="#666" stroke-width="1.5"/>
  <text x="128" y="168" font-size="13" fill="#666" font-family="Arial">AC = 20</text>
</svg>

</div>
</div>

---

## Midpoint & Distance Formulas

<div class="columns">
<div>

**Midpoint Formula**
$$M = \left(\frac{x_1+x_2}{2},\, \frac{y_1+y_2}{2}\right)$$

**Distance Formula** (from Pythagorean Theorem)
$$d = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2}$$

> **Example:** $A(2,5)$ and $B(8,1)$
>
> $M = \left(\frac{2+8}{2},\frac{5+1}{2}\right) = (5,3)$
>
> $d = \sqrt{6^2+4^2} = \sqrt{52} \approx 7.2$

**Why it works:** The horizontal and vertical distances form legs of a right triangle; $d$ is the hypotenuse.

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <line x1="30" y1="230" x2="270" y2="230" stroke="#bbb" stroke-width="1.5"/>
  <line x1="30" y1="230" x2="30" y2="20" stroke="#bbb" stroke-width="1.5"/>
  <polygon points="270,230 258,224 258,236" fill="#bbb"/>
  <polygon points="30,20 24,32 36,32" fill="#bbb"/>
  <text x="272" y="234" font-size="12" fill="#888" font-family="Arial">x</text>
  <text x="22" y="18" font-size="12" fill="#888" font-family="Arial">y</text>
  <text x="72" y="244" font-size="11" fill="#999" font-family="Arial">2</text>
  <text x="152" y="244" font-size="11" fill="#999" font-family="Arial">5</text>
  <text x="222" y="244" font-size="11" fill="#999" font-family="Arial">8</text>
  <circle cx="76" cy="130" r="7" fill="#e05c1a"/>
  <circle cx="226" cy="190" r="7" fill="#e05c1a"/>
  <text x="50" y="125" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">A(2,5)</text>
  <text x="230" y="186" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">B(8,1)</text>
  <line x1="76" y1="130" x2="226" y2="190" stroke="#1a3a5c" stroke-width="2.5" stroke-dasharray="7,3"/>
  <circle cx="151" cy="160" r="7" fill="#1a3a5c"/>
  <text x="158" y="153" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">M(5,3)</text>
  <line x1="76" y1="190" x2="226" y2="190" stroke="#ddd" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="76" y1="130" x2="76" y2="190" stroke="#ddd" stroke-width="1.5" stroke-dasharray="4,3"/>
  <rect x="76" y="180" width="12" height="12" fill="none" stroke="#ccc" stroke-width="1.2"/>
  <text x="135" y="210" font-size="12" fill="#aaa" font-family="Arial">Δx = 6</text>
  <text x="42" y="165" font-size="12" fill="#aaa" font-family="Arial">Δy=4</text>
</svg>

</div>
</div>

---

## Angles & the Protractor Postulate

<div class="columns">
<div>

An **angle** is formed by two rays (sides) sharing a common endpoint (**vertex**).

**Postulate 1-7 (Protractor):** Every angle has a unique measure from 0° to 180°.

| Type | Measure |
|------|---------|
| Acute | $0° < m < 90°$ |
| Right | $m = 90°$ |
| Obtuse | $90° < m < 180°$ |
| Straight | $m = 180°$ |

**Postulate 1-8 (Angle Addition):** If ray $BD$ is in the interior of $\angle ABC$:
$$m\angle ABD + m\angle DBC = m\angle ABC$$

</div>
<div>

<svg width="300" height="270" viewBox="0 0 300 270" xmlns="http://www.w3.org/2000/svg">
  <line x1="30" y1="75" x2="120" y2="75" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="30" y1="75" x2="75" y2="25" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M75,75 A45,45 0 0,0 56,43" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="74" y="66" font-size="13" fill="#e05c1a" font-family="Arial">45°</text>
  <text x="24" y="92" font-size="12" fill="#555" font-family="Arial">Acute</text>
  <line x1="160" y1="75" x2="260" y2="75" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="160" y1="75" x2="160" y2="15" stroke="#1a3a5c" stroke-width="2"/>
  <rect x="160" y="57" width="16" height="16" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="152" y="92" font-size="12" fill="#555" font-family="Arial">Right 90°</text>
  <line x1="30" y1="175" x2="160" y2="175" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="30" y1="175" x2="10" y2="128" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M90,175 A60,60 0 0,0 16,148" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="42" y="163" font-size="13" fill="#e05c1a" font-family="Arial">120°</text>
  <text x="24" y="192" font-size="12" fill="#555" font-family="Arial">Obtuse</text>
  <line x1="170" y1="230" x2="280" y2="230" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="170" y1="230" x2="225" y2="175" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="170" y1="230" x2="204" y2="175" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <text x="195" y="213" font-size="11" fill="#1a3a5c" font-family="Arial">A</text>
  <text x="215" y="213" font-size="11" fill="#e05c1a" font-family="Arial">D</text>
  <text x="164" y="246" font-size="11" fill="#555" font-family="Arial">∠ABD + ∠DBA = ∠ABC</text>
</svg>

</div>
</div>

---

## Angle Pairs

<div class="columns">
<div>

**Complementary** — two angles summing to 90°
**Supplementary** — two angles summing to 180°
**Linear pair** — adjacent angles forming a straight line (supplementary)
**Vertical angles** — opposite angles formed by two intersecting lines

> **Theorem 1-1:** Vertical angles are **congruent**.
>
> **Why:** Both $\angle 1$ and $\angle 3$ are supplementary to $\angle 2$, so they must be equal.

> **Theorem 1-2:** Linear pair angles are supplementary.

</div>
<div>

<svg width="300" height="270" viewBox="0 0 300 270" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="80" x2="105" y2="80" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="20" y1="80" x2="55" y2="22" stroke="#1a3a5c" stroke-width="2"/>
  <rect x="20" y="62" width="15" height="15" fill="none" stroke="#bbb" stroke-width="1"/>
  <path d="M55,80 A35,35 0 0,0 36,48" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="50" y="72" font-size="12" fill="#e05c1a" font-family="Arial">55°</text>
  <text x="22" y="60" font-size="11" fill="#888" font-family="Arial">35°</text>
  <text x="18" y="98" font-size="12" fill="#555" font-family="Arial">Complementary = 90°</text>
  <line x1="20" y1="160" x2="145" y2="160" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="63" y1="160" x2="93" y2="110" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M40" fill="none"/><path d="M43,160 A23,23 0 0,0 32,139" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M82,160 A23,23 0 0,1 90,138" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <text x="26" y="152" font-size="12" fill="#e05c1a" font-family="Arial">130°</text>
  <text x="82" y="148" font-size="12" fill="#1a3a5c" font-family="Arial">50°</text>
  <text x="18" y="178" font-size="12" fill="#555" font-family="Arial">Supplementary = 180°</text>
  <line x1="170" y1="60" x2="280" y2="195" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="280" y1="60" x2="170" y2="195" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="225" cy="128" r="4" fill="#1a3a5c"/>
  <path d="M238,128 A13,13 0 0,0 231,115" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M212,128 A13,13 0 0,1 219,141" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M225,115 A13,13 0 0,0 212,120" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <path d="M225,141 A13,13 0 0,1 238,136" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="241" y="114" font-size="12" fill="#e05c1a" font-family="Arial" font-weight="bold">∠1</text>
  <text x="198" y="148" font-size="12" fill="#e05c1a" font-family="Arial" font-weight="bold">∠3</text>
  <text x="198" y="116" font-size="12" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠2</text>
  <text x="232" y="148" font-size="12" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠4</text>
  <text x="168" y="218" font-size="12" fill="#555" font-family="Arial">∠1≅∠3 (vertical)</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 1 — Segment Midpoint

**Problem:** $M$ is the midpoint of $\overline{AB}$. $AM = 3x + 7$ and $MB = 5x - 3$. Find $AB$.

<div class="columns">
<div>

**Step 1:** Midpoint means $AM = MB$.
$$3x + 7 = 5x - 3$$

**Step 2:** Solve for $x$.
$$10 = 2x \;\Rightarrow\; x = 5$$

**Step 3:** Substitute.
$$AM = 3(5)+7 = 22, \quad MB = 5(5)-3 = 22\checkmark$$

**Step 4:** $AB = AM + MB = 22 + 22 = \boxed{44}$

</div>
<div>

<svg width="300" height="150" viewBox="0 0 300 150" xmlns="http://www.w3.org/2000/svg">
  <line x1="30" y1="75" x2="270" y2="75" stroke="#1a3a5c" stroke-width="3"/>
  <circle cx="30" cy="75" r="7" fill="#e05c1a"/>
  <circle cx="150" cy="75" r="7" fill="#1a3a5c"/>
  <circle cx="270" cy="75" r="7" fill="#e05c1a"/>
  <text x="22" y="58" font-size="15" fill="#e05c1a" font-family="Arial" font-weight="bold">A</text>
  <text x="143" y="58" font-size="15" fill="#1a3a5c" font-family="Arial" font-weight="bold">M</text>
  <text x="263" y="58" font-size="15" fill="#e05c1a" font-family="Arial" font-weight="bold">B</text>
  <path d="M30,96 Q90,115 150,96" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="62" y="125" font-size="13" fill="#e05c1a" font-family="Arial">3x + 7 = 22</text>
  <path d="M150,96 Q210,115 270,96" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="178" y="125" font-size="13" fill="#1a3a5c" font-family="Arial">5x − 3 = 22</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 2 — Vertical Angles

**Problem:** Two lines intersect. One angle is $(4x+10)°$, its vertical angle is $(6x-20)°$. Find all four angles.

<div class="columns">
<div>

**Step 1:** Vertical angles are equal.
$$4x + 10 = 6x - 20 \;\Rightarrow\; x = 15$$

**Step 2:** Find the angle.
$$\angle 1 = \angle 3 = 4(15)+10 = \mathbf{70°}$$

**Step 3:** Linear pair.
$$\angle 2 = \angle 4 = 180°-70° = \mathbf{110°}$$

**Check:** $70° + 110° = 180°$ ✓

</div>
<div>

<svg width="270" height="230" viewBox="0 0 270 230" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="45" x2="250" y2="185" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="250" y1="45" x2="20" y2="185" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="135" cy="115" r="5" fill="#1a3a5c"/>
  <path d="M150,115 A15,15 0 0,0 143,100" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <path d="M120,115 A15,15 0 0,1 127,130" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <path d="M135,100 A15,15 0 0,0 120,107" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M135,130 A15,15 0 0,1 150,123" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <text x="155" y="103" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">70°</text>
  <text x="102" y="140" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">70°</text>
  <text x="100" y="104" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">110°</text>
  <text x="136" y="140" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">110°</text>
  <text x="25" y="215" font-size="12" fill="#555" font-family="Arial">Vertical ≅; Linear pair supplementary</text>
</svg>

</div>
</div>

---

## Chapter 1 — Theorem Summary

| Result | Statement |
|--------|-----------|
| **Seg. Addition** | $B$ between $A,C \Rightarrow AB + BC = AC$ |
| **Angle Addition** | $D$ in int. $\angle ABC \Rightarrow m\angle ABD + m\angle DBC = m\angle ABC$ |
| **Midpoint** | $M = \!\left(\tfrac{x_1+x_2}{2}, \tfrac{y_1+y_2}{2}\right)$ |
| **Distance** | $d = \sqrt{(x_2-x_1)^2+(y_2-y_1)^2}$ |
| **Thm 1-1** | Vertical angles are congruent |
| **Thm 1-2** | Linear pair angles are supplementary |
| **Thm 1-3** | Non-right angles forming a right angle are complementary |

> **Key idea:** The distance formula is the Pythagorean theorem in disguise — $\Delta x$ and $\Delta y$ are the legs, $d$ is the hypotenuse.
