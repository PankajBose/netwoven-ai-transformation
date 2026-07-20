# Netwoven Transform with AI – Website HTML Package

This package contains a responsive rewrite of the **Transform with AI** page, centered on Netwoven's **AI Pilot-to-Production** positioning.

## Files

- `index.html` — complete standalone preview with header and footer.
- `wordpress-page-body.html` — page-body markup for the existing Netwoven WordPress template.
- `styles.css` — scoped CSS under `.nw-ai-page`, designed to minimize theme conflicts.
- `script.js` — mobile navigation and smooth in-page scrolling.
- `assets/` — logo, hero visual, framework PDF and three solution briefs.

## Recommended WordPress implementation

1. Back up or clone the current Transform with AI page into staging.
2. Upload the contents of `assets/` to the WordPress Media Library or a dedicated upload folder.
3. Paste `wordpress-page-body.html` into an Elementor HTML widget or use the markup to recreate sections with native Elementor containers.
4. Add `styles.css` to the page custom CSS, Elementor Site Settings, or enqueue it in the child theme.
5. Enqueue `script.js` in the child theme or add it through the site's approved custom-code mechanism.
6. Update all relative asset URLs after Media Library upload.
7. Replace the `mailto:` workshop CTA with the site's preferred form, CRM booking route or marketing automation landing page.
8. Keep the existing global Netwoven header, footer, cookie controls and analytics tags.

## Content/marketing integration points

- Primary CTA: Complimentary 2-hour Pilot-to-Production Workshop.
- Secondary CTA: Download Pilot-to-Production Framework.
- Contact page used in service cards: `https://netwoven.com/company/contact-us/`.
- Add campaign parameters to CTA links before publishing.
- Connect workshop submissions to the GTM campaign and CRM.

## SEO settings

**Page title:** AI Pilot-to-Production Services | Enterprise AI & AgentOps | Netwoven

**Meta description:** Move copilots, RAG applications and agentic AI from pilot to secure, governed enterprise production with Netwoven's productionization framework and Managed AgentOps.

**Suggested slug:** `/services/ai-pilot-to-production/` for a dedicated landing page, or retain `/services/transform-with-ai/` for the umbrella page.

## Important publishing checks

- Verify claims and customer references with marketing/legal before publishing.
- Compress the hero image to WebP/AVIF through the WordPress image pipeline.
- Add descriptive alt text in the CMS.
- Test keyboard navigation, contrast, mobile layout and form tracking.
- Confirm PDF URLs and downloadable asset names.
- Use the site's existing Microsoft partner badges rather than duplicating them in the page body.
