# COCCE — Android releases

Public **APK distribution** for **COCCE** (Create, Share, Shop & Earn).

This repository intentionally contains **no source code**. The APKs are built from the private COCCE source tree and signed with the COCCE release key.

Latest release: **COCCE 1.0.11** (`v1.0.11`), built from source commit `313b7c7220c003efec11fe09d17474ed097ab06f`. This release advances Feed and Shop through persistent unseen IDs in ORIGIN-ranked candidate batches after a long resume, app reopen, or pull refresh; Shop evaluates three ranked pages while continuing to show one visible page. During a live TV airing, presenter credits and the program mentions list are displayed separately. The previous v1.0.10 cache-first improvements remain: valid cached Feed and Shop items load immediately while the existing ORIGIN-ranked server refresh continues; an empty server response preserves the valid cache, refreshed candidates replace stale cache-only entries, and first-item rotation covers up to three valid candidates on later launches. The v1.0.9 fixes also remain, including multi-presenter rendering, non-blocking comment refresh, Feed/Shop background refresh, the onboarding folder fix, and the BeautyCamera dialog fix. The standard build includes COCCE TV without TV-specific build-time Dart defines; sign-in, server-side row-level security, and administrator checks remain in place. Earlier releases remain available unchanged.
- Website / download page: **https://cocce-super-app-222ac.web.app**
- Privacy policy: **https://cocce-super-app-222ac.web.app/privacy-policy.html**
- All releases: https://github.com/Hilpolith/COCCE-APP-RELEASES/releases
- Example COCCE TV link: https://cocce-super-app-222ac.web.app/tv/imperium/7431d91f-cc68-45c2-9969-98ec5f929197

---

## Download

Choose the build that matches your device. If you are not sure, use **Universal**.

| Variant | For | Version | Version code | Size (MiB) | Download |
| --- | --- | ---: | ---: | ---: | --- |
| **ARM64** (recommended) | 64-bit Android phones/tablets, most devices since 2017 | 1.0.11 | 2013 | 105.54 | [`cocce-arm64-v8a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.11/cocce-arm64-v8a.apk) |
| **Universal** | Any Android device (contains all supported ABIs) | 1.0.11 | 13 | 234.97 | [`cocce-universal.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.11/cocce-universal.apk) |
| **ARMv7** (32-bit) | Older 32-bit ARM devices | 1.0.11 | 1013 | 122.97 | [`cocce-armeabi-v7a.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.11/cocce-armeabi-v7a.apk) |
| **x86_64** | Emulators and Intel-based devices | 1.0.11 | 4013 | 100.44 | [`cocce-x86_64.apk`](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.11/cocce-x86_64.apk) |

Requirements: **Android 7.0 (API 24) or newer**. Package: `com.cocce.cocce_super_app`.

## Verify a download

Expected SHA-256 checksums for the four v1.0.11 APKs:

```text
2e865089c1c3e2e3626165f5ced3829d8a29df4d4ae4c956119c181dfc3ef183  cocce-arm64-v8a.apk
3eee300386fa4dc74f60637671b28a0fab69b9ad19e3100319697ba57b93627c  cocce-armeabi-v7a.apk
c3eda5956886b07892d7c6a636e91b9f6d79e6d3e37021aa902df9becc32bfd1  cocce-universal.apk
ed3c78917ee80451b4264903165c43e2a38e247adf140b23b8b4bcb979557037  cocce-x86_64.apk
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
