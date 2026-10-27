# COCCE Android 1.0.26

## Release notes

- Adds the Ads service updates: HTTP/HTTPS CTA destinations with an Ads marker, owner/admin editing and soft-cancel flows that preserve audit and billing history.
- Keeps Bunny-only private proof objects under a separate Ads prefix. Synthetic simulation remains independent and does not represent real engagement.
- Existing app features and all 24 app languages remain included; Android 7.0 (API 24) or newer is required.

## Verification

All four supplied APKs were checked with Android SDK build-tools: package `com.cocce.cocce_super_app`, version name `1.0.26`, compile/target SDK 36, and minimum SDK 24. APK v2 signature verification passed for every variant. ABI split version codes are arm64 `4031`, armv7 `3031`, x86_64 `6031`, and universal `2031`.

Focused Ads service tests: **10 passed**. Touched-files analyzer: **passed**. Portal typecheck/build: **passed**. The full suite was **not** green because it contains unrelated failures; this release does not claim a full-suite pass.

No APKs, signing files, secrets, or backend credentials are included in this metadata repository.

See [`SHA256SUMS.txt`](SHA256SUMS.txt) for download verification.
