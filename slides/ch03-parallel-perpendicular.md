---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 3
## Parallel & Perpendicular Lines

McGraw Hill Glencoe Geometry · Texas Edition

---

## Key Vocabulary

<div class="columns">
<div>

**Parallel lines** ($\ell \parallel m$) — coplanar lines that never intersect
**Perpendicular lines** ($\ell \perp m$) — lines intersecting at 90°
**Skew lines** — non-coplanar, non-intersecting (no parallel relationship)
**Transversal** — a line intersecting two or more other lines

When a transversal crosses two lines, it creates **8 angles** in 4 pairs:

| Pair | Location | Position |
|------|----------|----------|
| Corresponding | Same side, same position | ∠1 & ∠5 |
| Alt. Interior | Between lines, opposite sides | ∠3 & ∠6 |
| Alt. Exterior | Outside lines, opposite sides | ∠1 & ∠8 |
| Co-interior (Same-side) | Between lines, same side | ∠3 & ∠5 |

</div>
<div>

<svg width="290" height="280" viewBox="0 0 290 280" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="80" x2="270" y2="80" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="20" y1="200" x2="270" y2="200" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="130" y1="20" x2="170" y2="270" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="14" y="75" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">ℓ</text>
  <text x="14" y="195" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">m</text>
  <text x="172" y="265" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">t</text>
  <!-- Angle labels at upper intersection ~(138,80) -->
  <text x="112" y="72" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠1</text>
  <text x="144" y="72" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">∠2</text>
  <text x="112" y="96" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">∠3</text>
  <text x="144" y="96" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠4</text>
  <!-- Angle labels at lower intersection ~(153,200) -->
  <text x="126" y="192" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠5</text>
  <text x="158" y="192" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">∠6</text>
  <text x="126" y="216" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">∠7</text>
  <text x="158" y="216" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠8</text>
  <text x="20" y="258" font-size="11" fill="#555" font-family="Arial">∠1≅∠5 (corr.)  ∠3≅∠6 (alt.int.)</text>
</svg>

</div>
</div>

---

## Parallel Lines → Angle Relationships

When two **parallel** lines are cut by a transversal, three main theorems apply.

<div class="columns">
<div>

**Postulate 3-1:** Corresponding Angles
$$\ell \parallel m \;\Rightarrow\; \angle 1 \cong \angle 5$$

**Theorem 3-1:** Alternate Interior Angles
$$\ell \parallel m \;\Rightarrow\; \angle 3 \cong \angle 6$$

**Theorem 3-2:** Consecutive Interior Angles (Co-interior)
$$\ell \parallel m \;\Rightarrow\; \angle 3 + \angle 5 = 180°$$

**Theorem 3-3:** Alternate Exterior Angles
$$\ell \parallel m \;\Rightarrow\; \angle 1 \cong \angle 8$$

**Theorem 3-4:** Perpendicular Transversal
If a transversal is $\perp$ to one of two parallel lines, it is $\perp$ to the other.

</div>
<div>

<svg width="280" height="270" viewBox="0 0 280 270" xmlns="http://www.w3.org/2000/svg">
  <line x1="15" y1="80" x2="265" y2="80" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="15" y1="190" x2="265" y2="190" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="125" y1="20" x2="155" y2="255" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="5" y="75" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">ℓ ∥ m</text>
  <text x="5" y="188" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">m</text>
  <!-- Corresponding: ∠2 at top & ∠6 at bottom (same position) -->
  <path d="M135,80 A18,18 0 0,1 148,68" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <path d="M143,190 A18,18 0 0,1 156,178" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="150" y="70" font-size="12" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠2</text>
  <text x="158" y="180" font-size="12" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠6</text>
  <text x="165" y="78" font-size="12" fill="#1a3a5c" font-family="Arial">≅ (Corresponding)</text>
  <!-- Alt Interior: ∠3 & ∠6 (opposite sides, between lines) -->
  <path d="M127,80 A18,18 0 0,0 114,92" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <path d="M143,190 A18,18 0 0,1 156,178" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="96" y="98" font-size="12" fill="#e05c1a" font-family="Arial" font-weight="bold">∠3</text>
  <text x="158" y="183" font-size="12" fill="#e05c1a" font-family="Arial" font-weight="bold">∠6</text>
  <text x="5" y="145" font-size="12" fill="#e05c1a" font-family="Arial">∠3 ≅ ∠6 (Alt. Interior)</text>
  <text x="5" y="235" font-size="12" fill="#555" font-family="Arial">∠3 + ∠5 = 180° (Co-interior)</text>
</svg>

</div>
</div>

---

## Proving Lines Parallel (Converses)

The converses let us **prove** that two lines are parallel.

| Theorem | If ... then $\ell \parallel m$ |
|---------|-------------------------------|
| **Post. 3-2** | Corresponding angles are congruent |
| **Thm 3-5** | Alternate interior angles are congruent |
| **Thm 3-6** | Consecutive interior angles are supplementary |
| **Thm 3-7** | Both lines are perpendicular to the same line |

<div class="columns">
<div>

> **Example:** $\angle 3 = 65°$ and $\angle 6 = 65°$.
> Since alternate interior angles are equal, $\ell \parallel m$.

</div>
<div>

<svg width="260" height="140" viewBox="0 0 260 140" xmlns="http://www.w3.org/2000/svg">
  <line x1="15" y1="45" x2="245" y2="45" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="15" y1="110" x2="245" y2="110" stroke="#1a3a5c" stroke-width="2" stroke-dasharray="8,4"/>
  <line x1="115" y1="10" x2="135" y2="140" stroke="#e05c1a" stroke-width="2"/>
  <text x="95" y="38" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">∠3=65°</text>
  <text x="138" y="122" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">∠6=65°</text>
  <text x="155" y="45" font-size="12" fill="#1a3a5c" font-family="Arial">ℓ</text>
  <text x="155" y="110" font-size="12" fill="#1a3a5c" font-family="Arial">m ∥ ℓ?  YES ✓</text>
</svg>

</div>
</div>

---

## Slopes of Parallel & Perpendicular Lines

<div class="columns">
<div>

**Slope formula:**
$$m = \frac{y_2 - y_1}{x_2 - x_1} = \frac{\text{rise}}{\text{run}}$$

**Parallel lines** have **equal slopes**.
$$\ell_1 \parallel \ell_2 \;\Leftrightarrow\; m_1 = m_2$$

**Perpendicular lines** have **negative reciprocal slopes**.
$$\ell_1 \perp \ell_2 \;\Leftrightarrow\; m_1 \cdot m_2 = -1$$

> **Example:**
> Line 1: slope $= \frac{2}{3}$
> Parallel line: slope $= \frac{2}{3}$
> Perpendicular line: slope $= -\frac{3}{2}$

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Axes -->
  <line x1="30" y1="240" x2="280" y2="240" stroke="#bbb" stroke-width="1.5"/>
  <line x1="30" y1="240" x2="30" y2="20" stroke="#bbb" stroke-width="1.5"/>
  <polygon points="280,240 268,234 268,246" fill="#bbb"/>
  <polygon points="30,20 24,32 36,32" fill="#bbb"/>
  <text x="282" y="244" font-size="11" fill="#888" font-family="Arial">x</text>
  <text x="22" y="18" font-size="11" fill="#888" font-family="Arial">y</text>
  <!-- Parallel lines (slope 2/3) -->
  <line x1="30" y1="210" x2="210" y2="90" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="80" y1="240" x2="260" y2="120" stroke="#1a3a5c" stroke-width="2.5" stroke-dasharray="8,4"/>
  <text x="215" y="88" font-size="12" fill="#1a3a5c" font-family="Arial">m = 2/3</text>
  <text x="262" y="118" font-size="12" fill="#1a3a5c" font-family="Arial">∥</text>
  <!-- Perpendicular line (slope -3/2) -->
  <line x1="60" y1="60" x2="230" y2="230" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="232" y="232" font-size="12" fill="#e05c1a" font-family="Arial">m=−3/2</text>
  <!-- Right angle marker -->
  <rect x="128" y="148" width="14" height="14" transform="rotate(34,128,148)" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="55" y="258" font-size="11" fill="#555" font-family="Arial">Parallel: same slope  ∥  Perp: m₁·m₂=−1  ⊥</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 1 — Finding Angle Measures

**Given:** $\ell \parallel m$, transversal $t$. $\angle 1 = (3x + 20)°$, $\angle 5 = (5x - 10)°$.

<div class="columns">
<div>

$\angle 1$ and $\angle 5$ are **corresponding angles**, so they are equal.

**Step 1:** Set up equation.
$$3x + 20 = 5x - 10$$

**Step 2:** Solve.
$$30 = 2x \;\Rightarrow\; x = 15$$

**Step 3:** Find the angles.
$$\angle 1 = 3(15)+20 = \mathbf{65°}$$
$$\angle 5 = 5(15)-10 = \mathbf{65°}\; \checkmark$$

**Bonus:** $\angle 3 = 180° - 65° = 115°$ (linear pair)

</div>
<div>

<svg width="270" height="230" viewBox="0 0 270 230" xmlns="http://www.w3.org/2000/svg">
  <line x1="15" y1="75" x2="255" y2="75" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="15" y1="175" x2="255" y2="175" stroke="#1a3a5c" stroke-width="2.5"/>
  <line x1="120" y1="20" x2="145" y2="225" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="8" y="72" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">ℓ</text>
  <text x="8" y="172" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">m</text>
  <!-- ∠1 and ∠5 highlighted -->
  <path d="M130,75 A20,20 0 0,1 144,62" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <path d="M136,175 A20,20 0 0,1 150,162" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="146" y="65" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠1=65°</text>
  <text x="152" y="163" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">∠5=65°</text>
  <text x="15" y="215" font-size="12" fill="#555" font-family="Arial">Corresponding → equal when ℓ ∥ m</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 2 — Parallel & Perpendicular Lines

**Line $k$ passes through $(0,3)$ and $(4,5)$.**

Find equations for the line **parallel** and **perpendicular** to $k$ through the point $(2,0)$.

<div class="columns">
<div>

**Step 1:** Find slope of $k$.
$$m_k = \frac{5-3}{4-0} = \frac{2}{4} = \frac{1}{2}$$

**Parallel line** (same slope, through $(2,0)$):
$$y - 0 = \frac{1}{2}(x-2) \;\Rightarrow\; y = \frac{1}{2}x - 1$$

**Perpendicular line** (slope $= -2$, through $(2,0)$):
$$y - 0 = -2(x-2) \;\Rightarrow\; y = -2x + 4$$

</div>
<div>

<svg width="270" height="230" viewBox="0 0 270 230" xmlns="http://www.w3.org/2000/svg">
  <line x1="20" y1="215" x2="260" y2="215" stroke="#bbb" stroke-width="1.5"/>
  <line x1="20" y1="215" x2="20" y2="20" stroke="#bbb" stroke-width="1.5"/>
  <!-- Original line k: slope 1/2 -->
  <line x1="20" y1="175" x2="260" y2="55" stroke="#1a3a5c" stroke-width="2.5"/>
  <text x="245" y="52" font-size="12" fill="#1a3a5c" font-family="Arial">k (m=½)</text>
  <!-- Parallel: slope 1/2 through (2,0) → y=x/2-1 -->
  <line x1="20" y1="205" x2="260" y2="85" stroke="#1a3a5c" stroke-width="2" stroke-dasharray="7,4"/>
  <text x="245" y="82" font-size="12" fill="#1a3a5c" font-family="Arial">∥</text>
  <!-- Perpendicular: slope -2 through (2,0) → y=-2x+4 -->
  <line x1="20" y1="100" x2="140" y2="220" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="24" y="95" font-size="12" fill="#e05c1a" font-family="Arial">⊥ (m=−2)</text>
  <!-- Point (2,0) -->
  <circle cx="60" cy="215" r="6" fill="#e05c1a"/>
  <text x="40" y="212" font-size="11" fill="#e05c1a" font-family="Arial">(2,0)</text>
  <!-- Right angle box -->
  <rect x="55" y="209" width="11" height="11" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
</svg>

</div>
</div>

---

## Chapter 3 — Summary

| Result | Condition |
|--------|-----------|
| **Corr. Angles ≅** | $\ell \parallel m$ |
| **Alt. Int. Angles ≅** | $\ell \parallel m$ |
| **Co-int. Angles supp.** | $\ell \parallel m$ |
| **Alt. Ext. Angles ≅** | $\ell \parallel m$ |
| **Converse** | Equal corr./alt.int./alt.ext. or supp. co-int. → $\ell \parallel m$ |
| **Parallel slopes** | $m_1 = m_2$ |
| **Perpendicular slopes** | $m_1 \cdot m_2 = -1$ |

> **Memory trick:** "Parallel angles are C-shaped (co-interior, supplementary) or Z-shaped (alternate, congruent) or F-shaped (corresponding, congruent)."
