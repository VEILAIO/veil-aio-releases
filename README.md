# Veil AIO — Releases

Public release artifacts for **Veil AIO**: customer DMGs and the signed update
manifest the in-app updater consumes.

- `update-manifest.json` (+ `.sig`) — the Ed25519-signed manifest the app verifies
  against its baked public key before offering an update.
- `*.dmg` — the customer builds.

The application source lives in the private `veil-aio` repository. Releases here
are created with `desktop/scripts/publish-release.mjs`.
