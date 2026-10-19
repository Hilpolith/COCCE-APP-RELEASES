# COCCE — Android releases

![COCCE 1.0.22](https://img.shields.io/badge/COCCE-1.0.22-ED0747?style=for-the-badge) ![Signed Android release](https://img.shields.io/badge/Android-Signed%20release-16A34A?style=for-the-badge)

### ![A warmer welcome](https://img.shields.io/badge/A%20warmer%20welcome-ED0747?style=flat-square)
Meet animated characters as you sign in, create an account, recover a password and get started. Onboarding adds gradient progress and gentle feedback, with reduced-motion support.

### ![Smoother video recovery](https://img.shields.io/badge/Smoother%20video%20recovery-665BCA?style=flat-square)
Your visible cached video stays in place while fresh recommendations arrive. Failed playback can retry with a fresh source and recover the position of the same video.

### ![More reliable offline chats](https://img.shields.io/badge/More%20reliable%20offline%20chats-087F8C?style=flat-square)
Saved chats and groups can appear without waiting for a profile. Cached lists survive refresh errors and refresh on reconnection, with separate caches for each account.

All 24 app languages are preserved. Requires Android 7.0 or newer.

## Choose your download
**ARM64** is recommended for most newer phones. Choose **Universal** if you are unsure; it is larger. **ARMv7** is for older 32-bit ARM devices; **x86_64** is for compatible emulators/Intel devices.

| Build | Size (MiB) | Download |
| --- | ---: | --- |
| arm64 | 106.32 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.22/cocce-1.0.22-arm64.apk) |
| universal | 236.52 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.22/cocce-1.0.22-universal.apk) |
| armv7 | 123.82 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.22/cocce-1.0.22-armv7.apk) |
| x86_64 | 101.22 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.22/cocce-1.0.22-x86_64.apk) |

## Validation and important limits
All 41 combined app regression tests passed. All four APKs passed archive integrity, Android signing verification and signing-certificate matching against the trusted website association. Package: com.cocce.cocce_super_app.

No physical-device test was run. Native video playback and transition audio remain unverified.

Built from private source base `39da95515f70156c172de81d8e4a7fec004168b1` plus local app changes. App changes remain uncommitted and unpushed. Campaign automation is not part of this release, and no production campaign data or functions were changed.

[Download website](https://cocce-super-app-222ac.web.app/) · [Investor information](https://cocce.vercel.app/) · [All earlier releases](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases)

Earlier versions and their assets remain available unchanged. Download RELEASE_NOTES.html for the standalone colored-text edition, or SHA256SUMS.txt to verify files.

## SHA-256
```text
94ae54d426d7657a8a947998e42fc9930dbaf3c44f4bf2807181598dc777ae04  cocce-1.0.22-arm64.apk
563f6293851b2028bd1ea2f3add9b1e1a27e83cb9d2418c71f0d788af79deb4b  cocce-1.0.22-universal.apk
350dc125a01b35d62e8527948dfd50a58224584a66217ddc4cb2eaeaa7dd79d7  cocce-1.0.22-armv7.apk
a3aee75e58fcb878c5b4b41776b7d716d3e67ba73774e9321490a34b6884cd9f  cocce-1.0.22-x86_64.apk
```

---

## Share a COCCE link

Shared COCCE links use `https://cocce-super-app-222ac.web.app/<type>/<id>`. COCCE TV schedule links use `https://cocce-super-app-222ac.web.app/tv/<channel-slug>/<schedule-id>`; the example above opens a TV schedule when COCCE is installed and otherwise shows the web download page.

Supported link types include `video`, `feed`, `product`, `profile`, `creator`, `shop`, `business` and `tv`.

## Install

1. Download the build for your device.
2. Open it. If Android asks, allow **Install unknown apps** for your browser or file manager. This permission is only needed for the install.
3. Tap **Install**. COCCE will appear in your app list.

## About

COCCE is owned and operated by HILPOLITH PHILLIP ROTHSCHILD. For support or privacy requests, email **coccesuperapp@gmail.com**.

Source code is **not** published here. Please do not open issues asking for it.

All downloads use the established COCCE signing certificate recognized by the website Android App Links association.
