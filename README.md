# Texas Geometry Credit by Exam Prep

**Textbook:** McGraw Hill Glencoe Geometry Texas, 2015
**Exams:** UTHS Geometry A (Semester 1) and Geometry B (Semester 2)
**Format:** 40 multiple-choice questions, 3 hours, 70% to pass

---

## What's Inside

| Folder | Contents |
|--------|----------|
| `slides/` | Marp markdown slide decks — one per chapter (13 total) |
| `practice/` | Full-length 40-question practice exams + answer keys |
| `dist/` | Rendered HTML/PDF output (generated, not committed) |

### Slide Decks (by chapter)

| File | Chapter |
|------|---------|
| `ch01-points-lines-planes.md` | Ch 1: Points, Lines, Planes, and Angles |
| `ch02-reasoning-proof.md` | Ch 2: Reasoning and Proof |
| `ch03-parallel-perpendicular.md` | Ch 3: Parallel and Perpendicular Lines |
| `ch04-congruent-triangles.md` | Ch 4: Congruent Triangles |
| `ch05-relationships-triangles.md` | Ch 5: Relationships in Triangles |
| `ch06-proportions-similarity.md` | Ch 6: Proportions and Similarity |
| `ch07-right-triangles-trig.md` | Ch 7: Right Triangles and Trigonometry |
| `ch08-quadrilaterals.md` | Ch 8: Quadrilaterals |
| `ch09-transformations.md` | Ch 9: Transformations |
| `ch10-circles.md` | Ch 10: Circles |
| `ch11-areas.md` | Ch 11: Areas of Polygons and Circles |
| `ch12-surface-area.md` | Ch 12: Surface Area |
| `ch13-volume.md` | Ch 13: Volume |

### Practice Exams

| File | Description |
|------|-------------|
| `practice/exam-A-practice.md` | Semester A — 40 MCQ (Chapters 1–5, 7, 9) |
| `practice/exam-B-practice.md` | Semester B — 40 MCQ (Chapters 6, 8, 10–13) |
| `practice/exam-A-answers.md` | Answer key with explanations for Exam A |
| `practice/exam-B-answers.md` | Answer key with explanations for Exam B |

---

## Setup

```bash
npm install
```

## Render Slides (HTML)

```bash
npm run slides      # → dist/slides/*.html
npm run exam        # → dist/practice/*.html
npm run all         # both
```

## Render to PDF

```bash
npm run slides:pdf
npm run exam:pdf
npm run all:pdf
```

> PDF export requires Chrome/Edge installed. Marp uses it for headless rendering.

## View in VS Code

Install the **Marp for VS Code** extension for live slide preview while editing.

---

## Exam Coverage Map

### Semester A — Chapters 1–5, 7, 9

| Topic | Chapter | Questions (approx.) |
|-------|---------|---------------------|
| Points, lines, planes, angles | 1 | 5 |
| Coordinate geometry, midpoint, distance | 1 | 3 |
| Reasoning, conditionals, proofs | 2 | 6 |
| Parallel lines, transversals | 3 | 5 |
| Triangle congruence (SSS/SAS/ASA/AAS) | 4 | 8 |
| Triangle relationships, inequalities | 5 | 5 |
| Right triangles, Pythagorean Theorem, trig | 7 | 5 |
| Transformations (translations, reflections, rotations, dilations) | 9 | 3 |

### Semester B — Chapters 6, 8, 10–13

| Topic | Chapter | Questions (approx.) |
|-------|---------|---------------------|
| Proportions and similarity | 6 | 7 |
| Quadrilaterals | 8 | 6 |
| Circle theorems | 10 | 8 |
| Areas of polygons and circles | 11 | 5 |
| Surface area | 12 | 5 |
| Volume | 13 | 5 |
| Geometric probability | — | 4 |
