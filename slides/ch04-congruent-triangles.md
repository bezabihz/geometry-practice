---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 4
## Congruent Triangles

McGraw Hill Glencoe Geometry · Texas Edition

---

## Triangle Angle Sum & Exterior Angle

<div class="columns">
<div>

**Theorem 4-1 (Triangle Angle Sum):**
The sum of the interior angles of any triangle is 180°.
$$\angle A + \angle B + \angle C = 180°$$

**Theorem 4-2 (Exterior Angle):**
An exterior angle of a triangle equals the sum of the two non-adjacent interior angles.
$$m\angle 4 = m\angle 1 + m\angle 2$$

**Why it works:** $\angle 3 + \angle 4 = 180°$ (linear pair) and $\angle 1 + \angle 2 + \angle 3 = 180°$, so $\angle 4 = \angle 1 + \angle 2$.

> **Example:** $\angle A = 55°$, $\angle B = 70°$. Find $\angle C$.
> $\angle C = 180° - 55° - 70° = \mathbf{55°}$

</div>
<div>

<svg width="300" height="270" viewBox="0 0 300 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Triangle -->
  <polygon points="30,200 270,200 150,50" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Angle arcs -->
  <path d="M55,200 A25,25 0 0,0 42,178" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M245,200 A25,25 0 0,1 258,178" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M140,68 A20,20 0 0,1 160,68" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <!-- Labels -->
  <text x="18" y="225" font-size="15" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="260" y="225" font-size="15" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="143" y="42" font-size="15" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="46" y="196" font-size="13" fill="#e05c1a" font-family="Arial">55°</text>
  <text x="234" y="196" font-size="13" fill="#e05c1a" font-family="Arial">70°</text>
  <text x="144" y="86" font-size="13" fill="#e05c1a" font-family="Arial">55°</text>
  <!-- Exterior angle -->
  <line x1="270" y1="200" x2="300" y2="200" stroke="#555" stroke-width="2"/>
  <path d="M280,200 A15,15 0 0,0 273,186" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <text x="284" y="192" font-size="12" fill="#1a3a5c" font-family="Arial">∠4</text>
  <text x="25" y="252" font-size="12" fill="#555" font-family="Arial">∠4 = 55° + 55° = 110° (ext. angle thm)</text>
</svg>

</div>
</div>

---

## Congruent Triangles & CPCTC

Two triangles are **congruent** if all 6 corresponding parts (3 sides + 3 angles) are equal.

<div class="columns">
<div>

**CPCTC** — Corresponding Parts of Congruent Triangles are Congruent.

Use CPCTC as the reason *after* proving triangles congruent with a shortcut.

| Shortcut | What you need |
|----------|---------------|
| **SSS** | 3 pairs of ≅ sides |
| **SAS** | 2 sides + included angle |
| **ASA** | 2 angles + included side |
| **AAS** | 2 angles + non-included side |
| **HL** | Hypotenuse + leg (right △ only) |
| ~~AAA~~ | ✗ Only proves similarity |
| ~~SSA~~ | ✗ Ambiguous case |

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Triangle 1 -->
  <polygon points="20,200 120,200 70,80" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="8" y="220" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="120" y="220" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="63" y="72" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <!-- Triangle 2 -->
  <polygon points="165,200 265,200 215,80" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="153" y="220" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">D</text>
  <text x="265" y="220" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">E</text>
  <text x="208" y="72" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">F</text>
  <!-- Congruence marks -->
  <line x1="37" y1="148" x2="42" y2="144" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="39" y1="152" x2="44" y2="148" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="183" y1="148" x2="188" y2="144" stroke="#e05c1a" stroke-width="2"/>
  <line x1="185" y1="152" x2="190" y2="148" stroke="#e05c1a" stroke-width="2"/>
  <line x1="64" y1="202" x2="68" y2="202" stroke="#1a3a5c" stroke-width="3"/>
  <line x1="66" y1="199" x2="66" y2="205" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="208" y1="202" x2="212" y2="202" stroke="#e05c1a" stroke-width="3"/>
  <line x1="210" y1="199" x2="210" y2="205" stroke="#e05c1a" stroke-width="2"/>
  <!-- CPCTC arrow -->
  <line x1="130" y1="160" x2="165" y2="160" stroke="#555" stroke-width="2"/>
  <polygon points="165,160 155,155 155,165" fill="#555"/>
  <text x="128" y="250" font-size="12" fill="#555" font-family="Arial">△ABC ≅ △DEF  →  CPCTC</text>
</svg>

</div>
</div>

---

## SSS and SAS Congruence

<div class="columns">
<div>

**Postulate 4-1 — SSS**
If all three sides of one triangle are congruent to all three sides of another triangle, the triangles are congruent.

**Postulate 4-2 — SAS**
If two sides and the **included angle** are congruent, the triangles are congruent.

> ⚠️ The angle must be **between** the two sides (included).
> SSA (angle not included) is **not** a valid shortcut.

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- SSS label -->
  <text x="30" y="18" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">SSS</text>
  <!-- Triangle A (SSS) -->
  <polygon points="15,90 115,90 65,20" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Tick marks: 3 sides -->
  <line x1="38" y1="58" x2="43" y2="54" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="90" y1="58" x2="95" y2="62" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="62" y1="92" x2="68" y2="92" stroke="#555" stroke-width="2.5"/>
  <!-- Triangle B (SSS) -->
  <polygon points="155,90 255,90 205,20" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <line x1="178" y1="58" x2="183" y2="54" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="230" y1="58" x2="235" y2="62" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="202" y1="92" x2="208" y2="92" stroke="#555" stroke-width="2.5"/>
  <text x="130" y="58" font-size="18" fill="#555" font-family="Arial">≅</text>

  <!-- SAS label -->
  <text x="30" y="130" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">SAS</text>
  <!-- Triangle C (SAS) -->
  <polygon points="15,210 115,210 75,145" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <line x1="38" y1="182" x2="43" y2="178" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="62" y1="212" x2="68" y2="212" stroke="#555" stroke-width="2.5"/>
  <path d="M33,210 A22,22 0 0,0 27,190" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Triangle D (SAS) -->
  <polygon points="155,210 255,210 215,145" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <line x1="178" y1="182" x2="183" y2="178" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="202" y1="212" x2="208" y2="212" stroke="#555" stroke-width="2.5"/>
  <path d="M173,210 A22,22 0 0,0 167,190" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="130" y="178" font-size="18" fill="#555" font-family="Arial">≅</text>
  <text x="15" y="245" font-size="12" fill="#555" font-family="Arial">Included angle = angle between the two ≅ sides</text>
</svg>

</div>
</div>

---

## ASA, AAS, and HL

<div class="columns">
<div>

**Postulate 4-3 — ASA**
Two angles and the **included side** are congruent.

**Theorem 4-3 — AAS**
Two angles and a **non-included side** are congruent.

> ASA and AAS: once two angles are known, the third is determined (180° − sum). They differ only in *which* side is specified.

**Theorem 4-4 — HL (Hypotenuse-Leg)**
For **right triangles only**: hypotenuse and one leg are congruent.

> HL is a special case — it works because the Pythagorean theorem determines the missing leg.

</div>
<div>

<svg width="290" height="280" viewBox="0 0 290 280" xmlns="http://www.w3.org/2000/svg">
  <!-- ASA -->
  <text x="10" y="18" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">ASA — included side</text>
  <polygon points="15,80 115,80 65,20" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M30,80 A18,18 0 0,0 25,63" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <path d="M100,80 A18,18 0 0,1 105,63" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="62" y1="82" x2="68" y2="82" stroke="#1a3a5c" stroke-width="3"/>
  <polygon points="155,80 255,80 205,20" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M170,80 A18,18 0 0,0 165,63" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <path d="M240,80 A18,18 0 0,1 245,63" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="202" y1="82" x2="208" y2="82" stroke="#1a3a5c" stroke-width="3"/>
  <text x="127" y="56" font-size="16" fill="#555" font-family="Arial">≅</text>

  <!-- HL -->
  <text x="10" y="130" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">HL — right triangles only</text>
  <polygon points="15,220 115,220 15,145" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <rect x="15" y="205" width="14" height="14" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <line x1="58" y1="185" x2="64" y2="181" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="14" y1="180" x2="14" y2="186" stroke="#1a3a5c" stroke-width="3"/>
  <line x1="11" y1="183" x2="17" y2="183" stroke="#1a3a5c" stroke-width="3"/>
  <polygon points="165,220 265,220 165,145" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <rect x="165" y="205" width="14" height="14" fill="none" stroke="#1a3a5c" stroke-width="1.5"/>
  <line x1="208" y1="185" x2="214" y2="181" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="164" y1="180" x2="164" y2="186" stroke="#1a3a5c" stroke-width="3"/>
  <line x1="161" y1="183" x2="167" y2="183" stroke="#1a3a5c" stroke-width="3"/>
  <text x="127" y="190" font-size="16" fill="#555" font-family="Arial">≅</text>
  <text x="14" y="248" font-size="11" fill="#555" font-family="Arial">H = hypotenuse (opp. right angle), L = leg</text>
</svg>

</div>
</div>

---

## Isosceles & Equilateral Triangles

<div class="columns">
<div>

**Theorem 4-5 (Isosceles Triangle):**
If two sides of a triangle are congruent, then the base angles opposite those sides are congruent.

$$\overline{AB} \cong \overline{AC} \;\Rightarrow\; \angle B \cong \angle C$$

**Theorem 4-6 (Converse):**
If two angles of a triangle are congruent, then the sides opposite them are congruent.

**Corollary 4-2 (Equilateral):**
An equilateral triangle is also equiangular — each angle is **60°**.

> **Memory trick:** "Base angles of an isosceles triangle are equal" — think of the triangle as a rooftop; the two base angles hold up the same roof equally.

</div>
<div>

<svg width="290" height="260" viewBox="0 0 290 260" xmlns="http://www.w3.org/2000/svg">
  <!-- Isosceles triangle -->
  <polygon points="145,25 30,210 260,210" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Equal side marks -->
  <line x1="80" y1="110" x2="85" y2="106" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="83" y1="114" x2="88" y2="110" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="210" y1="106" x2="215" y2="110" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="207" y1="110" x2="212" y2="114" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Base angle arcs -->
  <path d="M54,210 A24,24 0 0,0 45,188" fill="none" stroke="#1a3a5c" stroke-width="2.5"/>
  <path d="M236,210 A24,24 0 0,1 245,188" fill="none" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Labels -->
  <text x="136" y="18" font-size="15" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="18" y="228" font-size="15" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="257" y="228" font-size="15" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="44" y="207" font-size="13" fill="#1a3a5c" font-family="Arial">β</text>
  <text x="240" y="207" font-size="13" fill="#1a3a5c" font-family="Arial">β</text>
  <text x="50" y="95" font-size="13" fill="#e05c1a" font-family="Arial">≅</text>
  <text x="214" y="95" font-size="13" fill="#e05c1a" font-family="Arial">≅</text>
  <!-- Base mark -->
  <line x1="143" y1="212" x2="147" y2="212" stroke="#555" stroke-width="3"/>
  <text x="40" y="250" font-size="13" fill="#555" font-family="Arial">AB ≅ AC  ⟹  ∠B ≅ ∠C</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example — Proving Triangle Congruence

**Given:** $M$ is the midpoint of $\overline{AC}$, $\angle 1 \cong \angle 2$. **Prove:** $\triangle ABM \cong \triangle CBM$

<div class="columns">
<div>

| # | Statement | Reason |
|---|-----------|--------|
| 1 | $M$ is midpoint of $\overline{AC}$ | Given |
| 2 | $\overline{AM} \cong \overline{CM}$ | Def. of midpoint |
| 3 | $\angle 1 \cong \angle 2$ | Given |
| 4 | $\overline{BM} \cong \overline{BM}$ | Reflexive Prop. |
| 5 | $\triangle ABM \cong \triangle CBM$ | **SAS** (2, 3, 4) |

**CPCTC:** $\overline{AB} \cong \overline{CB}$, $\angle ABM \cong \angle CBM$

</div>
<div>

<svg width="260" height="230" viewBox="0 0 260 230" xmlns="http://www.w3.org/2000/svg">
  <polygon points="130,20 20,210 240,210" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="130" y1="20" x2="130" y2="210" stroke="#e05c1a" stroke-width="2" stroke-dasharray="6,3"/>
  <circle cx="130" cy="210" r="6" fill="#e05c1a"/>
  <!-- Congruence marks on AM and CM -->
  <line x1="73" y1="212" x2="77" y2="212" stroke="#1a3a5c" stroke-width="3"/>
  <line x1="183" y1="212" x2="187" y2="212" stroke="#1a3a5c" stroke-width="3"/>
  <!-- Angle marks ∠1, ∠2 -->
  <path d="M130,40 A18,18 0 0,0 116,50" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M130,40 A18,18 0 0,1 144,50" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="100" y="52" font-size="12" fill="#e05c1a" font-family="Arial">∠1</text>
  <text x="140" y="52" font-size="12" fill="#e05c1a" font-family="Arial">∠2</text>
  <!-- Labels -->
  <text x="124" y="14" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="6" y="218" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="244" y="218" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="122" y="228" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">M</text>
  <text x="35" y="180" font-size="12" fill="#1a3a5c" font-family="Arial">△ABM</text>
  <text x="165" y="180" font-size="12" fill="#1a3a5c" font-family="Arial">△CBM</text>
</svg>

</div>
</div>

---

## Chapter 4 — Summary

| Shortcut | Requirements | Note |
|----------|-------------|------|
| **SSS** | 3 ≅ sides | — |
| **SAS** | 2 ≅ sides + included ∠ | Angle must be between the sides |
| **ASA** | 2 ≅ angles + included side | Side must be between the angles |
| **AAS** | 2 ≅ angles + non-included side | — |
| **HL** | Hyp. + leg | Right triangles only |
| **CPCTC** | After ≅ is proven | All 6 remaining parts are equal |
| **Isosceles Thm** | 2 ≅ sides → 2 ≅ base angles | Converse also true |

> **NOT valid:** AAA (gives similarity only) · SSA (ambiguous — two possible triangles)
