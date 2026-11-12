# Tasks

*Source of truth for the Fusion Canyon work queue. Rebuilt 2026-11-12 after the 2026-11-04 home wipe. One Active task at a time as a norm.*

## Active

None. Next: work the good first issues and the owner's queue below.

## Blocked

- **Secret scanning can be switched off again.** The repo is still attached to the org's `cs-free` code-security configuration, which turned scanning off on Space Peak. Detaching needs a token with the `admin:org` scope, which needs the owner's sign-in. Scanning and push protection read as enabled on 2026-11-12.
- **Corridor map export.** The 16-site map is at `https://felt.com/map/Fusion-Canyon-corridor-draft-v0-tTmfg7iZTimB8wraqY9A07D`. Felt's MCP is not in the workspace's current plan, so Claude cannot read the layers.
  - **Route without spending:** an editor exports each layer as GeoJSON from the Felt app. It lands in `03_deliverables/maps/`.
  - **Before CC0 applies,** check that no geometry traces OpenStreetMap. ODbL data cannot be relicensed.

## Backlog

1. **Decide the brand.** The name, the tagline "Build with fusion." and the palette are proposals on the concept draft. So is the mark, two canyon walls converging on a point of light.
2. **Map the Felt sites into `02_substance/`.** Once the corridor map export lands, add one source row per site.

## Done

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
