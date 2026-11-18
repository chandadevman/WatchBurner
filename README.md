# WatchBurner 0.1.2-beta

Latest saved version recovered for this handoff: **0.1.2-beta**. This is a beta/compatibility artifact, not a claim of production readiness.

## Files

- `releases/`: original Android `.apk` package(s), unchanged.
- `source/`: original source, documentation, tests, build configuration, and available dependency files in their native extensions.
- `SHA256SUMS.txt`: checksums for this app folder.

## Installation target

Install the APK on the Android phone. WatchBurner itself does not need a watch-side APK. The watch must support user-authorized wireless debugging.

## Source status

App-specific source is recovered and hash-verified. The shared build toolchain is missing from the truncated original archive. Read SOURCE_RECOVERY.md.

## Verification

REAL: APK ZIP integrity and required Android entries checked; release hashes matched archived source/bundle records. Sources were inspected for credential-file and common token/private-key patterns; no such embedded credentials were identified. Historical test reports retain their historical meaning. No fresh build or physical-device acceptance test was run during this packaging task.

NOT PROVEN: current installation compatibility, hardware behavior, background reliability, and production readiness.

Package identity: `com.tenvyro.faceport`. Preserved version code: `3`.
