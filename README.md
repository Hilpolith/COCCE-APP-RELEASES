# COCCE - Android releases

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository intentionally contains **no source code**. It exists so the COCCE
Android app can be downloaded without giving anyone access to the private source
repository. Every APK here is built from the private COCCE source tree and signed
with the COCCE release key.

Latest release: **COCCE 1.0.4**, built from source commit `36343f805b8bdf3590f640445cfb19e353d62f5d`. The three COCCE TV compile-time release gates were enabled for these release builds only; source defaults remain fail-closed.

* Website / download page: **https://cocce-super-app-222ac.web.app**
* Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
* All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases

---

## Download

Pick the build that matches your device. If you are not sure, use **Universal**.

| Variant | For | Version | Size | Download |
| --- | --- | --- | --- | --- |
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.4 | 105.48 MB | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.4/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all supported ABIs) | 1.0.4 | 202.77 MB | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.4/cocce-universal.apk) |
| **ARM** (32-bit) | Older 32-bit ARM devices | 1.0.4 | 122.91 MB | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.4/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.0 | 98.21 MB | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.0/cocce-x86_64.apk) |

Each link is pinned to the release that contains that ABI. ARM64, ARM, and Universal are v1.0.4; x86_64 remains on v1.0.0. Older release tags remain available, so existing direct download links continue to work.
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
72370BF217E28A725280696C2CA8C196C2D036DD00A9E2AE153F9ECD6D15D54C  cocce-arm64-v8a.apk
265D83410126F3CC1711C4982FAF3FD359027E87832D580E819B76938DC9EC5F  cocce-universal.apk
29D9F9141940D49DD7B1290397F209F1C6496D13C738D8863BD9D5F4CE54B8B9  cocce-armeabi-v7a.apk
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
