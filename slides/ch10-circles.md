---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 10
## Circles

McGraw Hill Glencoe Geometry · Texas Edition

---

## Circle Vocabulary

<div class="columns">
<div>

A **circle** is the set of all points equidistant from a center $O$. The distance is the **radius** $r$.

| Term | Definition |
|------|-----------|
| **Radius** | Segment from center to circle |
| **Diameter** | Chord through center; $d = 2r$ |
| **Chord** | Segment with both endpoints on circle |
| **Secant** | Line intersecting circle at 2 points |
| **Tangent** | Line touching circle at exactly 1 point |
| **Arc** | Part of the circle |
| **Central angle** | Vertex at center |
| **Inscribed angle** | Vertex on circle |

</div>
<div>

<svg width="300" height="280" viewBox="0 0 300 280" xmlns="http://www.w3.org/2000/svg">
  <!-- Circle -->
  <circle cx="150" cy="145" r="100" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Center -->
  <circle cx="150" cy="145" r="4" fill="#1a3a5c"/>
  <text x="155" y="142" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">O</text>
  <!-- Radius -->
  <line x1="150" y1="145" x2="220" y2="80" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="194" y="98" font-size="12" fill="#e05c1a" font-family="Arial" font-weight="bold">r</text>
  <!-- Diameter -->
  <line x1="50" y1="145" x2="250" y2="145" stroke="#1a3a5c" stroke-width="2" stroke-dasharray="5,3"/>
  <text x="140" y="162" font-size="12" fill="#1a3a5c" font-family="Arial">d = 2r</text>
  <!-- Chord (non-diameter) -->
  <line x1="80" y1="80" x2="220" y2="210" stroke="#555" stroke-width="2"/>
  <text x="62" y="75" font-size="12" fill="#555" font-family="Arial">chord</text>
  <!-- Tangent -->
  <line x1="50" y1="245" x2="250" y2="245" stroke="#e05c1a" stroke-width="2.5"/>
  <circle cx="150" cy="245" r="4" fill="#e05c1a"/>
  <line x1="150" y1="145" x2="150" y2="245" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <rect x="142" y="237" width="16" height="16" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="255" y="248" font-size="12" fill="#e05c1a" font-family="Arial">tangent</text>
</svg>

</div>
</div>

---

## Arc Measures & Central Angles

<div class="columns">
<div>

The **measure** of an arc equals its **central angle**.

| Arc | Definition | Measure |
|-----|-----------|---------|
| Minor arc $\stackrel{\frown}{AB}$ | Shorter arc | $< 180°$ |
| Major arc $\stackrel{\frown}{ACB}$ | Longer arc | $> 180°$ |
| Semicircle | Half the circle | $= 180°$ |

**Arc Addition Postulate:**
$$m\stackrel{\frown}{ABC} = m\stackrel{\frown}{AB} + m\stackrel{\frown}{BC}$$

> **Example:** Central angle $\angle AOB = 70°$.
> Minor arc $\stackrel{\frown}{AB} = 70°$
> Major arc $\stackrel{\frown}{ACB} = 360° - 70° = 290°$

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <circle cx="145" cy="130" r="105" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="145" cy="130" r="4" fill="#1a3a5c"/>
  <text x="150" y="128" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">O</text>
  <!-- Radii OA and OB for 70° central angle -->
  <line x1="145" y1="130" x2="230" y2="50" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="145" y1="130" x2="240" y2="175" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Points A and B -->
  <circle cx="230" cy="50" r="5" fill="#e05c1a"/>
  <circle cx="240" cy="175" r="5" fill="#e05c1a"/>
  <text x="234" y="46" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">A</text>
  <text x="244" y="180" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">B</text>
  <!-- Central angle arc -->
  <path d="M210,68 A55,55 0 0,1 222,163" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="228" y="120" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">70°</text>
  <!-- Minor arc label -->
  <text x="248" y="112" font-size="12" fill="#1a3a5c" font-family="Arial">minor arc</text>
  <text x="245" y="126" font-size="12" fill="#1a3a5c" font-family="Arial">AB = 70°</text>
  <!-- Major arc -->
  <path d="M230,50 A105,105 0 1,0 240,175" fill="none" stroke="#555" stroke-width="2" stroke-dasharray="6,3"/>
  <text x="15" y="138" font-size="12" fill="#555" font-family="Arial">major arc</text>
  <text x="15" y="153" font-size="12" fill="#555" font-family="Arial">= 290°</text>
</svg>

</div>
</div>

---

## Tangent & Inscribed Angle Theorems

<div class="columns">
<div>

**Theorem 10-1:** A tangent to a circle is perpendicular to the radius at the point of tangency.

**Theorem 10-2:** Two tangents from an external point are congruent.

**Theorem 10-3 (Inscribed Angle):** An inscribed angle measures **half** its intercepted arc.
$$m\angle ABC = \frac{1}{2} m\stackrel{\frown}{AC}$$

**Corollary 10-1:** Inscribed angles that intercept the same arc are congruent.

**Corollary 10-2:** An inscribed angle in a semicircle measures **90°**.

**Theorem 10-4:** Opposite angles of an inscribed quadrilateral are supplementary.

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <circle cx="145" cy="140" r="100" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="145" cy="140" r="4" fill="#1a3a5c"/>
  <text x="150" y="138" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">O</text>
  <!-- Tangent from external point P -->
  <circle cx="260" cy="220" r="5" fill="#555"/>
  <text x="263" y="222" font-size="13" fill="#555" font-family="Arial">P</text>
  <line x1="260" y1="220" x2="200" y2="60" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="260" y1="220" x2="50" y2="190" stroke="#e05c1a" stroke-width="2.5"/>
  <circle cx="200" cy="60" r="5" fill="#e05c1a"/>
  <circle cx="50" cy="190" r="5" fill="#e05c1a"/>
  <text x="204" y="56" font-size="12" fill="#e05c1a" font-family="Arial">T₁</text>
  <text x="32" y="192" font-size="12" fill="#e05c1a" font-family="Arial">T₂</text>
  <text x="200" y="245" font-size="12" fill="#e05c1a" font-family="Arial">PT₁ = PT₂ (Thm 10-2)</text>
  <!-- Inscribed angle -->
  <circle cx="60" cy="80" r="5" fill="#1a3a5c"/>
  <text x="44" y="78" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <line x1="60" y1="80" x2="200" y2="60" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="60" y1="80" x2="50" y2="190" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M78,90 A22,22 0 0,1 72,113" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <text x="82" y="108" font-size="12" fill="#1a3a5c" font-family="Arial">∠B</text>
  <text x="15" y="258" font-size="12" fill="#555" font-family="Arial">∠B = ½ arc T₁T₂ (inscribed ∠)</text>
</svg>

</div>
</div>

---

## Angle Formed by Chords, Secants & Tangents

<div class="columns">
<div>

| Angle formed by | Measure |
|----------------|---------|
| **2 chords** (inside) | $\frac{1}{2}(\text{arc}_1 + \text{arc}_2)$ |
| **2 secants** (outside) | $\frac{1}{2}(\text{far arc} - \text{near arc})$ |
| **tangent & chord** | $\frac{1}{2}(\text{intercepted arc})$ |
| **2 tangents** (outside) | $\frac{1}{2}(\text{major} - \text{minor arc})$ |

> **Mnemonic:** "Inside = add the arcs; outside = subtract the arcs (far − near), then halve."

> **Example (inside):** Two chords intersect. The intercepted arcs are 80° and 40°.
> $m\angle = \frac{1}{2}(80° + 40°) = \mathbf{60°}$

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Circle with two chords intersecting inside -->
  <circle cx="145" cy="130" r="100" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Chord 1: A to C -->
  <line x1="60" y1="60" x2="230" y2="200" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Chord 2: B to D -->
  <line x1="210" y1="50" x2="60" y2="200" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Intersection point -->
  <circle cx="135" cy="130" r="5" fill="#555"/>
  <text x="139" y="128" font-size="13" fill="#555" font-family="Arial" font-weight="bold">E</text>
  <!-- Angle arc -->
  <path d="M148,125 A14,14 0 0,0 140,116" fill="none" stroke="#555" stroke-width="2"/>
  <text x="150" y="118" font-size="12" fill="#555" font-family="Arial">∠</text>
  <!-- Endpoint labels -->
  <text x="46" y="58" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="231" y="205" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="213" y="48" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">B</text>
  <text x="44" y="205" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">D</text>
  <!-- Arc labels -->
  <text x="200" y="95" font-size="12" fill="#1a3a5c" font-family="Arial">arc AC = 80°</text>
  <text x="35" y="140" font-size="12" fill="#e05c1a" font-family="Arial">arc BD = 40°</text>
  <text x="30" y="248" font-size="13" fill="#555" font-family="Arial">∠AEB = ½(80°+40°) = 60°</text>
</svg>

</div>
</div>

---

## Segment Length Theorems

<div class="columns">
<div>

**Theorem 10-8 — Two Chords inside:**
$$EA \cdot EB = EC \cdot ED$$

**Theorem 10-9 — Two Secants from outside:**
$$PA \cdot PB = PC \cdot PD$$

**Theorem 10-10 — Secant & Tangent from outside:**
$$t^2 = PA \cdot PB$$

> **Why same-side products equal:** All three are derived from similar triangles formed by the intersecting lines inside or outside the circle.

> **Example (chords):** $EA = 4$, $EB = 9$, $EC = 6$. Find $ED$.
> $4 \times 9 = 6 \times ED$
> $ED = 6$

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Circle -->
  <circle cx="145" cy="130" r="95" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Two chords intersecting at E -->
  <line x1="60" y1="70" x2="240" y2="185" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="55" y1="185" x2="235" y2="70" stroke="#e05c1a" stroke-width="2.5"/>
  <circle cx="147" cy="128" r="5" fill="#555"/>
  <text x="152" y="126" font-size="13" fill="#555" font-family="Arial" font-weight="bold">E</text>
  <!-- Labels on the chord segments -->
  <text x="82" y="84" font-size="12" fill="#1a3a5c" font-family="Arial">A  EA=4</text>
  <text x="196" y="185" font-size="12" fill="#1a3a5c" font-family="Arial">B  EB=9</text>
  <text x="68" y="184" font-size="12" fill="#e05c1a" font-family="Arial">C  EC=6</text>
  <text x="196" y="80" font-size="12" fill="#e05c1a" font-family="Arial">D  ED=?</text>
  <!-- Formula -->
  <rect x="20" y="218" width="250" height="35" rx="6" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="145" y="233" font-size="13" fill="#1a3a5c" font-family="Arial" text-anchor="middle">EA · EB = EC · ED</text>
  <text x="145" y="249" font-size="13" fill="#e05c1a" font-family="Arial" text-anchor="middle">4 × 9 = 6 × 6  ✓</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example — Inscribed Angle & Arcs

**Circle $O$ has inscribed angle $\angle BAC = 35°$. Find arc $BC$, arc $BAC$, and $\angle BDC$ if $D$ is another point on the major arc.**

<div class="columns">
<div>

**Step 1:** Inscribed angle = half its intercepted arc.
$$m\stackrel{\frown}{BC} = 2 \times m\angle BAC = 2 \times 35° = \mathbf{70°}$$

**Step 2:** Find major arc.
$$m\stackrel{\frown}{BAC} = 360° - 70° = \mathbf{290°}$$

**Step 3:** $\angle BDC$ also intercepts arc $BC$ (same arc).
$$m\angle BDC = \frac{1}{2} \times 70° = \mathbf{35°}$$

(Corollary 10-1: inscribed angles intercepting same arc are congruent.)

</div>
<div>

<svg width="270" height="250" viewBox="0 0 270 250" xmlns="http://www.w3.org/2000/svg">
  <circle cx="135" cy="125" r="100" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="135" cy="125" r="4" fill="#1a3a5c"/>
  <text x="140" y="123" font-size="12" fill="#1a3a5c" font-family="Arial" font-weight="bold">O</text>
  <!-- Points A, B, C, D on circle -->
  <circle cx="50" cy="125" r="5" fill="#e05c1a"/>
  <circle cx="165" cy="32" r="5" fill="#e05c1a"/>
  <circle cx="225" cy="175" r="5" fill="#e05c1a"/>
  <circle cx="80" cy="215" r="5" fill="#1a3a5c"/>
  <text x="30" y="125" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">A</text>
  <text x="168" y="28" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">B</text>
  <text x="228" y="178" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">C</text>
  <text x="63" y="218" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">D</text>
  <!-- Angle BAC -->
  <line x1="50" y1="125" x2="165" y2="32" stroke="#e05c1a" stroke-width="2"/>
  <line x1="50" y1="125" x2="225" y2="175" stroke="#e05c1a" stroke-width="2"/>
  <path d="M70,120 A20,20 0 0,0 65,106" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="72" y="108" font-size="12" fill="#e05c1a" font-family="Arial">35°</text>
  <!-- Arc BC label -->
  <path d="M165,32 A100,100 0 0,1 225,175" fill="none" stroke="#1a3a5c" stroke-width="3"/>
  <text x="218" y="95" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">70°</text>
  <!-- Angle BDC (same intercepted arc) -->
  <line x1="80" y1="215" x2="165" y2="32" stroke="#555" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="80" y1="215" x2="225" y2="175" stroke="#555" stroke-width="1.5" stroke-dasharray="4,3"/>
</svg>

</div>
</div>

---

## Chapter 10 — Summary

| Theorem | Formula |
|---------|---------|
| **Tangent ⊥ Radius** | At point of tangency |
| **Two tangents** | $PT_1 = PT_2$ from same external point |
| **Inscribed angle** | $m\angle = \frac{1}{2} m\stackrel{\frown}{\text{arc}}$ |
| **Semicircle** | Inscribed angle = 90° |
| **Inscribed quad** | Opposite angles supplementary |
| **2 chords inside** | $m\angle = \frac{1}{2}(arc_1 + arc_2)$ |
| **2 secants outside** | $m\angle = \frac{1}{2}(far - near)$ |
| **Chord segments** | $EA \cdot EB = EC \cdot ED$ |
| **Secant-Tangent** | $t^2 = PA \cdot PB$ |

> **Key insight:** All circle angle theorems are ultimately derived from the inscribed angle theorem — central angle = arc, inscribed angle = half arc.
