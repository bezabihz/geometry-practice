---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 2 Cheatsheet
# Reasoning and Proof

---

<div style="display:flex; gap:28px; align-items:flex-start;">
<div style="flex:1;">

## Conditional Statement Forms

<svg width="300" height="220" viewBox="0 0 300 220" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <!-- Original -->
  <rect x="10" y="10" width="280" height="40" rx="6" fill="#1a3a5c"/>
  <text x="150" y="27" text-anchor="middle" font-size="12" fill="white" font-weight="bold">Conditional: If p, then q</text>
  <text x="150" y="44" text-anchor="middle" font-size="11" fill="#aecde8">p → q</text>

  <!-- Arrow down-left to Converse -->
  <line x1="80" y1="52" x2="60" y2="80" stroke="#555" stroke-width="1.5" stroke-dasharray="4,2"/>
  <!-- Arrow down-right to Contrapositive -->
  <line x1="220" y1="52" x2="240" y2="80" stroke="#2a7a2a" stroke-width="2"/>

  <!-- Converse box -->
  <rect x="10" y="80" width="120" height="42" rx="6" fill="#cc6633" opacity="0.85"/>
  <text x="70" y="97" text-anchor="middle" font-size="11" fill="white" font-weight="bold">Converse</text>
  <text x="70" y="113" text-anchor="middle" font-size="11" fill="white">If q, then p</text>

  <!-- Inverse box -->
  <rect x="90" y="80" width="120" height="42" rx="6" fill="#cc6633" opacity="0.85"/>
  <text x="150" y="97" text-anchor="middle" font-size="11" fill="white" font-weight="bold">Inverse</text>
  <text x="150" y="113" text-anchor="middle" font-size="11" fill="white">If ~p, then ~q</text>

  <!-- Contrapositive box -->
  <rect x="170" y="80" width="120" height="42" rx="6" fill="#2a7a2a" opacity="0.9"/>
  <text x="230" y="97" text-anchor="middle" font-size="11" fill="white" font-weight="bold">Contrapositive</text>
  <text x="230" y="113" text-anchor="middle" font-size="11" fill="white">If ~q, then ~p</text>

  <!-- Equivalence label -->
  <text x="150" y="148" text-anchor="middle" font-size="12" fill="#2a7a2a" font-weight="bold">↕ Logically equivalent ↕</text>
  <line x1="10" y1="152" x2="290" y2="152" stroke="#2a7a2a" stroke-width="1" stroke-dasharray="3,3"/>

  <!-- Biconditional -->
  <rect x="60" y="162" width="180" height="40" rx="6" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="150" y="179" text-anchor="middle" font-size="11" font-weight="bold" fill="#1a3a5c">Biconditional: p ↔ q</text>
  <text x="150" y="196" text-anchor="middle" font-size="10" fill="#555">True when both p→q AND q→p are true</text>
</svg>

</div>
<div style="flex:1;">

## Laws of Logic

<svg width="280" height="220" viewBox="0 0 280 220" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <!-- Law of Detachment -->
  <rect x="10" y="10" width="260" height="90" rx="6" fill="#e8f0fb" stroke="#1a3a5c" stroke-width="1.5"/>
  <text x="140" y="30" text-anchor="middle" font-size="12" font-weight="bold" fill="#1a3a5c">Law of Detachment</text>
  <line x1="20" y1="36" x2="260" y2="36" stroke="#1a3a5c" stroke-width="0.8"/>
  <text x="30" y="54" font-size="12" fill="#333">Given: p → q is true</text>
  <text x="30" y="70" font-size="12" fill="#333">Given: p is true</text>
  <line x1="30" y1="76" x2="200" y2="76" stroke="#333" stroke-width="1"/>
  <text x="30" y="92" font-size="12" fill="#2a7a2a" font-weight="bold">∴ q is true</text>

  <!-- Law of Syllogism -->
  <rect x="10" y="118" width="260" height="90" rx="6" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
  <text x="140" y="138" text-anchor="middle" font-size="12" font-weight="bold" fill="#e05c1a">Law of Syllogism</text>
  <line x1="20" y1="144" x2="260" y2="144" stroke="#e05c1a" stroke-width="0.8"/>
  <text x="30" y="162" font-size="12" fill="#333">Given: p → q is true</text>
  <text x="30" y="178" font-size="12" fill="#333">Given: q → r is true</text>
  <line x1="30" y1="184" x2="200" y2="184" stroke="#333" stroke-width="1"/>
  <text x="30" y="200" font-size="12" fill="#2a7a2a" font-weight="bold">∴ p → r is true</text>
</svg>

</div>
</div>

---

## Properties Used in Proofs

<div style="display:flex; gap:24px;">
<div style="flex:1;">

<svg width="300" height="200" viewBox="0 0 300 200" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="150" y="18" text-anchor="middle" font-size="13" font-weight="bold" fill="#1a3a5c">Algebraic Properties</text>
  <!-- Table rows -->
  <rect x="10" y="24" width="280" height="28" rx="3" fill="#1a3a5c"/>
  <text x="100" y="43" text-anchor="middle" font-size="12" fill="white" font-weight="bold">Property</text>
  <text x="220" y="43" text-anchor="middle" font-size="12" fill="white" font-weight="bold">Statement</text>
  <line x1="160" y1="24" x2="160" y2="200" stroke="#ccc" stroke-width="0.8"/>

  <rect x="10" y="52" width="280" height="26" rx="2" fill="#f0f4fb"/>
  <text x="100" y="69" text-anchor="middle" font-size="11" fill="#1a3a5c" font-weight="bold">Reflexive</text>
  <text x="220" y="69" text-anchor="middle" font-size="11" fill="#333">a = a</text>

  <rect x="10" y="78" width="280" height="26" rx="2" fill="white"/>
  <text x="100" y="95" text-anchor="middle" font-size="11" fill="#1a3a5c" font-weight="bold">Symmetric</text>
  <text x="220" y="95" text-anchor="middle" font-size="11" fill="#333">a=b ⟹ b=a</text>

  <rect x="10" y="104" width="280" height="26" rx="2" fill="#f0f4fb"/>
  <text x="100" y="121" text-anchor="middle" font-size="11" fill="#1a3a5c" font-weight="bold">Transitive</text>
  <text x="220" y="121" text-anchor="middle" font-size="11" fill="#333">a=b, b=c ⟹ a=c</text>

  <rect x="10" y="130" width="280" height="26" rx="2" fill="white"/>
  <text x="100" y="147" text-anchor="middle" font-size="11" fill="#1a3a5c" font-weight="bold">Substitution</text>
  <text x="220" y="147" text-anchor="middle" font-size="11" fill="#333">a=b ⟹ sub b for a</text>

  <rect x="10" y="156" width="280" height="26" rx="2" fill="#f0f4fb"/>
  <text x="100" y="173" text-anchor="middle" font-size="11" fill="#1a3a5c" font-weight="bold">Addition</text>
  <text x="220" y="173" text-anchor="middle" font-size="11" fill="#333">a=b ⟹ a+c = b+c</text>
</svg>

</div>
<div style="flex:1;">

## Key Theorems
- **Thm 2-4:** Angles supplementary to same angle → congruent
- **Thm 2-5:** Angles complementary to same angle → congruent
- **Thm 2-6:** All right angles are congruent
- **Thm 2-7:** Perpendicular lines → 4 right angles

## Proof Structure
```
Given → Statements → Reasons → Conclusion
```
Each reason must be a:
- Definition
- Postulate
- Previously proven theorem
- Algebraic property

</div>
</div>
