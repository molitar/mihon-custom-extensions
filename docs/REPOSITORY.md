# Mihon Extension Repository Configuration

Repository display name: Molitar Custom Extensions
GitHub owner: molitar

## Source repository

https://github.com/molitar/mihon-custom-extensions

## Distribution files (published 2026-11-05)

The distribution branch is `repo`.

Mihon repository address: https://raw.githubusercontent.com/molitar/mihon-custom-extensions/repo/index.min.json

Signing certificate SHA-256: 5e2b2564795db0af920d5ca1958de3a61b9dd40ad6278fbc007c9119ef2951ec

- repo.json: Mihon repository metadata and signing fingerprint.
- index.pb: current extension catalog.
- index.min.json: compatibility catalog.
- apk/: signed extension release artifacts.
- icon/: extension icons.

The final repo.json must contain a valid index_v2 URL,
repository name, website, and actual signing-key fingerprint.

The index must be generated from verified build artifacts.

Do not invent APK records, signing fingerprints, download URLs,
or successful build statuses.

## Identity policy

Every custom extension requires a distinct Android package and
Mihon source ID.

ManhwaZ (Custom):
- Package: eu.kanade.tachiyomi.extension.en.manhwazcustom
- Source ID: 3101173267604405323

Existing official and third-party extensions must remain untouched.

## Publishing policy

The repository is public and the `repo` branch is publicly readable, so it works as an ordinary Mihon extension repository.

Never publish signing private keys, access tokens, or private
diagnostic captures.

Keep the APK signing identity stable across future updates.

Test all custom APKs on the emulator before publishing.
