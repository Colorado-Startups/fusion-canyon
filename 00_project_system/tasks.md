# Tasks

*Source of truth for the Fusion Canyon work queue. Rebuilt 2026-11-12 after the 2026-11-04 home wipe. One Active task at a time as a norm.*

## Active

None. Next: work the good first issues and the owner's queue below.

## Blocked

None.

## Backlog

1. **Decide the brand.** The name, the tagline "Build with fusion." and the palette are proposals on the concept draft. So is the mark, two canyon walls converging on a point of light.
2. **Grow the corridor map.** Marvel Fusion has no public US address, so it has no pin yet. More sites come through issue #9.

## Done

- 2026-11-12 · **Corridor map rebuilt in the repo.**
  - The Felt map's data is locked behind Felt's paid plan, so the map now lives in git as `03_deliverables/map/`, published by `pages.yml` at `/map/`.
  - It runs MapLibre 5.24.0 over OpenFreeMap tiles, with Mapterhorn hillshade and 3D terrain.
  - The 14 sites come from primary sources read on 2026-11-12. Coordinates come from the US Census Geocoder, USGS and EIA, so the data stays CC0. The boundary is the convex hull of the 2020 Census places of the four core towns.
  - Found on the way: USGS streamgage 06752000 puts the Poudre Canyon mouth at 5,220 ft, not about 5,400. Advanced Energy's headquarters is Denver; Fort Collins is a research and service site.
- 2026-11-12 · **`cs-free` removed.** Turning secret scanning on detached the repo from the org's `cs-free` configuration; the API reads `removed`.
- 2026-11-12 · **FC-1 · Public and open to contributors.**
  - The repo is public, with Pages on (`https://colorado-startups.github.io/fusion-canyon/`) and Discussions on.
  - A ruleset requires `ci / ci-ok` and DCO, squash only. Fork runs wait for approval.
  - Private vulnerability reporting, secret scanning and push protection are on.
  - CODEOWNERS names the new `@Colorado-Startups/maintainers` team.
  - Five good first issues are open (#5 to #9).
- 2026-11-12 · **FC-1 steps 2 and 3 · Fact gate and Git Crafter setup.**
  - Every figure on the page was rechecked against a source read on 2026-11-12. ATLAS is now $160M, per CSU (May 2026), the ALEPH pulse is 30 fs at 800 nm (LaserNetUS), and Marvel Fusion's headcount is 120+ (the company).
  - The topping-out date moved to May 2026, and the comparison core is now named. Each change has a row in the source record.
  - The Quality, Process, CI and open-repo files come from Git Crafter v4.1.0. Photon Mountain's skills, hooks and extra workflows were not carried over, per the owner's 2026-11-12 call for fewer guardrails.
- 2026-11-12 · **FC-1 step 1, part one · Vision page restored.**
  - The repo had no copy, and the 2026-11-04 rebuild report lists none.
  - The live Artifact (`claude.ai/artifact/4ke4V4EajuRHSWsEnfYQ8V`, version 1790097756-20ca) was read in full and saved byte for byte as `03_deliverables/fusion_canyon_vision.html` (70,791 bytes, per `wc -c`). It has no scripts and no em dashes.
  - `project_context.md` was rebuilt from the page, the source record and the site's region data.
- 2026-11-04 · **Source record restored** (PR 1), from a Claude transcript.
