# Agent instructions

This repository is the Business Chinese consumer and distribution repository.

## Current source boundary

Reusable language-learning software stays in
`place-of-honor/learn-toki-pona` for now:
https://github.com/place-of-honor/learn-toki-pona

Do not copy or fork the terminal trainer, Android interface, games, scheduling,
or other shared learner mechanics into this repository merely to customize
Chinese content.

This repository owns Business-Chinese-specific corpus material and distributable
outputs derived from the shared learner.

When publishing an APK or command-line binary here, record the exact source
repository, source commit, target/platform, architecture, and SHA-256 in
`artifacts/manifest.tsv`. Keep build evidence distinct from runtime or
physical-device acceptance.

Factor the reusable learner into a separate standalone repository only after an
explicit decision that the language learner is sufficiently independent to
stand on its own.
