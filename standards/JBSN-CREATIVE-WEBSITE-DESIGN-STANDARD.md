# JBSN Creative — Website Design & Experience Standard
**Status: LOCKED BASELINE · Version 1.0 · 15 October 2026**

This standard governs all new JBSN Creative websites, landing pages, brand-led digital experiences and prospect demos. It is a working quality gate, not a claim of Awwwards recognition or a guarantee of commercial outcomes.

## 1. North star
Create a distinctive, premium, memorable digital experience that feels intentionally art-directed, is genuinely useful, works beautifully on mobile, and makes the next customer action obvious. The site must look designed for *this business* rather than generated from a reusable template.

Reference ambition: Awwwards / Site of Sites / Dribbble / Eleken-level craft, studied through examples such as Bruno Simon, UNITED24 Rebuild Map, Cohere, Apple, Kismet, FullyRaw, Industrial Jewellery, Ian's Pizza, Knapsack Creative, Grette, TechCrunch and Sophie Westfall. These are sources of inspiration and study—not assets or layouts to copy.

## 2. What we learn from the references
- **Bruno Simon:** a clear creative idea, playful exploration and memorable interaction. Use immersive 3D only when it supports the brand/story, with simple controls, a fallback and performance limits.
- **UNITED24 Rebuild Map:** meaningful data and visual storytelling can make a serious mission understandable. Use honest data, clear context, accessible visualisations and explain what is known.
- **Cohere:** confident positioning, structured product communication, credibility and strong hierarchy for complex offers.
- **Apple:** disciplined typography, purposeful whitespace, high-quality product storytelling, focused page flow and minimal friction.
- **Kismet / FullyRaw / Industrial Jewellery / Ian's Pizza:** treat each brand's category, audience, personality and visual world as a design input; use original art direction and content hierarchy rather than a generic agency aesthetic.
- **Knapsack Creative / Grette / TechCrunch / Sophie Westfall:** study relevant examples for their own strengths—creative identity, editorial hierarchy, information density, portfolio storytelling and clear navigation—without assuming every site should share one visual style.
- **Awwwards / Site of Sites / Dribbble / Eleken:** use for visual research, interaction patterns, UI craft and quality calibration. Inspiration must be translated into an original solution for the client's business.

## 3. Non-negotiable creative principles
1. **One concept per project.** Write a short creative thesis before coding: the audience, the business goal, the emotional tone, the distinctive visual idea and the main conversion action.
2. **Art direction before decoration.** Choose a coherent visual system: typography, colour, composition, imagery, shapes, grids, motion and voice. Each element must support the thesis.
3. **Original, not derivative.** Never clone a reference site, copy its exact layout/graphics/copy, or imply affiliation. Reinterpret principles into an original design suited to the client's identity.
4. **Business-first clarity.** Visitors should quickly understand what the business does, whom it serves, why it is credible, and what to do next.
5. **Conversion is designed, not bolted on.** Every key page needs a clear primary action, relevant secondary actions, low-friction contact/enquiry routes, and useful reassurance near decisions.
6. **Content is part of the design.** Use specific, concise, audience-aware copy. No filler headings, fake statistics, invented testimonials, unverified certifications, fabricated client logos or unsupported guarantees.
7. **Distinctive does not mean noisy.** Avoid generic gradients, floating glass cards, excessive pill badges, repeated three-card grids, giant empty hero sections and decorative animation unless there is a clear reason.
8. **Mobile is a first-class composition.** Do not merely shrink desktop. Recompose the layout, navigation, imagery, text length and CTA hierarchy for touch screens and slower connections.
9. **Respect the brand.** Use official, verified assets where available. If not, create a clearly disclosed concept wordmark or neutral art direction; never present invented logos or illustrative images as official assets.
10. **Trust over spectacle.** No dark patterns, fake urgency, misleading button states, auto-playing sound, fake dashboards, or UI that suggests a real submission/payment when it has not occurred.

## 4. Required design workflow
### A. Research
- Inspect the business's actual website, public profiles, products/services, audience, market, contact paths and competitors.
- Identify one or two concrete experience gaps: no website, weak/outdated site, inconsistent brand, unclear offer, poor mobile journey, weak lead capture, or confusing product discovery.
- Separate verified facts from assumptions. Record what needs owner approval.

### B. Creative direction
Before building, define:
- Audience and primary user need
- Business objective and conversion event
- One-sentence creative concept
- Brand personality and tone
- Typography, colour, spacing and image direction
- Signature interaction (if useful)
- Mobile strategy and performance budget

### C. Build
- Deliver complete, polished pages—not just a hero mockup.
- Make navigation, links, CTAs, contact options, forms and interactions work as advertised.
- Use semantic HTML, clear headings, accessible controls and responsive layouts.
- Use restrained, purposeful motion; honour `prefers-reduced-motion`.
- Keep imagery relevant, properly licensed/approved, optimised and correctly disclosed.
- Ensure every enquiry flow tells the truth about what happens next. A mail/WhatsApp link may prepare a draft; do not imply it was sent or stored.

### D. Quality assurance
Test at minimum:
- Mobile, tablet and desktop layouts
- Navigation, anchor links, buttons, forms and contact routes
- Keyboard access, focus states, contrast and reduced motion
- Image loading, overflow, console/runtime errors and broken links
- Loading speed and layout stability on mobile connections
- SEO title/description, social preview, favicon and semantic structure where relevant
- Accuracy of all facts, claims, contact details, prices and legal/compliance statements

### E. Review and release
A demo is not outreach-ready until it is deployed and its exact public URL is verified. Check the live URL, inspect the page, test key interactions, and confirm the correct business and concept appear. Do not describe a page as live before this check.

## 5. Motion and interaction rules
- Every animation must communicate hierarchy, feedback, continuity, discovery or brand character.
- Prefer smooth, short transitions and purposeful scroll reveals over animation on every element.
- Advanced canvas, WebGL, 3D, maps and scroll-driven storytelling are optional—not defaults. Use them only when they materially improve the experience.
- Provide an accessible, lightweight fallback for high-compute effects; do not block content behind a heavy animation or forced interaction.
- No sound without explicit user action. Provide pause/disable controls for ongoing motion.
- Interaction must work with touch, keyboard and reduced-motion settings wherever applicable.

## 6. Performance, accessibility and engineering
- Mobile usability and fast content visibility outrank visual effects.
- Optimise images (responsive sizes, modern formats when practical, lazy-load below the fold), limit third-party scripts and avoid unnecessary dependencies.
- Use semantic HTML, meaningful alt text, labels, visible focus, sufficient contrast, logical heading order and keyboard-operable controls.
- Avoid horizontal overflow, layout shifts, oversized video backgrounds and heavy assets without fallback.
- Validate links and critical flows after every deployment.
- Treat WCAG 2.2 AA as the target for accessibility checks where feasible; do not claim compliance without testing.

## 7. Prospect-demo rules
- Every demo is tailored to a real prospect and a specific opportunity.
- Label it clearly as an independent private concept, not the business's official website.
- Do not imply client approval, endorsement, partnership or ownership of the concept.
- Link to official channels when useful and verified. Mark proposed services, imagery, identity and copy for approval when uncertain.
- Avoid fake forms that pretend to submit. If a form is only a visual prototype, say so; if it prepares a WhatsApp/email draft, make that behaviour clear.
- **DEMO FIRST is mandatory:** research → build tailored demo → test → deploy → verify exact URL → prepare personalised outreach → founder manually reviews and sends.
- No outreach message may link to an unbuilt, broken or unverified demo. No automatic outreach sending.

## 8. Design review scorecard
Score each from 1–10. A new demo should score at least **8/10 in every category** before outreach; any critical trust, functionality, accessibility or mobile failure blocks release regardless of score.

| Category | Review question |
|---|---|
| Originality | Does this feel specifically conceived for this brand rather than templated? |
| Art direction | Are typography, colour, imagery, spacing and composition coherent and memorable? |
| First impression | Is the business/offer clear quickly, with a compelling visual hierarchy? |
| UX and navigation | Can users orient themselves and complete key tasks without confusion? |
| Conversion | Is the next step clear, relevant, trustworthy and low-friction? |
| Content accuracy | Are all claims grounded, useful and well written? |
| Responsive craft | Does the experience feel intentionally designed on phone, tablet and desktop? |
| Motion and interaction | Are effects purposeful, smooth, accessible and reliable? |
| Accessibility | Are keyboard, focus, contrast, labels, reduced motion and semantics addressed? |
| Performance and resilience | Does the site load quickly, avoid layout issues and degrade gracefully? |
| Brand fit | Does the experience express the business's own identity and audience? |
| Production readiness | Are links, CTAs, metadata, contact paths and live deployment verified? |

## 9. Release blockers
Do not send the demo to a prospect if any of the following is true:
- Broken/placeholder navigation, dead CTA or incorrect contact route
- Wrong business, inaccurate claim, invented proof, unapproved testimonial or misleading price
- Broken or unverified public URL
- Mobile overflow, unreadable text or unusable touch controls
- Fake submission/payment success or misleading interaction
- Unclear disclosure that the site is a private concept
- Missing approval caveat for uncertain services, identity or imagery

## 10. Final standard
**Premium art direction. Original concept. Clear storytelling. Useful interaction. Fast and accessible execution. Honest claims. Working conversion paths. Verified before outreach.**

The target is to build work worthy of comparison with exceptional global digital experiences while remaining original, appropriate to each client, and commercially effective. Awards and conversion rates are aspirations, not guaranteed outcomes.
