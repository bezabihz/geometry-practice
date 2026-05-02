---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 6
# Proportions and Similarity

### Unit 2 — Triangles
### McGraw Hill Glencoe Geometry Texas, 2015

---

## Key Vocabulary

| Term | Definition |
|------|-----------|
| **Ratio** | Comparison of two quantities: $\frac{a}{b}$ |
| **Proportion** | Equation stating two ratios are equal: $\frac{a}{b} = \frac{c}{d}$ |
| **Extremes** | Outer terms of a proportion ($a$ and $d$) |
| **Means** | Inner terms of a proportion ($b$ and $c$) |
| **Similar polygons** | Same shape, proportional sides, congruent angles |
| **Scale factor** | Ratio of corresponding sides of similar figures |
| **Dilation** | Enlargement or reduction preserving shape |

---

<!-- _class: theorem -->

## Cross-Products Property

> In the proportion $\dfrac{a}{b} = \dfrac{c}{d}$, the cross products are equal:

$$ad = bc$$

**Example:** $\dfrac{x}{6} = \dfrac{5}{3}$
$$3x = 30 \Rightarrow x = 10$$

---

<!-- _class: theorem -->

## Properties of Proportions

| Property | Statement |
|----------|-----------|
| **Reciprocal** | If $\dfrac{a}{b} = \dfrac{c}{d}$, then $\dfrac{b}{a} = \dfrac{d}{c}$ |
| **Exchange Means** | $\dfrac{a}{b} = \dfrac{c}{d} \Rightarrow \dfrac{a}{c} = \dfrac{b}{d}$ |
| **Addition** | $\dfrac{a}{b} = \dfrac{c}{d} \Rightarrow \dfrac{a+b}{b} = \dfrac{c+d}{d}$ |

---

<!-- _class: theorem -->

## Definition: Similar Polygons

> Two polygons are **similar** if:
> 1. All corresponding angles are **congruent**
> 2. All corresponding sides are **proportional**

$$\triangle ABC \sim \triangle DEF$$

$$\frac{AB}{DE} = \frac{BC}{EF} = \frac{AC}{DF} = k \quad (\text{scale factor})$$

---

<!-- _class: theorem -->

## Postulate 6-1: AA (Angle-Angle) Similarity

> If two angles of one triangle are congruent to two angles of another, the triangles are **similar**.

$$\angle A \cong \angle D \text{ and } \angle B \cong \angle E \Rightarrow \triangle ABC \sim \triangle DEF$$

*Only 2 angles needed — the 3rd follows from the angle sum.*

---

<!-- _class: theorem -->

## Theorem 6-1: SSS (Side-Side-Side) Similarity

> If all three pairs of corresponding sides are **proportional**, the triangles are **similar**.

$$\frac{AB}{DE} = \frac{BC}{EF} = \frac{AC}{DF} \Rightarrow \triangle ABC \sim \triangle DEF$$

---

<!-- _class: theorem -->

## Theorem 6-2: SAS (Side-Angle-Side) Similarity

> If two pairs of corresponding sides are **proportional** and the **included angles are congruent**, the triangles are **similar**.

$$\frac{AB}{DE} = \frac{BC}{EF} \text{ and } \angle B \cong \angle E \Rightarrow \triangle ABC \sim \triangle DEF$$

---

<!-- _class: theorem -->

## Theorem 6-3: Triangle Proportionality Theorem

> If a line is **parallel to one side** of a triangle and intersects the other two sides, it divides them **proportionally**.

$$DE \parallel BC \Rightarrow \frac{AD}{DB} = \frac{AE}{EC}$$

---

<!-- _class: theorem -->

## Theorem 6-4: Converse of Triangle Proportionality

> If a line divides two sides of a triangle **proportionally**, it is **parallel** to the third side.

$$\frac{AD}{DB} = \frac{AE}{EC} \Rightarrow DE \parallel BC$$

---

<!-- _class: theorem -->

## Theorem 6-5: Triangle Midsegment Theorem

> The segment connecting the **midpoints** of two sides of a triangle:
> 1. Is **parallel** to the third side
> 2. Is **half the length** of the third side

$$DE \text{ is midsegment} \Rightarrow DE \parallel BC \text{ and } DE = \frac{1}{2}BC$$

---

<!-- _class: example -->

### Example — Midsegment

In $\triangle ABC$, $D$ is the midpoint of $\overline{AB}$ and $E$ is the midpoint of $\overline{AC}$.

If $BC = 14$, find $DE$.

$$DE = \frac{1}{2}(14) = 7$$

---

<!-- _class: theorem -->

## Theorem 6-6: Proportional Parts (Parallel Lines)

> If three or more parallel lines intersect two transversals, they divide the transversals **proportionally**.

$$\ell_1 \parallel \ell_2 \parallel \ell_3 \Rightarrow \frac{AB}{BC} = \frac{DE}{EF}$$

---

<!-- _class: theorem -->

## Theorem 6-7: Angle Bisector Proportionality

> An **angle bisector** of a triangle divides the opposite side proportionally to the adjacent sides.

$$\overrightarrow{AD} \text{ bisects } \angle A \Rightarrow \frac{BD}{DC} = \frac{AB}{AC}$$

---

<!-- _class: theorem -->

## Similar Triangles — Perimeters and Areas

| Property | Scale Factor $k$ |
|----------|----------------|
| **Perimeters** | Ratio $= k$ |
| **Areas** | Ratio $= k^2$ |

**Example:** Scale factor $= \dfrac{3}{2}$
- Perimeter ratio $= \dfrac{3}{2}$
- Area ratio $= \dfrac{9}{4}$

---

<!-- _class: summary -->

## Chapter 6 — Theorem Summary

| # | Name | Key Idea |
|---|------|---------|
| Post. 6-1 | AA Similarity | 2 $\angle$s congruent → similar |
| Thm 6-1 | SSS Similarity | All sides proportional → similar |
| Thm 6-2 | SAS Similarity | 2 sides prop. + included $\angle$ ≅ |
| Thm 6-3/4 | Triangle Proportionality | Parallel line ↔ proportional sides |
| Thm 6-5 | Midsegment | $\frac{1}{2}$ length, parallel to base |
| Thm 6-6 | Parallel Lines | Divide transversals proportionally |
| Thm 6-7 | Angle Bisector | Divides opp. side proportionally |
