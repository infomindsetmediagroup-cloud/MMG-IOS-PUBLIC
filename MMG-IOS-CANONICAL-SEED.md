# MMG IOS Repository — Single Document Canonical Seed

Repository target: `infomindsetmediagroup-cloud/MMG-IOS-PUBLIC`

This single document contains the complete starter implementation for the Mindset Media Group™ IOS repository. Upload this one file to GitHub as:

`MMG-IOS-CANONICAL-SEED.md`

---

# 00-CONSTITUTION

## MMG IOS Repository Constitution

### Canonical Source Repository

Every approved production asset must have a versioned canonical source artifact that serves as the single source of truth.

Canonical source artifacts include:

- Homepage files
- Shopify Custom Liquid pages
- Reusable components
- CSS
- JavaScript
- SVG assets
- Brand assets
- Product pages
- Landing pages
- Publication assets
- Release documentation

### Golden Master Repository

Each production asset category has exactly one designated Golden Master source artifact.

All future development follows:

`Golden Master → Development → QA → Release Candidate → Approved Release → New Golden Master`

### Promotion Rule

A file may become a Golden Master only after:

1. Source artifact is complete.
2. Changelog is updated.
3. QA validation passes.
4. Release notes are written.
5. User approval is given.

---

# 01-GOLDEN-MASTERS

## Homepage Golden Master

Current status: Pending live source import.

### Target Baseline

- MMG Homepage v5 architecture
- Native Shopify announcement bar
- Native Shopify header
- Reusable MMG page-title strip
- Page-specific hero immediately below title strip
- Murecho typography
- Primary text: `#121212`
- Accent cyan: `#1CCBF5`
- Tight top/bottom spacing
- Apple-style interaction layer
- Shopify-safe Custom Liquid

### Next Action

Import the current live homepage Custom Liquid source as:

`MMG-HOMEPAGE-v5.0.liquid`

Then apply spacing corrections and promote as:

`MMG-HOMEPAGE-v5.1.liquid`

## Shopify Pages Golden Master

Current status: Pending source import.

## Components Golden Master

Component categories:

- Header
- Footer
- Page Title Strip
- Hero
- CTA
- Product Cards
- Knowledge Cards
- Section Wrappers
- FAQ
- Collection Modules

## CSS Golden Master

Current status: Pending source import.

## JavaScript Golden Master

Current status: Pending source import.

## SVG Golden Master

Current status: Pending import of approved MMG SVG/logo assets.

## Brand Assets Golden Master

Current status: Pending import.

## Product Pages Golden Master

Current status: Pending import.

## Publication Assets Golden Master

Current status: Pending import.

---

# 02-CANONICAL-SOURCE

## Homepage Source

Current status: Pending import.

Canonical naming convention:

- `MMG-HOMEPAGE-v5.0.liquid`
- `MMG-HOMEPAGE-v5.1.liquid`
- `MMG-HOMEPAGE-v5.2.liquid`

## Shopify Page Source

Use:

- `MMG-PAGE-[PAGE-NAME]-v[VERSION].liquid`

## Component Source

Use:

- `MMG-COMPONENT-[COMPONENT-NAME]-v[VERSION].liquid`

## CSS Source

Use:

- `MMG-CSS-[SCOPE]-v[VERSION].css`

## JavaScript Source

Use:

- `MMG-JS-[SCOPE]-v[VERSION].js`

## SVG Source

Use:

- `MMG-SVG-[ASSET-NAME]-v[VERSION].svg`

## Product Source

Use:

- `MMG-PRODUCT-[PRODUCT-SLUG]-v[VERSION].md`
- `MMG-PRODUCT-[PRODUCT-SLUG]-v[VERSION].liquid`

## Publication Source

Use:

- `MMG-PUBLICATION-[TITLE-ACRONYM]-v[VERSION].docx`
- `MMG-PUBLICATION-[TITLE-ACRONYM]-v[VERSION].pdf`
- `MMG-PUBLICATION-[TITLE-ACRONYM]-v[VERSION].md`

---

# 03-RELEASE-REGISTRY

## Release Notes Template

### Asset

Asset name:

### Version

Version:

### Release Date

YYYY-MM-DD

### Summary

What changed:

### Source Files

- Golden Master:
- Canonical Source:
- QA File:

### QA Result

Pass / Fail:

### Promotion Status

Promoted to Golden Master: Yes / No

### Notes

Additional production notes:

---

# 04-QA-REGISTRY

## Homepage QA Checklist

### Shopify Safety

- [ ] Paste-ready Custom Liquid.
- [ ] No duplicate `<title>` or meta description in body.
- [ ] No duplicate canonical tags in body.
- [ ] No unscoped global JavaScript conflicts.
- [ ] CSS scoped to MMG root where possible.

### Header / Title Strip / Hero

- [ ] No excess padding above MMG page-title strip.
- [ ] No excess padding below MMG page-title strip.
- [ ] Hero begins immediately below title strip.
- [ ] Native Shopify header remains intact.
- [ ] No visual double-gap between header and page content.

### Design System

- [ ] Font: Murecho.
- [ ] Primary text: `#121212`.
- [ ] Accent cyan: `#1CCBF5`.
- [ ] Buttons: 1px border, 0px radius, no shadow.
- [ ] Cards: left aligned, 0px radius.
- [ ] Inputs/media: 0px radius.
- [ ] Page width: 1200px.
- [ ] Grid gap: 8px.

### Responsive

- [ ] Mobile header spacing is clean.
- [ ] Title strip remains centered.
- [ ] Hero remains readable on mobile.
- [ ] No horizontal overflow.

### Release

- [ ] Changelog updated.
- [ ] Release notes written.
- [ ] Golden Master promotion recorded.

---

# 05-MANUFACTURING-TEMPLATES

## Homepage Manufacturing Template

```liquid
<!--
MMG Homepage Manufacturing Template
Use this template only as a starting point when no current Golden Master source exists.
-->

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

  #mmg-homepage-root .mmg-kicker {
    margin: 0 0 10px;
    color: #1CCBF5;
    font-weight: 700;
    letter-spacing: .12em;
    text-transform: uppercase;
  }

  #mmg-homepage-root .mmg-hero h2 {
    margin: 0;
    font-size: clamp(38px, 7vw, 86px);
    line-height: .95;
    letter-spacing: -0.06em;
  }

  #mmg-homepage-root .mmg-hero p:not(.mmg-kicker) {
    max-width: 720px;
    margin: 18px 0 0;
    font-size: clamp(16px, 2vw, 22px);
    line-height: 1.45;
  }
</style>
```

---

# 06-VALIDATED-LINK-REGISTRY

## Canonical Domain

Primary canonical base URL:

`https://themindsetmediagroup.com`

## Shopify Product URL Standard

Use short, clean product handles:

- `/products/creators-bible`
- `/products/ai-prompting-for-beginners`
- `/products/the-failure-advantage`

Long autogenerated handles should be avoided whenever possible.

---

# 07-SCHEMA-REGISTRY

## Shopify Page Schema Rules

- Use Shopify native SEO fields for page title, meta description, canonical behavior, and social previews where available.
- Do not duplicate document-level `<title>`, meta description, canonical, Open Graph, or Twitter tags inside Custom Liquid body code.
- Use Custom Liquid for semantic structure, H1/H2 hierarchy, crawlable content, internal links, image alt text, product interlinking, and structured content flow.

## JSON-LD

JSON-LD should only be included when it is intentionally scoped and does not conflict with Shopify/theme structured data output.

---

# 08-ENTITY-REGISTRY

## Canonical Brand Entity

Name:

`Mindset Media Group™`

Acronym:

`MMG`

Primary domain:

`https://themindsetmediagroup.com`

Core ecosystem positioning:

`Books. AI. Business. Creator Education.`

Brand role:

A practical knowledge ecosystem for modern creators, builders, authors, entrepreneurs, and AI-enabled operators.

---

# 09-KNOWLEDGE-GRAPH

## Core Relationships

Mindset Media Group™ connects:

- Books
- AI education
- Business education
- Creator education
- Shopify products
- Digital publications
- Website pages
- Product pages
- Social content
- Publication assets
- Release packages
- Knowledge systems

## Current Primary Website Architecture

1. Native Shopify announcement bar
2. Native Shopify header
3. Reusable MMG page-title strip
4. Page-specific hero
5. Content modules
6. Product / ecosystem sections
7. Founder / story / authority sections
8. Final CTA
9. Footer

---

# 10-DOCUMENTATION

## MMG Production Workflow

1. Start from the current Golden Master.
2. Copy the asset into Canonical Source as a new version.
3. Apply the requested production changes.
4. Run QA against the relevant checklist.
5. Create release notes.
6. Promote the approved release to Golden Master.
7. Preserve all prior versions.

## Repository Use Rule

This single document is the bootstrap seed. Once a desktop workflow or working connector is available, split this document into folder-based repository files matching the section headings.

---

# CHANGELOG

## Repository Initialization

- Created MMG IOS single-document seed.
- Consolidated Golden Master Repository doctrine.
- Consolidated Canonical Source Repository doctrine.
- Added Release Registry.
- Added QA Registry.
- Added Manufacturing Templates.
- Added Validated Link Registry.
- Added Schema Registry.
- Added Entity Registry.
- Added Knowledge Graph.
- Added production workflow documentation.

---

# MANIFEST

```json
{
  "repository": "MMG-IOS-PUBLIC",
  "owner": "infomindsetmediagroup-cloud",
  "status": "single-document bootstrap seed",
  "primary_layers": [
    "Constitution",
    "Golden Master Repository",
    "Canonical Source Repository",
    "Release Registry",
    "QA Registry",
    "Manufacturing Templates",
    "Validated Link Registry",
    "Schema Registry",
    "Entity Registry",
    "Knowledge Graph",
    "Documentation"
  ],
  "next_required_action": "Import the current live homepage Custom Liquid source as the initial Homepage Golden Master."
}
```
