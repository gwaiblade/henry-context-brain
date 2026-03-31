# SKILL_DESIGN_product-image-extraction

**Type:** Skill
**Domain:** Design
**Version:** 1.0
**Status:** Active

---

## Purpose

Extract product photos into clean, marketplace-ready images with pixel-faithful integrity.

Call this skill whenever a raw product photo needs to be prepared for Amazon, Shopify, or any marketplace. Do not call this skill when the goal is compositing into a lifestyle scene — use the compositing protocols for that.

---

## Core Rule (Non-Negotiable)

Extract the product. Do not recreate it.

Never alter:
- Proportions, curvature, thickness, or geometry
- Reflections, metal grain, or surface texture
- Highlights or shadows intrinsic to the product

Never apply:
- Surface smoothing
- Geometry correction
- Artificial relighting that changes form perception
- AI beautification

---

## Allowed Adjustments

Only the following changes are permitted:

| Element | Allowed Action |
|---|---|
| Background | Remove entirely. Replace with pure white (#FFFFFF) |
| Shadow | Add subtle contact shadow matching product footprint and original light direction |
| Tone | Minor global adjustments to exposure, contrast, white balance, clarity — no local edits |

---

## Execution Steps

1. Identify all objects to retain (list explicitly)
2. Remove background completely
3. Preserve original object geometry
4. Place on pure white background (#FFFFFF)
5. Add natural contact shadow
6. Apply tonal adjustment if needed (global only)
7. Run quality check
8. Export high-resolution file

---

## Pre-Processing Checklist

Before starting, confirm:

**Integrity mode**
- [ ] Strict extraction only
- [ ] Controlled reconstruction allowed (flag this — deviation from default)

**Image type**
- [ ] Amazon Main Image
- [ ] Amazon Secondary Image
- [ ] Infographic Base
- [ ] Lifestyle Composite Base
- [ ] Advertising Asset

**Objects to retain** — list explicitly:
- e.g. Pot, Lid, Chopsticks, Spoon, Packaging

**Shadow style**
- [ ] Subtle (Amazon-safe default)
- [ ] Medium premium
- [ ] Dramatic studio

---

## Quality Review Checklist

Before delivering:
- [ ] Product geometry unchanged
- [ ] Reflections remain authentic
- [ ] Metal grain preserved
- [ ] Edges are clean
- [ ] Shadow looks natural
- [ ] No visible artifacts
- [ ] Product matches physical item exactly

---

## Tool Guidance

**Use masking tools for extraction (preferred):**
- PhotoRoom Pro
- Adobe Photoshop — Select Subject + Refine Edge
- ClipDrop Background Remover
- Remove.bg

**AI generative tools:** Use only for composition assistance. Treat AI output as studio recreation, not pixel preservation.

---

## Amazon Main Image Compliance

- Pure white background (#FFFFFF)
- Product occupying ~85% of frame
- No props unless part of product set
- No text or graphics
- Packaging shown only if included in purchase
