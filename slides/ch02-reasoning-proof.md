---
marp: true
theme: geometry
math: katex
paginate: true
---

<!-- _class: title -->

# Chapter 2
# Reasoning and Proof

### Unit 1 — Lines and Angles
### McGraw Hill Glencoe Geometry Texas, 2015

---

## Key Vocabulary

| Term | Definition |
|------|-----------|
| **Inductive reasoning** | Using patterns/examples to form a conjecture |
| **Conjecture** | A conclusion based on inductive reasoning |
| **Counterexample** | One example that disproves a conjecture |
| **Conditional** | An if-then statement: $p \to q$ |
| **Hypothesis** | The "if" part ($p$) of a conditional |
| **Conclusion** | The "then" part ($q$) of a conditional |
| **Deductive reasoning** | Using accepted facts/laws to reach a conclusion |

---

<!-- _class: theorem -->

## Conditional Statements

A **conditional** has the form: **If $p$, then $q$** ($p \to q$)

| Form | Statement |
|------|-----------|
| **Conditional** | If $p$, then $q$ |
| **Converse** | If $q$, then $p$ |
| **Inverse** | If $\sim p$, then $\sim q$ |
| **Contrapositive** | If $\sim q$, then $\sim p$ |

> A conditional and its **contrapositive** are logically equivalent.  
> The converse and inverse are logically equivalent to each other.

---

<!-- _class: example -->

### Example — Conditional Forms

**Conditional:** If a figure is a square, then it has four sides.

| Form | Statement |
|------|-----------|
| Converse | If a figure has four sides, then it is a square. *(False)* |
| Inverse | If a figure is not a square, then it doesn't have four sides. *(False)* |
| Contrapositive | If a figure doesn't have four sides, then it is not a square. *(True)* |

---

<!-- _class: theorem -->

## Biconditional Statement

> A **biconditional** is true when the conditional AND its converse are both true.

$$p \leftrightarrow q \quad \text{"$p$ if and only if $q$"}$$

**Example:** An angle is a right angle **if and only if** its measure is 90°.

---

<!-- _class: theorem -->

## Law of Detachment

> If $p \to q$ is true and $p$ is true, then $q$ is true.

$$\frac{p \to q \quad p}{\therefore\ q}$$

**Example:**
- If it rains, the ground is wet. *(true)*
- It is raining. *(true)*
- $\therefore$ The ground is wet.

---

<!-- _class: theorem -->

## Law of Syllogism

> If $p \to q$ and $q \to r$ are both true, then $p \to r$ is true.

$$\frac{p \to q \quad q \to r}{\therefore\ p \to r}$$

**Example:**
- If a number ends in 0, it is divisible by 10.
- If a number is divisible by 10, it is divisible by 5.
- $\therefore$ If a number ends in 0, it is divisible by 5.

---

<!-- _class: theorem -->

## Postulate 2-1: Midpoint Uniqueness

> A segment has **exactly one midpoint**.

---

<!-- _class: theorem -->

## Postulate 2-2: Angle Bisector Uniqueness

> An angle has **exactly one bisector**.

---

<!-- _class: theorem -->

## Theorem 2-1: Properties Used in Proofs

**Reflexive Property:** $a = a$ (a quantity equals itself)

**Symmetric Property:** If $a = b$, then $b = a$

**Transitive Property:** If $a = b$ and $b = c$, then $a = c$

**Substitution Property:** If $a = b$, then $a$ may replace $b$ in any equation

---

<!-- _class: theorem -->

## Theorem 2-2: Segment Congruence Properties

> Segment congruence is:
> - **Reflexive:** $\overline{AB} \cong \overline{AB}$
> - **Symmetric:** If $\overline{AB} \cong \overline{CD}$, then $\overline{CD} \cong \overline{AB}$
> - **Transitive:** If $\overline{AB} \cong \overline{CD}$ and $\overline{CD} \cong \overline{EF}$, then $\overline{AB} \cong \overline{EF}$

---

<!-- _class: theorem -->

## Theorem 2-3: Angle Congruence Properties

> Angle congruence is:
> - **Reflexive:** $\angle A \cong \angle A$
> - **Symmetric:** If $\angle A \cong \angle B$, then $\angle B \cong \angle A$
> - **Transitive:** If $\angle A \cong \angle B$ and $\angle B \cong \angle C$, then $\angle A \cong \angle C$

---

<!-- _class: theorem -->

## Theorem 2-4: Supplementary Angle Pairs

> If two angles are supplementary to the **same angle** (or congruent angles), then they are congruent.

$$\text{If } \angle 1 \text{ and } \angle 2 \text{ are supp., and } \angle 1 \text{ and } \angle 3 \text{ are supp., then } \angle 2 \cong \angle 3$$

---

<!-- _class: theorem -->

## Theorem 2-5: Complementary Angle Pairs

> If two angles are complementary to the **same angle** (or congruent angles), then they are congruent.

---

<!-- _class: theorem -->

## Theorem 2-6: Right Angles

> All **right angles** are congruent.

$$\angle A = 90° \text{ and } \angle B = 90° \Rightarrow \angle A \cong \angle B$$

---

<!-- _class: theorem -->

## Theorem 2-7: Perpendicular Lines

> If two lines are perpendicular, they form **four right angles**.

$$\ell \perp m \Rightarrow \text{all four angles} = 90°$$

---

<!-- _class: summary -->

## Chapter 2 — Theorem Summary

| # | Name | Key Idea |
|---|------|---------|
| — | Law of Detachment | $p\to q,\ p \Rightarrow q$ |
| — | Law of Syllogism | $p\to q,\ q\to r \Rightarrow p\to r$ |
| Thm 2-1 | Algebraic Properties | Reflexive, Symmetric, Transitive, Substitution |
| Thm 2-2 | Segment Congruence | Reflexive, symmetric, transitive |
| Thm 2-3 | Angle Congruence | Reflexive, symmetric, transitive |
| Thm 2-4 | Supp. to Same | Two angles supp. to same → congruent |
| Thm 2-5 | Comp. to Same | Two angles comp. to same → congruent |
| Thm 2-6 | Right Angles | All right angles are congruent |
| Thm 2-7 | Perpendicular | $\perp$ lines form 4 right angles |
