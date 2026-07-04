# MMG Production Assets v1.1.0

Repository: `infomindsetmediagroup-cloud/MMG-IOS-PUBLIC`  
Milestone: `v1.1.0 — Website Engine`  
Status: Golden Master Candidate  
Date: 2026-07-04

This document is a single-upload container for the first real MMG production assets.

---

# RELEASE NOTES

# Release Notes — MMG Production Assets v1.1.0

## Release
MMG IOS Repository v1.1.0 — Website Engine Production Asset Start

## Date
2026-07-04

## Summary
This release transitions the MMG IOS repository from governance documentation to real production source assets.

## Files Included
- `MMG-HOMEPAGE-v5.1.liquid`
- `MMG-WEBSITE-v1.1.0.css`
- `MMG-INTERACTION-v1.1.0.js`
- `Page-Title-Strip.liquid`
- `Header-Notes.md`
- `Footer-Notes.md`
- `MMG-Logo-White-512.svg`
- `QA-v1.1.0.md`

## Status
Golden Master Candidate.

## Next Step
Visually test `MMG-HOMEPAGE-v5.1.liquid` inside Shopify. After approval, promote it to the Homepage Golden Master.


---

# QA

# QA — MMG Production Assets v1.1.0

## Homepage
- [x] Shopify-safe Custom Liquid structure.
- [x] Header spacing fix included.
- [x] Page-title-to-hero spacing fix included.
- [x] Murecho font declared.
- [x] Primary text `#121212`.
- [x] Accent cyan `#1CCBF5`.
- [x] Scoped JavaScript.
- [x] Reduced-motion support.

## Pending
- [ ] Shopify theme editor visual QA.
- [ ] Product links verified live.
- [ ] Mobile Safari visual QA.
- [ ] Final user approval.
- [ ] Golden Master promotion.


---

# WEBSITE / HOMEPAGE / MMG-HOMEPAGE-v5.1.liquid

```liquid
<!--
File: Website/Homepage/MMG-HOMEPAGE-v5.1.liquid
Mindset Media Group™ Homepage Golden Master Candidate
Version: 5.1
Use: Shopify Custom Liquid
-->

<div id="mmg-homepage-v51">
  <section class="mmg-page-title-strip" aria-label="Mindset Media Group title strip">
    <h1>Mindset Media Group™</h1>
    <p>KNOWLEDGE ECOSYSTEM</p>
  </section>

  <main class="mmg-main">
    <section class="mmg-hero mmg-reveal">
      <div class="mmg-page">
        <p class="mmg-kicker">Practical Knowledge for Modern Creators</p>
        <h2>Books. AI. Business. Creator Education.</h2>
        <p class="mmg-lede">A practical knowledge ecosystem for creators, builders, entrepreneurs, and AI-enabled operators.</p>
        <div class="mmg-actions">
          <a class="mmg-btn mmg-btn-primary" href="/collections/all">Explore Products</a>
          <a class="mmg-btn mmg-btn-secondary" href="/pages/about">Founder Story</a>
        </div>
      </div>
    </section>

    <section class="mmg-section mmg-reveal">
      <div class="mmg-page">
        <p class="mmg-section-label">01 Featured Products</p>
        <div class="mmg-grid mmg-grid-3">
          <a class="mmg-card" href="/products/creators-bible">
            <span>Creator System</span>
            <h3>The Creator’s Bible™</h3>
            <p>A complete creator operating manual for publishing, selling, and growing online.</p>
          </a>
          <a class="mmg-card" href="/products/ai-prompting-for-beginners">
            <span>AI Mastery Series</span>
            <h3>AI Prompting for Beginners™</h3>
            <p>A practical entry point into prompt structure, AI workflows, and creator productivity.</p>
          </a>
          <a class="mmg-card" href="/products/the-failure-advantage">
            <span>Mindset System</span>
            <h3>The Failure Advantage™</h3>
            <p>A disciplined framework for turning adversity and experience into forward motion.</p>
          </a>
        </div>
      </div>
    </section>

    <section class="mmg-section mmg-section-soft mmg-reveal">
      <div class="mmg-page">
        <p class="mmg-section-label">02 Built for Modern Creators</p>
        <h2>Systems over hype.</h2>
        <div class="mmg-grid mmg-grid-4">
          <div class="mmg-card"><h3>Learn Faster</h3><p>Action-ready knowledge for creators who need clarity.</p></div>
          <div class="mmg-card"><h3>Build Systems</h3><p>Repeatable frameworks for publishing and execution.</p></div>
          <div class="mmg-card"><h3>Use AI Better</h3><p>Prompting, workflow design, and AI-assisted production.</p></div>
          <div class="mmg-card"><h3>Ship Products</h3><p>Digital assets, books, pages, and creator tools.</p></div>
        </div>
      </div>
    </section>

    <section class="mmg-section mmg-reveal">
      <div class="mmg-page">
        <p class="mmg-section-label">03 Product Series</p>
        <div class="mmg-stack">
          <div class="mmg-row"><strong>Creator Education</strong><span>Publishing, monetization, audience building, and systems thinking.</span></div>
          <div class="mmg-row"><strong>AI Mastery</strong><span>Prompting, images, video, automation, and applied AI workflows.</span></div>
          <div class="mmg-row"><strong>Mindset</strong><span>Recovery, discipline, execution, resilience, and transformation.</span></div>
        </div>
      </div>
    </section>

    <section class="mmg-section mmg-section-dark mmg-reveal">
      <div class="mmg-page">
        <p class="mmg-section-label">04 Road to 1M</p>
        <h2>Built in public.</h2>
        <p class="mmg-lede">MMG is being built through daily publishing, creator education, experiments, and disciplined iteration.</p>
        <div class="mmg-actions">
          <a class="mmg-btn mmg-btn-light" href="https://www.tiktok.com/@mike777king" target="_blank" rel="noopener">Follow the Journey</a>
        </div>
      </div>
    </section>
  </main>
</div>

{% comment %}
Paste the contents of Website/CSS/MMG-WEBSITE-v1.1.0.css below this comment if Shopify requires a single Custom Liquid block.
Paste the contents of Website/JavaScript/MMG-INTERACTION-v1.1.0.js below the CSS.
{% endcomment %}

```

---

# WEBSITE / CSS / MMG-WEBSITE-v1.1.0.css

```css
/*
File: Website/CSS/MMG-WEBSITE-v1.1.0.css
MMG Website Framework
*/

.shopify-section:has(#mmg-homepage-v51),
.shopify-section:has(#mmg-homepage-v51) .page-width {
  margin-top: 0 !important;
  padding-top: 0 !important;
  padding-bottom: 0 !important;
}

#mmg-homepage-v51,
#mmg-homepage-v51 * {
  box-sizing: border-box;
}

#mmg-homepage-v51 {
  margin: 0;
  padding: 0;
  background: #ffffff;
  color: #121212;
  font-family: 'Murecho', 'Helvetica Neue', Arial, sans-serif;
  overflow: hidden;
}

#mmg-homepage-v51 .mmg-page-title-strip {
  margin: 0 !important;
  padding: 10px 16px 9px !important;
  text-align: center;
  background: #ffffff;
  border-bottom: 1px solid rgba(18,18,18,.08);
}

#mmg-homepage-v51 .mmg-page-title-strip h1 {
  margin: 0;
  color: #121212;
  font-size: clamp(28px, 5.7vw, 72px);
  line-height: .9;
  font-weight: 800;
  letter-spacing: -0.055em;
}

#mmg-homepage-v51 .mmg-page-title-strip p {
  margin: 8px 0 0;
  color: #1CCBF5;
  font-size: clamp(10px, 1.6vw, 19px);
  line-height: 1;
  font-weight: 800;
  letter-spacing: .24em;
}

#mmg-homepage-v51 .mmg-page {
  width: min(1200px, calc(100vw - 32px));
  margin: 0 auto;
}

#mmg-homepage-v51 .mmg-hero {
  margin: 0;
  padding: 42px 0 72px;
  background: radial-gradient(circle at 85% 10%, rgba(28,203,245,.24), transparent 34%), linear-gradient(180deg,#fff 0%,#f6fbfd 100%);
}

#mmg-homepage-v51 .mmg-section {
  margin: 0;
  padding: 72px 0;
  background: #ffffff;
}

#mmg-homepage-v51 .mmg-section-soft { background: #f7f7f7; }
#mmg-homepage-v51 .mmg-section-dark { background: #121212; color: #ffffff; }
#mmg-homepage-v51 .mmg-section-dark h2,
#mmg-homepage-v51 .mmg-section-dark p { color: #ffffff; }

#mmg-homepage-v51 .mmg-kicker,
#mmg-homepage-v51 .mmg-section-label {
  margin: 0 0 12px;
  color: #1CCBF5;
  font-size: 12px;
  font-weight: 800;
  letter-spacing: .16em;
  text-transform: uppercase;
}

#mmg-homepage-v51 h2 {
  margin: 0;
  font-size: clamp(40px,7vw,96px);
  line-height: .92;
  font-weight: 850;
  letter-spacing: -0.07em;
}

#mmg-homepage-v51 h3 {
  margin: 0 0 10px;
  font-size: clamp(22px,2.6vw,34px);
  line-height: 1;
  font-weight: 800;
  letter-spacing: -0.04em;
}

#mmg-homepage-v51 .mmg-lede {
  max-width: 780px;
  margin: 20px 0 0;
  font-size: clamp(17px,2.2vw,24px);
  line-height: 1.42;
  color: rgba(18,18,18,.72);
}

#mmg-homepage-v51 .mmg-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 28px;
}

#mmg-homepage-v51 .mmg-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 46px;
  padding: 13px 18px;
  border: 1px solid #121212;
  border-radius: 0;
  text-decoration: none;
  font-size: 14px;
  font-weight: 800;
  transition: transform .22s ease, background .22s ease, color .22s ease;
}

#mmg-homepage-v51 .mmg-btn:hover { transform: translateY(-2px); }
#mmg-homepage-v51 .mmg-btn-primary { color: #fff; background: #1CCBF5; border-color: #1CCBF5; }
#mmg-homepage-v51 .mmg-btn-secondary { color: #121212; background: transparent; }
#mmg-homepage-v51 .mmg-btn-light { color: #121212; background: #fff; border-color: #fff; }

#mmg-homepage-v51 .mmg-grid {
  display: grid;
  gap: 8px;
  margin-top: 30px;
}

#mmg-homepage-v51 .mmg-grid-3 { grid-template-columns: repeat(3,minmax(0,1fr)); }
#mmg-homepage-v51 .mmg-grid-4 { grid-template-columns: repeat(4,minmax(0,1fr)); }

#mmg-homepage-v51 .mmg-card {
  display: block;
  min-height: 220px;
  padding: 24px;
  background: #fff;
  border: 1px solid rgba(18,18,18,.10);
  border-radius: 0;
  color: inherit;
  text-decoration: none;
  transition: transform .24s ease, border-color .24s ease;
}

#mmg-homepage-v51 .mmg-card:hover {
  transform: translateY(-4px);
  border-color: #1CCBF5;
}

#mmg-homepage-v51 .mmg-card span {
  display: block;
  margin-bottom: 16px;
  color: #1CCBF5;
  font-size: 11px;
  font-weight: 800;
  letter-spacing: .14em;
  text-transform: uppercase;
}

#mmg-homepage-v51 .mmg-card p,
#mmg-homepage-v51 .mmg-row span {
  margin: 0;
  color: rgba(18,18,18,.70);
  font-size: 15px;
  line-height: 1.5;
}

#mmg-homepage-v51 .mmg-stack {
  display: grid;
  gap: 8px;
  margin-top: 30px;
}

#mmg-homepage-v51 .mmg-row {
  display: grid;
  grid-template-columns: 260px 1fr;
  gap: 24px;
  padding: 22px 0;
  border-top: 1px solid rgba(18,18,18,.12);
}

#mmg-homepage-v51 .mmg-reveal {
  opacity: 0;
  transform: translateY(18px);
  transition: opacity .7s ease, transform .7s ease;
}

#mmg-homepage-v51 .mmg-reveal.is-visible {
  opacity: 1;
  transform: translateY(0);
}

@media (max-width: 900px) {
  #mmg-homepage-v51 .mmg-grid-3,
  #mmg-homepage-v51 .mmg-grid-4,
  #mmg-homepage-v51 .mmg-row {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  #mmg-homepage-v51 .mmg-page-title-strip { padding: 8px 12px !important; }
  #mmg-homepage-v51 .mmg-page-title-strip h1 { font-size: clamp(31px,10vw,44px); }
  #mmg-homepage-v51 .mmg-page-title-strip p { font-size: 10px; letter-spacing: .18em; }
  #mmg-homepage-v51 .mmg-hero { padding: 32px 0 56px; }
  #mmg-homepage-v51 .mmg-section { padding: 56px 0; }
  #mmg-homepage-v51 .mmg-actions { display: grid; }
  #mmg-homepage-v51 .mmg-btn { width: 100%; }
}

@media (prefers-reduced-motion: reduce) {
  #mmg-homepage-v51 .mmg-reveal,
  #mmg-homepage-v51 .mmg-btn,
  #mmg-homepage-v51 .mmg-card {
    transition: none;
    transform: none;
  }
  #mmg-homepage-v51 .mmg-reveal { opacity: 1; }
}

```

---

# WEBSITE / JAVASCRIPT / MMG-INTERACTION-v1.1.0.js

```javascript
// File: Website/JavaScript/MMG-INTERACTION-v1.1.0.js
// MMG scoped interaction layer

(() => {
  const root = document.getElementById('mmg-homepage-v51');
  if (!root || root.dataset.mmgInit === 'true') return;
  root.dataset.mmgInit = 'true';

  const revealItems = root.querySelectorAll('.mmg-reveal');

  if (!('IntersectionObserver' in window)) {
    revealItems.forEach((item) => item.classList.add('is-visible'));
    return;
  }

  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry) => {
      if (entry.isIntersecting) {
        entry.target.classList.add('is-visible');
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.12 });

  revealItems.forEach((item) => observer.observe(item));
})();

```

---

# WEBSITE / COMPONENTS / Page-Title-Strip.liquid

```liquid
<!--
File: Website/Components/Page-Title-Strip.liquid
MMG Page Title Strip Component
-->

<section class="mmg-page-title-strip" aria-label="Mindset Media Group title strip">
  <h1>Mindset Media Group™</h1>
  <p>{{ page_subtitle | default: 'KNOWLEDGE ECOSYSTEM' }}</p>
</section>

```

---

# WEBSITE / COMPONENTS / Header-Notes.md

```markdown
<!--
File: Website/Components/Header-Notes.md
Native Shopify Header Rule
-->

# Header Component Standard

The MMG website uses the native Shopify header as the primary header layer.

Do not replace the native Shopify header unless explicitly directed.

Approved layer order:

1. Native Shopify announcement bar
2. Native Shopify header
3. MMG page-title strip
4. Page-specific hero

The page-title strip must sit directly beneath the native header with no excess top padding.

```

---

# WEBSITE / COMPONENTS / Footer-Notes.md

```markdown
<!--
File: Website/Components/Footer-Notes.md
Native Shopify Footer Rule
-->

# Footer Component Standard

The MMG website may use the native Shopify footer unless a custom footer is explicitly required.

Footer rules:

- Preserve Shopify policy links.
- Preserve payment/shop controls where applicable.
- Use MMG brand tone and canonical links.
- Avoid duplicate footer navigation if Shopify already renders it.

```

---

# BRAND / SVG / MMG-Logo-White-512.svg

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="512" height="128" viewBox="0 0 512 128" role="img" aria-label="Mindset Media Group logo">
  <style>
    .title{font-family:'Murecho','Helvetica Neue',Arial,sans-serif;font-weight:800;font-size:40px;fill:#FFFFFF;letter-spacing:-.6px}
    .sub{font-family:'Murecho','Helvetica Neue',Arial,sans-serif;font-weight:700;font-size:12px;fill:#FFFFFF;letter-spacing:2px}
    .rule{stroke:#FFFFFF;stroke-width:2;stroke-linecap:square}
  </style>
  <text x="256" y="54" class="title" text-anchor="middle">Mindset Media Group<tspan baseline-shift="super" font-size="16">™</tspan></text>
  <line x1="70" y1="84" x2="150" y2="84" class="rule"/>
  <text x="256" y="91" class="sub" text-anchor="middle">KNOWLEDGE ECOSYSTEM</text>
  <line x1="362" y1="84" x2="442" y2="84" class="rule"/>
</svg>

```

---

# NEXT STAGE

After this file is uploaded and committed, the repository should begin storing production source files as individual assets, not only combined markdown packages.

Recommended next direct files:

1. `Website/Homepage/MMG-HOMEPAGE-v5.1.liquid`
2. `Website/CSS/MMG-WEBSITE-v1.1.0.css`
3. `Website/JavaScript/MMG-INTERACTION-v1.1.0.js`
4. `Website/Components/Page-Title-Strip.liquid`
5. `Brand/SVG/MMG-Logo-White-512.svg`
