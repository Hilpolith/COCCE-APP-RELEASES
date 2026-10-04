# COCCE — Android releases

![COCCE 1.0.12](https://img.shields.io/badge/COCCE-1.0.12-2563EB?style=for-the-badge&logo=android&logoColor=white)
![Free download](https://img.shields.io/badge/Download-Free-16A34A?style=for-the-badge)
![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-0EA5E9?style=for-the-badge&logo=android&logoColor=white)

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository contains the downloadable Android releases, not the app source code. The APKs are built from the private COCCE source tree and signed with the COCCE release key.

**COCCE 1.0.12** improves presenter information in COCCE TV. When a schedule lists multiple presenters, their names are matched to the right profiles more reliably. Multi-word names stay intact, and schedule credits can refresh when program details change. COCCE TV is included in the regular app—there is nothing extra to install. Previous releases remain available unchanged.

Built from private source commit [`81373a7bd3c5307f16207b19315599a7d4cc36a9`](https://github.com/Hilpolith/COCCE_Super_App/commit/81373a7bd3c5307f16207b19315599a7d4cc36a9).

- Website / download page: **https://cocce-super-app-222ac.web.app**
- Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
- All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases
- Example COCCE TV link: https://cocce-super-app-222ac.web.app/tv/imperium/7431d91f-cc68-45c2-9969-98ec5f929197

---

## Download

Choose the build that matches your device. If you are not sure, use **Universal**. Most Android phones and tablets use **ARM64**.

| Variant | For | Version | Version code | Size (MiB) | Download |
| --- | --- | ---: | ---: | ---: | --- |
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.12 | 2014 | 105.54 | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.12/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all supported ABIs) | 1.0.12 | 14 | 207.73 | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.12/cocce-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM devices | 1.0.12 | 1014 | 109.36 | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.12/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.12 | 4014 | 86.81 | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.12/cocce-x86_64.apk) |

Requirements: **Android 7.0 (API 24) or newer**. Package: `com.cocce.cocce_super_app`.

## Verify a download

Expected SHA-256 checksums for the four v1.0.12 APKs:

```text
fd44321befdef1707ee4bac12854988abdc83bde19f9358e6f2ac3c5268397d9  cocce-arm64-v8a.apk
ab14d59fc70df66df2ecbcf47aad991dd121d30eab44c4b2ecf0be0a3a47212e  cocce-armeabi-v7a.apk
9b7cfa99ae74feb9f069c1d4b380fc1c6be5d690d1e17f603e8261ca2388fc9d  cocce-universal.apk
edfe7f1cfaa8de7a1e01e35453c6e15a302d16156a17880ff1cb2f652f9cbc1f  cocce-x86_64.apk
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
