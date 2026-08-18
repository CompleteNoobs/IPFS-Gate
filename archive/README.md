# archive/ — frozen snapshots of past working-build docs

This directory preserves point-in-time **copies** of build/deploy notes from
working builds, so they are not lost when the live docs (especially the deploy
walkthrough) get rewritten for a new platform. Files here are frozen snapshots —
the canonical, still-maintained versions live in the repo root.

## Snapshots

### `pre-nixos-alpine-build-2026-07-29/`
The last **Alpine/Ubuntu-era working-build** docs for the monolith, captured on
2026-07-29 before the move to a **NixOS** host (owner decision — NixOS becomes the
long-term owner-fleet OS). Preserved because the deploy walkthrough will be
rewritten for NixOS.

Manifest:
- `WalkThrough.wiki` — the Alpine/Ubuntu Docker deploy recipe + Common Problems
- `PICKUP-NOTES-2026-07-06.md` — pause-state snapshot (open >100MB bug, fed fragments)
- `STAGE-0-BASELINE.md` — the v1 build baseline
- `Archive.PRICING-V0.3-DESIGN-NOTES.md` — already-superseded v0.3 pricing (history only)

> Not archived (still canonical, kept live in repo root): `CLAUDE.md`,
> `roadmap_status.md`, `README.md`, and the current design notes
> (`PRICING-V1`, `WHITELIST-MODE`, `BYTE-RANGE`, `IPFS-Gate-Scale-Plan`,
> `ipfs-gate-cohosting-backstop`).
