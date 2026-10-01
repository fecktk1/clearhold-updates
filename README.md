# Clearhold macOS update artifacts

This repository is for publicly downloadable, signed Clearhold macOS update artifacts only. Application source, backend data, login credentials, notarization credentials, and the Sparkle private signing key are not stored here.

The `/test/` GitHub Pages channel is reserved for prerelease v1-to-v2 update verification. No stable channel is published until signing, notarization, widget and login QA, tamper rejection, offline recovery, and data-retention checks pass.

An appcast is authoritative only when its signature verifies against the public key embedded in the corresponding Clearhold app. Downloaded archives must carry valid Sparkle EdDSA signatures and Apple Developer ID signatures.
