# COCCE — Android releases

![COCCE 1.0.24](https://img.shields.io/badge/COCCE-1.0.24-ED0747?style=for-the-badge) ![Signed Android release](https://img.shields.io/badge/Android-Signed%20release-16A34A?style=for-the-badge)

### ![A softer selection](https://img.shields.io/badge/A%20softer%20selection-087F8C?style=flat-square)
The selected onboarding photo now appears circular and centered, with a fitting crop.

All 24 app languages are preserved. Requires Android 7.0 or newer.

## Choose your download
ARM64 is recommended for most newer phones. Choose Universal if unsure; ARMv7 is for older 32-bit ARM devices; x86_64 is for compatible emulators/Intel devices.

| Build | Size (MiB) | Download |
| --- | ---: | --- |
| arm64 | 106.33 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.24/cocce-1.0.24-arm64.apk) |
| universal | 236.56 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.24/cocce-1.0.24-universal.apk) |
| armv7 | 123.84 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.24/cocce-1.0.24-armv7.apk) |
| x86_64 | 101.24 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.24/cocce-1.0.24-x86_64.apk) |

## Validation and important limits
All 320 Flutter regression tests passed, including circular photo controls at narrow and large sizes, light/dark themes, LTR/RTL layouts, and centered portrait/landscape crop geometry. Four signed APK variants passed version, ABI, certificate, ZIP-integrity and SHA-256 verification.

No physical-device or live-account UI test was performed. Static analysis found no issues in the three touched Dart files; 149 pre-existing warning/info findings remain outside this fix. Existing onboarding tests explicitly record eight known city-controller disposal errors. No Supabase, signing-credential or service-account changes were made.

[Download website](https://cocce-super-app-222ac.web.app/) · [Investor information](https://cocce.vercel.app/) · [All earlier releases](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases)

Earlier versions and their assets remain available unchanged. Download RELEASE_NOTES.html for colored notes, or SHA256SUMS.txt to verify files.

## SHA-256
```text
a5816d65427f231fb3c6a5b2e4da87f1340ab10aa2a6e8e549f79f152d650b3d  cocce-1.0.24-arm64.apk
5de98865caa09d8ef7ca87dc4faba21d4729879df74d48e32a1653a4e6472192  cocce-1.0.24-universal.apk
143575df5d736d7cd9363b4fa9f7e27bcc5269ee3ad9a21f0a3425a4d5686f4b  cocce-1.0.24-armv7.apk
0ce2ca7fcc0c2146200c5bbb0072696a1043edca2dedb1943e5bf1da0619c797  cocce-1.0.24-x86_64.apk
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

All downloads use the established COCCE signing certificate recognized by the website Android App Links association.

All downloads use the established COCCE signing certificate recognized by the website Android App Links association.
