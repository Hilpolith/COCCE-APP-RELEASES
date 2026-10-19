# COCCE — Android releases

![COCCE 1.0.23](https://img.shields.io/badge/COCCE-1.0.23-ED0747?style=for-the-badge) ![Signed Android release](https://img.shields.io/badge/Android-Signed%20release-16A34A?style=for-the-badge)

### ![Real view counts](https://img.shields.io/badge/Real%20view%20counts-665BCA?style=flat-square)
Profile grids now show real video and product view counts.

### ![A softer selection](https://img.shields.io/badge/A%20softer%20selection-087F8C?style=flat-square)
The selected onboarding image now uses a squircle shape.

All 24 app languages are preserved. Requires Android 7.0 or newer.

## Choose your download
ARM64 is recommended for most newer phones. Choose Universal if unsure; ARMv7 is for older 32-bit ARM devices; x86_64 is for compatible emulators/Intel devices.

| Build | Size (MiB) | Download |
| --- | ---: | --- |
| arm64 | 106.33 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.23/cocce-1.0.23-arm64.apk) |
| universal | 236.55 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.23/cocce-1.0.23-universal.apk) |
| armv7 | 123.84 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.23/cocce-1.0.23-armv7.apk) |
| x86_64 | 101.23 | [Download APK](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases/download/v1.0.23/cocce-1.0.23-x86_64.apk) |

## Validation and important limits
All 310 Flutter regression tests passed, including exact count queries, zero/error handling, profile-tab count refreshes without resetting loaded items, stale-response protection, and the selected-photo squircle preview. Four signed APKs passed version, ABI, signature, ZIP-integrity and SHA-256 verification.

No physical-device or live-account UI test was performed. Static analysis reports no errors; 149 existing warning/info findings remain outside this fix. Existing onboarding tests explicitly record eight known city-controller disposal errors. No Supabase or service-account changes were made.

[Download website](https://cocce-super-app-222ac.web.app/) · [Investor information](https://cocce.vercel.app/) · [All earlier releases](https://github.com/Hilpolith/COCCE-APP-RELEASES/releases)

Earlier versions and their assets remain available unchanged. Download RELEASE_NOTES.html for colored notes, or SHA256SUMS.txt to verify files.

## SHA-256
```text
7ba0adb73952f10756fa9c20ac1b3a993ca143dc03156798effe3884ea08143a  cocce-1.0.23-arm64.apk
97f99c33dd0c737c623ed46ff5c443e0b128be691112d0de68a609e89e254f4f  cocce-1.0.23-universal.apk
ba0348c2a5eaf886c8f7ac26b6d8501c1fb7657e7f2135766c75a3b7210f40ed  cocce-1.0.23-armv7.apk
a39e7f9127c8286d5cfa856c8c7ee4ff408f4e4713b40a43662c5a692269b162  cocce-1.0.23-x86_64.apk
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
