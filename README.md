# COCCE - Android releases

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository intentionally contains **no source code**. It exists so the COCCE
Android app can be downloaded without giving anyone access to the private source
repository. Every APK here is built from the private COCCE source tree and signed
with the COCCE release key.

Latest release: **COCCE 1.0.5**, built from source commit `2319492594d02d3ce9434991111431fb6f7933a7`. COCCE TV is available in normal builds without build-time Dart defines; sign-in, server-side row-level security, and administrator checks remain in place.

* Website / download page: **https://cocce-super-app-222ac.web.app**
* Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
* All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases

---

## Download

Pick the build that matches your device. If you are not sure, use **Universal**.

| Variant | For | Version | Size | Download |
| --- | --- | --- | --- | --- |
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.5 | 105.48 MB | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.5/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all supported ABIs) | 1.0.5 | 221.22 MB | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.5/cocce-universal.apk) |
| **ARM** (32-bit) | Older 32-bit ARM devices | 1.0.5 | 122.91 MB | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.5/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.0 | 98.21 MB | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.0/cocce-x86_64.apk) |

Each link is pinned to the release that contains that ABI. ARM64, ARM, and Universal are v1.0.5; x86_64 remains on v1.0.0. Older release tags remain available, so existing direct download links continue to work.
Requirements: **Android 7.0 (API 24) or newer**. Package `com.cocce.cocce_super_app`.

## Install

1. Download the APK for your device.
2. Open it and allow **Install unknown apps** for the app you downloaded it with
   (Chrome, Files, ...) when Android asks. This is a one-time permission.
3. Tap **Install**. COCCE appears in your app drawer as **COCCE**.

## Verify a download

```bash
sha256sum cocce-arm64-v8a.apk
```

Expected checksums for the currently linked variants:
```
41420CE0FF282369E4815747E6A8BBB574EEC476443C56566940D87E12C7546A  cocce-arm64-v8a.apk
F5107BF73B406EE01C72F0B2E263EF9340979F31DBD932EC39359F71BADAE11C  cocce-universal.apk
EA6D709F41C3FAB9FD7CEEFB93380643CD03C0BFF7E12F49B2D02AC0FED8D11B  cocce-armeabi-v7a.apk
43236296D4F0CC587EBBD1216B6B967D890C1DACD2B2636A9EBE251365A97D50  cocce-x86_64.apk
```

Every APK is signed with the same release certificate, so newer versions install
straight over older ones:

```
Owner : CN=Cocce Super App, OU=Mobile, O=Cocce, L=City, ST=State, C=US
SHA-256: 63:B3:BA:18:BB:79:03:70:62:33:30:B7:75:73:32:69:B4:CC:28:3A:1C:E4:BE:25:A9:63:8F:3B:77:19:CE:F6
```

You can check it yourself:

```bash
apksigner verify --print-certs cocce-arm64-v8a.apk
```

## Deep links

Shared COCCE links look like `https://cocce-super-app-222ac.web.app/<type>/<id>`.
If the app is installed, Android hands the link to COCCE and opens the right
screen; if it is not, the same URL shows a web page for that item with a download
call to action.

Supported link types: `video`, `feed`, `product`, `profile`, `creator`, `shop`,
`business`.

## About

COCCE is owned and operated by HILPOLITH PHILLIP ROTHSCHILD. For support or
privacy requests: **coccesuperapp@gmail.com**.

Source code is **not** published here. Please do not open issues asking for it.
