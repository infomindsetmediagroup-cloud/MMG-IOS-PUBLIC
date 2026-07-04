# MMG IOS Repository v1.0

**Release:** v1.0.0 — Foundation  
**Date:** 2026-07-04  
**Repository:** `infomindsetmediagroup-cloud/MMG-IOS-PUBLIC`  
**Brand:** Mindset Media Group™  
**Acronym:** MMG  

---

## 1. Release Declaration

This document establishes **MMG IOS Repository v1.0** as the first official repository foundation for the Mindset Media Group™ production operating system.

This version is not a placeholder. It is the governing foundation for how MMG production assets are stored, versioned, validated, released, and promoted.

---

## 2. Repository Purpose

The MMG IOS Repository is the durable source-of-truth system for:

- Website source code
- Shopify Custom Liquid pages
- Reusable components
- CSS and JavaScript
- SVG logos and favicon assets
- Brand files
- Product source files
- Publication source files
- QA checklists
- Release notes
- Manufacturing templates
- Institutional knowledge
- Production standards
- Registry data

The repository exists so future MMG production does **not** depend on chat history, screenshots, memory, or reconstruction.

---

## 3. v1.0 Repository Architecture

```text
MMG-IOS/
│
├── README.md
├── INDEX.md
├── ROADMAP.md
├── CHANGELOG.md
│
├── Governance/
│   ├── MMG-IOS-Constitution.md
│   ├── Repository-Architecture.md
│   ├── Version-Control-Standard.md
│   ├── Production-Workflow.md
│   ├── Release-Management.md
│   └── QA-Standards.md
│
├── Golden-Masters/
│   ├── Website/
│   ├── Shopify/
│   ├── Components/
│   ├── CSS/
│   ├── JavaScript/
│   ├── SVG/
│   ├── Brand/
│   ├── Products/
│   └── Publications/
│
├── Canonical-Source/
│   ├── Website/
│   ├── Shopify/
│   ├── Components/
│   ├── CSS/
│   ├── JavaScript/
│   ├── SVG/
│   ├── Brand/
│   ├── Products/
│   └── Publications/
│
├── Registries/
│   ├── Asset-Registry.md
│   ├── Product-Registry.md
│   ├── Publication-Registry.md
│   ├── Brand-Registry.md
│   ├── Component-Registry.md
│   ├── Template-Registry.md
│   ├── Release-Registry.md
│   └── Knowledge-Registry.md
│
├── Engines/
│   ├── Website-Engine/
│   ├── Publishing-Engine/
│   ├── Product-Engine/
│   ├── Brand-Engine/
│   ├── AI-Engine/
│   └── Knowledge-Engine/
│
├── Manufacturing-Templates/
│   ├── Homepage/
│   ├── Landing-Page/
│   ├── Product-Page/
│   ├── Collection-Page/
│   ├── Article/
│   ├── Publication/
│   └── Release-Package/
│
├── QA/
│   ├── Website-QA.md
│   ├── Shopify-QA.md
│   ├── Publication-QA.md
│   ├── Brand-QA.md
│   └── Release-QA.md
│
├── Releases/
│   ├── Website/
│   ├── Brand/
│   ├── Products/
│   ├── Publications/
│   └── Repository/
│
└── Archive/
```

---

## 4. Golden Master Doctrine

A **Golden Master** is the currently approved, production-authoritative version of an MMG asset.

There must be exactly one active Golden Master per production asset category unless the user explicitly approves multiple channel-specific masters.

Examples:

- Homepage Golden Master
- Header Component Golden Master
- Footer Component Golden Master
- Page Title Strip Golden Master
- CSS Framework Golden Master
- JavaScript Interaction Layer Golden Master
- MMG Logo SVG Golden Master
- Product Page Template Golden Master
- Publication Editorial Template Golden Master

All future production begins from the current Golden Master.

---

## 5. Canonical Source Doctrine

The **Canonical Source** layer stores versioned source artifacts.

Golden Masters represent the active approved version. Canonical Source stores the version history.

Example:

```text
Canonical-Source/Website/Homepage/
├── MMG-HOMEPAGE-v5.0.liquid
├── MMG-HOMEPAGE-v5.1.liquid
├── MMG-HOMEPAGE-v5.2.liquid
└── CHANGELOG.md
```

---

## 6. Version Control Standard

MMG repository releases use semantic versioning:

```text
vMAJOR.MINOR.PATCH
```

### Repository Versions

- `v1.0.0` — Repository foundation
- `v1.1.0` — Website engine
- `v1.2.0` — Publishing engine
- `v1.3.0` — Product engine
- `v1.4.0` — Brand engine
- `v1.5.0` — Knowledge graph
- `v2.0.0` — Full digital asset manufacturing platform

### Asset Versions

Asset filenames use this format:

```text
MMG-[ASSET]-v[VERSION].[EXTENSION]
```

Examples:

```text
MMG-HOMEPAGE-v5.1.liquid
MMG-HEADER-COMPONENT-v1.0.liquid
MMG-PAGE-TITLE-STRIP-v1.0.liquid
MMG-LOGO-WHITE-v1.0.svg
MMG-CSS-WEBSITE-FRAMEWORK-v1.0.css
MMG-JS-INTERACTION-LAYER-v1.0.js
```

---

## 7. Production Workflow

All MMG production follows this sequence:

```text
Golden Master
    ↓
Development Copy
    ↓
Implementation
    ↓
QA Validation
    ↓
Release Candidate
    ↓
User Approval
    ↓
Approved Release
    ↓
Promote to New Golden Master
```

No production asset is promoted without QA validation and approval.

---

## 8. Website Engine v1.0 Baseline

The MMG website engine is governed by the following baseline:

- Native Shopify announcement bar when enabled
- Native Shopify header
- Reusable MMG page-title strip directly below native header
- Page-specific hero immediately below title strip
- Tightened vertical spacing between header, title strip, and hero
- Murecho typography
- Primary text: `#121212`
- Accent cyan: `#1CCBF5`
- Page width: `1200px`
- Grid gap: `8px`
- Buttons: 1px border, 0px radius, no shadow
- Cards: left aligned, 0px radius
- Inputs/media: 0px radius
- Shopify-native SEO fields for title, meta description, canonical, and social previews
- Custom Liquid body code for semantic content, hierarchy, links, alt text, and structured content flow
- Apple-style scroll reveal, hover depth, spotlight, button sheen, subtle parallax, sticky-header refinement, and reduced-motion safety

---

## 9. Homepage Golden Master Import Requirement

The next required production asset is:

```text
Golden-Masters/Website/Homepage/MMG-HOMEPAGE-v5.1.liquid
```

This file must contain the full production-ready Shopify Custom Liquid homepage, including:

- Complete HTML structure
- Scoped CSS
- Scoped JavaScript
- Page-title strip spacing fix
- Header-to-title transition fix
- Title-to-hero transition fix
- Current MMG homepage architecture
- QA notes
- Release notes

Until the current live homepage source is imported, the homepage Golden Master remains pending.

---

## 10. Repository Bootstrap Standard

The repository must be reproducible from a bootstrap package.

The bootstrap package should include:

- Directory structure
- README files
- Governance documents
- Registry templates
- QA templates
- Release templates
- Manufacturing templates
- Placeholder Golden Master directories
- Placeholder Canonical Source directories

The bootstrap is the rebuild mechanism if the repository is ever lost, corrupted, or migrated.

---

## 11. Registry System

### Asset Registry

Tracks every approved asset.

Fields:

```text
Asset ID
Asset Name
Category
Current Golden Master
Latest Version
File Path
Status
Release Date
Notes
```

### Product Registry

Tracks Shopify products and digital assets.

Fields:

```text
Product ID
Product Title
Product Family
Shopify Handle
Price
Cover Filename
Status
Release Package
Notes
```

### Publication Registry

Tracks books, guides, and digital publications.

Fields:

```text
Publication ID
Title
Acronym
Format
Current Manuscript Version
Current Cover Version
KDP Interior PDF
Digital Asset PDF
Release Package
Status
```

### Brand Registry

Tracks visual identity assets.

Fields:

```text
Asset Name
Asset Type
Color Variant
Format
Current Version
Golden Master Path
Usage Notes
```

### Component Registry

Tracks reusable web components.

Fields:

```text
Component Name
Component Type
Current Version
Golden Master Path
Dependencies
QA Status
```

### Release Registry

Tracks every approved release.

Fields:

```text
Release ID
Asset
Version
Release Date
QA Result
Approved By
Promoted to Golden Master
Notes
```

---

## 12. QA Gate

Every production release must pass:

- Structure validation
- Content validation
- Design-system validation
- Mobile validation
- Shopify safety validation
- SEO separation validation
- Accessibility validation
- Link validation
- File naming validation
- Release note validation

A failed QA gate blocks Golden Master promotion.

---

## 13. Release Notes Template

```markdown
# Release Notes

## Asset

## Version

## Release Date

## Summary

## Changed Files

## QA Result

## Promotion Status

## Known Issues

## Next Actions
```

---

## 14. Homepage Manufacturing Template

```liquid
<div id="mmg-homepage-root">
  <section class="mmg-page-title" aria-label="Mindset Media Group page title">
    <h1>Mindset Media Group™</h1>
    <p>KNOWLEDGE ECOSYSTEM</p>
  </section>

  <section class="mmg-hero" aria-label="Homepage hero">
    <div class="mmg-page-width">
      <p class="mmg-kicker">Practical Knowledge for Modern Creators</p>
      <h2>Books. AI. Business. Creator Education.</h2>
      <p>Build skills, systems, and momentum through the Mindset Media Group knowledge ecosystem.</p>
    </div>
  </section>
</div>

<style>
  #mmg-homepage-root,
  #mmg-homepage-root * {
    box-sizing: border-box;
  }

  .shopify-section:has(#mmg-homepage-root),
  .shopify-section:has(#mmg-homepage-root) .page-width {
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  #mmg-homepage-root {
    margin: 0;
    padding: 0;
    font-family: 'Murecho', 'Helvetica Neue', Arial, sans-serif;
    color: #121212;
    background: #ffffff;
  }

  #mmg-homepage-root .mmg-page-title {
    margin: 0;
    padding: 10px 16px;
    text-align: center;
    background: #ffffff;
    border-bottom: 1px solid rgba(18,18,18,.08);
  }

  #mmg-homepage-root .mmg-page-title h1 {
    margin: 0;
    font-size: clamp(28px, 5vw, 64px);
    line-height: .95;
    font-weight: 800;
    letter-spacing: -0.04em;
  }

  #mmg-homepage-root .mmg-page-title p {
    margin: 8px 0 0;
    font-size: clamp(11px, 1.7vw, 20px);
    line-height: 1;
    font-weight: 700;
    letter-spacing: .22em;
    color: #1CCBF5;
  }

  #mmg-homepage-root .mmg-hero {
    margin: 0;
    padding: 0 16px 48px;
    background: #ffffff;
  }

  #mmg-homepage-root .mmg-page-width {
    max-width: 1200px;
    margin: 0 auto;
    padding: 40px 0 0;
  }
</style>
```

---

## 15. Immediate Next Step

The next repository milestone is:

```text
MMG IOS Repository v1.1.0 — Website Engine
```

v1.1.0 should include:

1. Homepage Golden Master
2. Page Title Strip component
3. Header spacing standard
4. Footer standard
5. Website CSS framework
6. Interaction JavaScript framework
7. Shopify Custom Liquid QA checklist
8. Website release notes template

---

## 16. v1.0 Acceptance Criteria

MMG IOS Repository v1.0 is considered implemented when this document is uploaded to the repository and committed as:

```text
MMG-IOS-Repository-v1.0.md
```

Optional companion filename:

```text
README.md
```

This document becomes the first formal repository release artifact.

---

## 17. Changelog

### v1.0.0 — Foundation

- Established MMG IOS Repository as the durable production source of truth.
- Defined Golden Master doctrine.
- Defined Canonical Source doctrine.
- Defined version control standard.
- Defined repository architecture.
- Defined production workflow.
- Defined registry system.
- Defined QA gate.
- Defined homepage import requirement.
- Defined next milestone: Website Engine v1.1.0.
