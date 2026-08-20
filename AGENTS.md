# Multi-study public-repository policy

This repository is the privacy-first public-data surface for approved Wi-Fi
sensing studies, including MSB and UGRR. It may contain only public-safe
documentation, scripts, schemas, and manifest-approved sanitized bundles.
Scientific research development belongs outside this repository.

## Evidence and privacy

- Never infer research execution from this publication surface or fabricate
  measurements, results, participants, deployments, or empirical claims.
- Use neutral hardware wording only: “research sensing equipment” and
  “networked research equipment.” Do not publish model numbers, serials,
  hardware addresses, network identifiers, configuration snapshots, or device
  paths.
- Do not infer or publish real site, building, room, floor-plan, schedule,
  participant, access-control, natural-occupancy, network, or device details.
  Natural occupancy is never person or occupancy ground truth.
- Public material must use abstract identifiers such as `site-S01`, `level-Lxx`,
  and `zone-Zxx`. No exact address, room name, floorplan, or timetable belongs
  here.

## Publication controls

- Work directly on `main` for local changes; do not create feature branches or
  worktrees unless the user explicitly authorizes an exception.
- A public dataset is publishable only after documented privacy review,
  sanitization, manifest allowlisting, checksums, metadata, and a successful
  publication gate.
- Every future public dataset edit, commit, tag, release, or push requires
  explicit current user authorization. Preparation and validation alone do not
  authorize publication or remote mutation.
- Preserve unrelated changes. Do not weaken the validator or `.gitignore` to
  accommodate data; remove the data from this public surface instead.
