# 🎉 COCCE for Android 1.0.26

[![Version 1.0.26](https://img.shields.io/badge/COCCE-1.0.26-9333EA?style=for-the-badge)](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/tag/v1.0.26)
[![Android 7.0+](https://img.shields.io/badge/ANDROID-7.0%20OR%20NEWER-16A34A?style=for-the-badge)](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/tag/v1.0.26)
[![24 languages](https://img.shields.io/badge/LANGUAGES-24-0891B2?style=for-the-badge)](https://cocce-super-app-222ac.web.app/)

A warm hello to the latest COCCE release. Your existing app features and all 24 app languages are still here.

## ✨ What’s new

- **Clearer ad links:** Ads are marked, and their buttons can take you to a website.
- **More control for ad owners:** Owners and admins can update or stop an ad while its activity and billing history stay on record.
- **Proof kept separate:** Private ad proof files are stored separately from simulated activity. Simulated activity does not represent real engagement.

## 📲 Pick the right download

**Not sure? Choose Universal.** Most newer Android phones use ARM64. ARMv7 is for older 32-bit ARM phones; x86_64 is for compatible Intel devices and emulators. Android 7.0 or newer is required.

| Build | Best for | Download |
| --- | --- | --- |
| **ARM64** | Most newer Android phones | [⬇️ Download ARM64](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.26/cocce-1.0.26-arm64.apk) |
| **Universal** | If you’re not sure which build fits | [🌈 Download Universal](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.26/cocce-1.0.26-universal.apk) |
| **ARMv7** | Older 32-bit ARM phones | [⬇️ Download ARMv7](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.26/cocce-1.0.26-armv7.apk) |
| **x86_64** | Compatible Intel devices and emulators | [⬇️ Download x86_64](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.26/cocce-1.0.26-x86_64.apk) |

<details>
<summary>Optional: technical notes and verification</summary>

### Implementation details

- Ads service updates support HTTP/HTTPS CTA destinations with an Ads marker, owner/admin editing and soft-cancel flows that preserve audit and billing history.
- Private proof objects are Bunny-only and kept under a separate Ads prefix. Synthetic simulation remains independent and does not represent real engagement.

### Verification

All four supplied APKs were checked with Android SDK build-tools: package `com.cocce.cocce_super_app`, version name `1.0.26`, compile/target SDK 36, and minimum SDK 24. APK v2 signature verification passed for every variant. ABI split version codes are arm64 `4031`, armv7 `3031`, x86_64 `6031`, and universal `2031`.

Focused Ads service tests: **10 passed**. Touched-files analyzer: **passed**. Portal typecheck/build: **passed**. The full suite was **not** green because it contains unrelated failures; this release does not claim a full-suite pass.

No APKs, signing files, secrets, or backend credentials are included in this metadata repository.

See [`SHA256SUMS.txt`](SHA256SUMS.txt) to check that your download matches the published file.

### Source references

- App source ref: `482df3027d0387e84ac5ec57f2bfe35c05ae2795`
- Portal source ref: `ef6d3742186f7689547149284e61cb40739d0e6e`

</details>
