---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 1 — Cheatsheet
# Points, Lines, Planes & Angles

**Unit 1 | Glencoe Geometry TX 2015**

---

## Undefined Terms & Basic Postulates

<svg width="950" height="300" viewBox="0 0 950 300" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Point -->
  <circle cx="80" cy="100" r="6" fill="#1a3a5c"/>
  <text x="80" y="135" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Point A</text>
  <text x="80" y="152" text-anchor="middle" font-size="11" fill="#555">Location, no size</text>

  <!-- Line -->
  <line x1="160" y1="100" x2="340" y2="100" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="155" y1="94" x2="165" y2="106" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="335" y1="94" x2="345" y2="106" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="210" cy="100" r="5" fill="#e05c1a"/>
  <circle cx="290" cy="100" r="5" fill="#e05c1a"/>
  <text x="210" y="92" text-anchor="middle" font-size="12" fill="#e05c1a">A</text>
  <text x="290" y="92" text-anchor="middle" font-size="12" fill="#e05c1a">B</text>
  <text x="250" y="135" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Line AB</text>
  <text x="250" y="152" text-anchor="middle" font-size="11" fill="#555">Infinite points, 2 directions</text>

  <!-- Plane -->
  <polygon points="420,60 600,40 640,160 460,180" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <text x="530" y="115" text-anchor="middle" font-size="16" font-weight="bold" fill="#1a3a5c">Plane M</text>
  <circle cx="480" cy="100" r="4" fill="#e05c1a"/>
  <circle cx="540" cy="80" r="4" fill="#e05c1a"/>
  <circle cx="570" cy="130" r="4" fill="#e05c1a"/>
  <text x="470" y="93" font-size="12" fill="#e05c1a">A</text>
  <text x="530" y="73" font-size="12" fill="#e05c1a">B</text>
  <text x="574" y="142" font-size="12" fill="#e05c1a">C</text>
  <text x="530" y="200" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Plane</text>
  <text x="530" y="217" text-anchor="middle" font-size="11" fill="#555">Flat, infinite, 2D; needs 3 non-collinear pts</text>

  <!-- Segment and Ray -->
  <line x1="700" y1="80" x2="880" y2="80" stroke="#2a7a2a" stroke-width="2.5"/>
  <circle cx="700" cy="80" r="5" fill="#2a7a2a"/>
  <circle cx="880" cy="80" r="5" fill="#2a7a2a"/>
  <text x="700" y="70" text-anchor="middle" font-size="12" fill="#2a7a2a">A</text>
  <text x="880" y="70" text-anchor="middle" font-size="12" fill="#2a7a2a">B</text>
  <text x="790" y="105" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">Segment AB</text>
  <text x="790" y="122" text-anchor="middle" font-size="11" fill="#555">Two endpoints</text>

  <line x1="700" y1="170" x2="880" y2="170" stroke="#e05c1a" stroke-width="2.5"/>
  <circle cx="700" cy="170" r="5" fill="#e05c1a"/>
  <line x1="875" y1="164" x2="887" y2="176" stroke="#e05c1a" stroke-width="2"/>
  <line x1="875" y1="176" x2="887" y2="164" stroke="#e05c1a" stroke-width="2"/>
  <text x="700" y="160" text-anchor="middle" font-size="12" fill="#e05c1a">A</text>
  <text x="790" y="200" text-anchor="middle" font-size="13" font-weight="bold" fill="#e05c1a">Ray AB</text>
  <text x="790" y="217" text-anchor="middle" font-size="11" fill="#555">One endpoint, one direction</text>

  <!-- Postulates box -->
  <rect x="10" y="230" width="930" height="60" rx="6" fill="#1a3a5c" opacity="0.08" stroke="#1a3a5c" stroke-width="1"/>
  <text x="30" y="252" font-size="12" font-weight="bold" fill="#1a3a5c">Post. 1-1:</text><text x="115" y="252" font-size="12" fill="#333"> 2 points → exactly 1 line</text>
  <text x="320" y="252" font-size="12" font-weight="bold" fill="#1a3a5c">Post. 1-2:</text><text x="405" y="252" font-size="12" fill="#333"> 2 lines intersect → exactly 1 point</text>
  <text x="660" y="252" font-size="12" font-weight="bold" fill="#1a3a5c">Post. 1-3:</text><text x="745" y="252" font-size="12" fill="#333"> 2 planes → 1 line</text>
  <text x="30" y="275" font-size="12" font-weight="bold" fill="#1a3a5c">Post. 1-4:</text><text x="115" y="275" font-size="12" fill="#333"> 3 noncollinear points → exactly 1 plane</text>
</svg>

---

## Segment Addition Postulate & Midpoint

<svg width="950" height="320" viewBox="0 0 950 320" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <defs>
    <marker id="arrowG" markerWidth="8" markerHeight="6" refX="8" refY="3" orient="auto">
      <polygon points="0 0,8 3,0 6" fill="#2a7a2a"/>
    </marker>
  </defs>

  <!-- Segment Addition -->
  <text x="475" y="28" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Post. 1-6 — Segment Addition Postulate</text>
  <line x1="60" y1="80" x2="890" y2="80" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="120" cy="80" r="7" fill="#1a3a5c"/>
  <circle cx="500" cy="80" r="7" fill="#e05c1a"/>
  <circle cx="830" cy="80" r="7" fill="#1a3a5c"/>
  <text x="120" y="68" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="500" y="68" text-anchor="middle" font-size="14" font-weight="bold" fill="#e05c1a">B</text>
  <text x="830" y="68" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">C</text>
  <line x1="120" y1="100" x2="500" y2="100" stroke="#2a7a2a" stroke-width="1.5" marker-end="url(#arrowG)"/>
  <text x="310" y="118" text-anchor="middle" font-size="13" fill="#2a7a2a" font-weight="bold">AB</text>
  <line x1="500" y1="100" x2="830" y2="100" stroke="#cc3300" stroke-width="1.5"/>
  <line x1="498" y1="98" x2="508" y2="108" stroke="#cc3300" stroke-width="1.5"/>
  <text x="665" y="118" text-anchor="middle" font-size="13" fill="#cc3300" font-weight="bold">BC</text>
  <line x1="120" y1="140" x2="830" y2="140" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="120" y1="133" x2="120" y2="147" stroke="#1a3a5c" stroke-width="1.5"/>
  <line x1="830" y1="133" x2="830" y2="147" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="475" y="162" text-anchor="middle" font-size="13" fill="#1a3a5c" font-weight="bold">AC = AB + BC</text>

  <!-- Midpoint diagram -->
  <text x="475" y="198" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Midpoint Theorem</text>
  <line x1="60" y1="230" x2="890" y2="230" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="120" cy="230" r="7" fill="#1a3a5c"/>
  <circle cx="475" cy="230" r="8" fill="#2a7a2a"/>
  <circle cx="830" cy="230" r="7" fill="#1a3a5c"/>
  <text x="120" y="218" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="475" y="216" text-anchor="middle" font-size="15" font-weight="bold" fill="#2a7a2a">M</text>
  <text x="830" y="218" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">B</text>
  <line x1="120" y1="250" x2="470" y2="250" stroke="#2a7a2a" stroke-width="2"/>
  <text x="295" y="268" text-anchor="middle" font-size="13" fill="#2a7a2a" font-weight="bold">AM</text>
  <line x1="480" y1="250" x2="830" y2="250" stroke="#2a7a2a" stroke-width="2"/>
  <text x="655" y="268" text-anchor="middle" font-size="13" fill="#2a7a2a" font-weight="bold">MB</text>
  <text x="475" y="290" text-anchor="middle" font-size="13" fill="#2a7a2a">AM = MB = AB/2 · Coordinate midpoint: M = ((x₁+x₂)/2, (y₁+y₂)/2)</text>
</svg>

---

## Angle Types

<svg width="950" height="360" viewBox="0 0 950 360" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Acute -->
  <g transform="translate(30,30)">
    <rect x="0" y="0" width="170" height="200" rx="8" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
    <text x="85" y="22" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Acute</text>
    <line x1="85" y1="150" x2="160" y2="150" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="85" y1="150" x2="130" y2="65" stroke="#1a3a5c" stroke-width="2"/>
    <path d="M 110,150 A 25,25 0 0 0 108,125" stroke="#e05c1a" fill="none" stroke-width="2"/>
    <text x="118" y="137" font-size="12" fill="#e05c1a" font-weight="bold">θ</text>
    <text x="85" y="178" text-anchor="middle" font-size="20" fill="#1a3a5c" font-weight="bold">0° &lt; θ &lt; 90°</text>
  </g>

  <!-- Right -->
  <g transform="translate(220,30)">
    <rect x="0" y="0" width="170" height="200" rx="8" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="1.5"/>
    <text x="85" y="22" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">Right</text>
    <line x1="85" y1="150" x2="160" y2="150" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="85" y1="150" x2="85" y2="60" stroke="#1a3a5c" stroke-width="2"/>
    <rect x="85" y="132" width="18" height="18" fill="none" stroke="#2a7a2a" stroke-width="2"/>
    <text x="85" y="178" text-anchor="middle" font-size="20" fill="#2a7a2a" font-weight="bold">θ = 90°</text>
  </g>

  <!-- Obtuse -->
  <g transform="translate(410,30)">
    <rect x="0" y="0" width="170" height="200" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
    <text x="85" y="22" text-anchor="middle" font-size="13" font-weight="bold" fill="#e05c1a">Obtuse</text>
    <line x1="85" y1="150" x2="160" y2="150" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="85" y1="150" x2="25" y2="80" stroke="#1a3a5c" stroke-width="2"/>
    <path d="M 110,150 A 28,28 0 0 0 60,127" stroke="#e05c1a" fill="none" stroke-width="2"/>
    <text x="76" y="138" font-size="12" fill="#e05c1a" font-weight="bold">θ</text>
    <text x="85" y="178" text-anchor="middle" font-size="16" fill="#e05c1a" font-weight="bold">90° &lt; θ &lt; 180°</text>
  </g>

  <!-- Straight -->
  <g transform="translate(600,30)">
    <rect x="0" y="0" width="170" height="200" rx="8" fill="#fdecea" stroke="#cc2200" stroke-width="1.5"/>
    <text x="85" y="22" text-anchor="middle" font-size="13" font-weight="bold" fill="#cc2200">Straight</text>
    <line x1="10" y1="120" x2="160" y2="120" stroke="#1a3a5c" stroke-width="2.5"/>
    <circle cx="85" cy="120" r="5" fill="#cc2200"/>
    <path d="M 115,120 A 30,30 0 0 0 55,120" stroke="#cc2200" fill="none" stroke-width="2"/>
    <text x="85" y="112" text-anchor="middle" font-size="12" fill="#cc2200" font-weight="bold">180°</text>
    <text x="85" y="178" text-anchor="middle" font-size="20" fill="#cc2200" font-weight="bold">θ = 180°</text>
  </g>

  <!-- Reflex -->
  <g transform="translate(790,30)">
    <rect x="0" y="0" width="150" height="200" rx="8" fill="#f0e0f8" stroke="#880088" stroke-width="1.5"/>
    <text x="75" y="22" text-anchor="middle" font-size="13" font-weight="bold" fill="#880088">Reflex</text>
    <line x1="75" y1="130" x2="140" y2="130" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="75" y1="130" x2="115" y2="60" stroke="#1a3a5c" stroke-width="2"/>
    <path d="M 100,130 A 28,28 0 1 1 105,104" stroke="#880088" fill="none" stroke-width="2"/>
    <text x="40" y="100" font-size="12" fill="#880088" font-weight="bold">θ</text>
    <text x="75" y="178" text-anchor="middle" font-size="14" fill="#880088" font-weight="bold">180° &lt; θ &lt; 360°</text>
  </g>

  <!-- Angle Addition Postulate -->
  <rect x="10" y="248" width="930" height="100" rx="8" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="475" y="272" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Postulate 1-8 — Angle Addition Postulate</text>
  <text x="475" y="296" text-anchor="middle" font-size="13" fill="#333">If ray BD is in the interior of ∠ABC, then  m∠ABD + m∠DBC = m∠ABC</text>
  <text x="475" y="320" text-anchor="middle" font-size="13" fill="#555">Example: m∠ABD = 35°  and  m∠DBC = 50°  →  m∠ABC = 85°</text>
  <text x="475" y="340" text-anchor="middle" font-size="12" fill="#2a7a2a">Protractor Postulate: rays from a point paired with real numbers 0°–180°; angle measure = |difference|</text>
</svg>

---

## Angle Pairs — Vertical, Supplementary, Complementary

<svg width="950" height="360" viewBox="0 0 950 360" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Vertical Angles -->
  <text x="185" y="24" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Vertical Angles (Thm 1-1)</text>
  <line x1="60" y1="80" x2="310" y2="200" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="60" y1="200" x2="310" y2="80" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="185" cy="140" r="5" fill="#333"/>
  <path d="M 205,140 A 22,22 0 0 1 198,160" stroke="#2a7a2a" fill="rgba(0,150,0,0.15)" stroke-width="2"/>
  <path d="M 165,140 A 22,22 0 0 1 172,120" stroke="#2a7a2a" fill="rgba(0,150,0,0.15)" stroke-width="2"/>
  <path d="M 172,120 A 22,22 0 0 1 198,120" stroke="#cc3300" fill="rgba(200,0,0,0.1)" stroke-width="2"/>
  <path d="M 172,158 A 22,22 0 0 0 198,160" stroke="#cc3300" fill="rgba(200,0,0,0.1)" stroke-width="2"/>
  <text x="218" y="136" font-size="14" font-weight="bold" fill="#2a7a2a">∠1</text>
  <text x="140" y="150" font-size="14" font-weight="bold" fill="#2a7a2a">∠3</text>
  <text x="200" y="164" font-size="14" font-weight="bold" fill="#cc3300">∠4</text>
  <text x="148" y="126" font-size="14" font-weight="bold" fill="#cc3300">∠2</text>
  <text x="185" y="230" text-anchor="middle" font-size="12" fill="#2a7a2a" font-weight="bold">∠1 ≅ ∠3  and  ∠2 ≅ ∠4</text>
  <text x="185" y="248" text-anchor="middle" font-size="11" fill="#555">Vertical angles are always congruent</text>

  <!-- Supplementary -->
  <text x="545" y="24" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Supplementary (Thm 1-2) and Complementary (Thm 1-3)</text>
  <line x1="370" y1="120" x2="720" y2="120" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="545" y1="120" x2="545" y2="60" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="545" y1="120" x2="490" y2="65" stroke="#e05c1a" stroke-width="2"/>
  <path d="M 575,120 A 30,30 0 0 0 563,92" stroke="#cc3300" fill="none" stroke-width="2"/>
  <path d="M 514,94 A 30,30 0 0 0 545,90" stroke="#cc3300" fill="none" stroke-width="2"/>
  <text x="580" y="106" font-size="13" fill="#cc3300" font-weight="bold">∠1</text>
  <text x="515" y="105" font-size="13" fill="#cc3300" font-weight="bold">∠2</text>
  <path d="M 458,120 A 30,30 0 0 1 468,93" stroke="#2a7a2a" fill="none" stroke-width="2"/>
  <text x="443" y="107" font-size="13" fill="#2a7a2a" font-weight="bold">∠3</text>
  <text x="545" y="230" text-anchor="middle" font-size="12" fill="#cc3300" font-weight="bold">Linear Pair (∠1+∠2): supplementary → sum = 180°</text>
  <text x="545" y="250" text-anchor="middle" font-size="12" fill="#2a7a2a" font-weight="bold">Right-angle adjacent pair (∠1+∠3): complementary → sum = 90°</text>
  <text x="545" y="275" text-anchor="middle" font-size="12" fill="#1a3a5c">Thm 2-4: Two ∠s supplementary to same ∠ → congruent</text>
  <text x="545" y="295" text-anchor="middle" font-size="12" fill="#1a3a5c">Thm 2-5: Two ∠s complementary to same ∠ → congruent</text>
  <text x="545" y="315" text-anchor="middle" font-size="12" fill="#1a3a5c">Thm 2-6: All right angles are congruent</text>
  <text x="545" y="335" text-anchor="middle" font-size="12" fill="#1a3a5c">Thm 2-7: Perpendicular lines form 4 right angles</text>
</svg>

---

## Distance & Midpoint Formulas

<svg width="950" height="360" viewBox="0 0 950 360" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Coordinate grid -->
  <line x1="60" y1="20" x2="60" y2="330" stroke="#ccc" stroke-width="1"/>
  <line x1="60" y1="330" x2="530" y2="330" stroke="#ccc" stroke-width="1"/>
  <!-- Axis labels -->
  <text x="55" y="16" font-size="12" fill="#888">y</text>
  <text x="534" y="334" font-size="12" fill="#888">x</text>

  <!-- Grid lines -->
  <line x1="60" y1="250" x2="530" y2="250" stroke="#eee" stroke-width="1"/>
  <line x1="60" y1="170" x2="530" y2="170" stroke="#eee" stroke-width="1"/>
  <line x1="60" y1="90" x2="530" y2="90" stroke="#eee" stroke-width="1"/>
  <line x1="140" y1="20" x2="140" y2="330" stroke="#eee" stroke-width="1"/>
  <line x1="220" y1="20" x2="220" y2="330" stroke="#eee" stroke-width="1"/>
  <line x1="300" y1="20" x2="300" y2="330" stroke="#eee" stroke-width="1"/>
  <line x1="380" y1="20" x2="380" y2="330" stroke="#eee" stroke-width="1"/>
  <line x1="460" y1="20" x2="460" y2="330" stroke="#eee" stroke-width="1"/>

  <!-- Points -->
  <circle cx="140" cy="250" r="7" fill="#1a3a5c"/>
  <circle cx="460" cy="90" r="7" fill="#e05c1a"/>
  <circle cx="300" cy="170" r="8" fill="#2a7a2a"/>

  <!-- Labels -->
  <text x="125" y="272" font-size="13" font-weight="bold" fill="#1a3a5c">A(1,2)</text>
  <text x="465" y="108" font-size="13" font-weight="bold" fill="#e05c1a">B(5,6)</text>
  <text x="308" y="162" font-size="13" font-weight="bold" fill="#2a7a2a">M(3,4)</text>

  <!-- Hypotenuse (distance line) -->
  <line x1="140" y1="250" x2="460" y2="90" stroke="#1565C0" stroke-width="2.5"/>
  <text x="280" y="156" text-anchor="middle" font-size="12" fill="#1565C0" font-weight="bold">d</text>

  <!-- Legs -->
  <line x1="140" y1="250" x2="460" y2="250" stroke="#cc3300" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="460" y1="250" x2="460" y2="90" stroke="#cc3300" stroke-width="1.5" stroke-dasharray="5,3"/>
  <rect x="448" y="238" width="12" height="12" fill="none" stroke="#cc3300" stroke-width="1.5"/>
  <text x="300" y="278" text-anchor="middle" font-size="12" fill="#cc3300">Δx = 5−1 = 4</text>
  <text x="478" y="175" font-size="12" fill="#cc3300">Δy=4</text>

  <!-- Midpoint M marker -->
  <line x1="296" y1="162" x2="304" y2="178" stroke="#2a7a2a" stroke-width="1.5"/>

  <!-- Axis tick labels -->
  <text x="52" y="254" font-size="10" fill="#888" text-anchor="end">2</text>
  <text x="52" y="174" font-size="10" fill="#888" text-anchor="end">4</text>
  <text x="52" y="94" font-size="10" fill="#888" text-anchor="end">6</text>
  <text x="140" y="344" font-size="10" fill="#888" text-anchor="middle">1</text>
  <text x="300" y="344" font-size="10" fill="#888" text-anchor="middle">3</text>
  <text x="460" y="344" font-size="10" fill="#888" text-anchor="middle">5</text>

  <!-- Formulas panel -->
  <rect x="560" y="30" width="380" height="290" rx="8" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="750" y="58" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Formulas</text>
  <line x1="570" y1="66" x2="930" y2="66" stroke="#1a3a5c" stroke-width="1"/>

  <text x="580" y="92" font-size="13" font-weight="bold" fill="#1a3a5c">Distance Formula</text>
  <text x="580" y="116" font-size="13" fill="#333">d = √[(x₂−x₁)² + (y₂−y₁)²]</text>
  <text x="580" y="138" font-size="12" fill="#555">= √[(5−1)² + (6−2)²]</text>
  <text x="580" y="158" font-size="12" fill="#555">= √[16 + 16] = √32 = 4√2 ≈ 5.66</text>

  <line x1="570" y1="172" x2="930" y2="172" stroke="#ddd" stroke-width="1"/>
  <text x="580" y="196" font-size="13" font-weight="bold" fill="#1a3a5c">Midpoint Formula</text>
  <text x="580" y="220" font-size="13" fill="#333">M = ((x₁+x₂)/2 ,  (y₁+y₂)/2)</text>
  <text x="580" y="242" font-size="12" fill="#555">= ((1+5)/2 ,  (2+6)/2)</text>
  <text x="580" y="262" font-size="12" fill="#555">= (3 , 4) ✓</text>

  <line x1="570" y1="275" x2="930" y2="275" stroke="#ddd" stroke-width="1"/>
  <text x="580" y="296" font-size="12" fill="#333" font-weight="bold">On number line:  AB = |a − b|</text>
  <text x="580" y="313" font-size="12" fill="#555">Ruler Postulate: points ↔ real numbers</text>
</svg>

---

## Chapter 1 — Complete Reference

| Concept | Statement / Formula |
|---------|-------------------|
| **Segment Addition** | If $B$ between $A$ and $C$: $AB + BC = AC$ |
| **Midpoint** | $AM = MB = \frac{AB}{2}$; coordinate: $M=\left(\frac{x_1+x_2}{2},\frac{y_1+y_2}{2}\right)$ |
| **Distance** | $d = \sqrt{(x_2-x_1)^2+(y_2-y_1)^2}$ |
| **Angle Addition** | If $D$ interior to $\angle ABC$: $m\angle ABD + m\angle DBC = m\angle ABC$ |
| **Complementary** | Two angles whose sum $= 90°$ |
| **Supplementary** | Two angles whose sum $= 180°$ |
| **Linear Pair** | Adjacent angles forming a straight line → supplementary |
| **Vertical Angles (Thm 1-1)** | Vertical angles are congruent |
| **Post. 1-1** | Through any 2 points → exactly 1 line |
| **Post. 1-2** | 2 distinct lines intersect → exactly 1 point |
| **Post. 1-3** | 2 distinct planes intersect → exactly 1 line |
| **Post. 1-4** | 3 noncollinear points → exactly 1 plane |
| **Thm 2-4** | Angles supp. to same angle → congruent |
| **Thm 2-5** | Angles comp. to same angle → congruent |
| **Thm 2-6** | All right angles are congruent |
| **Thm 2-7** | Perpendicular lines → 4 right angles |
