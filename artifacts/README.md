# Build artifacts

Business Chinese APKs and command-line binaries belong here.

The implementation currently comes from
https://github.com/place-of-honor/learn-toki-pona rather than a duplicated
source tree in this repository.

Suggested paths for checked-in deliverables are:

- `artifacts/apk/` for Android packages;
- `artifacts/bin/<target>/` for command-line binaries.

Every deliverable must have a row in `manifest.tsv` naming the exact learner
source commit and SHA-256. A successful build is not by itself runtime or
physical-device acceptance.
