# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary: hiring managers, recruiters, and builders evaluating Angel J. for technical product / builder-track roles (new-grad and early-career). They arrive with little time — typically a phone or laptop between meetings — and need to judge craft, product sense, and taste in under a minute.

Secondary: peers and collaborators who want a designed view of selected work, not a repo dump.

## Product Purpose

A personal portfolio site that presents selected projects as **designed product artifacts** — closer to a Figma case-study / gallery presentation than a GitHub README list. Success means a visitor understands who Angel is, what was built, and why the work feels considered — then clicks through to a live demo or deeper breakdown.

The Computational Sound labs hub at the site root is an archive of coursework; it is not the primary hiring surface. `/home` is the portfolio.

## Positioning

GitHub shows that code exists. This site shows that **product and design judgment** exist: projects are framed with goals, architecture, timelines, and success metrics, and presented in a design-heavy, Figma-style layout that signals craft before the first line of code is read.

Neighboring “portfolio templates” and bare repo links cannot truthfully claim this combination of product narrative + design-led presentation of Angel’s own shipped work.

## Operating Context

- Hosted on GitHub Pages (`angelj-apps.github.io`).
- Static HTML/CSS (no app framework required for the portfolio shell).
- Selected work currently: Little Tools (GenUI hw1), Nodal, Garden Groovebox — each with a breakdown page under `/home/projects/`.
- Live embeds / demos where available (e.g. Groovebox on Pages; Little Tools at genaihelloworld.vercel.app).
- Visitors may also open GitHub for proof; the site must not invent metrics, testimonials, or employers.

## Capabilities and Constraints

- Surfaces: `/home` (portfolio), `/` (Computational Sound labs archive), `/home/projects/*` (project breakdowns).
- Project wheel / gallery on `/home` for browsing selected work; click-through to goal, architecture, production length, success metrics.
- Must not fabricate customers, logos, press, or success numbers; timelines and metrics stay honest or marked as course/self criteria.
- Stack for the site shell: static HTML/CSS on GitHub Pages (incumbent). Individual projects may use Next.js, Web Audio, extensions, etc. — those are evidence, not the portfolio’s runtime.
- Open: exact Figma-style interaction patterns (frames, boards, zoom) are a presentation goal to refine in design work — not yet a locked UX spec.

## Brand Commitments

- Name: **Angel J.** (full legal name may be added later; do not invent).
- Voice: classy, artsy, considered — product-minded without corporate fluff.
- Presentation mandate (user-binding): projects must be shown **design-heavy**, in a **Figma-style** manner — framed as designed work, not as a plain list of links.
- Computational Sound labs remain a separate archive; they should not overpower the portfolio’s hiring story.
- No fake social proof.

## Evidence on Hand

- Live portfolio draft: `home/index.html` and `home/projects/*/index.html`.
- Live demos / deploys: Garden Groovebox (`https://angelj-apps.github.io/CompSoundFinal/`), Little Tools (`https://genaihelloworld.vercel.app/`), Little Tools admin (`https://little-tools-admin.vercel.app/`).
- Repos: `angelj-apps/gen_ai_hello_world`, `angelj-apps/little-tools-admin`, `angelj-apps/nodal`, `angelj-apps/CompSoundFinal`, labs under `angelj-apps/*`.
- Do **not** fabricate screenshots of unshipped UIs, user quotes, or company case studies.

## Product Principles

1. **Design is part of the proof** — how the portfolio looks is evidence of judgment, not decoration on top of code.
2. **Projects as products** — every featured work gets goal, architecture, time, and success criteria.
3. **Honesty over polish theater** — never invent metrics, logos, or testimonials.
4. **Portfolio over archive** — `/home` leads; labs support context without becoming the headline.
5. **Taste with substance** — artsy and classy, still scannable for a hiring manager in sixty seconds.

## Accessibility & Inclusion

No product-specific legal standard was set. Default expectation: readable type, keyboard-reachable navigation, and contrast that holds on the portfolio’s light atelier surfaces. Tighten if a role or program requires WCAG AA explicitly.
