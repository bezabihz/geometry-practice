---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 5 — Cheatsheet
# Relationships in Triangles

**Unit 2 | Glencoe Geometry TX 2015**

---

## Perpendicular Bisectors & Angle Bisectors

<svg width="950" height="310" viewBox="0 0 950 310" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Perpendicular Bisector -->
  <rect x="10" y="10" width="450" height="290" rx="8" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <text x="235" y="32" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Theorems 5-1 &amp; 5-2: Perpendicular Bisector</text>
  <!-- Segment AB -->
  <line x1="60" y1="160" x2="410" y2="160" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="60" cy="160" r="6" fill="#1a3a5c"/>
  <circle cx="410" cy="160" r="6" fill="#1a3a5c"/>
  <circle cx="235" cy="160" r="5" fill="#e05c1a"/>
  <text x="50" y="152" font-size="14" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="413" y="152" font-size="14" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="235" y="152" text-anchor="middle" font-size="11" fill="#e05c1a">midpt</text>
  <!-- Perpendicular bisector line -->
  <line x1="235" y1="40" x2="235" y2="280" stroke="#2a7a2a" stroke-width="2.5"/>
  <rect x="225" y="152" width="14" height="14" fill="none" stroke="#333" stroke-width="2"/>
  <!-- Point P on bisector -->
  <circle cx="235" cy="90" r="6" fill="#e05c1a"/>
  <text x="245" y="88" font-size="13" font-weight="bold" fill="#e05c1a">P</text>
  <!-- Equal distances PA and PB -->
  <line x1="235" y1="90" x2="60" y2="160" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="235" y1="90" x2="410" y2="160" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="5,3"/>
  <text x="125" y="112" font-size="12" fill="#e05c1a" font-weight="bold">PA</text>
  <text x="335" y="112" font-size="12" fill="#e05c1a" font-weight="bold">PB</text>
  <text x="235" y="300" text-anchor="middle" font-size="12" fill="#2a7a2a" font-weight="bold">P on perp. bisector ↔ PA = PB</text>

  <!-- Angle Bisector -->
  <rect x="490" y="10" width="450" height="290" rx="8" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="2"/>
  <text x="715" y="32" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">Theorems 5-3 &amp; 5-4: Angle Bisector</text>
  <!-- Angle with bisector -->
  <line x1="560" y1="220" x2="870" y2="220" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="560" y1="220" x2="715" y2="60" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="560" y1="220" x2="820" y2="80" stroke="#2a7a2a" stroke-width="2.5" stroke-dasharray="6,3"/>
  <!-- Angle arcs -->
  <path d="M 590,220 A 30,30 0 0 1 581,193" stroke="#e05c1a" fill="rgba(220,80,0,0.1)" stroke-width="2"/>
  <path d="M 581,193 A 30,30 0 0 1 575,167" stroke="#e05c1a" fill="rgba(220,80,0,0.1)" stroke-width="2"/>
  <!-- Point P on bisector -->
  <circle cx="715" cy="150" r="6" fill="#e05c1a"/>
  <text x="725" y="148" font-size="13" font-weight="bold" fill="#e05c1a">P</text>
  <!-- Perpendicular distances from P to both rays -->
  <line x1="715" y1="150" x2="636" y2="188" stroke="#cc3300" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="715" y1="150" x2="771" y2="196" stroke="#cc3300" stroke-width="1.5" stroke-dasharray="5,3"/>
  <text x="660" y="188" font-size="12" fill="#cc3300" font-weight="bold">d₁</text>
  <text x="755" y="192" font-size="12" fill="#cc3300" font-weight="bold">d₂</text>
  <text x="715" y="300" text-anchor="middle" font-size="12" fill="#2a7a2a" font-weight="bold">P on ∠ bisector ↔ d₁ = d₂ (equidistant from sides)</text>
</svg>

---

## The Four Triangle Centers

<svg width="950" height="340" viewBox="0 0 950 340" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- CIRCUMCENTER -->
  <g transform="translate(10,10)">
    <rect x="0" y="0" width="220" height="320" rx="8" fill="#d0e8ff" stroke="#1565C0" stroke-width="2"/>
    <text x="110" y="22" text-anchor="middle" font-size="13" font-weight="bold" fill="#1565C0">Circumcenter</text>
    <text x="110" y="38" text-anchor="middle" font-size="10" fill="#555">Perp. bisectors meet</text>
    <polygon points="110,55 30,220 190,220" fill="#e8f4ff" stroke="#1565C0" stroke-width="2"/>
    <!-- Perpendicular bisectors -->
    <line x1="110" y1="55" x2="110" y2="220" stroke="#1565C0" stroke-width="1" stroke-dasharray="4,2"/>
    <line x1="30" y1="220" x2="150" y2="137" stroke="#1565C0" stroke-width="1" stroke-dasharray="4,2"/>
    <line x1="190" y1="220" x2="70" y2="137" stroke="#1565C0" stroke-width="1" stroke-dasharray="4,2"/>
    <circle cx="110" cy="155" r="6" fill="#1565C0"/>
    <text x="118" y="150" font-size="11" fill="#1565C0" font-weight="bold">O</text>
    <!-- Circumscribed circle -->
    <circle cx="110" cy="155" r="68" fill="none" stroke="#1565C0" stroke-width="1.5" stroke-dasharray="6,3" opacity="0.7"/>
    <text x="110" y="260" text-anchor="middle" font-size="11" fill="#1565C0">Equidistant from</text>
    <text x="110" y="275" text-anchor="middle" font-size="11" fill="#1565C0">all 3 vertices</text>
    <text x="110" y="292" text-anchor="middle" font-size="10" fill="#555">Center of circumscribed ⊙</text>
    <text x="110" y="310" text-anchor="middle" font-size="10" fill="#555">Can be outside the △</text>
  </g>

  <!-- INCENTER -->
  <g transform="translate(245,10)">
    <rect x="0" y="0" width="220" height="320" rx="8" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="2"/>
    <text x="110" y="22" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">Incenter</text>
    <text x="110" y="38" text-anchor="middle" font-size="10" fill="#555">Angle bisectors meet</text>
    <polygon points="110,55 30,220 190,220" fill="#e8f8e8" stroke="#2a7a2a" stroke-width="2"/>
    <!-- Angle bisectors -->
    <line x1="110" y1="55" x2="110" y2="220" stroke="#2a7a2a" stroke-width="1" stroke-dasharray="4,2"/>
    <line x1="30" y1="220" x2="170" y2="120" stroke="#2a7a2a" stroke-width="1" stroke-dasharray="4,2"/>
    <line x1="190" y1="220" x2="50" y2="120" stroke="#2a7a2a" stroke-width="1" stroke-dasharray="4,2"/>
    <circle cx="110" cy="168" r="6" fill="#2a7a2a"/>
    <text x="118" y="163" font-size="11" fill="#2a7a2a" font-weight="bold">I</text>
    <!-- Inscribed circle -->
    <circle cx="110" cy="168" r="48" fill="none" stroke="#2a7a2a" stroke-width="1.5" stroke-dasharray="6,3" opacity="0.7"/>
    <text x="110" y="260" text-anchor="middle" font-size="11" fill="#2a7a2a">Equidistant from</text>
    <text x="110" y="275" text-anchor="middle" font-size="11" fill="#2a7a2a">all 3 sides</text>
    <text x="110" y="292" text-anchor="middle" font-size="10" fill="#555">Center of inscribed ⊙</text>
    <text x="110" y="310" text-anchor="middle" font-size="10" fill="#555">Always inside △</text>
  </g>

  <!-- CENTROID -->
  <g transform="translate(480,10)">
    <rect x="0" y="0" width="220" height="320" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
    <text x="110" y="22" text-anchor="middle" font-size="13" font-weight="bold" fill="#e05c1a">Centroid</text>
    <text x="110" y="38" text-anchor="middle" font-size="10" fill="#555">Medians meet</text>
    <polygon points="110,55 30,220 190,220" fill="#fff0d8" stroke="#e05c1a" stroke-width="2"/>
    <!-- Medians (vertex to opposite midpoint) -->
    <line x1="110" y1="55" x2="110" y2="220" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,2"/>
    <line x1="30" y1="220" x2="150" y2="137" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,2"/>
    <line x1="190" y1="220" x2="70" y2="137" stroke="#e05c1a" stroke-width="1.5" stroke-dasharray="4,2"/>
    <circle cx="110" cy="178" r="6" fill="#e05c1a"/>
    <text x="118" y="173" font-size="11" fill="#e05c1a" font-weight="bold">G</text>
    <!-- 2:1 ratio label -->
    <text x="110" y="254" text-anchor="middle" font-size="12" fill="#e05c1a" font-weight="bold">2:1 ratio</text>
    <text x="110" y="270" text-anchor="middle" font-size="11" fill="#555">Vertex to G = 2/3 median</text>
    <text x="110" y="286" text-anchor="middle" font-size="11" fill="#555">G to midpoint = 1/3 median</text>
    <text x="110" y="302" text-anchor="middle" font-size="10" fill="#555">Center of gravity</text>
    <text x="110" y="315" text-anchor="middle" font-size="10" fill="#555">Always inside △</text>
  </g>

  <!-- ORTHOCENTER -->
  <g transform="translate(715,10)">
    <rect x="0" y="0" width="225" height="320" rx="8" fill="#f0e0f8" stroke="#880088" stroke-width="2"/>
    <text x="113" y="22" text-anchor="middle" font-size="13" font-weight="bold" fill="#880088">Orthocenter</text>
    <text x="113" y="38" text-anchor="middle" font-size="10" fill="#555">Altitudes meet</text>
    <polygon points="113,55 30,220 196,220" fill="#f8e8f8" stroke="#880088" stroke-width="2"/>
    <!-- Altitudes -->
    <line x1="113" y1="55" x2="113" y2="220" stroke="#880088" stroke-width="1.5" stroke-dasharray="4,2"/>
    <line x1="30" y1="220" x2="165" y2="133" stroke="#880088" stroke-width="1.5" stroke-dasharray="4,2"/>
    <line x1="196" y1="220" x2="62" y2="133" stroke="#880088" stroke-width="1.5" stroke-dasharray="4,2"/>
    <!-- Right angle markers at feet -->
    <rect x="108" y="212" width="10" height="10" fill="none" stroke="#333" stroke-width="1.5"/>
    <circle cx="113" cy="165" r="6" fill="#880088"/>
    <text x="121" y="160" font-size="11" fill="#880088" font-weight="bold">H</text>
    <text x="113" y="260" text-anchor="middle" font-size="11" fill="#880088">No special equidistance</text>
    <text x="113" y="276" text-anchor="middle" font-size="11" fill="#555">Inside: acute △</text>
    <text x="113" y="292" text-anchor="middle" font-size="11" fill="#555">At vertex: right △</text>
    <text x="113" y="308" text-anchor="middle" font-size="11" fill="#555">Outside: obtuse △</text>
  </g>
</svg>

---

## Centroid Theorem & Triangle Inequality

<svg width="950" height="300" viewBox="0 0 950 300" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Centroid ratio diagram -->
  <rect x="10" y="10" width="430" height="280" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="225" y="32" text-anchor="middle" font-size="14" font-weight="bold" fill="#e05c1a">Theorem 5-7: Centroid Theorem</text>
  <polygon points="225,60 60,230 390,230" fill="#fff0d8" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Median from top vertex to base midpoint -->
  <circle cx="225" cy="230" r="5" fill="#1a3a5c"/>
  <line x1="225" y1="60" x2="225" y2="230" stroke="#e05c1a" stroke-width="2"/>
  <!-- Centroid at 2/3 point -->
  <circle cx="225" cy="180" r="7" fill="#e05c1a"/>
  <text x="235" y="178" font-size="13" font-weight="bold" fill="#e05c1a">G</text>
  <!-- 2/3 marking -->
  <line x1="205" y1="60" x2="205" y2="180" stroke="#2a7a2a" stroke-width="2.5"/>
  <text x="196" y="124" font-size="12" fill="#2a7a2a" font-weight="bold" text-anchor="end">⅔</text>
  <!-- 1/3 marking -->
  <line x1="245" y1="180" x2="245" y2="230" stroke="#cc3300" stroke-width="2.5"/>
  <text x="254" y="208" font-size="12" fill="#cc3300" font-weight="bold">⅓</text>
  <!-- Vertex label -->
  <text x="225" y="52" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="235" y="244" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">M (midpt)</text>
  <text x="225" y="268" text-anchor="middle" font-size="13" fill="#e05c1a">If AM = 18:  AG = 12,  GM = 6</text>
  <text x="225" y="284" text-anchor="middle" font-size="12" fill="#555">AG = (2/3)AM  ·  GM = (1/3)AM</text>

  <!-- Triangle Inequality -->
  <rect x="460" y="10" width="480" height="280" rx="8" fill="#fdecea" stroke="#cc2200" stroke-width="2"/>
  <text x="700" y="32" text-anchor="middle" font-size="14" font-weight="bold" fill="#cc2200">Theorem 5-11: Triangle Inequality</text>
  <polygon points="700,70 540,230 860,230" fill="#ffd8d0" stroke="#cc2200" stroke-width="2.5"/>
  <text x="700" y="62" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="524" y="245" font-size="13" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="863" y="245" font-size="13" font-weight="bold" fill="#1a3a5c">C</text>
  <!-- Side labels -->
  <text x="606" y="145" font-size="13" fill="#cc2200" font-weight="bold">c</text>
  <text x="783" y="145" font-size="13" fill="#cc2200" font-weight="bold">b</text>
  <text x="700" y="248" text-anchor="middle" font-size="13" fill="#cc2200" font-weight="bold">a</text>
  <text x="700" y="272" text-anchor="middle" font-size="14" fill="#cc2200" font-weight="bold">a + b &gt; c,  a + c &gt; b,  b + c &gt; a</text>
  <text x="700" y="292" text-anchor="middle" font-size="12" fill="#555">Test: 4, 7, 12?  4+7=11 &lt; 12  ✗  NOT a triangle</text>
</svg>

---

## Hinge Theorem & Angle-Side Relationship

<svg width="950" height="290" viewBox="0 0 950 290" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Angle-Side Relationship -->
  <rect x="10" y="10" width="440" height="270" rx="8" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <text x="225" y="32" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Theorems 5-9 &amp; 5-10: Angle-Side</text>
  <polygon points="100,220 200,60 380,220" fill="#d0e8ff" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="84" y="236" font-size="14" font-weight="bold" fill="#cc2200">A</text>
  <text x="198" y="52" font-size="14" font-weight="bold" fill="#2a7a2a">B</text>
  <text x="382" y="236" font-size="14" font-weight="bold" fill="#1565C0">C</text>
  <!-- Side labels (opposite to each angle) -->
  <text x="296" y="148" font-size="14" fill="#cc2200" font-weight="bold">a (longest)</text>
  <text x="200" y="246" text-anchor="middle" font-size="14" fill="#2a7a2a" font-weight="bold">b</text>
  <text x="133" y="148" font-size="14" fill="#1565C0" font-weight="bold">c</text>
  <!-- Angle size indicators -->
  <path d="M 120,220 A 24,24 0 0 1 115,197" stroke="#cc2200" fill="rgba(200,0,0,0.2)" stroke-width="3"/>
  <text x="225" y="260" text-anchor="middle" font-size="12" fill="#cc2200" font-weight="bold">∠A largest  ↔  side a longest (BC)</text>
  <text x="225" y="278" text-anchor="middle" font-size="12" fill="#1a3a5c">Larger ∠ opposite longer side</text>

  <!-- Hinge Theorem -->
  <rect x="470" y="10" width="470" height="270" rx="8" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="2"/>
  <text x="705" y="32" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">Thm. 5-12 &amp; 5-13: Hinge Theorem</text>
  <!-- Two triangles sharing two equal sides -->
  <polygon points="520,220 620,80 700,220" fill="#c0ecc0" stroke="#2a7a2a" stroke-width="2"/>
  <polygon points="730,220 830,80 910,220" fill="#ffe0cc" stroke="#e05c1a" stroke-width="2"/>
  <!-- Shared side ticks -->
  <line x1="559" y1="158" x2="569" y2="148" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="769" y1="148" x2="779" y2="158" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="605" y1="220" x2="615" y2="220" stroke="#880088" stroke-width="3"/>
  <line x1="815" y1="220" x2="825" y2="220" stroke="#880088" stroke-width="3"/>
  <!-- Small angle arc -->
  <path d="M 538,220 A 22,22 0 0 1 534,198" stroke="#2a7a2a" fill="rgba(40,150,40,0.3)" stroke-width="3"/>
  <!-- Large angle arc -->
  <path d="M 754,220 A 30,30 0 0 1 748,190" stroke="#e05c1a" fill="rgba(220,80,0,0.3)" stroke-width="3"/>
  <!-- 3rd side labels -->
  <text x="652" y="148" font-size="12" fill="#2a7a2a" font-weight="bold">AC short</text>
  <text x="862" y="148" font-size="12" fill="#e05c1a" font-weight="bold">DF long</text>
  <text x="705" y="256" text-anchor="middle" font-size="12" fill="#2a7a2a">Same 2 sides: larger included ∠ → longer 3rd side</text>
  <text x="705" y="274" text-anchor="middle" font-size="12" fill="#2a7a2a">∠B &lt; ∠E  ⟹  AC &lt; DF  (and converse)</text>
</svg>

---

## Chapter 5 — Complete Reference

| Theorem | Statement |
|---------|-----------|
| **5-1** Perp. Bisector | Point on perp. bisector ↔ equidistant from endpoints |
| **5-3** Angle Bisector | Point on angle bisector ↔ equidistant from sides |
| **5-5** Circumcenter | Equidistant from all 3 vertices; center of circumscribed circle |
| **5-6** Incenter | Equidistant from all 3 sides; center of inscribed circle |
| **5-7** Centroid | Divides each median 2:1 from vertex; $CG = \frac{2}{3} \times \text{median}$ |
| **5-8** Exterior Angle Ineq. | Exterior angle > either non-adjacent interior angle |
| **5-9/10** Angle-Side | Larger angle ↔ longer opposite side |
| **5-11** Triangle Ineq. | Sum of any 2 sides > 3rd side |
| **5-12/13** Hinge Thm. | Same 2 sides: larger included angle ↔ longer 3rd side |

| Center | Built From | Location |
|--------|-----------|----------|
| **Circumcenter** | ⊥ bisectors | Inside (acute), on (right), outside (obtuse) |
| **Incenter** | ∠ bisectors | Always inside |
| **Centroid** | Medians | Always inside, $\frac{2}{3}$ from vertex |
| **Orthocenter** | Altitudes | Inside/on/outside depending on △ type |
