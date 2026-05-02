---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 2
## Reasoning and Proof

McGraw Hill Glencoe Geometry · Texas Edition

---

## Inductive vs. Deductive Reasoning

<div class="columns">
<div>

**Inductive reasoning** — observing patterns to make a **conjecture** (an educated guess).
A single counterexample disproves a conjecture.

**Deductive reasoning** — using accepted facts, definitions, and logic to *prove* a statement must be true.

| | Inductive | Deductive |
|--|-----------|-----------|
| Based on | Patterns / examples | Rules / logic |
| Result | Conjecture | Proof |
| Can be disproved by | Counterexample | Logical error |

> **Example conjecture:** "The sum of two odd numbers is even."
> Test: $3+5=8$ ✓, $7+9=16$ ✓ ... but to *prove* it, we need algebra, not examples.

</div>
<div>

<svg width="310" height="250" viewBox="0 0 310 250" xmlns="http://www.w3.org/2000/svg">
  <rect x="10" y="20" width="130" height="100" rx="10" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="75" y="45" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold" text-anchor="middle">Inductive</text>
  <text x="75" y="65" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">Example 1 ✓</text>
  <text x="75" y="82" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">Example 2 ✓</text>
  <text x="75" y="99" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">Example 3 ✓</text>
  <text x="75" y="116" font-size="12" fill="#e05c1a" font-family="Arial" text-anchor="middle">→ Conjecture</text>
  <rect x="170" y="20" width="130" height="100" rx="10" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="235" y="45" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold" text-anchor="middle">Deductive</text>
  <text x="235" y="65" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">Definitions</text>
  <text x="235" y="82" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">Postulates</text>
  <text x="235" y="99" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">Theorems</text>
  <text x="235" y="116" font-size="12" fill="#e05c1a" font-family="Arial" text-anchor="middle">→ Proof</text>
  <rect x="60" y="170" width="190" height="60" rx="8" fill="#fce4d6" stroke="#e05c1a" stroke-width="2"/>
  <text x="155" y="193" font-size="13" fill="#1a3a5c" font-family="Arial" text-anchor="middle">Counterexample</text>
  <text x="155" y="215" font-size="12" fill="#555" font-family="Arial" text-anchor="middle">One exception kills a conjecture!</text>
  <line x1="75" y1="120" x2="95" y2="170" stroke="#1a3a5c" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="235" y1="120" x2="215" y2="170" stroke="#1a3a5c" stroke-width="1.5" stroke-dasharray="4,3"/>
</svg>

</div>
</div>

---

## Conditional Statements

A **conditional statement** has the form: **If** *hypothesis* **then** *conclusion* ($p \to q$).

<div class="columns">
<div>

| Form | Symbol | Statement |
|------|--------|-----------|
| Conditional | $p \to q$ | If a figure is a square, then it has 4 sides. |
| Converse | $q \to p$ | If it has 4 sides, then it is a square. |
| Inverse | $\lnot p \to \lnot q$ | If not a square, then not 4 sides. |
| Contrapositive | $\lnot q \to \lnot p$ | If not 4 sides, then not a square. |

> The **contrapositive** always has the same truth value as the original conditional.
>
> The **converse** and **inverse** have the same truth value as each other (but may differ from the original).

</div>
<div>

<svg width="300" height="240" viewBox="0 0 300 240" xmlns="http://www.w3.org/2000/svg">
  <rect x="20" y="30" width="110" height="50" rx="8" fill="#deeaf7" stroke="#1a3a5c" stroke-width="2"/>
  <text x="75" y="52" font-size="13" fill="#1a3a5c" font-family="Arial" text-anchor="middle" font-weight="bold">p</text>
  <text x="75" y="70" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">Hypothesis</text>
  <rect x="170" y="30" width="110" height="50" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="2"/>
  <text x="225" y="52" font-size="13" fill="#1a3a5c" font-family="Arial" text-anchor="middle" font-weight="bold">q</text>
  <text x="225" y="70" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">Conclusion</text>
  <line x1="130" y1="55" x2="170" y2="55" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="170,55 160,50 160,60" fill="#1a3a5c"/>
  <text x="143" y="48" font-size="12" fill="#1a3a5c" font-family="Arial">p→q</text>
  <rect x="20" y="155" width="110" height="50" rx="8" fill="#fce4d6" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="75" y="177" font-size="13" fill="#1a3a5c" font-family="Arial" text-anchor="middle" font-weight="bold">¬p</text>
  <text x="75" y="195" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">not p</text>
  <rect x="170" y="155" width="110" height="50" rx="8" fill="#fce4d6" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="225" y="177" font-size="13" fill="#1a3a5c" font-family="Arial" text-anchor="middle" font-weight="bold">¬q</text>
  <text x="225" y="195" font-size="12" fill="#333" font-family="Arial" text-anchor="middle">not q</text>
  <line x1="75" y1="80" x2="75" y2="155" stroke="#aaa" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="225" y1="80" x2="225" y2="155" stroke="#aaa" stroke-width="1.5" stroke-dasharray="5,3"/>
  <line x1="170" y1="180" x2="130" y2="180" stroke="#e05c1a" stroke-width="2"/>
  <polygon points="130,180 140,175 140,185" fill="#e05c1a"/>
  <text x="135" y="173" font-size="11" fill="#e05c1a" font-family="Arial">¬q→¬p</text>
  <text x="55" y="130" font-size="11" fill="#555" font-family="Arial">negate</text>
  <text x="198" y="130" font-size="11" fill="#555" font-family="Arial">negate</text>
</svg>

</div>
</div>

---

## Biconditional Statements

A **biconditional** ($p \leftrightarrow q$) means "$p$ if and only if $q$" (often written **iff**).

> It is true when $p \to q$ AND $q \to p$ are both true.

<div class="columns">
<div>

**Example:**
- $p$: A figure is a square.
- $q$: A figure is an equilateral rectangle.

$p \leftrightarrow q$: "A figure is a square **if and only if** it is an equilateral rectangle." ✓ (both directions hold)

**Non-example:**
- $p$: An animal is a dog.
- $q$: An animal has four legs.

$p \to q$ ✓ (all dogs have 4 legs), but $q \to p$ ✗ (cats have 4 legs too). **Not biconditional.**

</div>
<div>

<svg width="300" height="220" viewBox="0 0 300 220" xmlns="http://www.w3.org/2000/svg">
  <circle cx="100" cy="110" r="75" fill="#deeaf7" fill-opacity="0.7" stroke="#1a3a5c" stroke-width="2"/>
  <circle cx="200" cy="110" r="75" fill="#fff3e0" fill-opacity="0.7" stroke="#e05c1a" stroke-width="2"/>
  <text x="60" y="105" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold" text-anchor="middle">p only</text>
  <text x="150" y="95" font-size="13" fill="#555" font-family="Arial" text-anchor="middle">p ↔ q</text>
  <text x="150" y="114" font-size="12" fill="#555" font-family="Arial" text-anchor="middle">both true</text>
  <text x="240" y="105" font-size="14" fill="#e05c1a" font-family="Arial" font-weight="bold" text-anchor="middle">q only</text>
  <text x="150" y="185" font-size="12" fill="#555" font-family="Arial" text-anchor="middle">Overlap = biconditional region</text>
</svg>

</div>
</div>

---

## Laws of Deductive Reasoning

<div class="columns">
<div>

**Law of Detachment**

If $p \to q$ is true, and $p$ is true, then $q$ must be true.

$$\frac{p \to q \quad p}{\therefore\; q}$$

> **Example:** "If it rains, the field is wet." It is raining. ∴ The field is wet.

**Law of Syllogism**

If $p \to q$ and $q \to r$ are both true, then $p \to r$ is true.

$$\frac{p \to q \quad q \to r}{\therefore\; p \to r}$$

> **Example:** "If it rains → field is wet; wet field → game cancelled."
> ∴ "If it rains → game cancelled."

</div>
<div>

<svg width="290" height="250" viewBox="0 0 290 250" xmlns="http://www.w3.org/2000/svg">
  <!-- Detachment -->
  <rect x="10" y="10" width="270" height="95" rx="8" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="145" y="32" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold" text-anchor="middle">Law of Detachment</text>
  <rect x="25" y="42" width="90" height="36" rx="5" fill="#fff" stroke="#1a3a5c" stroke-width="1"/>
  <text x="70" y="56" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle">p → q</text>
  <text x="70" y="72" font-size="11" fill="#888" font-family="Arial" text-anchor="middle">rule</text>
  <rect x="130" y="42" width="70" height="36" rx="5" fill="#fff" stroke="#e05c1a" stroke-width="1"/>
  <text x="165" y="56" font-size="12" fill="#e05c1a" font-family="Arial" text-anchor="middle">p</text>
  <text x="165" y="72" font-size="11" fill="#888" font-family="Arial" text-anchor="middle">fact</text>
  <polygon points="210,60 230,60 220,78" fill="#1a3a5c"/>
  <text x="240" y="67" font-size="14" fill="#1a3a5c" font-family="Arial" font-weight="bold">q</text>
  <!-- Syllogism -->
  <rect x="10" y="150" width="270" height="90" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="145" y="172" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold" text-anchor="middle">Law of Syllogism</text>
  <rect x="20" y="182" width="70" height="36" rx="5" fill="#fff" stroke="#1a3a5c" stroke-width="1"/>
  <text x="55" y="205" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle">p → q</text>
  <rect x="105" y="182" width="70" height="36" rx="5" fill="#fff" stroke="#1a3a5c" stroke-width="1"/>
  <text x="140" y="205" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle">q → r</text>
  <polygon points="185,200 205,200 195,218" fill="#e05c1a"/>
  <text x="212" y="210" font-size="12" fill="#e05c1a" font-family="Arial" font-weight="bold">p → r</text>
</svg>

</div>
</div>

---

## Properties Used in Proofs

These algebraic properties are the **justifications** used in two-column proofs.

| Property | Meaning | Example |
|----------|---------|---------|
| **Reflexive** | $a = a$ | $AB = AB$ |
| **Symmetric** | $a=b \Rightarrow b=a$ | If $\angle A = \angle B$, then $\angle B = \angle A$ |
| **Transitive** | $a=b,\;b=c \Rightarrow a=c$ | If $AB=CD$ and $CD=EF$, then $AB=EF$ |
| **Substitution** | If $a=b$, replace $a$ with $b$ | $x=3$, so $2x=6$ |
| **Addition** | $a=b \Rightarrow a+c = b+c$ | Add equal lengths |
| **Subtraction** | $a=b \Rightarrow a-c = b-c$ | Subtract equal lengths |
| **Multiplication** | $a=b \Rightarrow ac = bc$ | — |
| **Division** | $a=b,\;c\neq 0 \Rightarrow a/c = b/c$ | Divide both sides |

---

## Two-Column Proof Structure

A **two-column proof** has numbered **Statements** on the left and **Reasons** on the right.

<div class="columns">
<div>

**Given:** $m\angle 1 + m\angle 2 = 90°$, $m\angle 2 = 30°$

**Prove:** $m\angle 1 = 60°$

| # | Statement | Reason |
|---|-----------|--------|
| 1 | $m\angle 1 + m\angle 2 = 90°$ | Given |
| 2 | $m\angle 2 = 30°$ | Given |
| 3 | $m\angle 1 + 30° = 90°$ | Substitution (1,2) |
| 4 | $m\angle 1 = 60°$ | Subtraction Prop. |

</div>
<div>

<svg width="300" height="220" viewBox="0 0 300 220" xmlns="http://www.w3.org/2000/svg">
  <rect x="10" y="10" width="280" height="200" rx="10" fill="#f9f9f9" stroke="#1a3a5c" stroke-width="1.5"/>
  <rect x="10" y="10" width="280" height="36" rx="10" fill="#1a3a5c"/>
  <text x="150" y="34" font-size="14" fill="#fff" font-family="Arial" font-weight="bold" text-anchor="middle">Two-Column Proof Format</text>
  <line x1="10" y1="46" x2="290" y2="46" stroke="#1a3a5c" stroke-width="1"/>
  <line x1="145" y1="46" x2="145" y2="210" stroke="#1a3a5c" stroke-width="1"/>
  <text x="78" y="66" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold" text-anchor="middle">Statements</text>
  <text x="218" y="66" font-size="13" fill="#1a3a5c" font-family="Arial" font-weight="bold" text-anchor="middle">Reasons</text>
  <text x="20" y="88" font-size="12" fill="#333" font-family="Arial">1. p → q is true</text>
  <text x="155" y="88" font-size="12" fill="#333" font-family="Arial">Given</text>
  <text x="20" y="110" font-size="12" fill="#333" font-family="Arial">2. p is true</text>
  <text x="155" y="110" font-size="12" fill="#333" font-family="Arial">Given</text>
  <text x="20" y="132" font-size="12" fill="#333" font-family="Arial">3. Next step</text>
  <text x="155" y="132" font-size="12" fill="#333" font-family="Arial">Property / Thm</text>
  <text x="20" y="154" font-size="12" fill="#333" font-family="Arial">4. ...</text>
  <text x="155" y="154" font-size="12" fill="#333" font-family="Arial">...</text>
  <text x="20" y="186" font-size="12" fill="#e05c1a" font-family="Arial" font-weight="bold">n. Prove this!</text>
  <text x="155" y="186" font-size="12" fill="#e05c1a" font-family="Arial">Conclusion</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 1 — Law of Syllogism

**Given these three statements, write a conclusion:**

1. If a student passes the exam, they earn credit. ($p \to q$)
2. If a student earns credit, they advance to the next course. ($q \to r$)
3. Maria passed the exam. ($p$)

<div class="columns">
<div>

**Step 1:** Apply Law of Syllogism to (1) and (2):
> "If Maria passes → she advances." ($p \to r$)

**Step 2:** Apply Law of Detachment with (3):
> $p$ is true, so $r$ is true.

**Conclusion:** Maria advances to the next course.

</div>
<div>

<svg width="280" height="190" viewBox="0 0 280 190" xmlns="http://www.w3.org/2000/svg">
  <rect x="20" y="20" width="80" height="45" rx="8" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="60" y="37" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle" font-weight="bold">Pass</text>
  <text x="60" y="53" font-size="11" fill="#555" font-family="Arial" text-anchor="middle">p</text>
  <line x1="100" y1="42" x2="130" y2="42" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="130,42 120,37 120,47" fill="#1a3a5c"/>
  <rect x="130" y="20" width="80" height="45" rx="8" fill="#deeaf7" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="170" y="37" font-size="12" fill="#1a3a5c" font-family="Arial" text-anchor="middle" font-weight="bold">Credit</text>
  <text x="170" y="53" font-size="11" fill="#555" font-family="Arial" text-anchor="middle">q</text>
  <line x1="210" y1="42" x2="240" y2="42" stroke="#1a3a5c" stroke-width="2"/>
  <polygon points="240,42 230,37 230,47" fill="#1a3a5c"/>
  <rect x="215" y="20" width="50" height="45" rx="8" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="240" y="37" font-size="12" fill="#e05c1a" font-family="Arial" text-anchor="middle" font-weight="bold">Adv.</text>
  <text x="240" y="53" font-size="11" fill="#555" font-family="Arial" text-anchor="middle">r</text>
  <line x1="60" y1="65" x2="60" y2="100" stroke="#e05c1a" stroke-width="2" stroke-dasharray="4,3"/>
  <circle cx="60" cy="100" r="25" fill="#fce4d6" stroke="#e05c1a" stroke-width="2"/>
  <text x="60" y="96" font-size="12" fill="#e05c1a" font-family="Arial" text-anchor="middle">Maria</text>
  <text x="60" y="112" font-size="11" fill="#555" font-family="Arial" text-anchor="middle">passed!</text>
  <line x1="85" y1="100" x2="215" y2="50" stroke="#e05c1a" stroke-width="2" stroke-dasharray="4,3"/>
  <text x="65" y="155" font-size="12" fill="#1a3a5c" font-family="Arial">∴ Maria advances! (p→r, p true)</text>
</svg>

</div>
</div>

---

<!-- _class: example -->

## Worked Example 2 — Proof with Angle Bisector

**Given:** $\overrightarrow{BD}$ bisects $\angle ABC$, $m\angle ABC = 84°$. **Prove:** $m\angle ABD = 42°$.

| # | Statement | Reason |
|---|-----------|--------|
| 1 | $\overrightarrow{BD}$ bisects $\angle ABC$ | Given |
| 2 | $m\angle ABD = m\angle DBC$ | Def. of angle bisector |
| 3 | $m\angle ABD + m\angle DBC = m\angle ABC$ | Angle Addition Postulate |
| 4 | $m\angle ABD + m\angle ABD = 84°$ | Substitution (2 into 3) |
| 5 | $2\cdot m\angle ABD = 84°$ | Simplify |
| 6 | $m\angle ABD = 42°$ | Division Property ∎ |

---

## Chapter 2 — Summary

| Concept | Key Point |
|---------|-----------|
| **Inductive** | Patterns → conjecture; one counterexample destroys it |
| **Conditional** | $p \to q$; contrapositive ($\lnot q \to \lnot p$) always equivalent |
| **Biconditional** | $p \leftrightarrow q$; true only when both $p \to q$ and $q \to p$ hold |
| **Law of Detachment** | $p \to q$ and $p$ true $\Rightarrow q$ true |
| **Law of Syllogism** | $p \to q$ and $q \to r$ $\Rightarrow p \to r$ |
| **Two-Column Proof** | Every statement needs a reason: Given, Definition, Postulate, or Theorem |

> **Key insight:** The contrapositive is logically equivalent to the original conditional — proving one proves the other. This is a powerful proof technique.
