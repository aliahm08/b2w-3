# Brand assets — three-site design document

**Version:** 2026-10-09 / first review set. **Status:** generated concepts, not approved production assets. This folder does not modify the running websites.

## Section 1 — Design system

Six logical responsive columns on mobile, desktop and ultra-wide screens. Exactly five sections per website, with three disclosure layers per section. Golden-ratio geometry applies to paired information panels; at conflicting breakpoints six-column alignment and accessibility take precedence. Underlines only link text. Bold only headings or selected states. Italic emphasis is rare. Place labels on informative visuals. Reuse image filter treatment within each brand; respect existing approved original logos and live layouts. Motion should show state changes and respect reduced-motion. Tokens and reusable CSS are in `01-design-system/`.

## Section 2 — Prompt database

Every generated asset has one complete individually runnable prompt under `02-prompt-database/prompts/`, a searchable `prompts.json`, and a CSV index with ID, section, information depth, audience, trigger, contextual location, product boundary and asset path. Prompts embed brand guardrails so an isolated regeneration still follows the full design system.

## Section 3 — Actual brand asset library

Editable SVG master graphics live in `03-asset-library/`, grouped by website and placement. The nine shared examples include branded identity-reference graphics and five animated SVG state references. Original brand artwork is stored separately and unmodified. Rasterize SVG at 1200 × 742 for PNG exports. Each graphic is illustrative, not evidence of active integrations or real project records.

### B2W / five sections
1. **Mission** — `B2W-01-01` primary; `B2W-01-02` secondary; `B2W-01-03` tertiary.
2. **Capabilities** — `B2W-02-01` primary; `B2W-02-02` secondary; `B2W-02-03` tertiary.
3. **How we work** — `B2W-03-01` primary; `B2W-03-02` secondary; `B2W-03-03` tertiary.
4. **Work and expertise** — `B2W-04-01` primary; `B2W-04-02` secondary; `B2W-04-03` tertiary.
5. **Contact and trust** — `B2W-05-01` primary; `B2W-05-02` secondary; `B2W-05-03` tertiary.

### JasonAI / five sections
1. **Executive secretary** — `JAI-01-01` primary; `JAI-01-02` secondary; `JAI-01-03` tertiary.
2. **Capture** — `JAI-02-01` primary; `JAI-02-02` secondary; `JAI-02-03` tertiary.
3. **Business memory** — `JAI-03-01` primary; `JAI-03-02` secondary; `JAI-03-03` tertiary.
4. **Operations** — `JAI-04-01` primary; `JAI-04-02` secondary; `JAI-04-03` tertiary.
5. **App MVP introduction** — `JAI-05-01` primary; `JAI-05-02` secondary; `JAI-05-03` tertiary.

### Clara / five sections
1. **On-site voice note** — `CLA-01-01` primary; `CLA-01-02` secondary; `CLA-01-03` tertiary.
2. **Structured note** — `CLA-02-01` primary; `CLA-02-02` secondary; `CLA-02-03` tertiary.
3. **Preliminary estimate** — `CLA-03-01` primary; `CLA-03-02` secondary; `CLA-03-03` tertiary.
4. **Planning and verification** — `CLA-04-01` primary; `CLA-04-02` secondary; `CLA-04-03` tertiary.
5. **App MVP introduction** — `CLA-05-01` primary; `CLA-05-02` secondary; `CLA-05-03` tertiary.

## Publication guardrails

1. Use a six-column logical responsive grid on mobile, desktop and ultra-wide screens; change spans, not information hierarchy.
2. Each of the three sites has five sections; each section has three layers: main information, expanded detail, deepest inspection.
3. Use golden-ratio proportions 1:1.61803398875 across paired surface families and information regions when compatible with six-column constraints.
4. Typography size is uniform; bold only headings and active state, underline only actual links, italics only for rare deliberate emphasis.
5. Place explanatory labels inside the graphics. Graphics must communicate information, never be empty decorative AI illustration.
6. Use one brand-specific image filter per site on approved photographic assets; do not restyle existing approved logos, layouts or page templates.
7. Motion explains state, supports engagement but is subtle, respects prefers-reduced-motion and has equivalent readable static content.
8. Keep access, provenance, permissions and human approval explicit; never fabricate client records, real-time integrations, payroll outcomes, estimate accuracy or product availability.
9. Use anonymized illustrative data. No personal or client-identifying details in graphics or demo records.
10. Provide readable SVG with meaningful aria-label; interactivity must be keyboard accessible and visually focused.

## Original source / history

Reference originals and prior design notes exist in `aliahm08/B2W/public/brand/` and the user's B2W Drive design folder. This contribution is a reviewable library, not a replacement for approved live pages. No invented customers, fabricated performance claims, active payments, or validated renovation estimates.

## Explore

Open [`04-explorer/index.html`](04-explorer/index.html) using a simple local HTTP server, or inspect any SVG directly in GitHub. Review each asset ID independently before embedding into product pages. SVGs load without scripts or dependencies.
