---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 6
## Proportions & Similarity

McGraw Hill Glencoe Geometry · Texas Edition

---

## Ratios & Proportions

<div class="columns">
<div>

A **ratio** compares two quantities: $\dfrac{a}{b}$ or $a : b$

A **proportion** is an equation stating two ratios are equal:
$$\frac{a}{b} = \frac{c}{d}$$

**Cross-Products Property:**
$$\frac{a}{b} = \frac{c}{d} \;\Rightarrow\; ad = bc$$

**Properties of Proportions:**

| Property | Form |
|----------|------|
| Reciprocal | $\frac{a}{b} = \frac{c}{d} \Rightarrow \frac{b}{a} = \frac{d}{c}$ |
| Exchange means | $\frac{a}{b} = \frac{c}{d} \Rightarrow \frac{a}{c} = \frac{b}{d}$ |
| Addition | $\frac{a}{b} = \frac{c}{d} \Rightarrow \frac{a+b}{b} = \frac{c+d}{d}$ |

> **Example:** $\frac{x}{6} = \frac{10}{15} \;\Rightarrow\; 15x = 60 \;\Rightarrow\; x = 4$

</div>
<div>

<svg width="290" height="220" viewBox="0 0 290 220" xmlns="http://www.w3.org/2000/svg">
  <!-- Visual proportion bars -->
  <rect x="20" y="30" width="100" height="30" rx="5" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <text x="70" y="52" font-size="14" fill="#1a3a5c" font-family="Arial" text-anchor="middle" font-weight="bold">a = 6</text>
  <rect x="20" y="70" width="160" height="30" rx="5" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <text x="100" y="92" font-size="14" fill="#1a3a5c" font-family="Arial" text-anchor="middle">b = ?</text>
  <rect x="200" y="30" width="75" height="30" rx="5" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="237" y="52" font-size="14" fill="#e05c1a" font-family="Arial" text-anchor="middle">c = 10</text>
  <rect x="200" y="70" width="75" height="30" rx="5" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="237" y="92" font-size="14" fill="#e05c1a" font-family="Arial" text-anchor="middle">d = 15</text>
  <text x="145" y="52" font-size="20" fill="#555" font-family="Arial">=</text>
  <text x="145" y="92" font-size="20" fill="#555" font-family="Arial">=</text>
  <!-- Cross products -->
  <line x1="70" y1="105" x2="237" y2="135" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="237" y1="105" x2="70" y2="135" stroke="#1a3a5c" stroke-width="1.5" stroke-dasharray="4,3"/>
  <text x="105" y="160" font-size="13" fill="#1a3a5c" font-family="Arial">Cross products: ad = bc</text>
  <text x="105" y="185" font-size="13" fill="#555" font-family="Arial">6 × 15 = 90 = b × 10</text>
  <text x="105" y="205" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">b = 9</text>
</svg>

</div>
</div>

---

## Similar Polygons

Two polygons are **similar** ($\sim$) if:
1. All corresponding angles are congruent
2. All corresponding sides are proportional

<div class="columns">
<div>

The ratio of corresponding sides is the **scale factor** $k$.

$$\triangle ABC \sim \triangle DEF \;\Rightarrow\; \frac{AB}{DE} = \frac{BC}{EF} = \frac{CA}{FD} = k$$

**Perimeters** scale by $k$.
**Areas** scale by $k^2$.

> **Example:** Scale factor $k = \frac{3}{2}$.
> If $\triangle ABC$ has perimeter 18, then $\triangle DEF$ has perimeter $18 \times \frac{3}{2} = 27$.
> If area of $\triangle ABC = 20$, area of $\triangle DEF = 20 \times \left(\frac{3}{2}\right)^2 = 45$.

</div>
<div>

<svg width="290" height="250" viewBox="0 0 290 250" xmlns="http://www.w3.org/2000/svg">
  <!-- Small triangle -->
  <polygon points="30,170 110,170 70,80" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="18" y="188" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="112" y="188" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="62" y="73" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="60" y="185" font-size="12" fill="#1a3a5c" font-family="Arial">6</text>
  <text x="26" y="130" font-size="12" fill="#1a3a5c" font-family="Arial">5</text>
  <text x="95" y="130" font-size="12" fill="#1a3a5c" font-family="Arial">4</text>
  <!-- Large triangle -->
  <polygon points="155,205 245,205 200,80" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="143" y="223" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">D</text>
  <text x="247" y="223" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">E</text>
  <text x="192" y="73" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">F</text>
  <text x="193" y="222" font-size="12" fill="#e05c1a" font-family="Arial">9</text>
  <text x="154" y="152" font-size="12" fill="#e05c1a" font-family="Arial">7.5</text>
  <text x="228" y="152" font-size="12" fill="#e05c1a" font-family="Arial">6</text>
  <!-- Scale factor -->
  <text x="80" y="248" font-size="13" fill="#555" font-family="Arial">k = 9/6 = 6/4 = 7.5/5 = 3/2</text>
</svg>

</div>
</div>

---

## AA, SSS, and SAS Similarity

<div class="columns">
<div>

**Postulate 6-1 — AA Similarity**
If two angles of one triangle are congruent to two angles of another, the triangles are similar.

> Why only 2 angles? The third is determined: $180° -$ (sum of first two).

**Theorem 6-1 — SSS Similarity**
If all three pairs of sides are proportional, the triangles are similar.

**Theorem 6-2 — SAS Similarity**
If two sides are proportional and the included angles are congruent, the triangles are similar.

> **Note:** These similarity shortcuts parallel the congruence shortcuts — but proportional sides instead of equal sides.

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- AA label -->
  <text x="10" y="20" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">AA Similarity</text>
  <polygon points="20,95 120,95 70,25" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="160,95 260,95 210,25" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <!-- Angle marks -->
  <path d="M34,95 A16,16 0 0,0 29,80" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M174,95 A16,16 0 0,0 169,80" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M106,95 A16,16 0 0,1 111,80" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M246,95 A16,16 0 0,1 251,80" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="128" y="65" font-size="18" fill="#555" font-family="Arial" font-weight="bold">∼</text>
  <!-- SSS Similarity -->
  <text x="10" y="130" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">SSS Similarity</text>
  <polygon points="20,215 100,215 60,145" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="150,215 250,215 200,145" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="50" y="225" font-size="12" fill="#1a3a5c" font-family="Arial">6</text>
  <text x="26" y="185" font-size="12" fill="#1a3a5c" font-family="Arial">4</text>
  <text x="192" y="225" font-size="12" fill="#e05c1a" font-family="Arial">9</text>
  <text x="150" y="185" font-size="12" fill="#e05c1a" font-family="Arial">6</text>
  <text x="108" y="183" font-size="12" fill="#555" font-family="Arial">6/9 = 4/6 ✓</text>
  <text x="108" y="200" font-size="18" fill="#555" font-family="Arial">∼</text>
</svg>

</div>
</div>

---

## Triangle Proportionality Theorem

<div class="columns">
<div>

**Theorem 6-3 (Triangle Proportionality):**
If a line is parallel to one side of a triangle and intersects the other two sides, it divides them proportionally.

$$DE \parallel BC \;\Rightarrow\; \frac{AD}{DB} = \frac{AE}{EC}$$

**Theorem 6-4 (Converse):** If a line divides two sides of a triangle proportionally, it is parallel to the third side.

**Theorem 6-5 (Midsegment):**
The midsegment of a triangle:
- Connects midpoints of two sides
- Is parallel to the third side
- Is half as long as the third side

$$DE = \frac{1}{2} BC$$

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Main triangle -->
  <polygon points="145,20 20,240 270,240" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Parallel line DE inside -->
  <line x1="70" y1="130" x2="220" y2="130" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Points D and E on sides -->
  <circle cx="70" cy="130" r="5" fill="#e05c1a"/>
  <circle cx="220" cy="130" r="5" fill="#e05c1a"/>
  <!-- Labels -->
  <text x="138" y="14" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="6" y="255" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="272" y="255" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="55" y="125" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">D</text>
  <text x="224" y="125" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">E</text>
  <!-- Segment labels -->
  <text x="22" y="82" font-size="12" fill="#1a3a5c" font-family="Arial">AD</text>
  <text x="22" y="195" font-size="12" fill="#1a3a5c" font-family="Arial">DB</text>
  <text x="245" y="82" font-size="12" fill="#1a3a5c" font-family="Arial">AE</text>
  <text x="245" y="195" font-size="12" fill="#1a3a5c" font-family="Arial">EC</text>
  <!-- Parallel marks -->
  <line x1="140" y1="125" x2="150" y2="135" stroke="#e05c1a" stroke-width="2"/>
  <line x1="140" y1="235" x2="150" y2="245" stroke="#1a3a5c" stroke-width="2"/>
  <text x="30" y="268" font-size="12" fill="#555" font-family="Arial">AD/DB = AE/EC (proportional)</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 1 — Finding Unknown Sides

**Given:** $\triangle ABC \sim \triangle DEF$. $AB = 8$, $BC = 12$, $DE = 6$. Find $EF$.

<div class="columns">
<div>

**Step 1:** Identify the scale factor.
$$k = \frac{DE}{AB} = \frac{6}{8} = \frac{3}{4}$$

**Step 2:** Apply the scale factor to $BC$.
$$EF = k \cdot BC = \frac{3}{4} \cdot 12 = \mathbf{9}$$

**Bonus:** Find the ratio of areas.
$$\frac{\text{Area}(\triangle DEF)}{\text{Area}(\triangle ABC)} = k^2 = \left(\frac{3}{4}\right)^2 = \frac{9}{16}$$

</div>
<div>

<svg width="280" height="200" viewBox="0 0 280 200" xmlns="http://www.w3.org/2000/svg">
  <polygon points="30,170 170,170 100,40" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="18" y="188" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="172" y="188" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="93" y="33" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="91" y="185" font-size="13" fill="#1a3a5c" font-family="Arial">BC=12</text>
  <text x="33" y="110" font-size="13" fill="#1a3a5c" font-family="Arial">AB=8</text>
  <polygon points="190,170 280,170 235,75" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="178" y="188" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">D</text>
  <text x="282" y="188" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">E</text>
  <text x="228" y="68" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">F</text>
  <text x="225" y="185" font-size="13" fill="#e05c1a" font-family="Arial">EF=9</text>
  <text x="182" y="127" font-size="13" fill="#e05c1a" font-family="Arial">DE=6</text>
  <text x="80" y="15" font-size="12" fill="#555" font-family="Arial">k = 6/8 = 3/4</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 2 — Midsegment

**$D$ and $E$ are midpoints of $\overline{AB}$ and $\overline{AC}$ respectively. $BC = 28$. Find $DE$.**

<div class="columns">
<div>

**Midsegment Theorem:** $DE \parallel BC$ and $DE = \frac{1}{2} BC$

$$DE = \frac{1}{2} \cdot 28 = \mathbf{14}$$

**Extension:** If $AD = 5$, find $DB$.
Since $D$ is the midpoint: $DB = AD = 5$

**Extension 2:** Verify proportionality:
$$\frac{AD}{AB} = \frac{5}{10} = \frac{1}{2} = \frac{DE}{BC} = \frac{14}{28}\; \checkmark$$

</div>
<div>

<svg width="270" height="220" viewBox="0 0 270 220" xmlns="http://www.w3.org/2000/svg">
  <polygon points="135,20 20,200 250,200" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="78" cy="110" r="6" fill="#e05c1a"/>
  <circle cx="193" cy="110" r="6" fill="#e05c1a"/>
  <line x1="78" y1="110" x2="193" y2="110" stroke="#e05c1a" stroke-width="3"/>
  <text x="128" y="14" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="6" y="215" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="252" y="215" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="55" y="108" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">D</text>
  <text x="198" y="108" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">E</text>
  <!-- Midpoint marks -->
  <line x1="46" y1="62" x2="50" y2="58" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="48" y1="66" x2="52" y2="62" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="104" y1="58" x2="108" y2="62" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="106" y1="62" x2="110" y2="66" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="108" y="107" font-size="13" fill="#e05c1a" font-family="Arial">DE=14</text>
  <text x="108" y="208" font-size="13" fill="#1a3a5c" font-family="Arial">BC=28</text>
  <text x="15" y="240" font-size="12" fill="#555" font-family="Arial">Midsegment = ½ × base</text>
</svg>

</div>
</div>

---

## Chapter 6 — Summary

| Result | Statement |
|--------|-----------|
| **Cross-Product** | $\frac{a}{b}=\frac{c}{d} \Rightarrow ad=bc$ |
| **AA Similarity** | 2 ≅ angles → triangles similar |
| **SSS Similarity** | All 3 side ratios equal → similar |
| **SAS Similarity** | 2 proportional sides + included ∠ ≅ → similar |
| **Scale factor $k$** | Perimeters scale by $k$; areas scale by $k^2$ |
| **Proportionality Thm** | $DE \parallel BC$ → sides divided proportionally |
| **Midsegment** | Midpt-to-midpt segment $= \frac{1}{2}$ × parallel side |
| **Angle Bisector** | Divides opposite side in ratio of the adjacent sides |

> **Key insight:** Similarity is about shape; congruence is about shape *and* size. A scale factor of 1 makes them identical (congruent).
