# COCCE — Android releases

![COCCE 1.0.18](https://img.shields.io/badge/COCCE-1.0.18-ED0747?style=for-the-badge&logo=android&logoColor=white)
![Cleaner navigation](https://img.shields.io/badge/Cleaner-navigation-665BCA?style=for-the-badge)
![Free download](https://img.shields.io/badge/Download-Free-16A34A?style=for-the-badge)
![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-0EA5E9?style=for-the-badge&logo=android&logoColor=white)

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository contains the downloadable Android releases, not the app source code. The APKs are built from the private COCCE source tree and signed with the COCCE release key.

## What’s new in COCCE 1.0.18

The navigation bar and quick buttons now have a lighter look, with less blur and shadow. Your usual buttons and features are still there — the screen just feels less visually busy. Earlier releases remain available unchanged.

Built from source commit [`0f5662db39f1c9b8bb7712e3f094d2b6f371b6a3`](https://github.com/Hilpolith/COCCE_Super_App/commit/0f5662db39f1c9b8bb7712e3f094d2b6f371b6a3).

- Website / download page: **https://cocce-super-app-222ac.web.app**
- Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
- All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases
- Example COCCE TV link: https://cocce-super-app-222ac.web.app/tv/imperium/7431d91f-cc68-45c2-9969-98ec5f929197

---

## Download

Choose the build that matches your device. If you are not sure, use **Universal**. Most newer Android phones and tablets use **ARM64**.

| Variant | For | Version | Size (MiB) | Download |
| --- | --- | ---: | ---: | --- |
| **ARM64** (recommended) | Most newer 64-bit Android phones and tablets | 1.0.18 | 105.55 | [`cocce-1.0.18-arm64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.18/cocce-1.0.18-arm64.apk) |
| **Universal** | Supported Android devices; easiest if unsure (larger download) | 1.0.18 | 203.00 | [`cocce-1.0.18-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.18/cocce-1.0.18-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM Android devices | 1.0.18 | 122.99 | [`cocce-1.0.18-armv7.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.18/cocce-1.0.18-armv7.apk) |
| **x86_64** | Android emulators and compatible Intel-based devices | 1.0.18 | 100.46 | [`cocce-1.0.18-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.18/cocce-1.0.18-x86_64.apk) |

Requirements: **Android 7.0 (API 24) or newer**. Package: `com.cocce.cocce_super_app`.

## Verify a download

Expected SHA-256 checksums for the four v1.0.18 APKs:

```text
173f8624d00d2baaf03a2a4d663959268015f7395ccb56bc039cfe6837e5f867  cocce-1.0.18-arm64.apk
47d56dcf8ad248c18ba8fb42c3a687aea0483519d73fd219554a8e4dda239c0f  cocce-1.0.18-armv7.apk
3bfc1a23eb66452981f7d46cc70aa6b56e3b65799478c04264092721d610b620  cocce-1.0.18-universal.apk
bd51e52a75e298f9be012771edb3615eaa0d0b5bd04d96e4a78be2a07e6c0c22  cocce-1.0.18-x86_64.apk
```

All four APKs use the same release certificate:

```text
Owner : CN=Cocce Super App, OU=Mobile, O=Cocce, L=City, ST=State, C=US
SHA-256: 63:B3:BA:18:BB:79:03:70:62:33:30:B7:75:73:32:69:B4:CC:28:3A:1C:E4:BE:25:A9:63:8F:3B:77:19:CE:F6
```

The Android App Links association at [`/.well-known/assetlinks.json`](https://cocce-super-app-222ac.web.app/.well-known/assetlinks.json) includes this package and release certificate.

## Deep links

Shared COCCE links use `https://cocce-super-app-222ac.web.app/<type>/<id>`. COCCE TV schedule links use `https://cocce-super-app-222ac.web.app/tv/<channel-slug>/<schedule-id>`; the example above opens a TV schedule when COCCE is installed and otherwise displays the web fallback and download page.

Supported link types include `video`, `feed`, `product`, `profile`, `creator`, `shop`, `business`, and `tv`.

## Install

1. Download the APK for your device.
2. Open it and allow **Install unknown apps** for the app you downloaded it with (Chrome, Files, ...) when Android asks. This is a one-time permission.
3. Tap **Install**. COCCE appears in your app drawer as **COCCE**.

## About

COCCE is owned and operated by HILPOLITH PHILLIP ROTHSCHILD. For support or privacy requests: **coccesuperapp@gmail.com**.

Source code is **not** published here. Please do not open issues asking for it.
