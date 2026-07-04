# MMG Production Starter Pack v2.0 — Single Upload

Repository: `infomindsetmediagroup-cloud/MMG-IOS-PUBLIC`  
Purpose: single-document container for the Phase Three production asset layer.

This document contains the complete production starter pack in one uploadable file.

---

## Included Assets

- Website Homepage Liquid
- Website CSS Framework
- JavaScript Interaction Layer
- Page Title Strip Component
- White SVG Logo
- Cyan SVG Logo
- Black SVG Logo
- Product placeholders
- Publishing placeholders
- README
- Release Notes

---


---

# File: `Brand/SVG/MMG-Logo-Black-512.svg`

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="512" height="128" viewBox="0 0 512 128" role="img" aria-label="Mindset Media Group logo">
  <style>
    .title{font-family:'Murecho','Helvetica Neue',Arial,sans-serif;font-weight:800;font-size:40px;fill:#121212;letter-spacing:-.6px}
    .sub{font-family:'Murecho','Helvetica Neue',Arial,sans-serif;font-weight:700;font-size:12px;fill:#121212;letter-spacing:2px}
    .rule{stroke:#121212;stroke-width:2;stroke-linecap:square}
  </style>
  <text x="256" y="54" class="title" text-anchor="middle">Mindset Media Group<tspan baseline-shift="super" font-size="16">™</tspan></text>
  <line x1="70" y1="84" x2="150" y2="84" class="rule"/>
  <text x="256" y="91" class="sub" text-anchor="middle">KNOWLEDGE ECOSYSTEM</text>
  <line x1="362" y1="84" x2="442" y2="84" class="rule"/>
</svg>

```

---

# File: `Brand/SVG/MMG-Logo-Cyan-512.svg`

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="512" height="128" viewBox="0 0 512 128" role="img" aria-label="Mindset Media Group logo">
  <style>
    .title{font-family:'Murecho','Helvetica Neue',Arial,sans-serif;font-weight:800;font-size:40px;fill:#1CCBF5;letter-spacing:-.6px}
    .sub{font-family:'Murecho','Helvetica Neue',Arial,sans-serif;font-weight:700;font-size:12px;fill:#1CCBF5;letter-spacing:2px}
    .rule{stroke:#1CCBF5;stroke-width:2;stroke-linecap:square}
  </style>
  <text x="256" y="54" class="title" text-anchor="middle">Mindset Media Group<tspan baseline-shift="super" font-size="16">™</tspan></text>
  <line x1="70" y1="84" x2="150" y2="84" class="rule"/>
  <text x="256" y="91" class="sub" text-anchor="middle">KNOWLEDGE ECOSYSTEM</text>
  <line x1="362" y1="84" x2="442" y2="84" class="rule"/>
</svg>

```

---

# File: `Brand/SVG/MMG-Logo-White-512.svg`

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

# File: `Products/ai-prompting-for-beginners/README.md`

```markdown
# Placeholder

Production assets to be imported.

```

---

# File: `Products/creators-bible/README.md`

```markdown
# Placeholder

Production assets to be imported.

```

---

# File: `Products/the-failure-advantage/README.md`

```markdown
# Placeholder

Production assets to be imported.

```

---

# File: `Publishing/ai-mastery/README.md`

```markdown
# Placeholder

Production assets to be imported.

```

---

# File: `Publishing/creators-bible/README.md`

```markdown
# Placeholder

Production assets to be imported.

```

---

# File: `Publishing/micro-packs/README.md`

```markdown
# Placeholder

Production assets to be imported.

```

---

# File: `Publishing/reset-series/README.md`

```markdown
# Placeholder

Production assets to be imported.

```

---

# File: `README.md`

```markdown
# MMG Production Starter Pack v2.0

This package starts Phase Three: production population.

It contains standalone production files, not governance documents.

## Upload Targets

- `Website/Homepage/MMG-HOMEPAGE-v5.1.liquid`
- `Website/CSS/MMG-WEBSITE-v2.0.css`
- `Website/JavaScript/MMG-INTERACTION-v2.0.js`
- `Website/Components/Page-Title-Strip.liquid`
- `Brand/SVG/MMG-Logo-White-512.svg`
- `Brand/SVG/MMG-Logo-Cyan-512.svg`
- `Brand/SVG/MMG-Logo-Black-512.svg`

## Status

Golden Master candidates pending Shopify visual QA.

```

---

# File: `RELEASE-NOTES.md`

```markdown
# Release Notes — MMG Production Starter Pack v2.0

## Summary
Phase Three begins repository production population with standalone files.

## Assets
- Homepage Liquid
- Shared Website CSS
- Interaction JavaScript
- Page Title Strip component
- SVG logo variants

## Status
Candidate assets ready for repository upload and Shopify QA.

```

---

# File: `Website/CSS/MMG-WEBSITE-v2.0.css`

```css
/* MMG-WEBSITE-v2.0.css */

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

#mmg-homepage-v51 .mmg-grid {
  display: grid;
  gap: 8px;
  margin-top: 30px;
}

#mmg-homepage-v51 .mmg-grid-3 { grid-template-columns: repeat(3,minmax(0,1fr)); }

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

#mmg-homepage-v51 .mmg-card p {
  margin: 0;
  color: rgba(18,18,18,.70);
  font-size: 15px;
  line-height: 1.5;
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
  #mmg-homepage-v51 .mmg-grid-3 { grid-template-columns: 1fr; }
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

# File: `Website/Components/Page-Title-Strip.liquid`

```liquid
<section class="mmg-page-title-strip" aria-label="Mindset Media Group title strip">
  <h1>Mindset Media Group™</h1>
  <p>{{ page_subtitle | default: 'KNOWLEDGE ECOSYSTEM' }}</p>
</section>

```

---

# File: `Website/Homepage/MMG-HOMEPAGE-v5.1.liquid`

```liquid
<!--
MMG-HOMEPAGE-v5.1.liquid
Mindset Media Group™ Homepage Golden Master Candidate
Shopify Custom Liquid
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
  </main>
</div>

<link rel="stylesheet" href="{{ 'MMG-WEBSITE-v2.0.css' | asset_url }}">

<script src="{{ 'MMG-INTERACTION-v2.0.js' | asset_url }}" defer></script>

```

---

# File: `Website/JavaScript/MMG-INTERACTION-v2.0.js`

```javascript
// MMG-INTERACTION-v2.0.js

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
