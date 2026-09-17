# COCCE - Android releases

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository intentionally contains **no source code**. It exists so the COCCE
Android app can be downloaded without giving anyone access to the private source
repository. Every APK here is built from the private COCCE source tree and signed
with the COCCE release key.

* Website / download page: **https://cocce-super-app-222ac.web.app**
* Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
* All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases

---

## Download

Pick the build that matches your device. If you are not sure, use **Universal**.

| Variant | For | Version | Size | Download |
| --- | --- | --- | --- | --- |
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.0 | 101.53 MB | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/latest/download/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all ABIs) | 1.0.0 | 196.96 MB | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/latest/download/cocce-universal.apk) |
| **ARM** (32-bit) | Older 32-bit ARM devices | 1.0.0 | 119.43 MB | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/latest/download/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.0 | 98.14 MB | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/latest/download/cocce-x86_64.apk) |

These `releases/latest/download/...` links are **stable**: they always serve the
newest published release, so they can be printed in a QR code or hard-coded in a
website without ever changing.

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

Expected checksums for the current release:

```
3FF3B12A45A98F72ED88A25E5B5DDE6BC05DCAB72CC281EA57FBF22FFB909D8A  cocce-arm64-v8a.apk
80D03FC9D7FAA33E4877EC8569A7400B898964FBCC7DA1D72E441BF79767FAA4  cocce-universal.apk
3605C5CA6CCD81C0A9FDACAA1324763A3F62B75411904851A00E7B7626EE7AE5  cocce-armeabi-v7a.apk
3BF7CAFE786C44AB394B4C0DF0E00C6EE813896432970B53EB3CB664EC6FC367  cocce-x86_64.apk
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
