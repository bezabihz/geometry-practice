---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 3 — Cheatsheet
# Parallel & Perpendicular Lines

**Unit 1 | Glencoe Geometry TX 2015**

---

## Lines & Angle-Pair Vocabulary

<svg width="950" height="310" viewBox="0 0 950 310" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Parallel lines with transversal -->
  <line x1="80" y1="110" x2="500" y2="110" stroke="#1a3a5c" stroke-width="3"/>
  <line x1="80" y1="230" x2="500" y2="230" stroke="#1a3a5c" stroke-width="3"/>
  <line x1="200" y1="30" x2="380" y2="310" stroke="#e05c1a" stroke-width="3"/>

  <!-- Parallel arrows -->
  <text x="510" y="114" font-size="15" fill="#1a3a5c" font-weight="bold">ℓ</text>
  <text x="510" y="234" font-size="15" fill="#1a3a5c" font-weight="bold">m</text>
  <text x="384" y="304" font-size="15" fill="#e05c1a" font-weight="bold">t</text>
  <text x="50" y="108" font-size="13" fill="#1a3a5c">←→</text>
  <text x="50" y="228" font-size="13" fill="#1a3a5c">←→</text>

  <!-- Upper intersection -->
  <circle cx="258" cy="110" r="4" fill="#333"/>
  <!-- Lower intersection -->
  <circle cx="310" cy="230" r="4" fill="#333"/>

  <!-- Upper angle labels -->
  <text x="228" y="102" font-size="15" font-weight="bold" fill="#1565C0">∠1</text>
  <text x="265" y="102" font-size="15" font-weight="bold" fill="#880088">∠2</text>
  <text x="228" y="130" font-size="15" font-weight="bold" fill="#880088">∠3</text>
  <text x="265" y="130" font-size="15" font-weight="bold" fill="#1565C0">∠4</text>

  <!-- Lower angle labels -->
  <text x="279" y="222" font-size="15" font-weight="bold" fill="#1565C0">∠5</text>
  <text x="318" y="222" font-size="15" font-weight="bold" fill="#880088">∠6</text>
  <text x="279" y="250" font-size="15" font-weight="bold" fill="#880088">∠7</text>
  <text x="318" y="250" font-size="15" font-weight="bold" fill="#1565C0">∠8</text>

  <!-- Legend -->
  <rect x="560" y="30" width="380" height="260" rx="8" fill="#f4f8fc" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="750" y="56" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Angle Pair Reference</text>

  <rect x="575" y="68" width="14" height="14" fill="#1565C0" opacity="0.8"/>
  <text x="596" y="80" font-size="12" fill="#1565C0" font-weight="bold">Corresponding:</text>
  <text x="596" y="97" font-size="12" fill="#333">∠1&amp;∠5, ∠2&amp;∠6, ∠3&amp;∠7, ∠4&amp;∠8</text>
  <text x="596" y="113" font-size="11" fill="#555">Same position at each intersection</text>

  <rect x="575" y="124" width="14" height="14" fill="#2a7a2a" opacity="0.8"/>
  <text x="596" y="136" font-size="12" fill="#2a7a2a" font-weight="bold">Alternate Interior:</text>
  <text x="596" y="153" font-size="12" fill="#333">∠3&amp;∠6,  ∠4&amp;∠5</text>
  <text x="596" y="169" font-size="11" fill="#555">Between lines, opposite sides of t</text>

  <rect x="575" y="180" width="14" height="14" fill="#cc3300" opacity="0.8"/>
  <text x="596" y="192" font-size="12" fill="#cc3300" font-weight="bold">Alternate Exterior:</text>
  <text x="596" y="209" font-size="12" fill="#333">∠1&amp;∠8,  ∠2&amp;∠7</text>
  <text x="596" y="225" font-size="11" fill="#555">Outside lines, opposite sides of t</text>

  <rect x="575" y="236" width="14" height="14" fill="#e05c1a" opacity="0.8"/>
  <text x="596" y="248" font-size="12" fill="#e05c1a" font-weight="bold">Co-interior (Same-side Interior):</text>
  <text x="596" y="265" font-size="12" fill="#333">∠3&amp;∠5,  ∠4&amp;∠6</text>
  <text x="596" y="281" font-size="11" fill="#555">Between lines, same side of t → supp.</text>
</svg>

---

## Parallel Lines Theorems (Lines → Angle Relationships)

<svg width="950" height="340" viewBox="0 0 950 340" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Corresponding Angles -->
  <g transform="translate(10,20)">
    <rect x="0" y="0" width="215" height="290" rx="8" fill="#d0e8ff" stroke="#1565C0" stroke-width="2"/>
    <text x="108" y="22" text-anchor="middle" font-size="12" font-weight="bold" fill="#1565C0">Post. 3-1</text>
    <text x="108" y="38" text-anchor="middle" font-size="11" fill="#1565C0">Corresponding Angles</text>
    <line x1="20" y1="90" x2="195" y2="90" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="20" y1="160" x2="195" y2="160" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="80" y1="40" x2="135" y2="210" stroke="#e05c1a" stroke-width="2"/>
    <path d="M 103,90 A 16,16 0 0 1 97,74" stroke="#1565C0" fill="rgba(20,100,200,0.2)" stroke-width="2"/>
    <path d="M 120,160 A 16,16 0 0 1 114,144" stroke="#1565C0" fill="rgba(20,100,200,0.2)" stroke-width="2"/>
    <text x="108" y="240" text-anchor="middle" font-size="12" fill="#1565C0">ℓ∥m ⟹</text>
    <text x="108" y="258" text-anchor="middle" font-size="12" fill="#1565C0">corr. ∠s ≅</text>
    <text x="108" y="276" text-anchor="middle" font-size="11" fill="#555">∠2 ≅ ∠6 etc.</text>
  </g>

  <!-- Alt Interior -->
  <g transform="translate(240,20)">
    <rect x="0" y="0" width="215" height="290" rx="8" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="2"/>
    <text x="108" y="22" text-anchor="middle" font-size="12" font-weight="bold" fill="#2a7a2a">Theorem 3-1</text>
    <text x="108" y="38" text-anchor="middle" font-size="11" fill="#2a7a2a">Alternate Interior ∠s</text>
    <line x1="20" y1="90" x2="195" y2="90" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="20" y1="160" x2="195" y2="160" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="80" y1="40" x2="135" y2="210" stroke="#e05c1a" stroke-width="2"/>
    <path d="M 97,90 A 16,16 0 0 0 91,106" stroke="#2a7a2a" fill="rgba(40,150,40,0.2)" stroke-width="2"/>
    <path d="M 121,160 A 16,16 0 0 1 115,144" stroke="#2a7a2a" fill="rgba(40,150,40,0.2)" stroke-width="2"/>
    <text x="108" y="240" text-anchor="middle" font-size="12" fill="#2a7a2a">ℓ∥m ⟹</text>
    <text x="108" y="258" text-anchor="middle" font-size="12" fill="#2a7a2a">alt. int. ∠s ≅</text>
    <text x="108" y="276" text-anchor="middle" font-size="11" fill="#555">∠3 ≅ ∠6, ∠4 ≅ ∠5</text>
  </g>

  <!-- Co-interior -->
  <g transform="translate(470,20)">
    <rect x="0" y="0" width="215" height="290" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
    <text x="108" y="22" text-anchor="middle" font-size="12" font-weight="bold" fill="#e05c1a">Theorem 3-2</text>
    <text x="108" y="38" text-anchor="middle" font-size="11" fill="#e05c1a">Co-interior ∠s (Supp.)</text>
    <line x1="20" y1="90" x2="195" y2="90" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="20" y1="160" x2="195" y2="160" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="80" y1="40" x2="135" y2="210" stroke="#e05c1a" stroke-width="2"/>
    <path d="M 103,90 A 16,16 0 0 1 97,106" stroke="#e05c1a" fill="rgba(220,80,0,0.15)" stroke-width="2"/>
    <path d="M 121,160 A 16,16 0 0 1 115,144" stroke="#e05c1a" fill="rgba(220,80,0,0.15)" stroke-width="2"/>
    <text x="108" y="240" text-anchor="middle" font-size="12" fill="#e05c1a">ℓ∥m ⟹</text>
    <text x="108" y="258" text-anchor="middle" font-size="12" fill="#e05c1a">co-int. ∠s supp.</text>
    <text x="108" y="276" text-anchor="middle" font-size="11" fill="#555">∠3+∠5=180°</text>
  </g>

  <!-- Alt Exterior -->
  <g transform="translate(700,20)">
    <rect x="0" y="0" width="240" height="290" rx="8" fill="#fdecea" stroke="#cc2200" stroke-width="2"/>
    <text x="120" y="22" text-anchor="middle" font-size="12" font-weight="bold" fill="#cc2200">Theorem 3-3</text>
    <text x="120" y="38" text-anchor="middle" font-size="11" fill="#cc2200">Alternate Exterior ∠s</text>
    <line x1="20" y1="90" x2="220" y2="90" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="20" y1="160" x2="220" y2="160" stroke="#1a3a5c" stroke-width="2"/>
    <line x1="80" y1="40" x2="150" y2="210" stroke="#e05c1a" stroke-width="2"/>
    <path d="M 103,90 A 16,16 0 0 1 97,74" stroke="#cc2200" fill="rgba(180,0,0,0.15)" stroke-width="2"/>
    <path d="M 134,160 A 16,16 0 0 0 128,176" stroke="#cc2200" fill="rgba(180,0,0,0.15)" stroke-width="2"/>
    <text x="120" y="240" text-anchor="middle" font-size="12" fill="#cc2200">ℓ∥m ⟹</text>
    <text x="120" y="258" text-anchor="middle" font-size="12" fill="#cc2200">alt. ext. ∠s ≅</text>
    <text x="120" y="276" text-anchor="middle" font-size="11" fill="#555">∠1 ≅ ∠8, ∠2 ≅ ∠7</text>
  </g>
</svg>

---

## Converses — Proving Lines Parallel

<svg width="950" height="230" viewBox="0 0 950 230" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <rect x="10" y="10" width="930" height="210" rx="8" fill="#f4f8fc" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="475" y="38" text-anchor="middle" font-size="15" font-weight="bold" fill="#1a3a5c">To PROVE Lines Are Parallel — Use the CONVERSE</text>
  <line x1="20" y1="48" x2="930" y2="48" stroke="#1a3a5c" stroke-width="1"/>

  <!-- Headers -->
  <text x="180" y="70" text-anchor="middle" font-size="12" font-weight="bold" fill="#1a3a5c">Theorem #</text>
  <text x="440" y="70" text-anchor="middle" font-size="12" font-weight="bold" fill="#1a3a5c">If this angle condition holds...</text>
  <text x="770" y="70" text-anchor="middle" font-size="12" font-weight="bold" fill="#2a7a2a">...then lines are parallel</text>

  <line x1="20" y1="78" x2="930" y2="78" stroke="#ccc" stroke-width="1"/>

  <rect x="20" y="82" width="910" height="24" rx="2" fill="#e8f0fb"/>
  <text x="180" y="99" text-anchor="middle" font-size="12" fill="#1565C0">Post. 3-2 (Conv. Corr. ∠s)</text>
  <text x="440" y="99" text-anchor="middle" font-size="12" fill="#333">Corresponding ∠s ≅</text>
  <text x="770" y="99" text-anchor="middle" font-size="12" fill="#2a7a2a">∠1 ≅ ∠5  ⟹  ℓ ∥ m</text>

  <rect x="20" y="110" width="910" height="24" rx="2" fill="white"/>
  <text x="180" y="127" text-anchor="middle" font-size="12" fill="#2a7a2a">Thm. 3-5 (Conv. Alt. Int.)</text>
  <text x="440" y="127" text-anchor="middle" font-size="12" fill="#333">Alternate interior ∠s ≅</text>
  <text x="770" y="127" text-anchor="middle" font-size="12" fill="#2a7a2a">∠3 ≅ ∠6  ⟹  ℓ ∥ m</text>

  <rect x="20" y="138" width="910" height="24" rx="2" fill="#e8f0fb"/>
  <text x="180" y="155" text-anchor="middle" font-size="12" fill="#e05c1a">Thm. 3-6 (Conv. Co-int.)</text>
  <text x="440" y="155" text-anchor="middle" font-size="12" fill="#333">Co-interior ∠s supplementary</text>
  <text x="770" y="155" text-anchor="middle" font-size="12" fill="#2a7a2a">∠3 + ∠5 = 180°  ⟹  ℓ ∥ m</text>

  <rect x="20" y="166" width="910" height="24" rx="2" fill="white"/>
  <text x="180" y="183" text-anchor="middle" font-size="12" fill="#cc3300">Thm. 3-7 (Both ⊥ Same)</text>
  <text x="440" y="183" text-anchor="middle" font-size="12" fill="#333">Both lines ⊥ to same transversal</text>
  <text x="770" y="183" text-anchor="middle" font-size="12" fill="#2a7a2a">t⊥ℓ and t⊥m  ⟹  ℓ ∥ m</text>

  <rect x="20" y="194" width="910" height="24" rx="2" fill="#e8f0fb"/>
  <text x="180" y="211" text-anchor="middle" font-size="12" fill="#880088">Thm. 3-4 (Perp. Trans.)</text>
  <text x="440" y="211" text-anchor="middle" font-size="12" fill="#333">ℓ∥m and t⊥ℓ</text>
  <text x="770" y="211" text-anchor="middle" font-size="12" fill="#2a7a2a">then t ⊥ m also</text>
</svg>

---

## Slopes of Parallel & Perpendicular Lines

<svg width="950" height="340" viewBox="0 0 950 340" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;display:block;margin:0 auto;">
  <!-- Formula boxes -->
  <rect x="10" y="10" width="440" height="80" rx="8" fill="#d0e8ff" stroke="#1565C0" stroke-width="2"/>
  <text x="230" y="38" text-anchor="middle" font-size="14" font-weight="bold" fill="#1565C0">Parallel Lines</text>
  <text x="230" y="62" text-anchor="middle" font-size="14" fill="#1565C0">Same slope:  m₁ = m₂</text>
  <text x="230" y="82" text-anchor="middle" font-size="12" fill="#555">Example: m = 2/3 and m = 2/3 → parallel</text>

  <rect x="500" y="10" width="440" height="80" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="720" y="38" text-anchor="middle" font-size="14" font-weight="bold" fill="#e05c1a">Perpendicular Lines</text>
  <text x="720" y="62" text-anchor="middle" font-size="14" fill="#e05c1a">Negative reciprocal:  m₁ · m₂ = −1</text>
  <text x="720" y="82" text-anchor="middle" font-size="12" fill="#555">Example: m = 2/3 → perp. slope = −3/2</text>

  <!-- Slope formula -->
  <rect x="330" y="102" width="290" height="46" rx="6" fill="#1a3a5c"/>
  <text x="475" y="121" text-anchor="middle" font-size="12" fill="white" font-weight="bold">Slope Formula:</text>
  <text x="475" y="140" text-anchor="middle" font-size="13" fill="#aecde8">m = (y₂ − y₁) / (x₂ − x₁)</text>

  <!-- Coordinate grid for parallel lines -->
  <line x1="60" y1="160" x2="60" y2="330" stroke="#ccc" stroke-width="1"/>
  <line x1="60" y1="330" x2="440" y2="330" stroke="#ccc" stroke-width="1"/>
  <!-- Parallel lines -->
  <line x1="80" y1="300" x2="280" y2="180" stroke="#1565C0" stroke-width="2.5"/>
  <line x1="130" y1="320" x2="420" y2="200" stroke="#1565C0" stroke-width="2.5" stroke-dasharray="6,3"/>
  <!-- Rise/run labels -->
  <line x1="140" y1="260" x2="200" y2="260" stroke="#888" stroke-width="1" stroke-dasharray="3,2"/>
  <line x1="200" y1="260" x2="200" y2="224" stroke="#888" stroke-width="1" stroke-dasharray="3,2"/>
  <text x="170" y="275" text-anchor="middle" font-size="11" fill="#888">run</text>
  <text x="210" y="244" font-size="11" fill="#888">rise</text>
  <text x="250" y="320" text-anchor="middle" font-size="13" fill="#1565C0" font-weight="bold">Parallel (equal slopes)</text>

  <!-- Grid for perpendicular lines -->
  <line x1="560" y1="160" x2="560" y2="330" stroke="#ccc" stroke-width="1"/>
  <line x1="560" y1="330" x2="940" y2="330" stroke="#ccc" stroke-width="1"/>
  <!-- Perpendicular lines -->
  <line x1="580" y1="310" x2="780" y2="190" stroke="#1565C0" stroke-width="2.5"/>
  <line x1="630" y1="180" x2="770" y2="320" stroke="#e05c1a" stroke-width="2.5"/>
  <!-- Right angle marker -->
  <rect x="694" y="244" width="16" height="16" fill="none" stroke="#2a7a2a" stroke-width="2"/>
  <text x="752" y="320" text-anchor="middle" font-size="13" fill="#e05c1a" font-weight="bold">Perpendicular (neg. reciprocal)</text>
  <text x="614" y="192" font-size="11" fill="#1565C0">m = 3/5</text>
  <text x="776" y="310" font-size="11" fill="#e05c1a">m = −5/3</text>
</svg>

---

## Chapter 3 — Complete Reference

| Theorem | Condition (ℓ ∥ m) | Result |
|---------|-------------------|--------|
| **Post. 3-1** | $\ell \parallel m$ | Corresponding $\angle$s congruent |
| **Thm. 3-1** | $\ell \parallel m$ | Alternate interior $\angle$s congruent |
| **Thm. 3-2** | $\ell \parallel m$ | Co-interior (same-side) $\angle$s supplementary |
| **Thm. 3-3** | $\ell \parallel m$ | Alternate exterior $\angle$s congruent |
| **Thm. 3-4** | $\ell \parallel m$, $t \perp \ell$ | Then $t \perp m$ |
| **Post. 3-2** | Corresponding $\angle$s ≅ | Lines are parallel |
| **Thm. 3-5** | Alternate interior $\angle$s ≅ | Lines are parallel |
| **Thm. 3-6** | Co-interior $\angle$s supplementary | Lines are parallel |
| **Thm. 3-7** | Both $\perp$ same line | Lines are parallel |
| **Parallel slopes** | $m_1 = m_2$ | Lines are parallel |
| **Perpendicular slopes** | $m_1 \cdot m_2 = -1$ | Lines are perpendicular |

> **Memory tip:** To use theorems — given parallel lines, conclude about angles. To use **converses** — given angle facts, conclude lines are parallel.
