# COCCE — Android releases

![Latest release](https://img.shields.io/badge/COCCE-1.0.21-ED0747?style=for-the-badge&logo=android&logoColor=white)
![Free download](https://img.shields.io/badge/Download-Free-16A34A?style=for-the-badge)
![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-0EA5E9?style=for-the-badge&logo=android&logoColor=white)

COCCE brings videos, stories, chat, shopping and creator tools together in one app. This repository is for **signed Android downloads**; the app’s source code remains private.

## What’s new in COCCE 1.0.21

Make COCCE yours before you sign in. The Welcome screen now has matching, easy-to-find buttons to choose your language and app colors.

Earlier versions remain available and unchanged in [All releases](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases), including [COCCE 1.0.20](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/tag/v1.0.20).

Built from private source commit [`dc3dddff8762586d3adf13570e00f3bdcd56ca65`](https://github.com/Hilpolith/COCCE_Super_App/commit/dc3dddff8762586d3adf13570e00f3bdcd56ca65).

- Download page: [cocce-super-app-222ac.web.app](https://cocce-super-app-222ac.web.app)
- Investor information: [cocce.vercel.app](https://cocce.vercel.app/)
- Privacy policy: [Read the COCCE Privacy Policy](https://cocce-super-app-222ac.web.app/privacy-policy.html)
- All releases: [Browse earlier and current versions](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases)
- Example COCCE TV link: [Open a COCCE TV schedule](https://cocce-super-app-222ac.web.app/tv/imperium/7431d91f-cc68-45c2-9969-98ec5f929197)

---

## Download COCCE 1.0.21

Choose the download that best fits your device. **Most newer Android phones use ARM64.** If you are unsure, choose **Universal**; it is larger but includes every available device type.

| Download | For | Version | Size (MiB) | Get COCCE |
| --- | --- | ---: | ---: | --- |
| **ARM64** (recommended) | Most newer 64-bit Android phones and tablets | 1.0.21 | 106.30 | [Download ARM64](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.21/cocce-1.0.21-arm64.apk) |
| **Universal** | The simplest choice if you are not sure which build to use | 1.0.21 | 236.45 | [Download Universal](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.21/cocce-1.0.21-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM Android phones and tablets | 1.0.21 | 123.80 | [Download ARMv7](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.21/cocce-1.0.21-armv7.apk) |
| **x86_64** | Android emulators and compatible Intel-based devices | 1.0.21 | 101.20 | [Download x86_64](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.21/cocce-1.0.21-x86_64.apk) |

Requires **Android 7.0 or newer**. COCCE appears on your device as `com.cocce.cocce_super_app`.

### Check a downloaded file (optional)

These SHA-256 values let advanced users confirm that a download matches the published file:

```text
d0dc422d67d271a3e73259d22eb6c693644a4a3b56e9473a01616e7273527172  cocce-1.0.21-arm64.apk
899283da8345a49dafd4dc21e9a2eb985845534099d284c2ece040d502f4c794  cocce-1.0.21-armv7.apk
a16a4a86673422274cc670155a2a3b4b60a456d980e689bec5e87b6642c17ef9  cocce-1.0.21-universal.apk
1bce24b019bf362d74333a19f50c4d1b56171367ae0fbe3d6cffff86e0f89170  cocce-1.0.21-x86_64.apk
```

All four downloads use the same release certificate as earlier COCCE versions:

```text
Owner : CN=Cocce Super App, OU=Mobile, O=Cocce, L=City, ST=State, C=US
SHA-256: 63:B3:BA:18:BB:79:03:70:62:33:30:B7:75:73:32:69:B4:CC:28:3A:1C:E4:BE:25:A9:63:8F:3B:77:19:CE:F6
```

The Android App Links association at [`.well-known/assetlinks.json`](https://cocce-super-app-222ac.web.app/.well-known/assetlinks.json) recognizes this package and release certificate.

## Share a COCCE link

Shared COCCE links use `https://cocce-super-app-222ac.web.app/<type>/<id>`. COCCE TV schedule links use `https://cocce-super-app-222ac.web.app/tv/<channel-slug>/<schedule-id>`; the example above opens a TV schedule when COCCE is installed and otherwise shows the web download page.

Supported link types include `video`, `feed`, `product`, `profile`, `creator`, `shop`, `business` and `tv`.

## Install

1. Download the build for your device.
2. Open it. If Android asks, allow **Install unknown apps** for your browser or file manager. This permission is only needed for the install.
3. Tap **Install**. COCCE will appear in your app list.

## About

COCCE is owned and operated by HILPOLITH PHILLIP ROTHSCHILD. For support or privacy requests, email **coccesuperapp@gmail.com**.

Source code is **not** published here. Please do not open issues asking for it.
