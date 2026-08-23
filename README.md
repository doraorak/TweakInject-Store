# TI Store

Official package repository for [TweakInject](https://github.com/doraorak/TweakInject).

- `repo/Packages.json` — the manifest the app fetches
- `repo/debs/` — published package payloads

Each entry carries a `sha256` of its `.deb`. The app verifies it after download and
**before** the archive is unpacked, so a tampered package never reaches the extractor.

Moved here from `doraorak.github.io` so a publishing token can be scoped to this
repository alone.
