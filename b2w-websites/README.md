# B2W three-site starter (revision 01)

Open `b2w/index.html`, `jasonai/index.html`, or `clara/index.html` in a browser, or serve the parent folder through any static host. All three share `shared/style.css` and `shared/site.js` so global template and typography changes apply everywhere. Paths are relative and can be hosted as `/b2w/`, `/jasonai/`, `/clara/` on one domain, or split into three deployments while retaining assets and updating cross-site URLs.

## Included
- B2W: mission, capabilities, approach, products, founders/team roles, and contact form UI.
- JasonAI: message → project memory → action experience; functional browser-local payroll amounts, totals, adding a sample payment, activity approval/rejection; roadmap clearly marked planned.
- Clara: five-step clickable concept walk-through, estimate verification gates, scope/visual exploration, presentation stage; roadmap presented as a concept.
- Common responsive full-screen menu, editorial one-size 16px typography, scroll entry animations, reduced-motion preference, visual stamp/revision patterns, and brand color tokens.

## Before public launch (required)
1. Set an actual contact inbox in `shared/config.js`, or replace the mailto form with a validated server-side form endpoint. The form currently shows a transparent configuration error rather than claiming to submit.
2. Confirm founder names/roles and capability descriptions with the team. No customer logos, testimonials, fabricated results, or unverified integrations are included.
3. Supply genuine photos, diagrams, and approved logos/brand assets if required. The current package uses CSS illustrations; it does not pretend those are actual project imagery.
4. Verify domain names, links, legal company info, privacy policy, accessibility, and deployment settings. A commercial website handling personal data will need a real privacy policy and secure message-consent practices.
5. The JasonAI dashboard is only an interactive front-end sample; no account, WhatsApp, SMS, payments, database, or message API is connected. Clara is a concept UI, not a production AI service.

## Design rules
All display typography is 16px including section headings. Hierarchy comes from weight, color, spacing, layout, and animation. B2W uses orange, black, off-white; JasonAI uses green; Clara uses mauve, dark purple, and subtle blue-purple accents. Shared documents use `◈ BRAND · STATUS / REV N` labels, but these are visual status indicators, not cryptographic signatures or verification of facts.
