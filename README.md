# COCCE — Android releases

![COCCE 1.0.20](https://img.shields.io/badge/COCCE-1.0.20-ED0747?style=for-the-badge&logo=android&logoColor=white)
![Free download](https://img.shields.io/badge/Download-Free-16A34A?style=for-the-badge)
![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-0EA5E9?style=for-the-badge&logo=android&logoColor=white)

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository contains downloadable Android releases, not the app source code. The APKs are built from the private COCCE source tree and signed with the COCCE release key.

## What’s new in COCCE 1.0.20

- All **24 in-app languages** are now selectable. English and Kiswahili remain the original catalogs; the 22 additional catalogs are machine-generated and have **not** been human-reviewed. Some wording may be inaccurate. Please send corrections to **coccesuperapp@gmail.com**.
- The previous profile-settings dialog layout is restored, with text and titles centered.
- Direct and group chat notification replies have improved message metadata.
- Earlier releases, including v1.0.19, remain available unchanged.

Built from private source commit [`777bf6f3ac03440541bb5dd7e87001a2a55b0fa1`](https://github.com/Hilpolith/COCCE_Super_App/commit/777bf6f3ac03440541bb5dd7e87001a2a55b0fa1).

- Website / download page: **https://cocce-super-app-222ac.web.app**
- Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
- All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases
- Example COCCE TV link: https://cocce-super-app-222ac.web.app/tv/imperium/7431d91f-cc68-45c2-9969-98ec5f929197

---

## Download

Choose the build that matches your device. If you are not sure, use **Universal**. Most newer Android phones and tablets use **ARM64**.

| Variant | For | Version | Size (MiB) | Download |
| --- | --- | ---: | ---: | --- |
| **ARM64** (recommended) | Most newer 64-bit Android phones and tablets | 1.0.20 | 106.30 | [`cocce-1.0.20-arm64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.20/cocce-1.0.20-arm64.apk) |
| **Universal** | Supported Android devices; easiest if unsure (larger download) | 1.0.20 | 204.43 | [`cocce-1.0.20-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.20/cocce-1.0.20-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM Android devices | 1.0.20 | 123.80 | [`cocce-1.0.20-armv7.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.20/cocce-1.0.20-armv7.apk) |
| **x86_64** | Android emulators and compatible Intel-based devices | 1.0.20 | 101.20 | [`cocce-1.0.20-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.20/cocce-1.0.20-x86_64.apk) |

Requirements: **Android 7.0 (API 24) or newer**. Package: `com.cocce.cocce_super_app`.

## Verify a download

Expected SHA-256 checksums for the four v1.0.20 APKs:

```text
dd9c210def321a9087ef658c51937d098924d6d113c94c2fffdc52aa55c46a2d  cocce-1.0.20-arm64.apk
d42764d094ae06557e85f247540b03387ea0458f14f13f09ba843e8a535061af  cocce-1.0.20-armv7.apk
56c04d746b42964a87dc1df9c7c0cdbb9649ed81aab93dad04b46742075a52e0  cocce-1.0.20-universal.apk
d838365d1068c0222741083701ac189b98f8e2910c2fdb96aa9873460dbd9c91  cocce-1.0.20-x86_64.apk
```

All four APKs use the same release certificate as v1.0.19:

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
