---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 7 Cheatsheet
# Right Triangles & Trigonometry

---

<div style="display:flex; gap:24px; align-items:flex-start;">
<div style="flex:1; text-align:center;">

<svg width="300" height="270" viewBox="0 0 300 270" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="150" y="16" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">SOH-CAH-TOA</text>

  <!-- Right triangle -->
  <polygon points="30,220 260,220 260,60" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2.5"/>

  <!-- Right angle marker -->
  <rect x="244" y="204" width="16" height="16" fill="none" stroke="#333" stroke-width="2"/>

  <!-- Angle θ at A -->
  <path d="M 58,220 A 28,28 0 0 1 52,198" stroke="#e05c1a" fill="none" stroke-width="2.5"/>
  <text x="62" y="216" font-size="14" font-weight="bold" fill="#e05c1a">θ</text>

  <!-- Labels -->
  <text x="22" y="234" font-size="13" font-weight="bold" fill="#1a3a5c">A</text>
  <text x="262" y="234" font-size="13" font-weight="bold" fill="#1a3a5c">B</text>
  <text x="263" y="56" font-size="13" font-weight="bold" fill="#1a3a5c">C</text>

  <!-- Side labels -->
  <text x="148" y="240" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">adjacent</text>
  <text x="274" y="148" font-size="12" font-weight="bold" fill="#cc3300">opp.</text>
  <text x="115" y="128" text-anchor="middle" font-size="13" font-weight="bold" fill="#1565C0">hypotenuse</text>

  <!-- Formulas -->
  <rect x="20" y="250" width="260" height="16" rx="3" fill="#fff3e0" stroke="#e05c1a" stroke-width="1"/>
  <text x="150" y="262" text-anchor="middle" font-size="11" fill="#e05c1a" font-weight="bold">sin θ = opp/hyp · cos θ = adj/hyp · tan θ = opp/adj</text>
</svg>

</div>
<div style="flex:1;">

## SOH-CAH-TOA

$$\sin\theta = \frac{\text{opp}}{\text{hyp}} \qquad \cos\theta = \frac{\text{adj}}{\text{hyp}} \qquad \tan\theta = \frac{\text{opp}}{\text{adj}}$$

## Common Values

| $\theta$ | $\sin$ | $\cos$ | $\tan$ |
|----------|--------|--------|--------|
| 30° | $\frac{1}{2}$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{\sqrt{3}}$ |
| 45° | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{2}}{2}$ | $1$ |
| 60° | $\frac{\sqrt{3}}{2}$ | $\frac{1}{2}$ | $\sqrt{3}$ |

## Pythagorean Theorem
$$a^2 + b^2 = c^2$$

**Common triples:** 3-4-5, 5-12-13, 8-15-17

</div>
</div>

---

<div style="display:flex; gap:24px;">
<div style="flex:1; text-align:center;">

<svg width="280" height="220" viewBox="0 0 280 220" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="140" y="16" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">45°–45°–90° Triangle</text>

  <polygon points="30,190 230,190 230,40" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="2.5"/>
  <rect x="214" y="174" width="16" height="16" fill="none" stroke="#333" stroke-width="2"/>

  <!-- 45° angle arcs -->
  <path d="M 54,190 A 24,24 0 0 1 50,166" stroke="#e05c1a" fill="none" stroke-width="2"/>
  <path d="M 230,62 A 24,24 0 0 0 208,56" stroke="#e05c1a" fill="none" stroke-width="2"/>

  <!-- Labels -->
  <text x="56" y="186" font-size="12" fill="#e05c1a" font-weight="bold">45°</text>
  <text x="207" y="75" font-size="12" fill="#e05c1a" font-weight="bold">45°</text>
  <text x="12" y="202" font-size="13" fill="#1a3a5c" font-weight="bold">A</text>
  <text x="232" y="202" font-size="13" fill="#1a3a5c" font-weight="bold">B</text>
  <text x="234" y="38" font-size="13" fill="#1a3a5c" font-weight="bold">C</text>

  <!-- Side labels -->
  <text x="130" y="208" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">x</text>
  <text x="244" y="120" font-size="13" font-weight="bold" fill="#2a7a2a">x</text>
  <text x="108" y="118" text-anchor="middle" font-size="13" font-weight="bold" fill="#1565C0">x√2</text>
</svg>

</div>
<div style="flex:1; text-align:center;">

<svg width="280" height="220" viewBox="0 0 280 220" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="140" y="16" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">30°–60°–90° Triangle</text>

  <polygon points="30,190 230,190 30,70" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <rect x="30" y="174" width="16" height="16" fill="none" stroke="#333" stroke-width="2"/>

  <!-- Angle arcs -->
  <path d="M 54,190 A 24,24 0 0 1 50,166" stroke="#2a7a2a" fill="none" stroke-width="2"/>
  <path d="M 54,70 A 24,24 0 0 0 56,93" stroke="#1565C0" fill="none" stroke-width="2"/>

  <!-- Labels -->
  <text x="55" y="186" font-size="12" fill="#2a7a2a" font-weight="bold">30°</text>
  <text x="55" y="87" font-size="12" fill="#1565C0" font-weight="bold">60°</text>
  <text x="10" y="202" font-size="13" fill="#1a3a5c" font-weight="bold">B</text>
  <text x="233" y="202" font-size="13" fill="#1a3a5c" font-weight="bold">C</text>
  <text x="10" y="66" font-size="13" fill="#1a3a5c" font-weight="bold">A</text>

  <!-- Side labels -->
  <text x="130" y="208" text-anchor="middle" font-size="13" font-weight="bold" fill="#cc3300">2x (hyp)</text>
  <text x="14" y="135" font-size="12" font-weight="bold" fill="#2a7a2a">x</text>
  <text x="132" y="135" text-anchor="middle" font-size="13" font-weight="bold" fill="#1565C0">x√3</text>
</svg>

</div>
</div>
