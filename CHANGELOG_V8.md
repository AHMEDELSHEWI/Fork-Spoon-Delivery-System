# Fork & Spoon Delivery V8 Repair

- Baseline preserved: `main` / V7 unchanged.
- Branch: `v8-repair-2026-11-01`
- Commit: e90fba4c0aff92b1f5bb0045761518a4a420a31d
- Scope: delivery ledger validation and ID collision prevention.
- Changes: integer/non-negative quantity validation; delivered > 0 requirement; delivered quantity must cover sold + returned + damaged; collision-safe IDs; V8 storage key with V7 migration fallback.
- No product, price, commission, VAT, or layout changes.
- No deployment or external sharing performed.
