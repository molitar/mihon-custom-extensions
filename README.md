# Mihon Custom Extensions

Independent custom extensions maintained by molitar.

## Purpose

Maintain alternative Mihon extensions alongside upstream sources.

When an upstream or custom extension breaks, library entries can be
migrated temporarily to a working alternative while repairs are tested.

## Development policy

- Custom Android package names and distinct Mihon source identities.
- Never overwrite official or third-party extension installations.
- Preserve upstream attribution and applicable licenses.
- Diagnose failures using Mihon Extension Diagnostic Studio.
- Test repairs on the Android emulator before releasing.
- Keep versioned source code, changelogs, and rollback builds.
- Validate library migration and reading-progress behavior separately.

## Add this repository to Mihon

Settings > Browse > Extension repos > Add, and enter:

```
https://raw.githubusercontent.com/molitar/mihon-custom-extensions/repo/index.min.json
```

If that does not work, use `https://raw.githubusercontent.com/molitar/mihon-custom-extensions/repo/repo.json`.
The `repo` branch holds the published files (`index.pb`, `index.json`, `index.min.json`, `repo.json`, `apk/`, `icon/`); this `main` branch holds the source.

Signing certificate SHA-256 (Molitar Custom Extensions):
`5e2b2564795db0af920d5ca1958de3a61b9dd40ad6278fbc007c9119ef2951ec`

## Extensions

- ManhwaZ (Custom) 1.6.2 (`eu.kanade.tachiyomi.extension.en.manhwazcustom`)

## Status

Published on the `repo` branch (2026-11-05): ManhwaZ (Custom) 1.6.2.
