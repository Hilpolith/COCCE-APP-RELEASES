# COCCE for Android 1.0.27

[![Version 1.0.27](https://img.shields.io/badge/COCCE-1.0.27-9333EA?style=for-the-badge)](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/tag/v1.0.27)
[![Android 7.0+](https://img.shields.io/badge/ANDROID-7.0%20OR%20NEWER-16A34A?style=for-the-badge)](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/tag/v1.0.27)
[![24 languages](https://img.shields.io/badge/LANGUAGES-24-0891B2?style=for-the-badge)](https://cocce-super-app-222ac.web.app/)

Welcome to a clearer, friendlier COCCE Ads and Wallet experience. Your other app features and all 24 app languages are still here.

## What's new

- **Ads are easier to read:** business and campaign cards now have a brighter glass-style look, with clearer text and menus.
- **Preview your own ad:** watch your own campaign video while it is being reviewed. Only the signed-in owner can use this preview; watching it does not add views or likes.
- **Follow your results:** colorful charts make campaign views and likes easier to understand.
- **Wallet activity at a glance:** a colorful chart compares coins you purchase, receive and send over your latest active days. It animates when you open your wallet.

## Choose a download

**Not sure which file fits your phone? Choose Universal.** Most newer Android phones use ARM64. ARMv7 is for older 32-bit ARM phones; x86_64 is for some Intel-based devices and Android emulators. Android 7.0 or newer is required.

| Build | Best for | Size | Download |
| --- | --- | ---: | --- |
| **ARM64** | Most newer Android phones and tablets | 106.46 MiB | [Download ARM64](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.27/cocce-1.0.27-arm64.apk) |
| **Universal** | If you are not sure which build fits your device | 204.90 MiB | [Download Universal](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.27/cocce-1.0.27-universal.apk) |
| **ARMv7** | Older 32-bit ARM phones and tablets | 123.98 MiB | [Download ARMv7](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.27/cocce-1.0.27-armv7.apk) |
| **x86_64** | Android emulators and some Intel-based devices | 101.37 MiB | [Download x86_64](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.27/cocce-1.0.27-x86_64.apk) |

After downloading, open the file and follow Android's installation instructions. The [COCCE download website](https://cocce-super-app-222ac.web.app/) also includes the same four builds and language choices.

<details>
<summary>Optional: technical notes and verification</summary>

### Owner preview and privacy

The preview checks the signed-in account against the campaign owner. No public storage policy was added or loosened. Preview playback does not write views, likes, completions or billing activity, and the public ad feed is unchanged.

### Verification

- Package: `com.cocce.cocce_super_app`; version `1.0.27`; minimum Android version 7.0 (SDK 24).
- APK signatures were verified. Each APK uses the COCCE signing certificate already listed for App Links on the download site.
- ABI builds contain only their intended processor type; Universal includes `arm64-v8a`, `armeabi-v7a` and `x86_64`.
- Version code: `2032` for all four APK builds.
- Full Flutter suite: **421 passed**, including the wallet chart checks. Ads feature suite: **44 passed**. Localization suite: **9 passed**. Owner-preview contract tests: **5 passed**.
- The app-wide analyzer count stayed at the pre-change baseline (147 existing diagnostics); the wallet chart helper and tests add no new findings.

See [`SHA256SUMS.txt`](SHA256SUMS.txt) to verify your download.

### Wallet behavior

The wallet chart is visual only; it does not change coin purchases, transfers, balances or transaction records.

</details>

---

## Earlier release: COCCE for Android 1.0.26

[![Version 1.0.26](https://img.shields.io/badge/COCCE-1.0.26-9333EA?style=for-the-badge)](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/tag/v1.0.26)
[![Android 7.0+](https://img.shields.io/badge/ANDROID-7.0%20OR%20NEWER-16A34A?style=for-the-badge)](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/tag/v1.0.26)
[![24 languages](https://img.shields.io/badge/LANGUAGES-24-0891B2?style=for-the-badge)](https://cocce-super-app-222ac.web.app/)

A warm hello to the 1.0.26 release. Existing app features and all 24 app languages were included.

### What changed in 1.0.26

- Clearer ad links: Ads are marked, and their buttons can take you to a website.
- More control for ad owners: Owners and admins can update or stop an ad while its activity and billing history stay on record.
- Proof kept separate: Private ad proof files are stored separately from simulated activity. Simulated activity does not represent real engagement.

### 1.0.26 verification notes

The 1.0.26 APKs were checked with Android SDK build-tools for package `com.cocce.cocce_super_app`, version name `1.0.26`, compile/target SDK 36 and minimum SDK 24. APK v2 signature verification passed for every variant. The 1.0.26 full suite had unrelated failures, so that release did not claim a full-suite pass.

Earlier source references: app `482df3027d0387e84ac5ec57f2bfe35c05ae2795`; portal `ef6d3742186f7689547149284e61cb40739d0e6e`.
