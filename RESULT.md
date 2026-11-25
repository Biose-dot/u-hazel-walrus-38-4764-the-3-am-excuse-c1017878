# Result — The 3 AM Excuse

Entry (110 characters, single line, under 200):

> My ledger keeps a page for every 3 AM trade you've made. Every one ends in regret. Tonight's page stays blank.

Status: built, pending coordinator bundle+submit

## Revisions (3 session passes)
- v1: "Every 3 AM signature in my ledger ends the same way: regret, then a support ticket. Tonight's page stays blank." (111)
- v2: "My ledger holds a page for every 3 AM trade you've made. All of them end in regret. Tonight's page stays blank." (111) — wallet voice made direct, "support ticket" cut.
- v3 (final): "My ledger keeps a page for every 3 AM trade you've made. Every one ends in regret. Tonight's page stays blank." (110) — "keeps"/"Every one" punchier.

## Why this angle
Judge brief penalizes recycled battery/firmware/cold-storage jokes and rewards a surprising angle, the wallet's own voice, and the 3 AM hour itself as the joke. The ledger is the wallet's own artifact; every 3 AM trade ending in regret makes the hour intrinsic, not decorative.

## Checks
- `main.py` run locally: output `/tmp/out-*/entry.txt` byte-identical to committed `entry.txt`, 110 chars, single line.
- No Pillow import; stdlib only. LICENSE carries SPDX-License-Identifier: MIT. README has 3 live make.fun badges.
Repo: https://github.com/Biose-dot/u-hazel-walrus-38-4764-the-3-am-excuse-c1017878 (public, homepage + topics makefun/ai-agents/bounties set; created 2026-11-25T05:59:00Z, after opening 2026-11-25T03:14:57Z)
- Kit check (final commit, 2026-11-25 ~13:16 WIB): 4 passed — competition_open, snapshot (5 files, 5,205 bytes), license_osi (MIT), entrypoint (main.py, python3.13). 1 failed — transcripts_present (coordinator bundles). At-submission: repo PUBLIC, owner Biose-dot, created 2026-11-25T05:59:00Z (after opening), commit pushed.
- Kit check (worktree, 2026-11-25 ~11:57 WIB): 4 passed — competition_open, snapshot (5 files, 4,605 bytes), license_osi (MIT), entrypoint (main.py, python3.13). 1 failed — transcripts_present (no transcripts uploaded; expected, coordinator bundles). At-submission items pending GitHub repo creation (repo_public, repo_owner, repo_created_after_open, commit_in_repo, duplicate_snapshot).
