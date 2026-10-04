# COCCE — Android releases

![COCCE 1.0.13](https://img.shields.io/badge/COCCE-1.0.13-2563EB?style=for-the-badge&logo=android&logoColor=white)
![TV scheduling made easier](https://img.shields.io/badge/TV_scheduling-Made_easier-7C3AED?style=for-the-badge)
![Free download](https://img.shields.io/badge/Download-Free-16A34A?style=for-the-badge)
![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-0EA5E9?style=for-the-badge&logo=android&logoColor=white)

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository contains the downloadable Android releases, not the app source code. The APKs are built from the private COCCE source tree and signed with the COCCE release key.

## What’s new in COCCE 1.0.13

Adding the next programme to a COCCE TV channel is now easier. Choose **Add Next**, and COCCE checks the latest programme already scheduled on that channel, then lines the new one up right after it—even if the schedule list is filtered or has more than one page. You don’t need to work out the time yourself. Earlier releases remain available unchanged.

Built from source commit [`5cb358ed3d35f6c20ffba1ef0782f9d9434b2227`](https://github.com/Hilpolith/COCCE_Super_App/commit/5cb358ed3d35f6c20ffba1ef0782f9d9434b2227).

- Website / download page: **https://cocce-super-app-222ac.web.app**
- Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
- All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases
- Example COCCE TV link: https://cocce-super-app-222ac.web.app/tv/imperium/7431d91f-cc68-45c2-9969-98ec5f929197

---

## Download

Choose the build that matches your device. If you are not sure, use **Universal**. Most Android phones and tablets use **ARM64**.

| Variant | For | Version | Size (MiB) | Download |
| --- | --- | ---: | ---: | --- |
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.13 | 105.54 | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.13/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all supported ABIs) | 1.0.13 | 207.73 | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.13/cocce-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM devices | 1.0.13 | 109.36 | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.13/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.13 | 86.81 | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.13/cocce-x86_64.apk) |

Requirements: **Android 7.0 (API 24) or newer**. Package: `com.cocce.cocce_super_app`.

## Verify a download

Optional SHA-256 checksums for the four v1.0.13 APKs:

```text
c450922dc3b49f623b4cb944bf520cd461112de199ce7292346c6b2333555a3f  cocce-arm64-v8a.apk
4430dafc6547bb20a7d1e6ce6af24939f4f34afab676d9bc99e892647d48e991  cocce-armeabi-v7a.apk
83f1d47ef4976053f98405ab4d00a6f317b8777a91c2649d5ccb2494107ef3ff  cocce-universal.apk
65bf120330428d545fd882c96c225ea1e5c0f2b62af385be7e633f0f2cf1a4c2  cocce-x86_64.apk
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
