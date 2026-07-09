# UniSaaS.UniCORE.Forgejo

**UniCORE fork of upstream `codeberg.org/forgejo/forgejo`.** Part of the UniCORE upstream-merge building-block fleet.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
Fork family created: **2026-07-07 UTC.** Standard layer added: **2026-07-09 22:33 UTC.**

---

## What this repository is

`bryanunitek/UniSaaS.UniCORE.Forgejo` is the **Forgejo** family member.

**Family purpose:** Self-hosted lightweight software forge (Git hosting). The git.unitek-systems.com forge substrate — the UniCORE self-hosted GitHub-failover forge.

## Branch model

- `main` — tracks upstream `codeberg.org/forgejo/forgejo` (receives the periodic upstream-merge; nothing deploys from `main`).
- `unicore` — the deploy branch: `main` + UniCORE additions (Badge/attribution, config, integration). **Deploy ONLY from `unicore`.**

See [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) for the merge sequence and [`STARTING-POINT.md`](STARTING-POINT.md) for the upstream anchor. Upstream's own README is preserved verbatim as [`README.upstream.md`](README.upstream.md).

## Licence

Code additions match upstream's licence; UniCORE documentation additions are CC BY 4.0. See [`LICENSE.md`](LICENSE.md); upstream licence preserved as `LICENSE.upstream` where applicable.
