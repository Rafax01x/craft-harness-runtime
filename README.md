# craft-harness-runtime

Public runtime bundles for Craft Harness (Android AI coding agent).

Releases host the Ubuntu core rootfs (`.tar.zst`) + `manifest.json` that the app's
PRoot runtime installer downloads. The app reads the manifest, verifies the bundle
sha256, and extracts it on-device. No source code lives here.

Current bundle: `runtime-core-2026.09.5` — Ubuntu 20.04.5 ARM64 + Node.js 24.19.0 + Git 2.25.1.
