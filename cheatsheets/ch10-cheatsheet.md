---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: chapter -->
# Chapter 10: Circles
### Theorems, Postulates & Key Formulas

---

# Parts of a Circle

<svg viewBox="0 0 520 270" width="520" height="270" xmlns="http://www.w3.org/2000/svg" font-family="Arial" font-size="13">
  <!-- Circle -->
  <circle cx="200" cy="135" r="100" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Center -->
  <circle cx="200" cy="135" r="4" fill="#1a3a5c"/>
  <text x="207" y="131" fill="#1a3a5c" font-weight="bold">O (center)</text>
  <!-- Radius OA -->
  <line x1="200" y1="135" x2="270" y2="75" stroke="#e05c1a" stroke-width="2"/>
  <circle cx="270" cy="75" r="4" fill="#1a3a5c"/>
  <text x="275" y="72" fill="#e05c1a" font-weight="bold">A</text>
  <text x="225" y="95" fill="#e05c1a" font-size="11">radius r</text>
  <!-- Diameter BC -->
  <line x1="100" y1="135" x2="300" y2="135" stroke="#1a3a5c" stroke-width="2" stroke-dasharray="5,3"/>
  <circle cx="100" cy="135" r="4" fill="#1a3a5c"/>
  <circle cx="300" cy="135" r="4" fill="#1a3a5c"/>
  <text x="65" y="131" fill="#1a3a5c" font-weight="bold">B</text>
  <text x="305" y="131" fill="#1a3a5c" font-weight="bold">C</text>
  <text x="185" y="158" fill="#1a3a5c" font-size="11">diameter d=2r</text>
  <!-- Chord DE -->
  <line x1="120" y1="90" x2="280" y2="100" stroke="#2e8b57" stroke-width="2"/>
  <circle cx="120" cy="90" r="4" fill="#2e8b57"/>
  <circle cx="280" cy="100" r="4" fill="#2e8b57"/>
  <text x="100" y="87" fill="#2e8b57" font-weight="bold">D</text>
  <text x="284" y="98" fill="#2e8b57" font-weight="bold">E</text>
  <text x="175" y="86" fill="#2e8b57" font-size="11">chord</text>
  <!-- Secant line -->
  <line x1="350" y1="60" x2="420" y2="200" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="422" y="200" fill="#9b59b6" font-size="12">secant</text>
  <!-- Tangent line at top -->
  <line x1="140" y1="35" x2="320" y2="35" stroke="#c0392b" stroke-width="1.5"/>
  <circle cx="200" cy="35" r="4" fill="#c0392b"/>
  <text x="322" y="40" fill="#c0392b" font-size="12">tangent (touches at 1 pt)</text>
  <!-- Right angle at tangent point -->
  <line x1="200" y1="35" x2="200" y2="135" stroke="#c0392b" stroke-width="1" stroke-dasharray="4,3"/>
  <rect x="192" y="43" width="8" height="8" fill="none" stroke="#c0392b" stroke-width="1.5"/>
</svg>

| Term | Definition |
|------|-----------|
| **Radius** | Segment from center to any point on circle |
| **Diameter** | Chord through center; $d = 2r$ |
| **Chord** | Segment with both endpoints on circle |
| **Secant** | Line intersecting circle at 2 points |
| **Tangent** | Line intersecting circle at exactly 1 point |

---

# Central Angles & Arcs

<svg viewBox="0 0 520 260" width="520" height="260" xmlns="http://www.w3.org/2000/svg" font-family="Arial" font-size="13">
  <!-- Left: central angle -->
  <circle cx="140" cy="130" r="95" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="140" cy="130" r="4" fill="#1a3a5c"/>
  <text x="147" y="127" fill="#1a3a5c" font-weight="bold">O</text>
  <!-- Radii -->
  <line x1="140" y1="130" x2="220" y2="55" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="140" y1="130" x2="235" y2="165" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="220" cy="55" r="4" fill="#1a3a5c"/>
  <circle cx="235" cy="165" r="4" fill="#1a3a5c"/>
  <text x="224" y="52" fill="#1a3a5c">A</text>
  <text x="239" y="165" fill="#1a3a5c">B</text>
  <!-- Arc AB (minor) -->
  <path d="M 220,55 A 95,95 0 0,1 235,165" fill="none" stroke="#e05c1a" stroke-width="4"/>
  <text x="248" y="110" fill="#e05c1a" font-size="12">minor arc AB</text>
  <!-- Angle arc at center -->
  <path d="M 175,100 A 38,38 0 0,1 175,148" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="180" y="128" fill="#e05c1a" font-size="12">∠AOB</text>
  <!-- Major arc label -->
  <text x="30" y="150" fill="#2e8b57" font-size="12">major arc ADB</text>
  <!-- Semicircle label -->
  <text x="50" y="240" fill="#1a3a5c" font-size="12">semicircle = 180°</text>

  <!-- Right: Arc Measure table -->
  <rect x="310" y="20" width="200" height="220" rx="6" fill="#f4f8fc" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="320" y="45" fill="#1a3a5c" font-weight="bold" font-size="14">Arc Measures</text>
  <line x1="310" y1="52" x2="510" y2="52" stroke="#1a3a5c" stroke-width="1"/>
  <text x="320" y="72" fill="#1a3a5c" font-size="12">Minor arc = central ∠</text>
  <text x="320" y="92" fill="#1a3a5c" font-size="12">Major arc = 360° − minor</text>
  <text x="320" y="112" fill="#1a3a5c" font-size="12">Semicircle = 180°</text>
  <line x1="310" y1="120" x2="510" y2="120" stroke="#aecde8" stroke-width="1"/>
  <text x="320" y="140" fill="#e05c1a" font-weight="bold" font-size="12">Arc Addition Postulate</text>
  <text x="320" y="160" fill="#1a3a5c" font-size="12">arc ABC =</text>
  <text x="320" y="178" fill="#1a3a5c" font-size="12">arc AB + arc BC</text>
  <line x1="310" y1="188" x2="510" y2="188" stroke="#aecde8" stroke-width="1"/>
  <text x="320" y="208" fill="#2e8b57" font-weight="bold" font-size="12">Congruent Arcs</text>
  <text x="320" y="228" fill="#1a3a5c" font-size="11">Same measure in ≅ circles</text>
</svg>

> **Central Angle** = angle with vertex at center. Its arc measure **equals** the central angle measure.

---

# Arcs and Chords

<svg viewBox="0 0 520 260" width="520" height="260" xmlns="http://www.w3.org/2000/svg" font-family="Arial" font-size="12">
  <!-- Panel 1: Congruent chords ↔ congruent arcs -->
  <circle cx="110" cy="110" r="85" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="110" cy="110" r="3" fill="#1a3a5c"/>
  <!-- Chord AB -->
  <line x1="45" y1="75" x2="175" y2="75" stroke="#e05c1a" stroke-width="2.5"/>
  <circle cx="45" cy="75" r="3" fill="#1a3a5c"/>
  <circle cx="175" cy="75" r="3" fill="#1a3a5c"/>
  <text x="30" y="71" fill="#1a3a5c">A</text><text x="178" y="71" fill="#1a3a5c">B</text>
  <text x="90" y="68" fill="#e05c1a">chord</text>
  <!-- Chord CD -->
  <line x1="35" y1="150" x2="150" y2="190" stroke="#2e8b57" stroke-width="2.5"/>
  <circle cx="35" cy="150" r="3" fill="#1a3a5c"/>
  <circle cx="150" cy="190" r="3" fill="#1a3a5c"/>
  <text x="16" y="148" fill="#1a3a5c">C</text><text x="153" y="193" fill="#1a3a5c">D</text>
  <!-- Arc AB (top) -->
  <path d="M 45,75 A 85,85 0 0,1 175,75" fill="none" stroke="#e05c1a" stroke-width="3"/>
  <!-- tick marks equal -->
  <text x="95" y="40" fill="#e05c1a" font-size="11">≅ arcs ↔ ≅ chords</text>
  <!-- Perpendicular bisector from center -->
  <line x1="110" y1="110" x2="110" y2="75" stroke="#9b59b6" stroke-width="1.5" stroke-dasharray="4,3"/>
  <rect x="103" y="75" width="7" height="7" fill="none" stroke="#9b59b6" stroke-width="1.5"/>
  <text x="113" y="95" fill="#9b59b6" font-size="10">⊥ bisector</text>

  <!-- Panel 2: Perpendicular from center bisects chord -->
  <circle cx="370" cy="110" r="85" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="370" cy="110" r="3" fill="#1a3a5c"/>
  <text x="375" y="107" fill="#1a3a5c" font-weight="bold">O</text>
  <!-- Chord EF -->
  <line x1="305" y1="80" x2="435" y2="80" stroke="#1a3a5c" stroke-width="2.5"/>
  <circle cx="305" cy="80" r="3" fill="#1a3a5c"/>
  <circle cx="435" cy="80" r="3" fill="#1a3a5c"/>
  <text x="288" y="78" fill="#1a3a5c">E</text><text x="438" y="78" fill="#1a3a5c">F</text>
  <!-- Midpoint M -->
  <circle cx="370" cy="80" r="3" fill="#e05c1a"/>
  <text x="373" y="76" fill="#e05c1a">M</text>
  <!-- Perpendicular from O to chord -->
  <line x1="370" y1="110" x2="370" y2="80" stroke="#e05c1a" stroke-width="2"/>
  <rect x="363" y="80" width="7" height="7" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <!-- Equal segment ticks -->
  <line x1="335" y1="76" x2="335" y2="84" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="406" y1="76" x2="406" y2="84" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Theorem box -->
  <rect x="285" y="200" width="180" height="48" rx="4" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="295" y="218" fill="#1a3a5c" font-weight="bold" font-size="11">Thm 10.3</text>
  <text x="295" y="233" fill="#1a3a5c" font-size="11">OE ⊥ EF ⟹ OM bisects EF</text>
  <text x="295" y="245" fill="#1a3a5c" font-size="11">EM = MF</text>
</svg>

| Theorem | Statement |
|---------|-----------|
| **Thm 10.2** | In a circle, two chords are ≅ ↔ their arcs are ≅ |
| **Thm 10.3** | Diameter (or radius) ⊥ chord ↔ it bisects the chord and its arc |
| **Thm 10.4** | Two chords equidistant from center are ≅ |

---

# Inscribed Angles

<svg viewBox="0 0 520 260" width="520" height="260" xmlns="http://www.w3.org/2000/svg" font-family="Arial" font-size="12">
  <!-- Left: Inscribed angle theorem -->
  <circle cx="130" cy="130" r="95" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="130" cy="130" r="3" fill="#1a3a5c"/>
  <text x="136" y="127" fill="#1a3a5c" font-size="11">O</text>
  <!-- Inscribed angle at A -->
  <circle cx="60" cy="170" r="4" fill="#e05c1a"/>
  <text x="42" y="170" fill="#e05c1a" font-weight="bold">A</text>
  <!-- Intercepted arc BC -->
  <circle cx="175" cy="55" r="4" fill="#1a3a5c"/>
  <circle cx="215" cy="165" r="4" fill="#1a3a5c"/>
  <text x="179" y="50" fill="#1a3a5c">B</text>
  <text x="219" y="165" fill="#1a3a5c">C</text>
  <!-- Sides of inscribed angle -->
  <line x1="60" y1="170" x2="175" y2="55" stroke="#e05c1a" stroke-width="2"/>
  <line x1="60" y1="170" x2="215" y2="165" stroke="#e05c1a" stroke-width="2"/>
  <!-- Arc BC (intercepted) -->
  <path d="M 175,55 A 95,95 0 0,1 215,165" fill="none" stroke="#1a3a5c" stroke-width="4"/>
  <!-- Central angle OB OC -->
  <line x1="130" y1="130" x2="175" y2="55" stroke="#2e8b57" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="130" y1="130" x2="215" y2="165" stroke="#2e8b57" stroke-width="1.5" stroke-dasharray="5,3"/>
  <!-- Angle labels -->
  <text x="82" y="162" fill="#e05c1a" font-size="11">inscribed ∠</text>
  <text x="82" y="175" fill="#e05c1a" font-size="11">= ½ arc BC</text>
  <text x="160" y="115" fill="#2e8b57" font-size="11">central ∠</text>
  <text x="160" y="128" fill="#2e8b57" font-size="11">= arc BC</text>

  <!-- Right: Special cases -->
  <rect x="285" y="15" width="220" height="240" rx="6" fill="#f4f8fc" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="295" y="38" fill="#1a3a5c" font-weight="bold" font-size="13">Special Inscribed Angle Cases</text>
  <line x1="285" y1="46" x2="505" y2="46" stroke="#aecde8" stroke-width="1"/>
  <text x="295" y="65" fill="#e05c1a" font-weight="bold" font-size="11">Thm 10.7: Semicircle</text>
  <text x="295" y="82" fill="#1a3a5c" font-size="11">Inscribed angle in semicircle = 90°</text>
  <text x="295" y="94" fill="#1a3a5c" font-size="11">(intercepts diameter → 180°÷2)</text>
  <line x1="285" y1="103" x2="505" y2="103" stroke="#aecde8" stroke-width="1"/>
  <text x="295" y="120" fill="#e05c1a" font-weight="bold" font-size="11">Thm 10.8: Same Arc</text>
  <text x="295" y="137" fill="#1a3a5c" font-size="11">Inscribed angles intercepting</text>
  <text x="295" y="152" fill="#1a3a5c" font-size="11">the same arc are congruent</text>
  <line x1="285" y1="163" x2="505" y2="163" stroke="#aecde8" stroke-width="1"/>
  <text x="295" y="180" fill="#e05c1a" font-weight="bold" font-size="11">Thm 10.9: Inscribed Quadrilateral</text>
  <text x="295" y="197" fill="#1a3a5c" font-size="11">Opposite angles of an inscribed</text>
  <text x="295" y="212" fill="#1a3a5c" font-size="11">quadrilateral are supplementary</text>
  <text x="295" y="227" fill="#1a3a5c" font-size="11">∠A + ∠C = 180°, ∠B + ∠D = 180°</text>
</svg>

> **Inscribed Angle Theorem (10.6):** An inscribed angle = **½** its intercepted arc.
> $$\angle A = \frac{1}{2} \overset{\frown}{BC}$$

---

# Tangent Lines

<svg viewBox="0 0 520 260" width="520" height="260" xmlns="http://www.w3.org/2000/svg" font-family="Arial" font-size="12">
  <!-- Left: Tangent perpendicular to radius -->
  <circle cx="120" cy="130" r="90" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="120" cy="130" r="3" fill="#1a3a5c"/>
  <text x="127" y="127" fill="#1a3a5c" font-weight="bold">O</text>
  <!-- Radius to tangent point P -->
  <line x1="120" y1="130" x2="210" y2="130" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="210" cy="130" r="4" fill="#e05c1a"/>
  <text x="215" y="127" fill="#e05c1a" font-weight="bold">P</text>
  <text x="155" y="123" fill="#1a3a5c" font-size="11">r</text>
  <!-- Tangent line at P -->
  <line x1="210" y1="55" x2="210" y2="205" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="215" y="80" fill="#e05c1a">tangent</text>
  <!-- Right angle -->
  <rect x="200" y="120" width="10" height="10" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <!-- Theorem label -->
  <text x="20" y="225" fill="#1a3a5c" font-size="11">Thm 10.10: radius ⊥ tangent at point of tangency</text>

  <!-- Right: Two tangents from external point -->
  <circle cx="380" cy="130" r="75" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="380" cy="130" r="3" fill="#1a3a5c"/>
  <text x="387" y="127" fill="#1a3a5c" font-weight="bold">O</text>
  <!-- External point Q -->
  <circle cx="510" cy="130" r="4" fill="#2e8b57"/>
  <text x="514" y="127" fill="#2e8b57" font-weight="bold">Q</text>
  <!-- Tangent lines from Q to circle -->
  <line x1="510" y1="130" x2="340" y2="62" stroke="#2e8b57" stroke-width="2"/>
  <line x1="510" y1="130" x2="340" y2="198" stroke="#2e8b57" stroke-width="2"/>
  <!-- Tangent points A, B -->
  <circle cx="340" cy="62" r="4" fill="#1a3a5c"/>
  <circle cx="340" cy="198" r="4" fill="#1a3a5c"/>
  <text x="324" y="59" fill="#1a3a5c">A</text>
  <text x="324" y="203" fill="#1a3a5c">B</text>
  <!-- Equal mark -->
  <text x="420" y="88" fill="#2e8b57" font-size="12">QA</text>
  <text x="420" y="178" fill="#2e8b57" font-size="12">QB</text>
  <text x="435" y="133" fill="#2e8b57" font-size="14" font-weight="bold">=</text>
  <text x="295" y="248" fill="#1a3a5c" font-size="11">Thm 10.11: QA = QB (two tangents from ext. point)</text>
</svg>

| Theorem | Statement |
|---------|-----------|
| **Thm 10.10** | A tangent to a circle is perpendicular to the radius at the point of tangency |
| **Thm 10.11** | Two tangent segments from the same external point are congruent |

---

# Angle Measures: Secants & Tangents

<svg viewBox="0 0 540 270" width="540" height="270" xmlns="http://www.w3.org/2000/svg" font-family="Arial" font-size="11">
  <!-- Case 1: Vertex ON circle (inscribed / tangent-chord) -->
  <g transform="translate(0,0)">
    <circle cx="90" cy="135" r="75" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
    <circle cx="90" cy="210" r="4" fill="#e05c1a"/>
    <text x="72" y="228" fill="#e05c1a" font-weight="bold">P (on circle)</text>
    <line x1="90" y1="210" x2="155" y2="75" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="90" y1="210" x2="15" y2="135" stroke="#e05c1a" stroke-width="2"/>
    <!-- arc labels -->
    <path d="M 155,75 A 75,75 0 0,0 15,135" fill="none" stroke="#1a3a5c" stroke-width="3"/>
    <text x="50" y="72" fill="#1a3a5c" font-size="10">arc a</text>
    <text x="8" y="245" fill="#e05c1a" font-size="10">angle = (1/2) arc a</text>
    <text x="8" y="258" fill="#1a3a5c" font-size="10">vertex ON circle</text>
  </g>

  <!-- Case 2: Vertex INSIDE circle (two chords) -->
  <g transform="translate(182,0)">
    <circle cx="90" cy="135" r="75" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
    <!-- chord 1 -->
    <line x1="20" y1="90" x2="165" y2="175" stroke="#1a3a5c" stroke-width="2"/>
    <!-- chord 2 -->
    <line x1="25" y1="185" x2="160" y2="80" stroke="#e05c1a" stroke-width="2"/>
    <!-- intersection -->
    <circle cx="89" cy="133" r="4" fill="#2e8b57"/>
    <text x="94" y="131" fill="#2e8b57" font-weight="bold">X</text>
    <!-- arc labels -->
    <text x="85" y="55" fill="#1a3a5c" font-size="10">arc a</text>
    <text x="130" y="175" fill="#e05c1a" font-size="10">arc b</text>
    <text x="8" y="245" fill="#2e8b57" font-size="10">angle = (1/2)(a + b)</text>
    <text x="8" y="258" fill="#1a3a5c" font-size="10">vertex INSIDE circle</text>
  </g>

  <!-- Case 3: Vertex OUTSIDE circle -->
  <g transform="translate(364,0)">
    <circle cx="90" cy="135" r="75" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
    <!-- External point -->
    <circle cx="195" cy="135" r="4" fill="#9b59b6"/>
    <text x="200" y="133" fill="#9b59b6" font-weight="bold">Q</text>
    <!-- Two secants -->
    <line x1="195" y1="135" x2="20" y2="80" stroke="#9b59b6" stroke-width="2"/>
    <line x1="195" y1="135" x2="20" y2="190" stroke="#1a3a5c" stroke-width="2"/>
    <!-- Intercept arcs -->
    <path d="M 20,80 A 75,75 0 0,0 20,190" fill="none" stroke="#1a3a5c" stroke-width="3"/>
    <text x="22" y="80" fill="#9b59b6" font-size="10">far arc F</text>
    <text x="22" y="200" fill="#1a3a5c" font-size="10">near arc N</text>
    <text x="10" y="245" fill="#9b59b6" font-size="10">angle = (1/2)(F - N)</text>
    <text x="10" y="258" fill="#1a3a5c" font-size="10">vertex OUTSIDE circle</text>
  </g>
</svg>

| Vertex Location | Angle Formula |
|----------------|--------------|
| **On circle** (inscribed or tangent-chord) | $\angle = \dfrac{1}{2} \overset{\frown}{arc}$ |
| **Inside circle** (two chords cross) | $\angle = \dfrac{1}{2}(\overset{\frown}{a} + \overset{\frown}{b})$ |
| **Outside circle** (two secants/tangent) | $\angle = \dfrac{1}{2}(\overset{\frown}{far} - \overset{\frown}{near})$ |

---

# Segment Lengths in Circles

<svg viewBox="0 0 530 250" width="530" height="250" xmlns="http://www.w3.org/2000/svg" font-family="Arial" font-size="11">
  <!-- Case 1: Two chords intersecting inside -->
  <g transform="translate(0,0)">
    <circle cx="100" cy="125" r="85" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
    <!-- Chord AC -->
    <line x1="22" y1="90" x2="178" y2="160" stroke="#1a3a5c" stroke-width="2"/>
    <!-- Chord BD -->
    <line x1="30" y1="185" x2="170" y2="65" stroke="#e05c1a" stroke-width="2"/>
    <!-- Intersection E -->
    <circle cx="100" cy="125" r="4" fill="#2e8b57"/>
    <!-- Labels -->
    <text x="8" y="88" fill="#1a3a5c">A</text><text x="180" y="160" fill="#1a3a5c">C</text>
    <text x="16" y="190" fill="#e05c1a">B</text><text x="172" y="65" fill="#e05c1a">D</text>
    <text x="108" y="122" fill="#2e8b57">E</text>
    <!-- Segment labels -->
    <text x="38" y="110" fill="#1a3a5c" font-size="10">a</text>
    <text x="143" y="148" fill="#1a3a5c" font-size="10">c</text>
    <text x="55" y="165" fill="#e05c1a" font-size="10">b</text>
    <text x="140" y="82" fill="#e05c1a" font-size="10">d</text>
    <text x="20" y="225" fill="#2e8b57" font-size="11" font-weight="bold">a · c = b · d</text>
    <text x="5" y="240" fill="#1a3a5c" font-size="10">chords inside circle</text>
  </g>

  <!-- Case 2: Two secants from external point -->
  <g transform="translate(190,0)">
    <circle cx="100" cy="125" r="75" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
    <circle cx="210" cy="125" r="4" fill="#9b59b6"/>
    <text x="215" y="123" fill="#9b59b6" font-weight="bold">P</text>
    <!-- Secant 1 -->
    <line x1="210" y1="125" x2="30" y2="80" stroke="#1a3a5c" stroke-width="2"/>
    <!-- Secant 2 -->
    <line x1="210" y1="125" x2="30" y2="170" stroke="#e05c1a" stroke-width="2"/>
    <!-- Near and far points -->
    <circle cx="170" cy="115" r="3" fill="#1a3a5c"/>
    <circle cx="55" cy="84" r="3" fill="#1a3a5c"/>
    <circle cx="162" cy="133" r="3" fill="#e05c1a"/>
    <circle cx="45" cy="162" r="3" fill="#e05c1a"/>
    <!-- Labels -->
    <text x="170" y="108" fill="#1a3a5c" font-size="10">A</text>
    <text x="40" y="81" fill="#1a3a5c" font-size="10">B</text>
    <text x="155" y="147" fill="#e05c1a" font-size="10">C</text>
    <text x="30" y="167" fill="#e05c1a" font-size="10">D</text>
    <text x="20" y="225" fill="#9b59b6" font-size="11" font-weight="bold">PA · PB = PC · PD</text>
    <text x="5" y="240" fill="#1a3a5c" font-size="10">two secants from outside</text>
  </g>

  <!-- Case 3: Secant + Tangent from external point -->
  <g transform="translate(368,0)">
    <circle cx="80" cy="125" r="70" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
    <circle cx="185" cy="125" r="4" fill="#c0392b"/>
    <text x="190" y="123" fill="#c0392b" font-weight="bold">P</text>
    <!-- Tangent -->
    <line x1="185" y1="125" x2="80" y2="55" stroke="#c0392b" stroke-width="2.5"/>
    <circle cx="80" cy="55" r="3" fill="#c0392b"/>
    <text x="68" y="50" fill="#c0392b" font-size="10">T</text>
    <!-- Secant -->
    <line x1="185" y1="125" x2="14" y2="155" stroke="#1a3a5c" stroke-width="2"/>
    <circle cx="148" cy="133" r="3" fill="#1a3a5c"/>
    <circle cx="18" cy="153" r="3" fill="#1a3a5c"/>
    <text x="148" y="147" fill="#1a3a5c" font-size="10">A</text>
    <text x="5" y="152" fill="#1a3a5c" font-size="10">B</text>
    <!-- Formula -->
    <text x="5" y="225" fill="#c0392b" font-size="11" font-weight="bold">PT² = PA · PB</text>
    <text x="5" y="240" fill="#1a3a5c" font-size="10">tangent-secant from outside</text>
  </g>
</svg>

| Configuration | Formula |
|--------------|---------|
| Two chords intersect **inside** | $a \cdot c = b \cdot d$ |
| Two secants from **outside** | $PA \cdot PB = PC \cdot PD$ |
| Tangent & secant from **outside** | $PT^2 = PA \cdot PB$ |

---

# Equation of a Circle

<svg viewBox="0 0 520 255" width="520" height="255" xmlns="http://www.w3.org/2000/svg" font-family="Arial" font-size="12">
  <!-- Coordinate axes -->
  <line x1="30" y1="210" x2="280" y2="210" stroke="#888" stroke-width="1.5"/>
  <line x1="155" y1="20" x2="155" y2="230" stroke="#888" stroke-width="1.5"/>
  <text x="283" y="214" fill="#888">x</text>
  <text x="157" y="18" fill="#888">y</text>
  <!-- Circle centered at (h,k) -->
  <circle cx="155" cy="120" r="80" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Center -->
  <circle cx="155" cy="120" r="4" fill="#e05c1a"/>
  <text x="160" y="117" fill="#e05c1a" font-weight="bold">(h, k)</text>
  <!-- Radius to edge -->
  <line x1="155" y1="120" x2="220" y2="60" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="220" cy="60" r="4" fill="#1a3a5c"/>
  <text x="225" y="57" fill="#1a3a5c">(x, y)</text>
  <text x="182" y="82" fill="#1a3a5c">r</text>
  <!-- Dashed legs of right triangle -->
  <line x1="155" y1="120" x2="220" y2="120" stroke="#aaa" stroke-width="1" stroke-dasharray="4,3"/>
  <line x1="220" y1="60" x2="220" y2="120" stroke="#aaa" stroke-width="1" stroke-dasharray="4,3"/>
  <text x="183" y="135" fill="#888" font-size="11">x − h</text>
  <text x="224" y="95" fill="#888" font-size="11">y − k</text>
  <!-- Right angle -->
  <rect x="212" y="112" width="8" height="8" fill="none" stroke="#aaa" stroke-width="1.5"/>

  <!-- Formula box -->
  <rect x="295" y="30" width="215" height="200" rx="6" fill="#f4f8fc" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="305" y="55" fill="#1a3a5c" font-weight="bold" font-size="13">Standard Form</text>
  <text x="305" y="85" fill="#e05c1a" font-size="14" font-weight="bold">(x-h)²+(y-k)²=r²</text>
  <text x="305" y="108" fill="#1a3a5c" font-size="11">center (h, k), radius r</text>
  <line x1="295" y1="118" x2="510" y2="118" stroke="#aecde8" stroke-width="1"/>
  <text x="305" y="138" fill="#1a3a5c" font-weight="bold" font-size="12">Example:</text>
  <text x="305" y="158" fill="#1a3a5c" font-size="11">Center (3, -2), r = 5</text>
  <text x="305" y="178" fill="#e05c1a" font-size="11">(x-3)²+(y+2)²=25</text>
  <line x1="295" y1="190" x2="510" y2="190" stroke="#aecde8" stroke-width="1"/>
  <text x="305" y="210" fill="#1a3a5c" font-weight="bold" font-size="12">Origin form (h=0, k=0):</text>
  <text x="305" y="228" fill="#e05c1a" font-size="12">x² + y² = r²</text>
</svg>

> Derived from the **Distance Formula**: $r = \sqrt{(x-h)^2 + (y-k)^2}$, squaring both sides gives the circle equation.

To find center/radius from general form $x^2+y^2+Dx+Ey+F=0$: **complete the square** for both $x$ and $y$.

---

# Arc Length & Sector Area

<svg viewBox="0 0 520 250" width="520" height="250" xmlns="http://www.w3.org/2000/svg" font-family="Arial" font-size="12">
  <!-- Left: Arc length diagram -->
  <circle cx="110" cy="125" r="90" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="110" cy="125" r="3" fill="#1a3a5c"/>
  <text x="116" y="122" fill="#1a3a5c" font-weight="bold">O</text>
  <!-- Radii -->
  <line x1="110" y1="125" x2="185" y2="45" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="110" y1="125" x2="200" y2="155" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="185" cy="45" r="4" fill="#1a3a5c"/>
  <circle cx="200" cy="155" r="4" fill="#1a3a5c"/>
  <text x="189" y="42" fill="#1a3a5c">A</text>
  <text x="204" y="158" fill="#1a3a5c">B</text>
  <!-- Arc AB highlighted -->
  <path d="M 185,45 A 90,90 0 0,1 200,155" fill="none" stroke="#e05c1a" stroke-width="5"/>
  <!-- Central angle label -->
  <path d="M 152,100 A 42,42 0 0,1 158,145" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="162" y="125" fill="#e05c1a" font-size="11">N°</text>
  <!-- Sector shading -->
  <path d="M 110,125 L 185,45 A 90,90 0 0,1 200,155 Z" fill="#fff3e0" fill-opacity="0.6" stroke="none"/>
  <text x="145" y="108" fill="#e05c1a" font-size="10">sector</text>
  <!-- r label -->
  <text x="140" y="75" fill="#1a3a5c" font-size="11">r</text>

  <!-- Right: Formulas -->
  <rect x="260" y="20" width="250" height="215" rx="6" fill="#f4f8fc" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="270" y="45" fill="#1a3a5c" font-weight="bold" font-size="13">Arc Length</text>
  <text x="270" y="70" fill="#e05c1a" font-size="13">L = (N/360) × 2πr</text>
  <text x="270" y="90" fill="#1a3a5c" font-size="11">N = central angle (degrees)</text>
  <line x1="260" y1="100" x2="510" y2="100" stroke="#aecde8" stroke-width="1"/>
  <text x="270" y="120" fill="#1a3a5c" font-weight="bold" font-size="13">Sector Area</text>
  <text x="270" y="145" fill="#e05c1a" font-size="13">A = (N/360) × πr²</text>
  <text x="270" y="165" fill="#1a3a5c" font-size="11">fraction of circle × full area</text>
  <line x1="260" y1="175" x2="510" y2="175" stroke="#aecde8" stroke-width="1"/>
  <text x="270" y="195" fill="#1a3a5c" font-weight="bold" font-size="12">Segment Area</text>
  <text x="270" y="215" fill="#1a3a5c" font-size="11">= Sector area - Triangle area</text>
  <text x="270" y="228" fill="#1a3a5c" font-size="11">(sector OAB minus triangle OAB)</text>
</svg>

| Quantity | Formula | Note |
|---------|---------|------|
| **Circumference** | $C = 2\pi r = \pi d$ | Full circle |
| **Arc Length** | $\ell = \dfrac{N}{360} \cdot 2\pi r$ | $N$ = central angle° |
| **Sector Area** | $A = \dfrac{N}{360} \cdot \pi r^2$ | Pie-slice region |
| **Segment Area** | Sector $-$ $\triangle OAB$ | Region between chord and arc |

---

<!-- _class: summary -->
# Chapter 10 — Quick Reference

| # | Theorem / Formula | Key Idea |
|---|------------------|---------|
| **10.2** | ≅ chords ↔ ≅ arcs | in same or ≅ circles |
| **10.3** | Diameter ⊥ chord ↔ bisects chord & arc | perpendicular bisector passes through center |
| **10.4** | Equidistant chords are ≅ | |
| **10.6** | Inscribed ∠ = ½ intercepted arc | vertex ON circle |
| **10.7** | Inscribed ∠ in semicircle = 90° | intercepts diameter |
| **10.8** | Inscribed ∠s same arc are ≅ | |
| **10.9** | Inscribed quad: opp. ∠s supplementary | ∠A+∠C=180° |
| **10.10** | Radius ⊥ tangent at tangent point | |
| **10.11** | 2 tangents from ext. pt. are ≅ | |
| **Angles** | On: ½arc · Inside: ½(a+b) · Outside: ½(far−near) | location of vertex matters |
| **Segments** | Chords: $ac=bd$ · Secants: $PA·PB=PC·PD$ · Tangent: $PT^2=PA·PB$ | |
| **Equation** | $(x-h)^2+(y-k)^2=r^2$ | center $(h,k)$, radius $r$ |
| **Arc length** | $\frac{N}{360}\cdot 2\pi r$ | **Sector area:** $\frac{N}{360}\cdot\pi r^2$ |
