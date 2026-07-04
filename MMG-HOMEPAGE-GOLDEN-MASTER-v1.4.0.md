
# MMG Homepage Golden Master v1.4.0 Package

This single upload contains the Homepage Golden Master milestone package.

---


# MMG Homepage Golden Master v1.4.0

Status: Golden Master Candidate  
Asset Type: Shopify Custom Liquid Homepage  
Repository Milestone: v1.4.0 — Homepage Golden Master

---

## Purpose

This document establishes the MMG homepage as the first primary production asset in the MMG IOS repository.

The homepage is no longer treated as a temporary page build. It is now a versioned, governed, QA-controlled production source asset.

---

## Canonical File

Recommended production file:

`Website/Homepage/MMG-HOMEPAGE-v5.1.liquid`

---

## Homepage Architecture

The homepage must follow this approved structure:

1. Native Shopify announcement bar
2. Native Shopify header
3. MMG Page Title Strip
4. Homepage Hero
5. Featured Products
6. Built for Modern Creators
7. Product Series
8. Road to 1M Followers
9. Founder / Story section
10. Final CTA
11. Native or approved MMG footer

---

## Required Fixes Included

This Golden Master includes the spacing corrections identified during visual QA:

- Remove excess top padding above the MMG title strip.
- Remove excess bottom padding beneath the MMG title strip.
- Ensure the hero begins immediately below the page title strip.
- Preserve the native Shopify header.
- Avoid duplicate header/title spacing.
- Keep mobile spacing tight and intentional.

---

## Design System Binding

This homepage is bound to:

- Font: Murecho
- Primary text: `#121212`
- Accent cyan: `#1CCBF5`
- Background: white / soft white
- Page width: `1200px`
- Grid gap: `8px`
- Buttons: 1px border, 0px radius, no shadow
- Cards: sharp corners, left-aligned, hover depth only
- Motion: scoped reveal system with reduced-motion safety

---

## Golden Master Rules

The homepage cannot be changed casually after approval.

All future homepage updates must follow:

1. Copy current Golden Master.
2. Increment version.
3. Apply changes.
4. Run QA.
5. Create release notes.
6. Promote only after approval.

---

## Shopify Safety

The homepage body code must not include duplicate:

- `<title>`
- meta description
- canonical tag
- Open Graph tags
- Twitter card tags

Shopify native SEO settings remain responsible for document-level SEO.

---

## Homepage QA Gate

Before promotion:

- [ ] Desktop visual QA passed.
- [ ] Mobile visual QA passed.
- [ ] Header/title/hero spacing verified.
- [ ] Product links verified.
- [ ] No horizontal overflow.
- [ ] CTA buttons render correctly.
- [ ] JavaScript is scoped.
- [ ] Reduced-motion support works.
- [ ] No duplicate SEO tags.
- [ ] User approves visual result.

---

## Production Source

The production liquid source is contained in the prior `MMG-Production-Assets-v1.1.0.md` package and should be extracted into:

`Website/Homepage/MMG-HOMEPAGE-v5.1.liquid`

---

## Promotion Status

Current status: Candidate  
Promote to Golden Master after Shopify visual QA.

---

## Next Repository Milestone

`v1.5.0 — Product Engine`

The next stage should establish the canonical structure for MMG Shopify products, product metadata, URL handles, pricing rules, cover image registry requirements, and digital download release packages.


---

# QA


# MMG Homepage Golden Master QA v1.4.0

## Required Checks

### Header / Spacing
- [ ] Native Shopify header remains visible.
- [ ] No excess white gap between header and title strip.
- [ ] No excess white gap between title strip and hero.
- [ ] Page title strip is centered.
- [ ] Mobile spacing remains tight.

### Design System
- [ ] Murecho typography renders correctly.
- [ ] Accent cyan matches `#1CCBF5`.
- [ ] Primary text matches `#121212`.
- [ ] Cards use sharp corners.
- [ ] Buttons use sharp corners and 1px borders.

### Shopify
- [ ] Custom Liquid pastes cleanly.
- [ ] No duplicate document-level SEO tags.
- [ ] Links resolve correctly.
- [ ] No broken scripts.
- [ ] No theme editor rendering errors.

### Responsive
- [ ] iPhone Safari QA.
- [ ] Desktop QA.
- [ ] Tablet QA if available.
- [ ] No horizontal overflow.

## Result

Status: Pending visual QA.


---

# RELEASE NOTES


# Release Notes — MMG Homepage Golden Master v1.4.0

## Asset

MMG Homepage

## Version

v5.1 source under repository milestone v1.4.0.

## Summary

This release declares the homepage as the first primary MMG production asset governed by the repository.

## Includes

- Homepage Golden Master doctrine.
- Architecture definition.
- Spacing correction requirements.
- Shopify safety requirements.
- QA gate.
- Golden Master promotion workflow.

## Status

Candidate. Awaiting Shopify visual QA and user approval before final Golden Master promotion.

