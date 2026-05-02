---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 4
# Congruent Triangles

### Unit 2 — Triangles
### McGraw Hill Glencoe Geometry Texas, 2015

---

## Key Vocabulary

| Term | Definition |
|------|-----------|
| **Congruent polygons** | All corresponding sides and angles are congruent |
| **CPCTC** | Corresponding Parts of Congruent Triangles are Congruent |
| **Included angle** | The angle between two given sides |
| **Included side** | The side between two given angles |
| **Isosceles triangle** | At least two congruent sides |
| **Equilateral triangle** | All three sides congruent |
| **Corollary** | A theorem that follows directly from another |

---

<!-- _class: theorem -->

## Theorem 4-1: Triangle Angle Sum

> The sum of the measures of the angles of a triangle is **180°**.

$$m\angle A + m\angle B + m\angle C = 180°$$

**Example:** If $m\angle A = 50°$ and $m\angle B = 70°$, then $m\angle C = 60°$.

---

<!-- _class: theorem -->

## Theorem 4-2: Exterior Angle Theorem

> An **exterior angle** of a triangle equals the sum of the two **non-adjacent interior angles**.

$$m\angle 4 = m\angle 1 + m\angle 2$$

```
       A
      /|
     / |
    /  |
   B———C——→ (exterior angle at C)
```

---

<!-- _class: theorem -->

## Corollary 4-1: Third Angle Corollary

> If two angles of one triangle are congruent to two angles of another triangle, then the **third angles** are also congruent.

$$\angle A \cong \angle D \text{ and } \angle B \cong \angle E \Rightarrow \angle C \cong \angle F$$

---

<!-- _class: theorem -->

## Postulate 4-1: SSS (Side-Side-Side) Congruence

> If **three sides** of one triangle are congruent to three sides of another, the triangles are **congruent**.

$$AB = DE,\ BC = EF,\ AC = DF \Rightarrow \triangle ABC \cong \triangle DEF$$

*No angle information needed.*

---

<!-- _class: theorem -->

## Postulate 4-2: SAS (Side-Angle-Side) Congruence

> If **two sides** and the **included angle** of one triangle are congruent to those of another, the triangles are **congruent**.

$$AB = DE,\ \angle B \cong \angle E,\ BC = EF \Rightarrow \triangle ABC \cong \triangle DEF$$

*The angle must be between the two sides.*

---

<!-- _class: theorem -->

## Postulate 4-3: ASA (Angle-Side-Angle) Congruence

> If **two angles** and the **included side** of one triangle are congruent to those of another, the triangles are **congruent**.

$$\angle A \cong \angle D,\ AB = DE,\ \angle B \cong \angle E \Rightarrow \triangle ABC \cong \triangle DEF$$

*The side must be between the two angles.*

---

<!-- _class: theorem -->

## Theorem 4-3: AAS (Angle-Angle-Side) Congruence

> If **two angles** and a **non-included side** of one triangle are congruent to those of another, the triangles are **congruent**.

$$\angle A \cong \angle D,\ \angle B \cong \angle E,\ BC = EF \Rightarrow \triangle ABC \cong \triangle DEF$$

*AAS is a theorem (proved), not a postulate.*

---

<!-- _class: theorem -->

## Theorem 4-4: HL (Hypotenuse-Leg) Congruence

> For **right triangles**: if the **hypotenuse** and one **leg** are congruent, the triangles are **congruent**.

$$\text{Right } \triangle ABC \cong \text{Right } \triangle DEF \text{ if hyp and one leg are } \cong$$

*Only applies to right triangles.*

---

## Congruence Shortcut Summary

| Shortcut | Type | Notes |
|----------|------|-------|
| **SSS** | Postulate | 3 sides |
| **SAS** | Postulate | 2 sides + included $\angle$ |
| **ASA** | Postulate | 2 $\angle$s + included side |
| **AAS** | Theorem | 2 $\angle$s + non-included side |
| **HL** | Theorem | Right triangles only |
| ~~AAA~~ | ✗ NOT valid | Proves similarity, not congruence |
| ~~SSA~~ | ✗ NOT valid | "Ambiguous case" |

---

<!-- _class: theorem -->

## Theorem 4-5: Isosceles Triangle Theorem

> If two sides of a triangle are congruent, then the **angles opposite** those sides are congruent.

$$\overline{AB} \cong \overline{AC} \Rightarrow \angle B \cong \angle C$$

*(Base angles of an isosceles triangle are congruent.)*

---

<!-- _class: theorem -->

## Theorem 4-6: Converse of Isosceles Triangle Theorem

> If two angles of a triangle are congruent, then the **sides opposite** those angles are congruent.

$$\angle B \cong \angle C \Rightarrow \overline{AB} \cong \overline{AC}$$

---

<!-- _class: theorem -->

## Corollary 4-2: Equilateral Triangle

> A triangle is **equilateral** if and only if it is **equiangular**.

$$\overline{AB} \cong \overline{BC} \cong \overline{AC} \iff \angle A = \angle B = \angle C = 60°$$

---

<!-- _class: example -->

### Example — Proving Congruence

**Given:** $M$ is the midpoint of $\overline{AB}$; $\angle ACM \cong \angle BCM$

**Prove:** $\triangle ACM \cong \triangle BCM$

| Statement | Reason |
|-----------|--------|
| $AM = BM$ | Definition of midpoint |
| $\angle ACM \cong \angle BCM$ | Given |
| $CM = CM$ | Reflexive property |
| $\triangle ACM \cong \triangle BCM$ | **SAS** |

---

<!-- _class: summary -->

## Chapter 4 — Theorem Summary

| # | Name | Key Idea |
|---|------|---------|
| Thm 4-1 | Angle Sum | $\angle A + \angle B + \angle C = 180°$ |
| Thm 4-2 | Exterior Angle | Ext. $\angle$ = sum of remote interior $\angle$s |
| Cor 4-1 | Third Angle | 2 pairs congruent → 3rd pair congruent |
| Post 4-1 | SSS | 3 sides |
| Post 4-2 | SAS | 2 sides + included angle |
| Post 4-3 | ASA | 2 angles + included side |
| Thm 4-3 | AAS | 2 angles + non-included side |
| Thm 4-4 | HL | Hypotenuse-leg (right triangles) |
| Thm 4-5 | Isosceles | $\cong$ sides → $\cong$ base angles |
| Thm 4-6 | Conv. Isosceles | $\cong$ angles → $\cong$ opposite sides |
| Cor 4-2 | Equilateral | Equilateral $\iff$ equiangular ($60°$ each) |
