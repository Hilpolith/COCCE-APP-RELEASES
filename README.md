# COCCE — Android releases

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository intentionally contains **no source code**. It exists so COCCE can be downloaded without giving anyone access to the private source repository. Every APK here is built from the COCCE source tree and signed with the COCCE release key.

Latest release: **COCCE 1.0.6**, built from source commit `4682f350c6be2f9288da66c848d5b90fc7264ed5`.

This standard build includes COCCE TV without TV-specific build-time Dart defines; sign-in, server-side row-level security, and administrator checks remain in place.

- Website / download page: **https://cocce-super-app-222ac.web.app**
- Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
- All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases

---

## Download

Pick the build that matches your device. If you are not sure, use **Universal**.

| Variant | For | Version | Size | Download |
| --- | --- | --- | ---: | --- |
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.6 | 105.50 MiB | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.6/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all supported ABIs) | 1.0.6 | 234.86 MiB | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.6/cocce-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM devices | 1.0.6 | 122.93 MiB | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.6/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.6 | 100.40 MiB | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.6/cocce-x86_64.apk) |

All four variants are version 1.0.6. Requirements: **Android 7.0 (API 24) or newer**. Package: `com.cocce.cocce_super_app`.

## Install

1. Download the APK for your device.
2. Open it and allow **Install unknown apps** for the app you downloaded it with (Chrome, Files, ...) when Android asks. This is a one-time permission.
3. Tap **Install**. COCCE appears in your app drawer as **COCCE**.

## Verify a download

Run this in the directory containing the APKs:

```bash
sha256sum -c SHA256SUMS.txt
```

Expected SHA-256 checksums for the v1.0.6 variants:

```text
67ce452f3b1bbe122a2d0ba1d78012bf47e0a9bd25465a30c332ab866b3ebcee  cocce-arm64-v8a.apk
d417e9681c0b608c8341e4a1a354356c39861566bc1e33ea55e037aa5e06609d  cocce-armeabi-v7a.apk
9ff9cda805ea9e7b921a882faf1f8893f10167da02c65f88b73bb5da9bbcd00e  cocce-universal.apk
f8d74215dda9665d029addb5b3525bcaf10924a6069340f6edd2e1b18233d9eb  cocce-x86_64.apk
```

Every APK is signed with the same release certificate, so newer versions install straight over older ones:

```text
Owner : CN=Cocce Super App, OU=Mobile, O=Cocce, L=City, ST=State, C=US
SHA-256: 63:B3:BA:18:BB:79:03:70:62:33:30:B7:75:73:32:69:B4:CC:28:3A:1C:E4:BE:25:A9:63:8F:3B:77:19:CE:F6
```

You can check it yourself:

```bash
apksigner verify --print-certs cocce-arm64-v8a.apk
```

## Deep links

Shared COCCE links look like `https://cocce-super-app-222ac.web.app/<type>/<id>`. If the app is installed, Android hands supported links to COCCE; otherwise the same URL shows a web page for the item with a download call to action.

Supported link types: `video`, `feed`, `product`, `profile`, `creator`, `shop`, `business`.

## About

COCCE is owned and operated by HILPOLITH PHILLIP ROTHSCHILD. For support or privacy requests: **coccesuperapp@gmail.com**.

Source code is **not** published here. Please do not open issues asking for it.
