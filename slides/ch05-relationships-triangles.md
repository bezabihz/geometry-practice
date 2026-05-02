---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 5
# Relationships in Triangles

### Unit 2 — Triangles
### McGraw Hill Glencoe Geometry Texas, 2015

---

## Key Vocabulary

| Term | Definition |
|------|-----------|
| **Perpendicular bisector** | $\perp$ to a segment at its midpoint |
| **Angle bisector** | Ray dividing an angle into two congruent angles |
| **Median** | Segment from vertex to midpoint of opposite side |
| **Altitude** | Perpendicular segment from vertex to opposite side (or its extension) |
| **Circumcenter** | Intersection of perpendicular bisectors |
| **Incenter** | Intersection of angle bisectors |
| **Centroid** | Intersection of medians |
| **Orthocenter** | Intersection of altitudes |

---

## Triangle Centers

| Center | From | Property |
|--------|------|---------|
| **Circumcenter** | Perp. bisectors | Equidistant from vertices; circumscribed circle center |
| **Incenter** | Angle bisectors | Equidistant from sides; inscribed circle center |
| **Centroid** | Medians | Balancing point; $\frac{2}{3}$ of median from vertex |
| **Orthocenter** | Altitudes | May be inside, on, or outside triangle |

---

<!-- _class: theorem -->

## Theorem 5-1: Perpendicular Bisector Theorem

> If a point is on the **perpendicular bisector** of a segment, it is **equidistant** from the endpoints.

$$P \text{ on perp. bisector of } \overline{AB} \Rightarrow PA = PB$$

---

<!-- _class: theorem -->

## Theorem 5-2: Converse of Perpendicular Bisector

> If a point is **equidistant** from the endpoints of a segment, it lies on the **perpendicular bisector**.

$$PA = PB \Rightarrow P \text{ lies on perp. bisector of } \overline{AB}$$

---

<!-- _class: theorem -->

## Theorem 5-3: Angle Bisector Theorem

> If a point is on the **bisector of an angle**, it is **equidistant** from the sides of the angle.

$$P \text{ on bisector of } \angle A \Rightarrow d(P, \overrightarrow{AB}) = d(P, \overrightarrow{AC})$$

---

<!-- _class: theorem -->

## Theorem 5-4: Converse of Angle Bisector Theorem

> If a point in the interior of an angle is **equidistant from the sides**, it lies on the **angle bisector**.

---

<!-- _class: theorem -->

## Theorem 5-5: Circumcenter Theorem

> The **circumcenter** of a triangle is equidistant from all three vertices.

$$CA = CB = CC$$

*The circumcenter is the center of the circumscribed circle.*

---

<!-- _class: theorem -->

## Theorem 5-6: Incenter Theorem

> The **incenter** of a triangle is equidistant from all three sides.

*The incenter is the center of the inscribed circle.*

---

<!-- _class: theorem -->

## Theorem 5-7: Centroid Theorem

> The **centroid** divides each median in a $2:1$ ratio from vertex to midpoint.

$$\text{Centroid to vertex} = \frac{2}{3} \times \text{median length}$$

**Example:** If median $AM = 12$, then centroid $G$ satisfies $AG = 8$ and $GM = 4$.

---

<!-- _class: theorem -->

## Theorem 5-8: Exterior Angle Inequality

> An **exterior angle** of a triangle is greater than either of the **non-adjacent interior angles**.

$$m\angle 4 > m\angle 1 \quad \text{and} \quad m\angle 4 > m\angle 2$$

---

<!-- _class: theorem -->

## Theorem 5-9: Angle-Side Relationship

> In a triangle, the **larger side** is opposite the **larger angle**.

$$m\angle A > m\angle B \Rightarrow BC > AC$$

*(The longest side is opposite the largest angle.)*

---

<!-- _class: theorem -->

## Theorem 5-10: Converse of Angle-Side Relationship

> In a triangle, the **larger angle** is opposite the **larger side**.

$$BC > AC \Rightarrow m\angle A > m\angle B$$

---

<!-- _class: theorem -->

## Theorem 5-11: Triangle Inequality Theorem

> The **sum of any two sides** of a triangle must be **greater than** the third side.

$$AB + BC > AC$$
$$AB + AC > BC$$
$$BC + AC > AB$$

**Test:** Can 5, 7, 10 form a triangle?  
$5 + 7 = 12 > 10$ ✓, $5 + 10 = 15 > 7$ ✓, $7 + 10 = 17 > 5$ ✓ → **Yes**

---

<!-- _class: example -->

### Example — Triangle Inequality

Can segments of length 3, 5, and 9 form a triangle?

$$3 + 5 = 8 \not> 9 \quad \text{✗ FAILS}$$

**No**, these cannot form a triangle.

---

<!-- _class: theorem -->

## Theorem 5-12: Hinge Theorem (SAS Inequality)

> If two triangles have two pairs of congruent sides, the triangle with the **larger included angle** has the **longer third side**.

$$\overline{AB} \cong \overline{DE},\ \overline{BC} \cong \overline{EF},\ m\angle B > m\angle E \Rightarrow AC > DF$$

---

<!-- _class: theorem -->

## Theorem 5-13: Converse of Hinge Theorem

> If two triangles have two pairs of congruent sides, the triangle with the **longer third side** has the **larger included angle**.

$$AC > DF \Rightarrow m\angle B > m\angle E$$

---

<!-- _class: example -->

### Example — Centroid

Triangle $ABC$ has centroid $G$. Median $\overline{BD}$ has length 18.

$$BG = \frac{2}{3}(18) = 12 \qquad GD = \frac{1}{3}(18) = 6$$

---

<!-- _class: summary -->

## Chapter 5 — Theorem Summary

| # | Name | Key Idea |
|---|------|---------|
| Thm 5-1/2 | Perp. Bisector | On bisector $\iff$ equidistant from endpoints |
| Thm 5-3/4 | Angle Bisector | On bisector $\iff$ equidistant from sides |
| Thm 5-5 | Circumcenter | Equidistant from vertices |
| Thm 5-6 | Incenter | Equidistant from sides |
| Thm 5-7 | Centroid | $\tfrac{2}{3}$ from vertex along median |
| Thm 5-8 | Ext. Angle Ineq. | Exterior $\angle$ > non-adjacent interior $\angle$s |
| Thm 5-9/10 | Angle-Side | Larger $\angle$ ↔ longer opposite side |
| Thm 5-11 | Triangle Inequality | Sum of any 2 sides > 3rd side |
| Thm 5-12/13 | Hinge Theorem | Larger included $\angle$ ↔ longer 3rd side |
