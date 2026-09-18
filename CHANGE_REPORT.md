# Consolidation report — 18 September 2026

Original HEAD: `0ccb3f678faf1e81154757c0737826eff66e4642`.

The successor is [cdond-c3-udapeople](https://github.com/stevegod01/cdond-c3-udapeople). This repository remains a historical variant with its existing source and Git history.

Implemented changes:

- Added a clear successor README and preserved the original README under docs/legacy.
- Preserved the original CircleCI deployment configuration under docs/legacy and replaced active CI with a notice-only workflow, preventing cleanup commits from deploying or changing a database.
- Recorded all 21 changed shared files and two variant-only files, with original blob IDs and immutable source links, in the canonical repository's docs/CONSOLIDATION.md and JSON manifest.
- Created an ignored local backup at .local-backup/pre-consolidation.bundle. git bundle verify reports a complete history with nine refs, including remote feature/dependency branches. The backup is local only and is not intended to be committed.

Checks: bundle verification passed; active YAML parsed; git diff --check passed. Application/infrastructure files were not edited or executed in this historical repository. Archival and remote publishing are handled separately by the main task; this lane made no remote changes.
