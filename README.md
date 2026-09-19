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
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.0 | 101.59 MB | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/latest/download/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all ABIs) | 1.0.0 | 197.12 MB | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/latest/download/cocce-universal.apk) |
| **ARM** (32-bit) | Older 32-bit ARM devices | 1.0.0 | 119.49 MB | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/latest/download/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.0 | 98.2 MB | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/latest/download/cocce-x86_64.apk) |

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
110E38F7F1BB80B69E8A40776D28CD35F9055204BD00B5C3B1B504DCEDBACCCF  cocce-arm64-v8a.apk
40E6F1CDEEAAEFF8D79676E9069633C6B20093DB485F0E30AA142890202B78F3  cocce-universal.apk
2CD1FF2ACD08F32ADEE6B2C60952D65CF7F7C6675410232353CF9FC691E9B150  cocce-armeabi-v7a.apk
C8E282302D4CE5980967E2656D9EFAC72A35C7CCC4E234E59BED47DDEB1201DA  cocce-x86_64.apk
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
