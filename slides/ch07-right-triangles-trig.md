---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 7
# Right Triangles and Trigonometry

### Unit 2 — Triangles
### McGraw Hill Glencoe Geometry Texas, 2015

---

## Key Vocabulary

| Term | Definition |
|------|-----------|
| **Hypotenuse** | Side opposite the right angle (longest side) |
| **Legs** | The two sides that form the right angle |
| **Geometric mean** | $x$ such that $\dfrac{a}{x} = \dfrac{x}{b}$, so $x = \sqrt{ab}$ |
| **Trigonometric ratio** | Ratio of two sides of a right triangle |
| **Angle of elevation** | Angle above the horizontal |
| **Angle of depression** | Angle below the horizontal |

---

<!-- _class: theorem -->

## Theorem 7-1: Pythagorean Theorem

> In a right triangle, the square of the **hypotenuse** equals the sum of squares of the **legs**.

$$a^2 + b^2 = c^2$$

where $c$ is the hypotenuse and $a$, $b$ are the legs.

**Example:** Legs 3 and 4 → Hypotenuse $= \sqrt{9+16} = \sqrt{25} = 5$.

---

<!-- _class: theorem -->

## Theorem 7-2: Converse of Pythagorean Theorem

> If $a^2 + b^2 = c^2$, then the triangle is a **right triangle**.

| Condition | Triangle type |
|-----------|--------------|
| $a^2 + b^2 = c^2$ | Right |
| $a^2 + b^2 > c^2$ | Acute |
| $a^2 + b^2 < c^2$ | Obtuse |

---

## Pythagorean Triples

Common integer sets satisfying $a^2 + b^2 = c^2$:

| Triple | Multiples |
|--------|-----------|
| **3, 4, 5** | 6-8-10, 9-12-15, … |
| **5, 12, 13** | 10-24-26, … |
| **8, 15, 17** | — |
| **7, 24, 25** | — |

---

<!-- _class: theorem -->

## Theorem 7-3: Geometric Mean (Altitude)

> In a right triangle, the **altitude** to the hypotenuse is the geometric mean between the two segments of the hypotenuse.

$$\frac{AD}{CD} = \frac{CD}{DB} \Rightarrow CD = \sqrt{AD \cdot DB}$$

---

<!-- _class: theorem -->

## Theorem 7-4: Geometric Mean (Legs)

> Each **leg** is the geometric mean of the hypotenuse and the segment of the hypotenuse adjacent to that leg.

$$\frac{AB}{AC} = \frac{AC}{AD} \Rightarrow AC = \sqrt{AB \cdot AD}$$

---

## Special Right Triangles

### 45°–45°–90° Triangle

$$\text{legs} = x \qquad \text{hypotenuse} = x\sqrt{2}$$

**Example:** Leg $= 5 \Rightarrow$ hypotenuse $= 5\sqrt{2}$

---

## Special Right Triangles

### 30°–60°–90° Triangle

$$\text{short leg} = x \qquad \text{long leg} = x\sqrt{3} \qquad \text{hypotenuse} = 2x$$

| Angle | Opposite side |
|-------|--------------|
| 30° | $x$ (short leg) |
| 60° | $x\sqrt{3}$ (long leg) |
| 90° | $2x$ (hypotenuse) |

**Example:** Short leg $= 4 \Rightarrow$ Long leg $= 4\sqrt{3}$, Hyp $= 8$

---

## Trigonometric Ratios

For a right triangle with acute angle $\theta$:

$$\sin\theta = \frac{\text{opposite}}{\text{hypotenuse}} \qquad \cos\theta = \frac{\text{adjacent}}{\text{hypotenuse}} \qquad \tan\theta = \frac{\text{opposite}}{\text{adjacent}}$$

**Memory aid: SOH-CAH-TOA**

| Ratio | Abbr. | Meaning |
|-------|-------|---------|
| **S**ine | SOH | **O**pposite/**H**ypotenuse |
| **C**osine | CAH | **A**djacent/**H**ypotenuse |
| **T**angent | TOA | **O**pposite/**A**djacent |

---

## Common Trig Values

| $\theta$ | $\sin\theta$ | $\cos\theta$ | $\tan\theta$ |
|----------|-------------|-------------|-------------|
| $30°$ | $\frac{1}{2}$ | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{3}}{3}$ |
| $45°$ | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{2}}{2}$ | $1$ |
| $60°$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{2}$ | $\sqrt{3}$ |

---

<!-- _class: example -->

### Example — Finding a Side

In right $\triangle ABC$, $\angle B = 90°$, $\angle A = 35°$, $AB = 10$.

Find $BC$:

$$\tan 35° = \frac{BC}{AB} = \frac{BC}{10}$$

$$BC = 10 \cdot \tan 35° \approx 10 \times 0.700 = 7.00$$

---

<!-- _class: example -->

### Example — Finding an Angle

In right $\triangle ABC$, $\angle B = 90°$, $AB = 6$, $AC = 10$.

$$\cos A = \frac{AB}{AC} = \frac{6}{10} = 0.6$$

$$\angle A = \cos^{-1}(0.6) \approx 53.1°$$

---

<!-- _class: theorem -->

## Angle of Elevation and Depression

> - **Angle of elevation**: measured upward from horizontal
> - **Angle of depression**: measured downward from horizontal

They are **alternate interior angles** when the horizontal lines are parallel → equal measures.

$$\theta_{\text{elevation}} = \theta_{\text{depression}}$$

---

<!-- _class: summary -->

## Chapter 7 — Theorem Summary

| # | Name | Key Idea |
|---|------|---------|
| Thm 7-1 | Pythagorean Theorem | $a^2 + b^2 = c^2$ |
| Thm 7-2 | Converse Pythagorean | $a^2+b^2=c^2$ → right $\triangle$ |
| Thm 7-3 | Geo. Mean (Altitude) | Altitude = geo. mean of hyp. segments |
| Thm 7-4 | Geo. Mean (Leg) | Leg = geo. mean of hyp. and adj. segment |
| — | 45-45-90 | Legs $x$; hyp $x\sqrt{2}$ |
| — | 30-60-90 | Sides $x$, $x\sqrt{3}$, $2x$ |
| — | SOH-CAH-TOA | $\sin$, $\cos$, $\tan$ ratios |
