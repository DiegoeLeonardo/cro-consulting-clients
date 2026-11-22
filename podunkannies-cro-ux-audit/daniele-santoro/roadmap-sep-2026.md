# PodunkAnnies CRO UX Delivery Roadmap

**Hypothetical retrospective reconstruction | September 2026 rollout and ongoing review**

Prepared by **Daniele Santoro · DS CRO Consulting · Godoa**.

This roadmap follows the implementation plan in the audit prepared on 25 August 2026. It assumes a 1 September start, with a four-week delivery window through 28 September. Calendar dates and sequencing within each window are illustrative; execution and outcomes are **Not verified**.

## Source and scope

[PodunkAnnies CRO UX Audit](https://diegoeleonardo.github.io/cro-consulting-clients/podunkannies-cro-ux-audit/daniele-santoro/), Implementation, Rollout plan; Findings 1–7; Accessibility corrections; Performance priorities. The source specifies Week 1, Weeks 2–3, Weeks 3–4 and ongoing checks. It does not specify a four-month implementation programme. The audit is a desktop qualitative review; mobile validation is required before release.

## Source aligned delivery plan

| ID | Deliverable | Audit timing | Illustrative start | Illustrative finish | Effort or priority |
|---|---|---|---|---|---|
| PA01 | Repair conversion blockers and policy consistency | Week 1 | 2026-09-01 | 2026-09-07 | P0 |
| PA02 | Bring collection products into the first viewport | Weeks 2–3 | 2026-09-08 | 2026-09-21 | P1 |
| PA03 | Require size selection and add purchase reassurance | Weeks 2–3 | 2026-09-08 | 2026-09-21 | P1 |
| PA04 | Expand filters and populate search shortcuts | Weeks 3–4 | 2026-09-15 | 2026-09-28 | P2 |
| PA05 | Optimize product-grid image loading | Weeks 3–4 | 2026-09-15 | 2026-09-28 | P2 |
| PA06 | Accessibility and funnel monitoring | Ongoing from Week 1 | 2026-09-01 | 2026-10-31 | Ongoing |
| PA07 | After-hours events and policy refinements | Finding 7; timing not specified | 2026-09-08 | 2026-09-28 | P2 |

## Delivery gates

### PA01 Repair conversion blockers and policy consistency

Fix Sale CTA and terms link; clarify disabled checkout; align eligible $75+ shipping language and exclusions; improve cart guidance.

**Acceptance:** Verify destinations, client-approved policies and checkout state. Remove mandatory terms checkbox only if confirmed unnecessary.

### PA02 Bring collection products into the first viewport

Compress collection headers; shorten introduction; surface product count, relevant category chips and first product row.

**Acceptance:** Check desktop and key mobile widths; preserve brand imagery and validate collection-to-product clicks.

### PA03 Require size selection and add purchase reassurance

Neutral Select a size state; explicit choice before ATC; adjacent size guide, delivery/shipping eligibility and return charges.

**Acceptance:** Test all variant/stock combinations and chosen-size confirmation; verify $15 oversize return charge applicability before displaying.

### PA04 Expand filters and populate search shortcuts

Add useful product type, size, color, material and in-stock filters; search shortcuts, synonyms/misspellings and privacy-aware recent searches.

**Acceptance:** Verify filter combinations/reset, empty results, counts and predictive thumbnails.

### PA05 Optimize product-grid image loading

Responsive WebP/AVIF; reserve dimensions; tune lazy loading; preload only critical hero; defer nonessential assets/scripts.

**Acceptance:** Verify image visibility, layout stability and interaction performance on mobile and desktop.

### PA06 Accessibility and funnel monitoring

Homepage H1 and event heading hierarchy; descriptive labels; keyboard focus; dialogs; contrast. Compare funnel metrics to baseline.

**Acceptance:** Track collection-to-product clicks, ATC, checkout starts/completion, search conversion and size-related returns. Monitoring continues beyond this illustrative end date.

### PA07 After-hours events and policy refinements

Rename After Party; primary booking form/email fallback; neutral choices for event type, party size and location; response expectations and complete returns guidance.

**Acceptance:** Additional illustrative scheduling of a documented finding, not a source-mandated delivery window. Confirm operational promises and validate forms without real bookings.

## Rollout and validation

Capture the pre-change baseline before release. Repair broken links and misleading/incorrect states as fixes; evaluate nonessential design changes with usability checks or controlled experiments where traffic permits. Test navigation, filters, product gallery, size selection, sticky purchase controls and checkout at key mobile widths before release. Keep rollback instructions with each release.

| Metric | Decision supported |
|---|---|
| Collection-to-product clicks | Whether products become easier to discover |
| Add-to-cart rate | Whether product decisions become clearer |
| Checkout starts and completion | Whether cart blockers and cost surprises decrease |
| Search conversion | Whether shortcuts, synonyms and results improve discovery |
| Size-related returns | Whether deliberate variant choice improves order accuracy |

Review weekly through rollout and afterward. Annotate traffic mix and seasonality; do not attribute every before/after movement to UX changes. No conversion lift, completed deployment, real booking or actual checkout is claimed.

## GitHub Project fields

Use ID, Title, Client, Audit timing, Start date, Target date, Priority and Evidence status. Label all items Hypothetical; do not mark Done without delivery evidence. PA07 maps to an audit finding but its specific dates are added planning assumptions. Ongoing work has no source-defined finish date; 31 October is only a review checkpoint.
