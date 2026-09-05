# Regulus Sales OS (v4.0)

Single-file internal sales operating system. No backend. `index.html` is everything.
Companion: `Regulus_Sales_Bible.pdf` (v4, 69 pages).

## Publish on GitHub Pages
Upload `index.html` → Settings → Pages → Deploy from a branch → `main` / root.

## Daily role model (REGULUS OPERATING TARGET — not from the original Sales Bible)
- **IB** Inbound / Reactivation — inbound: all received · 40 SMS · 40 emails · 40 LI connections · 40 LI follow-ups · Residential Qualified Lead → Sale ≥60% · pipeline-based up to 3 sales/day (manager-enabled).
- **OB** Outbound Prospecting — 50 quality calls · 50 emails · 40 SMS · 40 + 40 LinkedIn · OUTPUT: 1 walkthrough · 2 vendor packages successfully sent.
- **MIXED** — inbound: all received · 40 OB calls · 40 SMS · 40 emails · 40 + 40 LinkedIn · 40 new leads. Capacity rule: each inbound call −2.5% on outbound activity, floor 25% (manager-editable).
- **CUSTOM** — manager-defined.
Plan states: DEFAULT / ADJUSTED / CUSTOM. "Edit today's goals" applies to one day only; "Save as new default" (manager) changes the role default on that device.
Sales Bible standards (80/12/5/2/1/1 weekly, inbound and LinkedIn) remain labeled SALES BIBLE STANDARD.

## Stored locally (this device only)
Role, view, daily counters (by date, with role history), today's overrides, custom defaults, capacity rule edits, checklist progress. No customer data. CRM = system of record.

## Content lives in `const D = {...}`: `roleDefs`, `capacityRules`, `metricGroups`, `live` (incl. SMS + residential), `emailTemplates`, `vendorPackage`, `residential`, `diagnostics`, plus all Sales Bible content.
