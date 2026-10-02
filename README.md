# COCCE — Android releases

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository intentionally contains **no source code**. The APKs are built from the private COCCE source tree and signed with the COCCE release key.

Latest release: **COCCE 1.0.7** (`v1.0.7`), built from approved source commit `a3d72b09853eff0b0024ead1c6b7fc3e1a79db44`. This standard build includes COCCE TV without TV-specific build-time Dart defines; sign-in, server-side row-level security, and administrator checks remain in place. The prior `v1.0.6` release is retained unchanged.

- Website / download page: **https://cocce-super-app-222ac.web.app**
- Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
- All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases
- Example COCCE TV link: https://cocce-super-app-222ac.web.app/tv/imperium/7431d91f-cc68-45c2-9969-98ec5f929197

---

## Download

Choose the build that matches your device. If you are not sure, use **Universal**.

| Variant | For | Version | Size (MiB) | Download |
| --- | --- | --- | ---: | --- |
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.7 | 105.50 | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.7/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all supported ABIs) | 1.0.7 | 202.85 | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.7/cocce-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM devices | 1.0.7 | 122.94 | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.7/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.7 | 100.41 | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.7/cocce-x86_64.apk) |

Requirements: **Android 7.0 (API 24) or newer**. Package: `com.cocce.cocce_super_app`.

## Verify a download

Expected SHA-256 checksums for the four v1.0.7 APKs:

```text
9b4adf14a4248402a96abede1bac40a4f0d627c15b54116313fb74e9540a384f  cocce-arm64-v8a.apk
46fbdb962de240991e51a38a45969e822022d4ed41857bcc8697357250a8fc72  cocce-armeabi-v7a.apk
a00ff3a103057bb8cfe9c299d447b3357e8c9d99dc6cbe91605bfc66d2ed30fe  cocce-universal.apk
93044665768b74cee4e4515298ecb839ce280ed2eaeb484c2ada2223933c7521  cocce-x86_64.apk
```

All four APKs use the same release certificate:

```text
Owner : CN=Cocce Super App, OU=Mobile, O=Cocce, L=City, ST=State, C=US
SHA-256: 63:B3:BA:18:BB:79:03:70:62:33:30:B7:75:73:32:69:B4:CC:28:3A:1C:E4:BE:25:A9:63:8F:3B:77:19:CE:F6
```

The Android App Links association at [`/.well-known/assetlinks.json`](https://cocce-super-app-222ac.web.app/.well-known/assetlinks.json) includes this package and release certificate.

## Deep links

Shared COCCE links use `https://cocce-super-app-222ac.web.app/<type>/<id>`. COCCE TV schedule links use `https://cocce-super-app-222ac.web.app/tv/<channel-slug>/<schedule-id>`; for example, the link above opens a TV schedule when COCCE is installed and otherwise displays the web fallback and download page.

Supported link types include `video`, `feed`, `product`, `profile`, `creator`, `shop`, `business`, and `tv`.

## Install

1. Download the APK for your device.
2. Open it and allow **Install unknown apps** for the app you downloaded it with (Chrome, Files, ...) when Android asks. This is a one-time permission.
3. Tap **Install**. COCCE appears in your app drawer as **COCCE**.

## About

COCCE is owned and operated by HILPOLITH PHILLIP ROTHSCHILD. For support or privacy requests: **coccesuperapp@gmail.com**.

Source code is **not** published here. Please do not open issues asking for it.
