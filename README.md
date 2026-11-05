# Vyntra Update Manifest

This repository is the public source of truth for Vyntra update metadata.

- `update.json` describes the latest release.
- APK binaries remain attached to GitHub Releases in `Dancode-del/vyntra`.
- The SHA-256 value is copied from GitHub's uploaded release asset digest.
- The current manifest is marked `verification: pending` because no update-signing public/private key pair has been configured yet.

Do not mark a release verified or publish a signature until the app's pinned public key and the release workflow's private signing key are configured. The app must independently verify the signed manifest and downloaded APK.
