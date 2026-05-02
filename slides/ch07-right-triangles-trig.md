---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 7
## Right Triangles & Trigonometry

McGraw Hill Glencoe Geometry · Texas Edition

---

## The Pythagorean Theorem

<div class="columns">
<div>

**Theorem 7-1 (Pythagorean Theorem):**
In a right triangle with legs $a$, $b$ and hypotenuse $c$:
$$a^2 + b^2 = c^2$$

**Theorem 7-2 (Converse):**
If $a^2 + b^2 = c^2$, then the triangle is a right triangle.

| If $a^2 + b^2$ vs $c^2$ | Triangle type |
|------------------------|---------------|
| $= c^2$ | Right |
| $< c^2$ | Obtuse |
| $> c^2$ | Acute |

**Common Pythagorean Triples:**
$3\text{-}4\text{-}5$, $\;5\text{-}12\text{-}13$, $\;8\text{-}15\text{-}17$, $\;7\text{-}24\text{-}25$

Any multiple of a triple is also a triple: $6\text{-}8\text{-}10$, $\;9\text{-}12\text{-}15$, …

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <!-- Right triangle -->
  <polygon points="30,230 200,230 200,60" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <rect x="200" y="214" width="16" height="16" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Squares on sides -->
  <rect x="30" y="230" width="170" height="40" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5" fill-opacity="0.6"/>
  <rect x="200" y="60" width="40" height="170" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5" fill-opacity="0.6"/>
  <!-- Labels -->
  <text x="18" y="250" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="202" y="250" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="202" y="55" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="104" y="224" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">a</text>
  <text x="204" y="150" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">b</text>
  <text x="90" y="155" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">c</text>
  <text x="103" y="258" font-size="12" fill="#e05c1a" font-family="Arial">a²</text>
  <text x="215" y="148" font-size="12" fill="#1a3a5c" font-family="Arial">b²</text>
  <text x="30" y="14" font-size="15" fill="#555" font-family="Arial" font-weight="bold">a² + b² = c²</text>
</svg>

</div>
</div>

---

## Special Right Triangles

<div class="columns">
<div>

**45°-45°-90° Triangle**
Both legs equal; hypotenuse is $\sqrt{2}$ times a leg.
$$\text{leg} : \text{leg} : \text{hyp} = 1 : 1 : \sqrt{2}$$

If leg $= x$, then hypotenuse $= x\sqrt{2}$.

---

**30°-60°-90° Triangle**
Sides are in ratio $1:\sqrt{3}:2$.
$$\text{short} : \text{long leg} : \text{hyp} = 1 : \sqrt{3} : 2$$

If short leg $= x$: long leg $= x\sqrt{3}$, hyp $= 2x$.

> **Memory trick for 30-60-90:** The short leg is half the hypotenuse. Multiply by $\sqrt{3}$ to get the long leg.

</div>
<div>

<svg width="290" height="280" viewBox="0 0 290 280" xmlns="http://www.w3.org/2000/svg">
  <!-- 45-45-90 triangle -->
  <polygon points="20,130 130,130 130,20" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <rect x="114" y="114" width="16" height="16" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M38,130 A18,18 0 0,0 32,114" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <path d="M130,38 A18,18 0 0,1 114,32" fill="none" stroke="#e05c1a" stroke-width="2"/>
  <text x="22" y="148" font-size="13" fill="#e05c1a" font-family="Arial">45°</text>
  <text x="132" y="38" font-size="13" fill="#e05c1a" font-family="Arial">45°</text>
  <text x="70" y="147" font-size="13" fill="#1a3a5c" font-family="Arial">x</text>
  <text x="132" y="80" font-size="13" fill="#1a3a5c" font-family="Arial">x</text>
  <text x="55" y="75" font-size="13" fill="#e05c1a" font-family="Arial">x√2</text>
  <text x="28" y="18" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">45-45-90</text>

  <!-- 30-60-90 triangle -->
  <polygon points="20,270 170,270 20,200" fill="#fff3e0" stroke="#e05c1a" stroke-width="2.5"/>
  <rect x="20" y="254" width="14" height="14" fill="none" stroke="#e05c1a" stroke-width="1.5"/>
  <path d="M36,270 A20,20 0 0,0 31,252" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M160,270 A20,20 0 0,1 155,252" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <text x="30" y="268" font-size="12" fill="#1a3a5c" font-family="Arial">60°</text>
  <text x="145" y="267" font-size="12" fill="#1a3a5c" font-family="Arial">30°</text>
  <text x="82" y="268" font-size="12" fill="#e05c1a" font-family="Arial">x√3</text>
  <text x="2" y="238" font-size="12" fill="#e05c1a" font-family="Arial">x</text>
  <text x="92" y="232" font-size="12" fill="#1a3a5c" font-family="Arial">2x</text>
  <text x="160" y="195" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">30-60-90</text>
</svg>

</div>
</div>

---

## Trigonometric Ratios (SOH-CAH-TOA)

<div class="columns">
<div>

In a right triangle with acute angle $\theta$:

$$\sin\theta = \frac{\text{Opposite}}{\text{Hypotenuse}} \quad \textbf{SOH}$$

$$\cos\theta = \frac{\text{Adjacent}}{\text{Hypotenuse}} \quad \textbf{CAH}$$

$$\tan\theta = \frac{\text{Opposite}}{\text{Adjacent}} \quad \textbf{TOA}$$

| Angle | sin | cos | tan |
|-------|-----|-----|-----|
| 30° | $\frac{1}{2}$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{\sqrt{3}}$ |
| 45° | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{2}}{2}$ | $1$ |
| 60° | $\frac{\sqrt{3}}{2}$ | $\frac{1}{2}$ | $\sqrt{3}$ |

</div>
<div>

<svg width="290" height="270" viewBox="0 0 290 270" xmlns="http://www.w3.org/2000/svg">
  <polygon points="30,230 230,230 230,60" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <rect x="214" y="214" width="16" height="16" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Angle theta at A -->
  <path d="M55,230 A25,25 0 0,0 47,208" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="56" y="222" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">θ</text>
  <!-- Labels -->
  <text x="14" y="249" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="233" y="249" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="233" y="55" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <!-- Side labels -->
  <text x="120" y="250" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">Adjacent</text>
  <text x="235" y="150" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">Opp.</text>
  <text x="90" y="150" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold">Hyp.</text>
  <!-- SOH-CAH-TOA box -->
  <rect x="15" y="10" width="250" height="42" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="28" y="30" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">sin=O/H</text>
  <text x="118" y="30" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">cos=A/H</text>
  <text x="208" y="30" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">tan=O/A</text>
  <text x="28" y="46" font-size="12" fill="#e05c1a" font-family="Arial">SOH</text>
  <text x="123" y="46" font-size="12" fill="#e05c1a" font-family="Arial">CAH</text>
  <text x="213" y="46" font-size="12" fill="#e05c1a" font-family="Arial">TOA</text>
</svg>

</div>
</div>

---

## Angles of Elevation & Depression

<div class="columns">
<div>

**Angle of elevation** — angle measured *upward* from horizontal to a line of sight.

**Angle of depression** — angle measured *downward* from horizontal to a line of sight.

> Both angles are formed with a **horizontal line** and are **equal** (alternate interior angles with parallel horizontals).

> **Example:** A ladder leans against a wall. The base is 6 ft from the wall and makes a 65° angle with the ground. How high does the ladder reach?
>
> $\tan 65° = \frac{h}{6}$
>
> $h = 6 \cdot \tan 65° \approx 6 \times 2.145 \approx \mathbf{12.9 \text{ ft}}$

</div>
<div>

<svg width="290" height="250" viewBox="0 0 290 250" xmlns="http://www.w3.org/2000/svg">
  <!-- Ground -->
  <line x1="10" y1="200" x2="280" y2="200" stroke="#1a3a5c" stroke-width="2.5"/>
  <!-- Building -->
  <rect x="220" y="60" width="40" height="140" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <!-- Observer -->
  <circle cx="40" cy="195" r="8" fill="#e05c1a"/>
  <text x="30" y="220" font-size="12" fill="#1a3a5c" font-family="Arial">Observer</text>
  <!-- Line of sight -->
  <line x1="40" y1="195" x2="220" y2="62" stroke="#e05c1a" stroke-width="2.5" stroke-dasharray="6,3"/>
  <!-- Horizontal from observer -->
  <line x1="40" y1="195" x2="160" y2="195" stroke="#555" stroke-width="1.5" stroke-dasharray="4,3"/>
  <!-- Elevation angle arc -->
  <path d="M90,195 A50,50 0 0,0 75,162" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="95" y="186" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">θ elev.</text>
  <!-- Horizontal from top -->
  <line x1="220" y1="62" x2="160" y2="62" stroke="#555" stroke-width="1.5" stroke-dasharray="4,3"/>
  <!-- Depression angle -->
  <path d="M195,62 A30,30 0 0,1 182,82" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <text x="155" y="80" font-size="12" fill="#1a3a5c" font-family="Arial">θ dep.</text>
  <!-- Height label -->
  <text x="262" y="135" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold">h</text>
  <text x="60" y="248" font-size="12" fill="#555" font-family="Arial">Elevation = Depression (alt. int. angles)</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 1 — Using Pythagorean Theorem

**A right triangle has legs of 5 and 12. Find the hypotenuse and classify the triangle.**

<div class="columns">
<div>

$$c^2 = a^2 + b^2 = 5^2 + 12^2 = 25 + 144 = 169$$

$$c = \sqrt{169} = \mathbf{13}$$

**Classification check:** $5^2 + 12^2 = 169 = 13^2$ → Right triangle ✓

**Also:** $(5, 12, 13)$ is a Pythagorean triple.

**Trig ratios for the 13-angle at bottom:**
$$\sin\theta = \frac{12}{13}, \quad \cos\theta = \frac{5}{13}, \quad \tan\theta = \frac{12}{5}$$

</div>
<div>

<svg width="260" height="220" viewBox="0 0 260 220" xmlns="http://www.w3.org/2000/svg">
  <polygon points="30,190 200,190 200,50" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <rect x="184" y="174" width="16" height="16" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <path d="M55,190 A25,25 0 0,0 47,168" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="57" y="182" font-size="13" fill="#e05c1a" font-family="Arial" font-weight="bold">θ</text>
  <text x="18" y="208" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="202" y="208" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">B</text>
  <text x="202" y="45" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">C</text>
  <text x="104" y="208" font-size="14" fill="#1a3a5c" font-family="Arial">a = 12</text>
  <text x="205" y="122" font-size="14" fill="#1a3a5c" font-family="Arial">b = 5</text>
  <text x="85" y="118" font-size="14" fill="#e05c1a" font-family="Arial">c = 13</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 2 — Trigonometry Application

**From a point 40 m from the base of a building, the angle of elevation to the top is 52°. Find the height of the building.**

<div class="columns">
<div>

**Draw:** Right triangle with adjacent side = 40 m, angle = 52°.

**Set up:** We want the opposite side (height $h$).

$$\tan 52° = \frac{h}{40}$$

**Solve:**
$$h = 40 \cdot \tan 52° \approx 40 \times 1.2799 \approx \mathbf{51.2 \text{ m}}$$

**Check:** $\sin 52° = h/c$, so $c = h/\sin 52° \approx 64.9$ m (the line-of-sight distance).

</div>
<div>

<svg width="270" height="220" viewBox="0 0 270 220" xmlns="http://www.w3.org/2000/svg">
  <polygon points="30,190 200,190 200,40" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2.5"/>
  <rect x="184" y="174" width="16" height="16" fill="none" stroke="#1a3a5c" stroke-width="2"/>
  <!-- angle 52° -->
  <path d="M58,190 A28,28 0 0,0 48,166" fill="none" stroke="#e05c1a" stroke-width="2.5"/>
  <text x="60" y="181" font-size="13" fill="#e05c1a" font-family="Arial">52°</text>
  <text x="18" y="208" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">A</text>
  <text x="102" y="208" font-size="14" fill="#1a3a5c" font-family="Arial">40 m</text>
  <text x="205" y="118" font-size="14" fill="#e05c1a" font-family="Arial">h = ?</text>
  <text x="75" y="120" font-size="14" fill="#1a3a5c" font-family="Arial">hyp</text>
  <text x="55" y="248" font-size="13" fill="#555" font-family="Arial">tan 52° = h/40  →  h ≈ 51.2 m</text>
</svg>

</div>
</div>

---

## Chapter 7 — Summary

| Formula | When to use |
|---------|-------------|
| $a^2 + b^2 = c^2$ | Find a side in any right triangle |
| **45-45-90** | Hyp $= \text{leg} \times \sqrt{2}$ |
| **30-60-90** | Long leg $= \text{short} \times \sqrt{3}$; Hyp $= 2 \times \text{short}$ |
| $\sin\theta = \frac{O}{H}$ | Opposite & hypotenuse known/needed |
| $\cos\theta = \frac{A}{H}$ | Adjacent & hypotenuse known/needed |
| $\tan\theta = \frac{O}{A}$ | Opposite & adjacent known/needed |
| $\theta = \sin^{-1}(r)$ etc. | Find an angle from side ratios |

> **SOH-CAH-TOA:** Some Old Hippos Can't Always Hide Their Old Age.
>
> **Key insight:** Trig ratios are just the Pythagorean theorem restated as ratios — sin²θ + cos²θ = 1 always holds.
