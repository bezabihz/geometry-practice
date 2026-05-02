---
marp: true
theme: geometry
math: katex
paginate: true
html: true
---

<!-- _class: title -->

# Chapter 13 Cheatsheet
# Volume

---

<div style="text-align:center;">

<svg width="680" height="270" viewBox="0 0 680 270" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <text x="340" y="18" text-anchor="middle" font-size="14" font-weight="bold" fill="#1a3a5c">Volume — All Solids</text>

  <!-- RECTANGULAR PRISM -->
  <g transform="translate(10,35)">
    <rect x="0" y="0" width="118" height="220" rx="6" fill="#d0e8ff" stroke="#1565C0" stroke-width="1.5"/>
    <text x="59" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#1565C0">Rect. Prism</text>
    <!-- 3D box -->
    <rect x="14" y="30" width="60" height="50" fill="#e8f4ff" stroke="#1565C0" stroke-width="1.5"/>
    <polygon points="14,30 28,18 88,18 74,30" fill="#c0d8f0" stroke="#1565C0" stroke-width="1.5"/>
    <polygon points="74,30 88,18 88,68 74,80" fill="#b0ccec" stroke="#1565C0" stroke-width="1.5"/>
    <text x="44" y="58" text-anchor="middle" font-size="10" fill="#1565C0">l</text>
    <text x="6" y="58" font-size="10" fill="#1565C0">w</text>
    <text x="84" y="52" font-size="10" fill="#1565C0">h</text>
    <text x="59" y="108" text-anchor="middle" font-size="13" font-weight="bold" fill="#1565C0">V = lwh</text>
    <text x="59" y="126" text-anchor="middle" font-size="11" fill="#1565C0">= Bh</text>
    <text x="59" y="146" text-anchor="middle" font-size="10" fill="#555">B = base area</text>
  </g>

  <!-- CYLINDER -->
  <g transform="translate(140,35)">
    <rect x="0" y="0" width="118" height="220" rx="6" fill="#d0f0d0" stroke="#2a7a2a" stroke-width="1.5"/>
    <text x="59" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#2a7a2a">Cylinder</text>
    <ellipse cx="59" cy="44" rx="38" ry="12" fill="#b0e0b0" stroke="#2a7a2a" stroke-width="1.5"/>
    <rect x="21" y="44" width="76" height="50" fill="#c8ecc8" stroke="#2a7a2a" stroke-width="1.5"/>
    <ellipse cx="59" cy="94" rx="38" ry="12" fill="#a0d8a0" stroke="#2a7a2a" stroke-width="1.5"/>
    <line x1="59" y1="44" x2="97" y2="44" stroke="#555" stroke-width="1.2" stroke-dasharray="3,2"/>
    <text x="62" y="40" font-size="10" fill="#555">r</text>
    <text x="100" y="72" font-size="10" fill="#555">h</text>
    <text x="59" y="118" text-anchor="middle" font-size="13" font-weight="bold" fill="#2a7a2a">V = πr²h</text>
    <text x="59" y="138" text-anchor="middle" font-size="10" fill="#555">(= Bh, B = πr²)</text>
  </g>

  <!-- PYRAMID -->
  <g transform="translate(270,35)">
    <rect x="0" y="0" width="118" height="220" rx="6" fill="#fff3e0" stroke="#e05c1a" stroke-width="1.5"/>
    <text x="59" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#e05c1a">Pyramid</text>
    <polygon points="59,28 14,98 104,98" fill="#ffe0b0" stroke="#e05c1a" stroke-width="1.5"/>
    <polygon points="104,98 59,28 90,60" fill="#ffd090" stroke="#e05c1a" stroke-width="1.5" opacity="0.7"/>
    <line x1="59" y1="28" x2="59" y2="98" stroke="#555" stroke-width="1.2" stroke-dasharray="3,2"/>
    <text x="63" y="67" font-size="10" fill="#555">h</text>
    <text x="59" y="116" text-anchor="middle" font-size="13" font-weight="bold" fill="#e05c1a">V = ⅓Bh</text>
    <text x="59" y="136" text-anchor="middle" font-size="10" fill="#555">= ⅓ × (prism vol)</text>
  </g>

  <!-- CONE -->
  <g transform="translate(400,35)">
    <rect x="0" y="0" width="118" height="220" rx="6" fill="#fdecea" stroke="#cc2200" stroke-width="1.5"/>
    <text x="59" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#cc2200">Cone</text>
    <polygon points="59,28 14,98 104,98" fill="#ffcccc" stroke="#cc2200" stroke-width="1.5"/>
    <ellipse cx="59" cy="98" rx="45" ry="12" fill="#ff9999" stroke="#cc2200" stroke-width="1.5"/>
    <line x1="59" y1="28" x2="59" y2="98" stroke="#555" stroke-width="1.2" stroke-dasharray="3,2"/>
    <text x="63" y="67" font-size="10" fill="#555">h</text>
    <line x1="59" y1="98" x2="104" y2="98" stroke="#555" stroke-width="1.2" stroke-dasharray="3,2"/>
    <text x="80" y="110" font-size="10" fill="#555">r</text>
    <text x="59" y="128" text-anchor="middle" font-size="13" font-weight="bold" fill="#cc2200">V = ⅓πr²h</text>
    <text x="59" y="148" text-anchor="middle" font-size="10" fill="#555">= ⅓ × (cylinder vol)</text>
  </g>

  <!-- SPHERE -->
  <g transform="translate(530,35)">
    <rect x="0" y="0" width="138" height="220" rx="6" fill="#f0e0f8" stroke="#880088" stroke-width="1.5"/>
    <text x="69" y="18" text-anchor="middle" font-size="12" font-weight="bold" fill="#880088">Sphere</text>
    <circle cx="69" cy="72" r="46" fill="#e0c0f0" stroke="#880088" stroke-width="1.5"/>
    <ellipse cx="69" cy="72" rx="46" ry="14" fill="none" stroke="#880088" stroke-width="1" stroke-dasharray="4,2"/>
    <line x1="69" y1="72" x2="115" y2="72" stroke="#555" stroke-width="1.2" stroke-dasharray="3,2"/>
    <text x="91" y="68" font-size="11" fill="#555" font-weight="bold">r</text>
    <text x="69" y="136" text-anchor="middle" font-size="13" font-weight="bold" fill="#880088">V = 4/3 πr³</text>
    <text x="69" y="156" text-anchor="middle" font-size="11" fill="#880088">SA = 4πr²</text>
  </g>
</svg>

</div>

---

<div style="display:flex; gap:24px;">
<div style="flex:1;">

## Volume Quick Reference

| Solid | Formula | Memory |
|-------|---------|--------|
| Prism | $Bh$ | Base × height |
| Cylinder | $\pi r^2 h$ | Prism with circle base |
| Pyramid | $\frac{1}{3}Bh$ | ⅓ of prism |
| Cone | $\frac{1}{3}\pi r^2 h$ | ⅓ of cylinder |
| Sphere | $\frac{4}{3}\pi r^3$ | — |

> **Key pattern:** Pyramid/Cone $= \frac{1}{3} \times$ matching Prism/Cylinder

</div>
<div style="flex:1;">

## Similar Solids

If scale factor $= k$:

<svg width="260" height="140" viewBox="0 0 260 140" xmlns="http://www.w3.org/2000/svg" style="font-family:sans-serif;">
  <!-- Small cube -->
  <rect x="20" y="50" width="40" height="40" fill="#d0e8ff" stroke="#1565C0" stroke-width="2"/>
  <polygon points="20,50 30,40 70,40 60,50" fill="#b0ccec" stroke="#1565C0" stroke-width="2"/>
  <polygon points="60,50 70,40 70,80 60,90" fill="#90b8e0" stroke="#1565C0" stroke-width="2"/>
  <text x="40" y="105" text-anchor="middle" font-size="11" fill="#1565C0">side = 1</text>

  <!-- Arrow -->
  <text x="105" y="75" font-size="22" fill="#1a3a5c">→</text>
  <text x="105" y="90" text-anchor="middle" font-size="10" fill="#555">k=2</text>

  <!-- Large cube -->
  <rect x="140" y="30" width="80" height="80" fill="#d0e8ff" stroke="#1565C0" stroke-width="2"/>
  <polygon points="140,30 160,10 220,10 200,30" fill="#b0ccec" stroke="#1565C0" stroke-width="2"/>
  <polygon points="200,30 220,10 220,90 200,110" fill="#90b8e0" stroke="#1565C0" stroke-width="2"/>
  <text x="180" y="125" text-anchor="middle" font-size="11" fill="#1565C0">side = 2</text>
</svg>

| Measure | Ratio |
|---------|-------|
| Linear (edges) | $k$ |
| Surface area | $k^2$ |
| Volume | $k^3$ |

**Example** $k=2$: SA ratio $=4$, Vol ratio $=8$

</div>
</div>
