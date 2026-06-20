# PurePOS — QA Confidence Dashboard

Live, auto-refreshing view of the autonomous QA spine's **per-area confidence** over time.

**Live page:** https://tallmancycles.github.io/purepos-qa-dashboard/

This repo is the *published artifact* only — a static `index.html` plus `confidence-history.json`.
The dashboard source lives in the private `purepos-qa` repo (`qa-system/dashboard/`), and the data is
refreshed from the QA spine's `CONFIDENCE_HISTORY` state **on every spine cycle** by the
`publish-dashboard` workflow. No customer data, PII, or secrets are published — only per-area
confidence percentages, demo build SHAs, and timestamps.
