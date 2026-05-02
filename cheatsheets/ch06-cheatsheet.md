---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 6 Cheatsheet
# Proportions & Similarity

---

<div style="display:flex; gap:24px; align-items:flex-start;">
<div style="flex:1.1; text-align:center;">

<svg width="340" height="290" viewBox="0 0 340 290" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="170" y="18" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Similar Triangles — AA, SSS∼, SAS∼</text>

  <!-- Small triangle -->
  <polygon points="30,240 110,240 70,130" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2"/>
  <text x="18" y="252" font-size="12" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="112" y="252" font-size="12" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="70" y="122" font-size="12" font-weight="bold" fill="#1a3a5c">C</text>

  <!-- Small triangle side ticks (1x) -->
  <line x1="68" y1="240" x2="72" y2="240" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="46" y1="189" x2="52" y2="183" stroke="#2a7a2a" stroke-width="2"/>
  <line x1="86" y1="183" x2="92" y2="189" stroke="#1565C0" stroke-width="2"/>

  <!-- Angle congruence arcs (small) -->
  <path d="M 42,240 A 14,14 0 0 1 38,226" stroke="#cc3300" fill="none" stroke-width="1.8"/>
  <path d="M 96,240 A 14,14 0 0 0 100,226" stroke="#880088" fill="none" stroke-width="1.8"/>

  <!-- Similarity arrow -->
  <text x="170" y="195" text-anchor="middle" font-size="22" fill="#1a3a5c">∼</text>
  <text x="170" y="215" text-anchor="middle" font-size="11" fill="#555">△ABC ∼ △DEF</text>

  <!-- Large triangle -->
  <polygon points="230,240 310,240 270,90" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="218" y="252" font-size="12" font-weight="bold" fill="#e05c1a">D</text>
  <text x="312" y="252" font-size="12" font-weight="bold" fill="#e05c1a">E</text>
  <text x="270" y="82" font-size="12" font-weight="bold" fill="#e05c1a">F</text>

  <!-- Large triangle side ticks (2x) -->
  <line x1="267" y1="240" x2="271" y2="240" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="263" y1="242" x2="267" y2="242" stroke="#e05c1a" stroke-width="2.5"/>
  <line x1="244" y1="168" x2="250" y2="162" stroke="#2a7a2a" stroke-width="2"/>
  <line x1="247" y1="165" x2="253" y2="159" stroke="#2a7a2a" stroke-width="2"/>
  <line x1="287" y1="162" x2="293" y2="168" stroke="#1565C0" stroke-width="2"/>
  <line x1="290" y1="165" x2="296" y2="171" stroke="#1565C0" stroke-width="2"/>

  <!-- Angle congruence arcs (large) -->
  <path d="M 242,240 A 14,14 0 0 1 238,226" stroke="#cc3300" fill="none" stroke-width="1.8"/>
  <path d="M 296,240 A 14,14 0 0 0 300,226" stroke="#880088" fill="none" stroke-width="1.8"/>

  <!-- Proportion label -->
  <text x="170" y="268" text-anchor="middle" font-size="12" fill="#1a3a5c" font-weight="bold">AB/DE = BC/EF = AC/DF = k</text>
  <text x="170" y="284" text-anchor="middle" font-size="11" fill="#555">∠A≅∠D, ∠B≅∠E, ∠C≅∠F</text>
</svg>

</div>
<div style="flex:1;">

## Similarity Shortcuts

| Shortcut | Condition |
|----------|-----------|
| **AA** | 2 pairs of ≅ angles |
| **SSS∼** | All 3 sides proportional |
| **SAS∼** | 2 sides proportional + included ∠ ≅ |

## Scale Factor $k$

$$\text{Sides ratio} = k$$
$$\text{Perimeter ratio} = k$$
$$\text{Area ratio} = k^2$$

**Example:** $k = \frac{3}{2}$
- Perimeter ratio: $\frac{3}{2}$
- Area ratio: $\frac{9}{4}$

</div>
</div>

---

<div style="display:flex; gap:24px;">
<div style="flex:1.2; text-align:center;">

<svg width="320" height="200" viewBox="0 0 320 200" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="160" y="16" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Triangle Proportionality &amp; Midsegment</text>

  <!-- Main triangle -->
  <polygon points="160,20 20,180 300,180" fill="#f4f8fc" stroke="#1a3a5c" stroke-width="2"/>
  <text x="160" y="14" text-anchor="middle" font-size="12" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="8" y="192" font-size="12" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="302" y="192" font-size="12" font-weight="bold" fill="#1a3a5c">C</text>

  <!-- Midsegment DE (midpoints of AB and AC) -->
  <line x1="90" y1="100" x2="230" y2="100" stroke="#e05c1a" stroke-width="2.5"/>
  <circle cx="90" cy="100" r="4" fill="#e05c1a"/>
  <circle cx="230" cy="100" r="4" fill="#e05c1a"/>
  <text x="78" y="96" font-size="12" font-weight="bold" fill="#e05c1a">D</text>
  <text x="234" y="96" font-size="12" font-weight="bold" fill="#e05c1a">E</text>

  <!-- Parallel symbol -->
  <text x="155" y="93" font-size="11" fill="#e05c1a" font-weight="bold">DE ∥ BC</text>

  <!-- BC base -->
  <text x="160" y="196" text-anchor="middle" font-size="11" fill="#1a3a5c" font-weight="bold">BC</text>

  <!-- Annotations -->
  <text x="160" y="154" text-anchor="middle" font-size="11" fill="#2a7a2a">DE = ½·BC</text>
  <text x="160" y="170" text-anchor="middle" font-size="11" fill="#555">AD/DB = AE/EC (proportionality)</text>
</svg>

</div>
<div style="flex:1;">

## Key Theorems

| Theorem | Statement |
|---------|-----------|
| **6-3** Triangle Proportionality | $\parallel$ line divides sides proportionally |
| **6-5** Midsegment | $DE = \frac{1}{2}BC$, $DE \parallel BC$ |
| **6-7** Angle Bisector | $\frac{BD}{DC} = \frac{AB}{AC}$ |

## Angle Bisector Example

If $AB = 10$, $AC = 6$, and $BC = 8$:
$$\frac{BD}{DC} = \frac{10}{6} = \frac{5}{3}$$
$$BD = 5,\quad DC = 3$$

</div>
</div>
