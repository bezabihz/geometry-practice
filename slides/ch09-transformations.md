---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 9
# Transformations

### Unit 3 — Quadrilaterals and Circles
### McGraw Hill Glencoe Geometry Texas, 2015

---

## Key Vocabulary

| Term | Definition |
|------|-----------|
| **Transformation** | Movement of a figure in a plane |
| **Preimage** | Original figure before transformation |
| **Image** | Resulting figure after transformation |
| **Isometry** | Transformation that preserves size and shape (congruence) |
| **Rigid motion** | Another name for isometry |
| **Composition** | Two or more transformations applied in sequence |

---

## Types of Transformations

| Type | Isometry? | Preserves |
|------|:---------:|---------|
| **Translation** | ✓ | Size, shape, orientation |
| **Reflection** | ✓ | Size, shape; flips orientation |
| **Rotation** | ✓ | Size, shape, orientation |
| **Dilation** | ✗ | Shape (not size) |

---

<!-- _class: theorem -->

## Translation

> A **translation** moves every point the same distance and direction.

**Coordinate notation:** $(x, y) \to (x + a,\ y + b)$

**Vector notation:** $\langle a, b \rangle$ means move $a$ units right and $b$ units up.

**Example:** Translate $A(3, 2)$ by $\langle -1, 4 \rangle$:
$$A' = (3 + (-1),\ 2 + 4) = (2, 6)$$

---

<!-- _class: theorem -->

## Reflection

> A **reflection** flips a figure over a line (the **line of reflection**).

| Line of Reflection | Rule |
|-------------------|------|
| $x$-axis | $(x, y) \to (x, -y)$ |
| $y$-axis | $(x, y) \to (-x, y)$ |
| $y = x$ | $(x, y) \to (y, x)$ |
| $y = -x$ | $(x, y) \to (-y, -x)$ |

---

<!-- _class: theorem -->

## Rotation

> A **rotation** turns a figure about a fixed **center point** by a given **angle**.

Common rotations about the origin:

| Rotation | Rule |
|----------|------|
| $90°$ CCW | $(x, y) \to (-y, x)$ |
| $180°$ | $(x, y) \to (-x, -y)$ |
| $270°$ CCW (= $90°$ CW) | $(x, y) \to (y, -x)$ |
| $360°$ | $(x, y) \to (x, y)$ |

---

<!-- _class: example -->

### Example — Rotation 90° CCW

Rotate $P(4, -2)$ by $90°$ counterclockwise about the origin.

$$(x, y) \to (-y, x)$$
$$P(4, -2) \to P'(2, 4)$$

---

<!-- _class: theorem -->

## Theorem 9-1: Reflections Preserve Congruence

> A reflection is an **isometry**: the image is congruent to the preimage.

$$\triangle ABC \cong \triangle A'B'C'$$

---

<!-- _class: theorem -->

## Theorem 9-2: Composition of Reflections — Parallel Lines

> A composition of reflections over two **parallel** lines is equivalent to a **translation**.

The translation distance = **twice** the distance between the lines.

$$\text{distance of translation} = 2d(\ell_1, \ell_2)$$

---

<!-- _class: theorem -->

## Theorem 9-3: Composition of Reflections — Intersecting Lines

> A composition of reflections over two **intersecting** lines is equivalent to a **rotation**.

The rotation angle = **twice** the angle between the lines.

$$\text{angle of rotation} = 2 \times \theta$$

---

<!-- _class: theorem -->

## Dilation

> A **dilation** with center $C$ and scale factor $k$ maps each point $P$ to $P'$ such that:

$$CP' = k \cdot CP$$

**Coordinate rule** (center at origin):

$$(x, y) \to (kx,\ ky)$$

- $k > 1$: **enlargement**
- $0 < k < 1$: **reduction**
- $k = 1$: identity (no change)

---

<!-- _class: example -->

### Example — Dilation

Dilate $\triangle ABC$ with vertices $A(2,4)$, $B(0,2)$, $C(4,0)$ by scale factor $k = 3$.

$$A' = (6, 12),\quad B' = (0, 6),\quad C' = (12, 0)$$

The image is **3 times larger** and **similar** to the original.

---

<!-- _class: theorem -->

## Symmetry

| Type | Description |
|------|-------------|
| **Line symmetry** | Figure maps onto itself when reflected over a line |
| **Rotational symmetry** | Figure maps onto itself when rotated $< 360°$ |
| **Point symmetry** | Maps onto itself when rotated $180°$ about a center |

**Example:** A regular hexagon has 6 lines of symmetry and rotational symmetry of order 6 (every 60°).

---

<!-- _class: summary -->

## Chapter 9 — Transformation Summary

| Transformation | Rule (origin) | Isometry |
|---------------|--------------|:--------:|
| Translation $\langle a,b \rangle$ | $(x+a, y+b)$ | ✓ |
| Reflection over $x$-axis | $(x, -y)$ | ✓ |
| Reflection over $y$-axis | $(-x, y)$ | ✓ |
| Rotation $90°$ CCW | $(-y, x)$ | ✓ |
| Rotation $180°$ | $(-x,-y)$ | ✓ |
| Rotation $270°$ CCW | $(y,-x)$ | ✓ |
| Dilation scale $k$ | $(kx, ky)$ | ✗ |

---

<!-- _class: summary -->

## Composition Theorems

| Theorem | Condition | Equivalent To |
|---------|-----------|--------------|
| Thm 9-2 | Reflect over 2 parallel lines | Translation (2× distance) |
| Thm 9-3 | Reflect over 2 intersecting lines | Rotation (2× angle) |
