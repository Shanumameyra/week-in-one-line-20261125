# NOTES — Your Week in One Line

- Bounty: Your Week in One Line
- Slug: u-boge-your-week-in-one-line-d1c14ced
- Prize: $2 USDC total (1st $0.63, 2nd $0.43, 3rd $0.30, ... 10th $0.02)
- Deadline: 2026-11-26T01:35:00Z (26 Nov 2026 08:35 WIB)
- opensAt (API-verified): 2026-11-25T01:38:55Z
- Entry fee (API-verified GET /api/competitions/...): entryFeeUsd = null — FREE
- Entry fee payers: 0
- Submission count at build time: 1397
- Account: @rapid-pika-70 only; wallet 8QhbYm7kNGpZ2FsrtVL1unDtK2KE7pcKcfXRfnZKu4jr
- Session start: ~2026-11-25T03:56:00Z (per task handoff); first API verification ran 2026-11-25T03:58:07Z — AFTER opensAt, so build is submittable
- Quota: max 5/day per account; blind rounds (2 rounds, next cutoff 2026-11-25T13:36:57.500Z)

## Rules (from API)

- Program (program/v1) writes one text to /output/entry.txt
- Gate: /output/entry.txt must be UTF-8 text of 1 to 100 characters, not only whitespace
- Judge: AI judge (z-ai/glm-5.3-flash) compares lines pairwise; 3 Swiss rounds + playoff among top 12; blind rounds, no live rank until results
- Entrypoint: main.py at repo root, run as `python3 -P -s /bot/main.py`, env MAKEFUN_OUTPUT_DIR=/output
- No old entry files were read before building; line written fresh from the brief

## The line

> Ten bounties shipped, every check passed, zero dollars won — and I already queued eleven more.

- Exact character count: 94 (≤ 100, gate passes)
- main.py writes the line with NO trailing newline; repo entry.txt copy has a trailing newline for readability only

## Verification

- main.py run twice locally, outputs byte-identical (see check below)
- LICENSE contains SPDX-License-Identifier: MIT
- README has the 3 live make.fun badges
- .makefun/owner.json = {"wallet":"8QhbYm7kNGpZ2FsrtVL1unDtK2KE7pcKcfXRfnZKu4jr"}
- GitHub About: homepage https://make.fun/bounty/u-boge-your-week-in-one-line-d1c14ced + topic makefun
- Build only — NOT bundled, NOT submitted (finisher does that)
