# STATUS — UniSaaS.UniCORE.Forgejo

**Repository state as of 2026-07-09 22:33 UTC.**

---

## Full working fork

This repository is a **full working fork** of upstream `codeberg.org/forgejo/forgejo` (real upstream tree on both `main` and `unicore`), created 2026-07-07 and enrolled in the UniCORE upstream-merge cron fleet on 2026-07-09.

- `main` mirrors upstream at `14cb1dea00` (advances via the periodic upstream-merge cron).
- `unicore` carries UniCORE additions and is the deploy branch.
- Standard layer (README/LICENSE/AI-AUTHORSHIP/UPSTREAM-MERGE-DISCIPLINE/STARTING-POINT/STATUS) added 2026-07-09 22:33 UTC to conform to the fleet standard.

## Enrolled in

- **UniCORE upstream-merge cron fleet** (weekly `git fetch upstream` → merge into `main` → merge `main` into `unicore`, per `CRON-AGENT.md`).
- **UniCORE Sanity Check** Step 9 (Repository + Infrastructure Integrity Audit).
