# Public dataset policy

- Publish measured data only when its source evidence and checksums were
  inspected; never invent or relabel an experiment.
- Reconstruct public rows without MAC addresses, credentials, absolute times,
  private source/session IDs, site details, or host paths.
- Every dataset needs a local README, data dictionary, SHA-256 checksums, and a
  passing `python3 validate_dataset.py` run.
- Preserve scientific limitations and capture failures in the published
  documentation and summary rows.
- Work on `main`. Dataset edits, commits, tags, releases, and pushes require an
  explicit current user request. Never weaken `.gitignore` or the validator to
  admit a failing file.
