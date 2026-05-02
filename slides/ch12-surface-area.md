---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 12
# Surface Area

### Unit 4 — Area and Volume
### McGraw Hill Glencoe Geometry Texas, 2015

---

## Key Vocabulary

| Term | Definition |
|------|-----------|
| **Polyhedron** | 3D solid with flat polygon faces |
| **Prism** | Polyhedron with two congruent parallel bases |
| **Pyramid** | Polyhedron with one base; other faces are triangles meeting at a vertex |
| **Cylinder** | Solid with two congruent circular bases |
| **Cone** | Solid with one circular base and a vertex |
| **Lateral face** | Non-base face of a prism or pyramid |
| **Lateral area (LA)** | Total area of lateral faces only |
| **Surface area (SA)** | Total area of all faces |
| **Slant height ($\ell$)** | Height of a lateral face (pyramid or cone) |

---

## Euler's Formula

> For any **polyhedron**:

$$F + V - E = 2$$

where $F$ = faces, $V$ = vertices, $E$ = edges.

**Example:** Cube: $F=6$, $V=8$, $E=12$ → $6+8-12=2$ ✓

---

<!-- _class: theorem -->

## Theorem 12-1: Lateral Area of a Right Prism

$$LA = Ph$$

where $P$ = perimeter of base, $h$ = height.

$$SA = LA + 2B = Ph + 2B$$

where $B$ = area of one base.

---

<!-- _class: example -->

### Example — Rectangular Prism

Prism: $l=5$, $w=3$, $h=4$

$$LA = 2(5+3)(4) = 2(8)(4) = 64$$
$$SA = 64 + 2(5 \times 3) = 64 + 30 = 94$$

---

<!-- _class: theorem -->

## Theorem 12-2: Lateral Area of a Right Cylinder

$$LA = 2\pi rh$$

$$SA = 2\pi rh + 2\pi r^2$$

**Example:** Radius 3, height 7:
$$SA = 2\pi(3)(7) + 2\pi(9) = 42\pi + 18\pi = 60\pi$$

---

<!-- _class: theorem -->

## Theorem 12-3: Lateral Area of a Regular Pyramid

$$LA = \frac{1}{2}P\ell$$

where $P$ = perimeter of base, $\ell$ = slant height.

$$SA = \frac{1}{2}P\ell + B$$

---

<!-- _class: example -->

### Example — Square Pyramid

Base side $= 6$, slant height $= 5$.

$$LA = \frac{1}{2}(24)(5) = 60$$
$$SA = 60 + 36 = 96$$

---

<!-- _class: theorem -->

## Theorem 12-4: Lateral Area of a Cone

$$LA = \pi r\ell$$

where $r$ = radius, $\ell$ = slant height.

$$SA = \pi r\ell + \pi r^2$$

**Slant height relationship:** $\ell^2 = r^2 + h^2$

---

<!-- _class: theorem -->

## Surface Area of a Sphere

$$SA = 4\pi r^2$$

**Example:** Radius $= 6$:
$$SA = 4\pi(36) = 144\pi \approx 452.4$$

---

## Surface Area Summary

| Solid | Lateral Area | Surface Area |
|-------|-------------|-------------|
| Right Prism | $Ph$ | $Ph + 2B$ |
| Cylinder | $2\pi rh$ | $2\pi rh + 2\pi r^2$ |
| Regular Pyramid | $\frac{1}{2}P\ell$ | $\frac{1}{2}P\ell + B$ |
| Cone | $\pi r\ell$ | $\pi r\ell + \pi r^2$ |
| Sphere | — | $4\pi r^2$ |

*$P$ = perimeter of base, $h$ = height, $B$ = base area, $\ell$ = slant height*

---

<!-- _class: example -->

### Example — Cone

A cone has radius 5 and height 12. Find the surface area.

**Step 1:** Find slant height:
$$\ell = \sqrt{5^2 + 12^2} = \sqrt{25 + 144} = \sqrt{169} = 13$$

**Step 2:** Find SA:
$$SA = \pi(5)(13) + \pi(5)^2 = 65\pi + 25\pi = 90\pi \approx 282.7$$

---

## Cross Sections

| Solid | Cutting plane | Cross section |
|-------|--------------|--------------|
| Sphere | Any | Circle |
| Cylinder | $\parallel$ to base | Circle |
| Cylinder | $\perp$ to base | Rectangle |
| Cube | $\parallel$ to face | Square |
| Cube | diagonal | Rectangle |
| Pyramid | $\parallel$ to base | Similar polygon |

---

<!-- _class: summary -->

## Chapter 12 — Formula Summary

| Solid | SA Formula |
|-------|-----------|
| Right Prism | $Ph + 2B$ |
| Cylinder | $2\pi rh + 2\pi r^2$ |
| Regular Pyramid | $\frac{1}{2}P\ell + B$ |
| Cone | $\pi r\ell + \pi r^2$; slant $\ell = \sqrt{r^2+h^2}$ |
| Sphere | $4\pi r^2$ |
