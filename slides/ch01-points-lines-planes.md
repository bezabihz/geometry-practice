---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 1
# Points, Lines, Planes, and Angles

### Unit 1 — Lines and Angles
### McGraw Hill Glencoe Geometry Texas, 2015

---

## Key Vocabulary

| Term | Definition |
|------|-----------|
| **Point** | A location with no size or shape |
| **Line** | Infinitely many points extending in two directions |
| **Plane** | Flat surface extending infinitely in all directions |
| **Segment** | Part of a line with two endpoints |
| **Ray** | Part of a line with one endpoint, extending in one direction |
| **Collinear** | Points on the same line |
| **Coplanar** | Points or lines on the same plane |

---

<!-- _class: theorem -->

## Postulate 1-1: Unique Line

> Through any **two points**, there is exactly **one line**.

$$\text{Points } A \text{ and } B \Rightarrow \overleftrightarrow{AB} \text{ is unique}$$

**Diagram:** `A ——————— B`  (only one line passes through both)

---

<!-- _class: theorem -->

## Postulate 1-2: Line Intersection

> If two distinct lines **intersect**, they intersect in exactly **one point**.

$$\ell_1 \cap \ell_2 = \{P\}$$

**Note:** Two lines either are parallel (never intersect), identical, or intersect at exactly one point.

---

<!-- _class: theorem -->

## Postulate 1-3: Plane Intersection

> If two distinct planes **intersect**, they intersect in exactly **one line**.

**Example:** The floor and a wall of a room intersect along one edge (a line).

---

<!-- _class: theorem -->

## Postulate 1-4: Unique Plane

> Through any **three noncollinear points** there is exactly **one plane**.

**Key word:** *Noncollinear* — the three points must not all lie on the same line.

---

<!-- _class: theorem -->

## Postulate 1-5: Ruler Postulate

> The points on a line can be paired one-to-one with the **real numbers**.  
> The distance between points $A$ and $B$ is:

$$AB = |a - b|$$

where $a$ and $b$ are the coordinates of $A$ and $B$.

---

<!-- _class: theorem -->

## Postulate 1-6: Segment Addition Postulate

> If $B$ is between $A$ and $C$, then:

$$AB + BC = AC$$

**Example:** If $AB = 5$ and $BC = 8$, then $AC = 13$.

`A ——5—— B ——8—— C`

---

<!-- _class: theorem -->

## Midpoint Theorem

> The **midpoint** $M$ of segment $\overline{AB}$ divides it into two congruent segments:

$$AM = MB = \frac{AB}{2}$$

**Coordinate Midpoint Formula:**

$$M = \left(\frac{x_1 + x_2}{2},\ \frac{y_1 + y_2}{2}\right)$$

---

<!-- _class: example -->

### Example — Midpoint

Find the midpoint of $A(2, 5)$ and $B(8, 1)$.

$$M = \left(\frac{2+8}{2},\ \frac{5+1}{2}\right) = \left(5,\ 3\right)$$

**Check:** Distance from $A$ to $M$ = Distance from $M$ to $B$.

---

<!-- _class: theorem -->

## Distance Formula

$$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

**Example:** Distance from $A(1, 2)$ to $B(4, 6)$:

$$d = \sqrt{(4-1)^2 + (6-2)^2} = \sqrt{9 + 16} = \sqrt{25} = 5$$

---

<!-- _class: theorem -->

## Postulate 1-7: Protractor Postulate

> Rays from a point can be paired with real numbers from $0°$ to $180°$.  
> The measure of an angle is the absolute difference of its ray coordinates.

$$m\angle AOB = |r_1 - r_2|$$

---

<!-- _class: theorem -->

## Postulate 1-8: Angle Addition Postulate

> If $D$ is in the interior of $\angle ABC$, then:

$$m\angle ABD + m\angle DBC = m\angle ABC$$

**Example:** If $m\angle ABD = 35°$ and $m\angle DBC = 50°$, then $m\angle ABC = 85°$.

---

<!-- _class: theorem -->

## Angle Pairs: Definitions

| Pair | Definition | Sum |
|------|-----------|-----|
| **Complementary** | Two angles | $= 90°$ |
| **Supplementary** | Two angles | $= 180°$ |
| **Linear Pair** | Adjacent, supplementary angles | $= 180°$ |
| **Vertical Angles** | Opposite angles from two intersecting lines | Equal |

---

<!-- _class: theorem -->

## Vertical Angles Theorem (Theorem 1-1)

> **Vertical angles are congruent.**

$$\angle 1 \cong \angle 3 \quad \text{and} \quad \angle 2 \cong \angle 4$$

```
     \  /
   2  \/  1
   ---/\---
   3  /\  4
     /  \
```

If $\angle 1 = 70°$, then $\angle 3 = 70°$ and $\angle 2 = \angle 4 = 110°$.

---

<!-- _class: theorem -->

## Supplement Theorem (Theorem 1-2)

> If two angles form a **linear pair**, they are **supplementary**.

$$m\angle 1 + m\angle 2 = 180°$$

---

<!-- _class: theorem -->

## Complement Theorem (Theorem 1-3)

> If the noncommon sides of two adjacent angles form a **right angle**, the angles are **complementary**.

$$m\angle 1 + m\angle 2 = 90°$$

---

<!-- _class: summary -->

## Chapter 1 — Theorem Summary

| # | Name | Statement |
|---|------|-----------|
| Post. 1-1 | Unique Line | 2 points → 1 line |
| Post. 1-2 | Line Intersection | 2 lines → 1 point |
| Post. 1-3 | Plane Intersection | 2 planes → 1 line |
| Post. 1-4 | Unique Plane | 3 noncollinear pts → 1 plane |
| Post. 1-6 | Segment Addition | $AB + BC = AC$ |
| Post. 1-8 | Angle Addition | $m\angle ABD + m\angle DBC = m\angle ABC$ |
| Thm. 1-1 | Vertical Angles | Vertical $\angles$ are $\cong$ |
| Thm. 1-2 | Supplement | Linear pair → supplementary |
| Thm. 1-3 | Complement | Right angle → complementary pair |
