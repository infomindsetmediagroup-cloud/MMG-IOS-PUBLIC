# MMG Website Engine v1.1.0 — Phase 1 Single Upload

This single file contains the Homepage Golden Master Candidate package.

## Recommended repository path

`Website/Homepage/MMG-WEBSITE-ENGINE-v1.1.0-PHASE-1.md`

---

## README

# MMG Website Engine v1.1.0 — Phase 1

This package contains the Homepage Golden Master Candidate.

## Upload to Repository

Recommended GitHub paths:

```text
Website/Homepage/MMG-HOMEPAGE-v5.1.liquid
Website/Homepage/QA.md
Website/Homepage/RELEASE-NOTES.md
```

## Shopify Use

Paste `MMG-HOMEPAGE-v5.1.liquid` into the homepage Custom Liquid section or the appropriate Shopify theme/page location.

## Note

This is a production candidate built from the approved MMG IOS doctrine. Exact parity with the current live homepage requires importing the current live Shopify source.


---

## RELEASE NOTES

# Release Notes — MMG-HOMEPAGE-v5.1

## Asset
MMG Homepage

## Version
v5.1

## Repository Milestone
MMG IOS Repository v1.1.0 — Website Engine

## Release Date
2026-07-04

## Summary
Created the Homepage Golden Master Candidate for the MMG IOS Repository Website Engine phase one.

## Major Changes
- Rebuilt homepage as a complete Shopify Custom Liquid document.
- Implemented tightened native-header-to-page-title spacing.
- Implemented tightened page-title-to-hero transition.
- Preserved MMG v5 architecture.
- Applied Murecho typography.
- Applied website accent cyan `#1CCBF5`.
- Added scoped CSS and scoped JavaScript.
- Added Apple-style reveal interaction layer.
- Added reduced-motion accessibility safety.

## Files
- `MMG-HOMEPAGE-v5.1.liquid`
- `QA.md`
- `RELEASE-NOTES.md`

## Promotion Status
Candidate. Promote to Golden Master after visual QA in Shopify.


---

## QA

# Homepage QA — MMG-HOMEPAGE-v5.1

## Status
Golden Master Candidate.

## Validated
- Shopify-safe Custom Liquid body source.
- No duplicate `<title>`, meta description, canonical, Open Graph, or Twitter tags.
- Murecho typography declared.
- Primary text uses `#121212`.
- Accent uses `#1CCBF5`.
- Header-to-title spacing fix included.
- Title-to-hero spacing tightened.
- Page-title strip centered.
- Section wrapper padding targeted with `:has(#mmg-homepage-v51)`.
- JavaScript scoped to page root.
- Reduced-motion safety included.
- Mobile responsive grid collapse included.

## Pending
- Import current live homepage source if exact parity is required.
- Visual QA inside Shopify theme editor.
- Product image integration if desired.
- Final user approval before Golden Master promotion.


---

## HOMEPAGE SOURCE — MMG-HOMEPAGE-v5.1.liquid

```liquid
<!--
MMG-HOMEPAGE-v5.1.liquid
Mindset Media Group™
Shopify Custom Liquid Homepage Golden Master Candidate
Version: 5.1
Accent: #1CCBF5
Font: Murecho
Purpose: Homepage Golden Master import for MMG IOS Repository v1.1.0 — Website Engine
-->

<div id="mmg-homepage-v51">
  <section class="mmg-title-strip" aria-label="Mindset Media Group title strip">
    <h1>Mindset Media Group™</h1>
    <p>KNOWLEDGE ECOSYSTEM</p>
  </section>

  <main class="mmg-home-main">
    <section class="mmg-hero mmg-reveal" aria-label="Homepage hero">
      <div class="mmg-page">
        <p class="mmg-kicker">Practical Knowledge for Modern Creators</p>
        <h2>Books. AI. Business. Creator Education.</h2>
        <p class="mmg-lede">
          Build skills, systems, and momentum through the Mindset Media Group knowledge ecosystem.
        </p>
        <div class="mmg-actions">
          <a href="/collections/all" class="mmg-btn mmg-btn-primary">Explore Products</a>
          <a href="/pages/about" class="mmg-btn mmg-btn-secondary">Founder Story</a>
        </div>
      </div>
    </section>

    <section class="mmg-section mmg-reveal" aria-label="Featured products">
      <div class="mmg-page">
        <p class="mmg-section-num">01</p>
        <h2>Featured Products</h2>
        <div class="mmg-grid mmg-grid-3">
          <a class="mmg-card" href="/products/creators-bible">
            <span>Creator System</span>
            <h3>The Creator’s Bible™</h3>
            <p>A complete creator operating manual for building, publishing, selling, and growing online.</p>
          </a>
          <a class="mmg-card" href="/products/ai-prompting-for-beginners">
            <span>AI Mastery Series</span>
            <h3>AI Prompting for Beginners™</h3>
            <p>A practical entry point into prompt structure, AI workflows, and creator productivity.</p>
          </a>
          <a class="mmg-card" href="/products/the-failure-advantage">
            <span>Mindset System</span>
            <h3>The Failure Advantage™</h3>
            <p>A disciplined framework for turning adversity, recovery, and experience into forward motion.</p>
          </a>
        </div>
      </div>
    </section>

    <section class="mmg-section mmg-section-soft mmg-reveal" aria-label="Built for modern creators">
      <div class="mmg-page">
        <p class="mmg-section-num">02</p>
        <h2>Built for Modern Creators</h2>
        <div class="mmg-grid mmg-grid-4">
          <div class="mmg-card"><h3>Learn Faster</h3><p>Clear, practical systems for creators who need action-ready knowledge.</p></div>
          <div class="mmg-card"><h3>Build Systems</h3><p>Templates, frameworks, and operating models for repeatable execution.</p></div>
          <div class="mmg-card"><h3>Use AI Better</h3><p>Prompting, workflow design, and AI-assisted publishing for real-world use.</p></div>
          <div class="mmg-card"><h3>Ship Products</h3><p>Digital assets, books, pages, and creator tools built for distribution.</p></div>
        </div>
      </div>
    </section>

    <section class="mmg-section mmg-reveal" aria-label="Product series">
      <div class="mmg-page">
        <p class="mmg-section-num">03</p>
        <h2>Product Series</h2>
        <div class="mmg-stack">
          <div class="mmg-row"><strong>Creator Education</strong><span>Publishing, monetization, audience building, and systems thinking.</span></div>
          <div class="mmg-row"><strong>AI Mastery</strong><span>Prompting, images, video, automation, and applied AI workflows.</span></div>
          <div class="mmg-row"><strong>Mindset</strong><span>Recovery, discipline, execution, resilience, and personal transformation.</span></div>
        </div>
      </div>
    </section>

    <section class="mmg-section mmg-section-dark mmg-reveal" aria-label="Road to one million">
      <div class="mmg-page">
        <p class="mmg-section-num">04</p>
        <h2>Road to 1M Followers</h2>
        <p class="mmg-lede">
          MMG is being built in public through daily publishing, creator education, live experiments, and disciplined iteration.
        </p>
        <div class="mmg-actions">
          <a href="https://www.tiktok.com/@mike777king" class="mmg-btn mmg-btn-light" rel="noopener" target="_blank">Follow the Journey</a>
        </div>
      </div>
    </section>

    <section class="mmg-section mmg-reveal" aria-label="Founder story">
      <div class="mmg-page mmg-two-col">
        <div>
          <p class="mmg-section-num">05</p>
          <h2>Built from the Ground Up</h2>
        </div>
        <div>
          <p class="mmg-lede">
            From professional Honda auto technician to digital creator and publisher, Mindset Media Group is built around practical knowledge,
            disciplined execution, and the belief that creators need systems—not hype.
          </p>
        </div>
      </div>
    </section>

    <section class="mmg-final mmg-reveal" aria-label="Final call to action">
      <div class="mmg-page">
        <h2>Post. Learn. Improve. Build in public.</h2>
        <p>Explore the MMG knowledge ecosystem and build the next version of your creator operation.</p>
        <a href="/collections/all" class="mmg-btn mmg-btn-primary">Enter the Ecosystem</a>
      </div>
    </section>
  </main>
</div>

<style>
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

  #mmg-homepage-v51 .mmg-title-strip {
    margin: 0 !important;
    padding: 10px 16px 9px !important;
    text-align: center;
    background: #ffffff;
    border-top: 0;
    border-bottom: 1px solid rgba(18,18,18,.08);
  }

  #mmg-homepage-v51 .mmg-title-strip h1 {
    margin: 0;
    color: #121212;
    font-size: clamp(28px, 5.7vw, 72px);
    line-height: .9;
    font-weight: 800;
    letter-spacing: -0.055em;
  }

  #mmg-homepage-v51 .mmg-title-strip p {
    margin: 8px 0 0;
    color: #1CCBF5;
    font-size: clamp(10px, 1.6vw, 19px);
    line-height: 1;
    font-weight: 800;
    letter-spacing: .24em;
    text-transform: uppercase;
  }

  #mmg-homepage-v51 .mmg-home-main {
    margin: 0;
    padding: 0;
  }

  #mmg-homepage-v51 .mmg-page {
    width: min(1200px, calc(100vw - 32px));
    margin: 0 auto;
  }

  #mmg-homepage-v51 .mmg-hero {
    margin: 0;
    padding: 42px 0 72px;
    background:
      radial-gradient(circle at 85% 10%, rgba(28,203,245,.24), transparent 34%),
      linear-gradient(180deg, #ffffff 0%, #f6fbfd 100%);
  }

  #mmg-homepage-v51 .mmg-kicker,
  #mmg-homepage-v51 .mmg-section-num {
    margin: 0 0 12px;
    color: #1CCBF5;
    font-size: 12px;
    line-height: 1;
    font-weight: 800;
    letter-spacing: .16em;
    text-transform: uppercase;
  }

  #mmg-homepage-v51 h2 {
    margin: 0;
    color: #121212;
    font-size: clamp(40px, 7vw, 96px);
    line-height: .92;
    font-weight: 850;
    letter-spacing: -0.07em;
  }

  #mmg-homepage-v51 h3 {
    margin: 0 0 10px;
    color: #121212;
    font-size: clamp(22px, 2.6vw, 34px);
    line-height: 1;
    font-weight: 800;
    letter-spacing: -0.04em;
  }

  #mmg-homepage-v51 p {
    color: rgba(18,18,18,.72);
  }

  #mmg-homepage-v51 .mmg-lede {
    max-width: 780px;
    margin: 20px 0 0;
    font-size: clamp(17px, 2.2vw, 24px);
    line-height: 1.42;
    font-weight: 450;
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
    line-height: 1;
    font-weight: 800;
    letter-spacing: .02em;
    transition: transform .22s ease, background .22s ease, color .22s ease, border-color .22s ease;
  }

  #mmg-homepage-v51 .mmg-btn:hover {
    transform: translateY(-2px);
  }

  #mmg-homepage-v51 .mmg-btn-primary {
    color: #ffffff;
    background: #1CCBF5;
    border-color: #1CCBF5;
  }

  #mmg-homepage-v51 .mmg-btn-secondary {
    color: #121212;
    background: transparent;
  }

  #mmg-homepage-v51 .mmg-btn-light {
    color: #121212;
    background: #ffffff;
    border-color: #ffffff;
  }

  #mmg-homepage-v51 .mmg-section {
    margin: 0;
    padding: 72px 0;
    background: #ffffff;
  }

  #mmg-homepage-v51 .mmg-section-soft {
    background: #f7f7f7;
  }

  #mmg-homepage-v51 .mmg-section-dark {
    background: #121212;
    color: #ffffff;
  }

  #mmg-homepage-v51 .mmg-section-dark h2,
  #mmg-homepage-v51 .mmg-section-dark p {
    color: #ffffff;
  }

  #mmg-homepage-v51 .mmg-grid {
    display: grid;
    gap: 8px;
    margin-top: 30px;
  }

  #mmg-homepage-v51 .mmg-grid-3 {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  #mmg-homepage-v51 .mmg-grid-4 {
    grid-template-columns: repeat(4, minmax(0, 1fr));
  }

  #mmg-homepage-v51 .mmg-card {
    position: relative;
    display: block;
    min-height: 240px;
    padding: 24px;
    background: #ffffff;
    border: 1px solid rgba(18,18,18,.10);
    border-radius: 0;
    color: inherit;
    text-decoration: none;
    overflow: hidden;
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

  #mmg-homepage-v51 .mmg-row strong {
    font-size: 18px;
    font-weight: 850;
  }

  #mmg-homepage-v51 .mmg-row span {
    color: rgba(18,18,18,.70);
    font-size: 18px;
    line-height: 1.45;
  }

  #mmg-homepage-v51 .mmg-two-col {
    display: grid;
    grid-template-columns: .8fr 1.2fr;
    gap: 48px;
    align-items: start;
  }

  #mmg-homepage-v51 .mmg-final {
    margin: 0;
    padding: 78px 0 88px;
    text-align: center;
    background: linear-gradient(180deg, #f6fbfd 0%, #ffffff 100%);
  }

  #mmg-homepage-v51 .mmg-final .mmg-page {
    display: grid;
    justify-items: center;
  }

  #mmg-homepage-v51 .mmg-final p {
    max-width: 680px;
    margin: 20px auto 0;
    font-size: 19px;
    line-height: 1.45;
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
    #mmg-homepage-v51 .mmg-two-col {
      grid-template-columns: 1fr;
    }

    #mmg-homepage-v51 .mmg-row {
      grid-template-columns: 1fr;
      gap: 8px;
    }
  }

  @media (max-width: 640px) {
    #mmg-homepage-v51 .mmg-title-strip {
      padding: 8px 12px 8px !important;
    }

    #mmg-homepage-v51 .mmg-title-strip h1 {
      font-size: clamp(31px, 10vw, 44px);
    }

    #mmg-homepage-v51 .mmg-title-strip p {
      font-size: 10px;
      letter-spacing: .18em;
    }

    #mmg-homepage-v51 .mmg-hero {
      padding: 32px 0 56px;
    }

    #mmg-homepage-v51 .mmg-section {
      padding: 56px 0;
    }

    #mmg-homepage-v51 .mmg-actions {
      display: grid;
    }

    #mmg-homepage-v51 .mmg-btn {
      width: 100%;
    }
  }

  @media (prefers-reduced-motion: reduce) {
    #mmg-homepage-v51 .mmg-reveal,
    #mmg-homepage-v51 .mmg-btn,
    #mmg-homepage-v51 .mmg-card {
      transition: none;
      transform: none;
    }

    #mmg-homepage-v51 .mmg-reveal {
      opacity: 1;
    }
  }
</style>

<script>
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
</script>

```
