---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 3
# Parallel and Perpendicular Lines

### Unit 1 — Lines and Angles
### McGraw Hill Glencoe Geometry Texas, 2015

---

## Key Vocabulary

| Term | Definition |
|------|-----------|
| **Parallel lines** | Coplanar lines that never intersect ($\ell \parallel m$) |
| **Perpendicular lines** | Lines that intersect at 90° ($\ell \perp m$) |
| **Skew lines** | Non-coplanar, non-intersecting lines |
| **Transversal** | A line that crosses two or more other lines |
| **Corresponding angles** | Same position at each intersection |
| **Alternate interior angles** | Between parallel lines, on opposite sides of transversal |
| **Co-interior (same-side) angles** | Between parallel lines, on same side of transversal |

---

## Angle Pairs with a Transversal

```
        t
        |
  ——1—2——  ← line ℓ
  ——3—4——
        |
  ——5—6——  ← line m
  ——7—8——
        |
```

| Pair | Angles | Parallel → |
|------|--------|-----------|
| Corresponding | ∠1 & ∠5, ∠2 & ∠6, etc. | Congruent |
| Alt. Interior | ∠3 & ∠6, ∠4 & ∠5 | Congruent |
| Alt. Exterior | ∠1 & ∠8, ∠2 & ∠7 | Congruent |
| Co-interior | ∠3 & ∠5, ∠4 & ∠6 | Supplementary |

---

<!-- _class: theorem -->

## Postulate 3-1: Corresponding Angles Postulate

> If two **parallel** lines are cut by a transversal, then **corresponding angles are congruent**.

$$\ell \parallel m \Rightarrow \angle 1 \cong \angle 5$$

This is the foundation for all parallel line angle theorems.

---

<!-- _class: theorem -->

## Theorem 3-1: Alternate Interior Angles

> If two **parallel** lines are cut by a transversal, then **alternate interior angles are congruent**.

$$\ell \parallel m \Rightarrow \angle 3 \cong \angle 6$$

**Proof basis:** Corresponding Angles Postulate + Vertical Angles Theorem.

---

<!-- _class: theorem -->

## Theorem 3-2: Consecutive Interior Angles (Co-interior)

> If two **parallel** lines are cut by a transversal, then **consecutive interior angles are supplementary**.

$$\ell \parallel m \Rightarrow m\angle 3 + m\angle 5 = 180°$$

Also called **co-interior** or **same-side interior** angles.

---

<!-- _class: theorem -->

## Theorem 3-3: Alternate Exterior Angles

> If two **parallel** lines are cut by a transversal, then **alternate exterior angles are congruent**.

$$\ell \parallel m \Rightarrow \angle 1 \cong \angle 8$$

---

<!-- _class: theorem -->

## Theorem 3-4: Perpendicular Transversal

> In a plane, if a line is perpendicular to one of two **parallel** lines, it is perpendicular to the other.

$$\ell \parallel m \text{ and } t \perp \ell \Rightarrow t \perp m$$

---

## Converses — Proving Lines Parallel

The converses are used to **prove** lines are parallel:

| Theorem | Condition | Conclusion |
|---------|-----------|-----------|
| Post. 3-2 | Corresponding $\angle$s ≅ | Lines $\parallel$ |
| Thm. 3-5 | Alt. interior $\angle$s ≅ | Lines $\parallel$ |
| Thm. 3-6 | Consec. interior $\angle$s supp. | Lines $\parallel$ |
| Thm. 3-7 | Alt. exterior $\angle$s ≅ | Lines $\parallel$ |

---

<!-- _class: theorem -->

## Postulate 3-2: Converse of Corresponding Angles

> If two lines are cut by a transversal so that **corresponding angles are congruent**, then the lines are **parallel**.

$$\angle 1 \cong \angle 5 \Rightarrow \ell \parallel m$$

---

<!-- _class: theorem -->

## Theorem 3-5: Converse of Alternate Interior Angles

> If two lines are cut by a transversal so that **alternate interior angles are congruent**, then the lines are **parallel**.

$$\angle 3 \cong \angle 6 \Rightarrow \ell \parallel m$$

---

<!-- _class: theorem -->

## Theorem 3-6: Converse of Consecutive Interior Angles

> If two lines are cut by a transversal so that **consecutive interior angles are supplementary**, then the lines are **parallel**.

$$m\angle 3 + m\angle 5 = 180° \Rightarrow \ell \parallel m$$

---

<!-- _class: theorem -->

## Theorem 3-7: Parallel Lines in a Plane

> In a plane, if two lines are both **perpendicular to the same line**, they are **parallel** to each other.

$$t \perp \ell \text{ and } t \perp m \Rightarrow \ell \parallel m$$

---

## Slopes of Parallel and Perpendicular Lines

| Relationship | Condition |
|-------------|-----------|
| **Parallel lines** | Equal slopes: $m_1 = m_2$ |
| **Perpendicular lines** | Negative reciprocal slopes: $m_1 \cdot m_2 = -1$ |
| **Horizontal line** | Slope $= 0$ |
| **Vertical line** | Slope undefined |

**Slope formula:** $m = \dfrac{y_2 - y_1}{x_2 - x_1}$

---

<!-- _class: example -->

### Example — Parallel/Perpendicular Slopes

Line $\ell$ passes through $(0, 2)$ and $(3, 8)$.
$$m_\ell = \frac{8-2}{3-0} = \frac{6}{3} = 2$$

- **Parallel line** has slope $= 2$
- **Perpendicular line** has slope $= -\dfrac{1}{2}$

---

<!-- _class: summary -->

## Chapter 3 — Theorem Summary

| # | Name | Key Idea |
|---|------|---------|
| Post. 3-1 | Corr. Angles | $\parallel$ lines → corr. $\angle$s ≅ |
| Thm. 3-1 | Alt. Interior | $\parallel$ lines → alt. int. $\angle$s ≅ |
| Thm. 3-2 | Co-interior | $\parallel$ lines → consec. int. $\angle$s supp. |
| Thm. 3-3 | Alt. Exterior | $\parallel$ lines → alt. ext. $\angle$s ≅ |
| Thm. 3-4 | Perp. Transversal | $t\perp\ell,\ \ell\parallel m \Rightarrow t\perp m$ |
| Post. 3-2 | Conv. Corr. Angles | Corr. $\angle$s ≅ → lines $\parallel$ |
| Thm. 3-5 | Conv. Alt. Interior | Alt. int. ≅ → lines $\parallel$ |
| Thm. 3-6 | Conv. Co-interior | Consec. int. supp. → lines $\parallel$ |
| Thm. 3-7 | Both $\perp$ Same | $t\perp\ell,\ t\perp m \Rightarrow \ell\parallel m$ |
