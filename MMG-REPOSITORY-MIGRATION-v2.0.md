
# MMG Repository Migration & Operationalization Plan v2.0

## Status
Approved migration plan for transitioning the MMG IOS repository from a bootstrap repository into an operational production repository.

---

# Phase A — Freeze the Foundation

The following documents become the repository governance baseline:

- README.md
- INDEX.md
- MMG-IOS-CANONICAL-SEED.md
- MMG-IOS-Repository-v1.0.md
- MMG-IOS-v1.0-COMPLETION-REPORT.md
- MMG-DESIGN-SYSTEM-v1.2.0.md
- MMG-COMPONENT-LIBRARY-v1.3.0.md
- MMG-HOMEPAGE-GOLDEN-MASTER-v1.4.0.md
- MMG-PRODUCT-ENGINE-v1.5.0.md

No additional governance documents should be created unless the operating model changes.

---

# Phase B — Repository Structure

Target layout:

MMG-IOS/
├── Governance/
├── Website/
│   ├── Homepage/
│   ├── Components/
│   ├── CSS/
│   └── JavaScript/
├── Brand/
│   ├── Logos/
│   ├── SVG/
│   └── Favicons/
├── Products/
├── Publishing/
├── QA/
├── Releases/
└── Archive/

---

# Phase C — Production Asset Import Order

1. Homepage Liquid
2. Shared CSS
3. Shared JavaScript
4. Page Title Strip
5. Header component
6. Footer component
7. SVG logo library
8. Favicon assets
9. Product source packages
10. Publication source packages

---

# Operational Rules

- Golden Masters are never edited directly.
- Create a working copy for every change.
- QA before promotion.
- Every production asset has release notes.
- Version numbers increase with each approved revision.

---

# Definition of Operational

The repository is considered operational when new work is committed primarily as production assets rather than governance documentation.

Future commits should consist of:
- Shopify Liquid
- CSS
- JavaScript
- SVG
- Product metadata
- Publications
- Release packages

---

# Next Active Work

Immediate priorities:

- Import homepage source as a standalone `.liquid` file.
- Commit shared CSS.
- Commit shared JavaScript.
- Commit SVG logo assets.
- Begin versioning real Shopify pages.

This document concludes the bootstrap phase and begins operational use of the MMG IOS repository.
