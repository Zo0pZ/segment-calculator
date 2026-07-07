# Product

## Register

product

## Users

Financial advisers, used client-facing during planning meetings. The adviser is typically sat with (or screen-sharing to) a client while working through investment bond segment numbers and withdrawal scenarios live. The tool needs to hold up under that scrutiny: legible at a glance, calm enough not to distract from the conversation, and credible as a Canada Life-branded instrument in front of a client.

## Product Purpose

A segment calculator for Canada Life investment bond planning: helps advisers work out segment counts, withdrawals, and related figures accurately and quickly. Success looks like an adviser trusting the number without double-checking it elsewhere, and being able to talk a client through the inputs/outputs on screen without the interface getting in the way. Speed/accuracy of the calculation and clarity of presentation matter equally — this is not a back-office-only tool.

## Brand Personality

Precise, trustworthy, calm. Financial-services tone: confidence through clarity, not flourish. Understated rather than "fintech startup" styled.

## Anti-references

- Generic AI-slop SaaS dashboard: gradient hero metrics, cream/sand backgrounds, identical card grids, tiny uppercase tracked eyebrows, side-stripe borders as decoration.
- Legacy/dated Excel-like or Windows-forms calculator look — bare spreadsheet grids, no visual hierarchy.

## Design Principles

- Client-facing credibility: every screen should look presentable if a client is watching over the adviser's shoulder or on a screen-share.
- Calculation clarity over decoration: inputs, results, and the relationship between them must read instantly — no ornamentation that competes with the numbers.
- Preserve brand identity: Canada Life red (`#BA0C2F`) and the existing token system are established; extend them rather than replacing them.
- Accessibility is load-bearing, not a checkbox: this tool has already been through two rounds of WCAG remediation (contrast fixes, 16px minimum text) — new work must not regress those.
- Dense but calm: financial tools legitimately carry a lot of fields and figures; manage that density with layout and hierarchy rather than by shrinking or decorating.

## Accessibility & Inclusion

WCAG 2.2 AA. Confirmed by recent commit history: colour-contrast remediation for AA compliance, and a 16px minimum base font size across the tool. Any new UI must meet or exceed these existing bars — check contrast ratios (body text ≥4.5:1, large text ≥3:1) and keep to the 16px minimum.
