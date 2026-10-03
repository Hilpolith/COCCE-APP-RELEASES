# COCCE — Android releases

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository intentionally contains **no source code**. The APKs are built from the private COCCE source tree and signed with the COCCE release key.

Latest release: **COCCE 1.0.10** (`v1.0.10`), built from source commit `a63b026ab36903c97040c0630aa21ca9287281aa`. This release loads valid cached Feed and Shop items immediately while the existing ORIGIN CORE-ranked server refresh continues in the background. An empty server response preserves the valid cache, refreshed candidates replace stale cache-only entries, and the first item rotates across up to three valid candidates on later launches. No ORIGIN CORE scoring or ranking logic was changed. The previous 1.0.9 fixes remain, including multi-presenter rendering, non-blocking comment refresh, Feed/Shop background refresh, the onboarding folder fix, and the BeautyCamera dialog fix. The standard build includes COCCE TV without TV-specific build-time Dart defines; sign-in, server-side row-level security, and administrator checks remain in place. Earlier releases remain available unchanged.

- Website / download page: **https://cocce-super-app-222ac.web.app**
- Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
- All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases
- Example COCCE TV link: https://cocce-super-app-222ac.web.app/tv/imperium/7431d91f-cc68-45c2-9969-98ec5f929197

---

## Download

Choose the build that matches your device. If you are not sure, use **Universal**.

| Variant | For | Version | Size (MiB) | Download |
| --- | --- | --- | ---: | --- |
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.10 | 105.53 | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.10/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all supported ABIs) | 1.0.10 | 234.96 | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.10/cocce-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM devices | 1.0.10 | 122.97 | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.10/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.10 | 100.43 | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.10/cocce-x86_64.apk) |

Requirements: **Android 7.0 (API 24) or newer**. Package: `com.cocce.cocce_super_app`.

## Verify a download

Expected SHA-256 checksums for the four v1.0.10 APKs:

```text
9b1c39af41e926d73ef9045a10c9488113ab7a70309c2c5c9c3ef4e2b5c90f2f  cocce-arm64-v8a.apk
c23636ca795cc8887d7bf71ef2bc50f7fb375faa6cf62835942a7b1ec1f7314f  cocce-armeabi-v7a.apk
a55eff842837d0b615ad9f77702db926b48a2736d830bc14b50f1393cd90c737  cocce-universal.apk
8931e6b0390cc6c5e5c090becebb4dd7fa6adb993b9c6f4ae84ea7ab192b72cd  cocce-x86_64.apk
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
