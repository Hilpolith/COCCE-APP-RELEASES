# COCCE — Android releases

![COCCE 1.0.19](https://img.shields.io/badge/COCCE-1.0.19-ED0747?style=for-the-badge&logo=android&logoColor=white)
![Softer Shop look](https://img.shields.io/badge/Shop-Softer%20look-665BCA?style=for-the-badge)
![Free download](https://img.shields.io/badge/Download-Free-16A34A?style=for-the-badge)
![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-0EA5E9?style=for-the-badge&logo=android&logoColor=white)

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository contains the downloadable Android releases, not the app source code. The APKs are built from the private COCCE source tree and signed with the COCCE release key.

## What’s new in COCCE 1.0.19

The Shop screen's top bar and quick buttons now look lighter and less busy. Your familiar filters and buttons are still there, and selected filters remain easy to spot. Earlier releases remain available unchanged.

Built from source commit [`d53505834293b471938d414fd1719b182df2d597`](https://github.com/Hilpolith/COCCE_Super_App/commit/d53505834293b471938d414fd1719b182df2d597).

- Website / download page: **https://cocce-super-app-222ac.web.app**
- Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
- All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases
- Example COCCE TV link: https://cocce-super-app-222ac.web.app/tv/imperium/7431d91f-cc68-45c2-9969-98ec5f929197

---

## Download

Choose the build that matches your device. If you are not sure, use **Universal**. Most newer Android phones and tablets use **ARM64**.

| Variant | For | Version | Size (MiB) | Download |
| --- | --- | ---: | ---: | --- |
| **ARM64** (recommended) | Most newer 64-bit Android phones and tablets | 1.0.19 | 105.55 | [`cocce-1.0.19-arm64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.19/cocce-1.0.19-arm64.apk) |
| **Universal** | Supported Android devices; easiest if unsure (larger download) | 1.0.19 | 235.02 | [`cocce-1.0.19-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.19/cocce-1.0.19-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM Android devices | 1.0.19 | 122.99 | [`cocce-1.0.19-armv7.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.19/cocce-1.0.19-armv7.apk) |
| **x86_64** | Android emulators and compatible Intel-based devices | 1.0.19 | 100.46 | [`cocce-1.0.19-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.19/cocce-1.0.19-x86_64.apk) |

Requirements: **Android 7.0 (API 24) or newer**. Package: `com.cocce.cocce_super_app`.

## Verify a download

Expected SHA-256 checksums for the four v1.0.19 APKs:

```text
a2fb65951bc1a31d6ff95e9c3f45ef15644621d54476caf070694a9068efdb54  cocce-1.0.19-arm64.apk
dc61e329a75f757a2521f925428f8ec999795a9b7f11c0e88266bc3b19ba6706  cocce-1.0.19-armv7.apk
652017371dddbd950a04c282f114742f82d36b0d2c8d6f54c89d112fa9f49565  cocce-1.0.19-universal.apk
fb4c5c736a642e39d1ec7a6a90860f483acc72aef80f60e843c2a6eb49cf2409  cocce-1.0.19-x86_64.apk
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
