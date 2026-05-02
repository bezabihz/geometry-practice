---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 4 — Cheatsheet
# Congruent Triangles

**Unit 2 | Glencoe Geometry TX 2015**

---

## Triangle Angle Sum & Exterior Angle Theorems

<svg width="950" height="320" viewBox="0 0 950 320" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Angle Sum -->
  <rect x="10" y="10" width="440" height="295" rx="8" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <text x="230" y="34" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Theorem 4-1: Triangle Angle Sum</text>
  <polygon points="230,70 80,240 380,240" fill="#d0e8ff" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="230" y="62" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="66" y="255" font-size="14" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="383" y="255" font-size="14" font-weight="bold" fill="#1a3a5c">C</text>
  <!-- Angle arcs -->
  <path d="M 230,95 A 26,26 0 0 1 215,96" stroke="#e05c1a" fill="rgba(220,80,0,0.15)" stroke-width="2"/>
  <path d="M 100,240 A 26,26 0 0 1 103,215" stroke="#2a7a2a" fill="rgba(40,150,40,0.15)" stroke-width="2"/>
  <path d="M 356,215 A 26,26 0 0 1 360,240" stroke="#1565C0" fill="rgba(20,100,200,0.15)" stroke-width="2"/>
  <text x="235" y="105" font-size="13" fill="#e05c1a" font-weight="bold">∠A</text>
  <text x="110" y="225" font-size="13" fill="#2a7a2a" font-weight="bold">∠B</text>
  <text x="335" y="225" font-size="13" fill="#1565C0" font-weight="bold">∠C</text>
  <text x="230" y="276" text-anchor="middle" font-size="14" fill="#1a3a5c" font-weight="bold">∠A + ∠B + ∠C = 180°</text>
  <text x="230" y="296" text-anchor="middle" font-size="11" fill="#555">All interior angles of any triangle sum to 180°</text>

  <!-- Exterior Angle -->
  <rect x="470" y="10" width="470" height="295" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="705" y="34" text-anchor="middle" font-size="14" font-weight="bold" fill="#e05c1a">Theorem 4-2: Exterior Angle Theorem</text>
  <polygon points="620,70 520,240 820,240" fill="#ffe0cc" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="620" y="62" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="506" y="255" font-size="14" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="822" y="255" font-size="14" font-weight="bold" fill="#1a3a5c">C</text>
  <!-- Exterior angle extension -->
  <line x1="520" y1="240" x2="900" y2="240" stroke="#e05c1a" stroke-width="2"/>
  <text x="880" y="255" font-size="13" fill="#e05c1a" font-weight="bold">D</text>
  <!-- Exterior angle arc -->
  <path d="M 844,214 A 28,28 0 0 1 848,240" stroke="#cc2200" fill="rgba(180,0,0,0.15)" stroke-width="2.5"/>
  <text x="856" y="226" font-size="15" fill="#cc2200" font-weight="bold">∠4</text>
  <!-- Remote interior angle arcs -->
  <path d="M 620,92 A 24,24 0 0 1 605,94" stroke="#2a7a2a" fill="rgba(40,150,40,0.15)" stroke-width="2"/>
  <path d="M 540,240 A 24,24 0 0 1 542,217" stroke="#1565C0" fill="rgba(20,100,200,0.15)" stroke-width="2"/>
  <text x="624" y="105" font-size="13" fill="#2a7a2a" font-weight="bold">∠1</text>
  <text x="548" y="226" font-size="13" fill="#1565C0" font-weight="bold">∠2</text>
  <text x="705" y="276" text-anchor="middle" font-size="14" fill="#e05c1a" font-weight="bold">∠4 = ∠1 + ∠2</text>
  <text x="705" y="296" text-anchor="middle" font-size="11" fill="#555">Exterior ∠ = sum of two non-adjacent interior ∠s</text>
</svg>

---

## Congruence Shortcuts: SSS and SAS

<svg width="950" height="320" viewBox="0 0 950 320" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- SSS -->
  <rect x="10" y="10" width="450" height="300" rx="8" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <text x="235" y="34" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Postulate 4-1: SSS Congruence</text>
  <text x="235" y="54" text-anchor="middle" font-size="12" fill="#555">If 3 sides of one △ ≅ 3 sides of another → △s ≅</text>
  <!-- Triangle 1 -->
  <polygon points="80,200 200,90 320,200" fill="#d0e8ff" stroke="#1a3a5c" stroke-width="2"/>
  <text x="65" y="214" font-size="12" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="199" y="82" font-size="12" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="322" y="214" font-size="12" font-weight="bold" fill="#1a3a5c">C</text>
  <!-- Tick marks -->
  <line x1="127" y1="152" x2="137" y2="142" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="258" y1="142" x2="268" y2="152" stroke="#2a7a2a" stroke-width="2.5"/>
  <line x1="197" y1="200" x2="203" y2="200" stroke="#1565C0" stroke-width="3"/>
  <!-- = sign -->
  <text x="235" y="225" text-anchor="middle" font-size="20" fill="#1a3a5c">≅</text>
  <text x="235" y="260" text-anchor="middle" font-size="13" fill="#1a3a5c">△ABC ≅ △DEF</text>
  <text x="235" y="278" text-anchor="middle" font-size="12" fill="#555">AB=DE, BC=EF, AC=DF</text>
  <text x="235" y="298" text-anchor="middle" font-size="11" fill="#2a7a2a">No angle info needed!</text>

  <!-- SAS -->
  <rect x="490" y="10" width="450" height="300" rx="8" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="2"/>
  <text x="715" y="34" text-anchor="middle" font-size="14" font-weight="bold" fill="#2a7a2a">Postulate 4-2: SAS Congruence</text>
  <text x="715" y="54" text-anchor="middle" font-size="12" fill="#555">2 sides + included angle → △s ≅</text>
  <!-- Triangle -->
  <polygon points="560,200 680,90 800,200" fill="#c0ecc0" stroke="#2a7a2a" stroke-width="2"/>
  <text x="545" y="214" font-size="12" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="679" y="82" font-size="12" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="802" y="214" font-size="12" font-weight="bold" fill="#1a3a5c">C</text>
  <!-- Side ticks on 2 sides -->
  <line x1="607" y1="152" x2="617" y2="142" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="677" y1="200" x2="683" y2="200" stroke="#1565C0" stroke-width="3"/>
  <!-- Included angle arc at B -->
  <path d="M 664,108 A 22,22 0 0 1 696,108" stroke="#cc2200" fill="rgba(200,0,0,0.15)" stroke-width="2.5"/>
  <text x="680" y="116" text-anchor="middle" font-size="11" fill="#cc2200" font-weight="bold">included ∠</text>
  <text x="715" y="260" text-anchor="middle" font-size="13" fill="#2a7a2a">AB=DE, ∠B≅∠E, BC=EF</text>
  <text x="715" y="280" text-anchor="middle" font-size="12" fill="#555">→ △ABC ≅ △DEF</text>
  <text x="715" y="298" text-anchor="middle" font-size="11" fill="#cc2200">∠ MUST be between the two sides!</text>
</svg>

---

## Congruence Shortcuts: ASA, AAS, and HL

<svg width="950" height="330" viewBox="0 0 950 330" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- ASA -->
  <rect x="10" y="10" width="290" height="305" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="155" y="30" text-anchor="middle" font-size="13" font-weight="bold" fill="#e05c1a">Post. 4-3: ASA</text>
  <text x="155" y="48" text-anchor="middle" font-size="11" fill="#555">2 angles + included side</text>
  <polygon points="50,240 155,100 260,240" fill="#ffe0cc" stroke="#e05c1a" stroke-width="2"/>
  <text x="36" y="255" font-size="12" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="154" y="92" font-size="12" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="262" y="255" font-size="12" font-weight="bold" fill="#1a3a5c">C</text>
  <path d="M 72,240 A 22,22 0 0 1 70,217" stroke="#e05c1a" fill="rgba(220,80,0,0.2)" stroke-width="2"/>
  <path d="M 238,217 A 22,22 0 0 1 238,240" stroke="#1565C0" fill="rgba(20,100,200,0.2)" stroke-width="2"/>
  <line x1="150" y1="240" x2="160" y2="240" stroke="#2a7a2a" stroke-width="3"/>
  <text x="155" y="274" text-anchor="middle" font-size="11" fill="#cc2200">side BETWEEN ∠s</text>
  <text x="155" y="292" text-anchor="middle" font-size="13" fill="#e05c1a">△ABC ≅ △DEF</text>

  <!-- AAS -->
  <rect x="320" y="10" width="290" height="305" rx="8" fill="#f0e0f8" stroke="#880088" stroke-width="2"/>
  <text x="465" y="30" text-anchor="middle" font-size="13" font-weight="bold" fill="#880088">Theorem 4-3: AAS</text>
  <text x="465" y="48" text-anchor="middle" font-size="11" fill="#555">2 angles + non-included side</text>
  <polygon points="360,240 465,100 570,240" fill="#f0d8f8" stroke="#880088" stroke-width="2"/>
  <text x="346" y="255" font-size="12" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="464" y="92" font-size="12" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="572" y="255" font-size="12" font-weight="bold" fill="#1a3a5c">C</text>
  <path d="M 382,240 A 22,22 0 0 1 380,217" stroke="#e05c1a" fill="rgba(220,80,0,0.2)" stroke-width="2"/>
  <path d="M 448,218 A 22,22 0 0 1 448,200" stroke="#1565C0" fill="rgba(20,100,200,0.2)" stroke-width="2"/>
  <!-- Non-included side tick (BC side) -->
  <line x1="513" y1="152" x2="523" y2="162" stroke="#2a7a2a" stroke-width="3"/>
  <text x="465" y="274" text-anchor="middle" font-size="11" fill="#cc2200">side NOT between ∠s</text>
  <text x="465" y="292" text-anchor="middle" font-size="13" fill="#880088">△ABC ≅ △DEF</text>

  <!-- HL -->
  <rect x="630" y="10" width="310" height="305" rx="8" fill="#fdecea" stroke="#cc2200" stroke-width="2"/>
  <text x="785" y="30" text-anchor="middle" font-size="13" font-weight="bold" fill="#cc2200">Theorem 4-4: HL</text>
  <text x="785" y="48" text-anchor="middle" font-size="11" fill="#555">Hypotenuse-Leg (RIGHT △s only)</text>
  <!-- Right triangle -->
  <polygon points="660,240 660,110 870,240" fill="#ffd0cc" stroke="#cc2200" stroke-width="2"/>
  <rect x="660" y="222" width="18" height="18" fill="none" stroke="#333" stroke-width="2"/>
  <text x="646" y="255" font-size="12" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="644" y="104" font-size="12" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="873" y="255" font-size="12" font-weight="bold" fill="#1a3a5c">C</text>
  <!-- Hypotenuse tick -->
  <line x1="756" y1="172" x2="769" y2="178" stroke="#cc2200" stroke-width="2.5"/>
  <text x="790" y="165" font-size="11" fill="#cc2200" font-weight="bold">hypotenuse</text>
  <!-- Leg tick -->
  <line x1="655" y1="175" x2="665" y2="175" stroke="#2a7a2a" stroke-width="3"/>
  <text x="785" y="280" text-anchor="middle" font-size="11" fill="#cc2200">ONLY for right triangles</text>
  <text x="785" y="298" text-anchor="middle" font-size="12" fill="#cc2200">hyp + one leg → ≅</text>
</svg>

---

## Isosceles & Equilateral Triangles

<svg width="950" height="300" viewBox="0 0 950 300" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Isosceles -->
  <rect x="10" y="10" width="450" height="280" rx="8" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <text x="235" y="32" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Theorems 4-5 &amp; 4-6: Isosceles Triangle</text>
  <polygon points="235,70 80,240 390,240" fill="#d0e8ff" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="235" y="62" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="64" y="255" font-size="14" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="393" y="255" font-size="14" font-weight="bold" fill="#1a3a5c">C</text>
  <!-- Congruent leg ticks -->
  <line x1="152" y1="162" x2="162" y2="152" stroke="#e05c1a" stroke-width="3"/>
  <line x1="308" y1="152" x2="318" y2="162" stroke="#e05c1a" stroke-width="3"/>
  <!-- Base angle arcs -->
  <path d="M 100,240 A 24,24 0 0 1 102,216" stroke="#2a7a2a" fill="rgba(40,150,40,0.2)" stroke-width="2.5"/>
  <path d="M 366,216 A 24,24 0 0 1 368,240" stroke="#2a7a2a" fill="rgba(40,150,40,0.2)" stroke-width="2.5"/>
  <text x="107" y="222" font-size="13" fill="#2a7a2a" font-weight="bold">∠B</text>
  <text x="342" y="222" font-size="13" fill="#2a7a2a" font-weight="bold">∠C</text>
  <text x="235" y="270" text-anchor="middle" font-size="13" fill="#e05c1a" font-weight="bold">AB ≅ AC  ⟹  ∠B ≅ ∠C (Thm 4-5)</text>
  <text x="235" y="287" text-anchor="middle" font-size="13" fill="#2a7a2a" font-weight="bold">∠B ≅ ∠C  ⟹  AB ≅ AC (Thm 4-6 Converse)</text>

  <!-- Equilateral -->
  <rect x="490" y="10" width="450" height="280" rx="8" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="2"/>
  <text x="715" y="32" text-anchor="middle" font-size="14" font-weight="bold" fill="#2a7a2a">Corollary 4-2: Equilateral ↔ Equiangular</text>
  <polygon points="715,70 570,240 860,240" fill="#c0ecc0" stroke="#2a7a2a" stroke-width="2.5"/>
  <text x="715" y="62" text-anchor="middle" font-size="14" font-weight="bold" fill="#2a7a2a">A</text>
  <text x="554" y="255" font-size="14" font-weight="bold" fill="#2a7a2a">B</text>
  <text x="863" y="255" font-size="14" font-weight="bold" fill="#2a7a2a">C</text>
  <!-- Triple tick marks all sides -->
  <line x1="636" y1="162" x2="646" y2="152" stroke="#2a7a2a" stroke-width="3"/>
  <line x1="639" y1="165" x2="649" y2="155" stroke="#2a7a2a" stroke-width="3"/>
  <line x1="778" y1="152" x2="788" y2="162" stroke="#2a7a2a" stroke-width="3"/>
  <line x1="781" y1="155" x2="791" y2="165" stroke="#2a7a2a" stroke-width="3"/>
  <line x1="711" y1="240" x2="719" y2="240" stroke="#2a7a2a" stroke-width="3"/>
  <line x1="714" y1="244" x2="716" y2="244" stroke="#2a7a2a" stroke-width="3"/>
  <!-- 60° labels -->
  <text x="577" y="244" font-size="14" fill="#1565C0" font-weight="bold">60°</text>
  <text x="715" y="95" text-anchor="middle" font-size="14" fill="#1565C0" font-weight="bold">60°</text>
  <text x="836" y="244" font-size="14" fill="#1565C0" font-weight="bold">60°</text>
  <text x="715" y="270" text-anchor="middle" font-size="13" fill="#2a7a2a" font-weight="bold">All sides equal ↔ all angles = 60°</text>
</svg>

---

## Chapter 4 — Complete Reference

| Shortcut | Type | Requirement | Notes |
|----------|------|-------------|-------|
| **SSS** | Postulate | 3 pairs of ≅ sides | No angles needed |
| **SAS** | Postulate | 2 sides + included ∠ | ∠ must be between sides |
| **ASA** | Postulate | 2 angles + included side | Side must be between ∠s |
| **AAS** | Theorem | 2 angles + non-included side | Side not between ∠s |
| **HL** | Theorem | Hypotenuse + leg | **Right triangles only** |
| ~~AAA~~ | ✗ Invalid | 3 angles only | Proves similarity, not congruence |
| ~~SSA~~ | ✗ Invalid | 2 sides + non-included ∠ | Ambiguous — doesn't work |

| Theorem | Statement |
|---------|-----------|
| **4-1** Angle Sum | $\angle A + \angle B + \angle C = 180°$ |
| **4-2** Exterior Angle | Ext. $\angle$ = sum of 2 remote interior $\angle$s |
| **Cor. 4-1** Third Angle | 2 pairs congruent ⟹ 3rd pair congruent |
| **4-5** Isosceles | $\cong$ sides ⟹ $\cong$ base angles |
| **4-6** Converse Isosceles | $\cong$ angles ⟹ $\cong$ opposite sides |
| **Cor. 4-2** Equilateral | Equilateral ↔ equiangular (all 60°) |

> **CPCTC:** After proving triangles congruent, all corresponding parts are congruent.
