# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## Download the APK

[**⬇️ Open APK download page**](https://github.com/MateusGavet/GavetRecorder-APK/releases/tag/v1.1.0-beta)

[**🌐 Open installation guide**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->

## Background video recorder for Android

GavetRecorder is an Android application designed to record video in the background using a foreground service. It is intended for users who need continuous local video recording, simple manual installation and organized storage on the device.

> **Important:** This APK is distributed outside the Google Play Store. Android may ask you to allow installation from unknown apps before installing it.

## Languages

- [English](README.md)
- [Português](README.pt-BR.md)
- [Español](README.es.md)
- [Français](README.fr.md)
- [Deutsch](README.de.md)
- [Italiano](README.it.md)
- [日本語](README.ja.md)
- [한국어](README.ko.md)
- [中文](README.zh-CN.md)
- [Русский](README.ru.md)
- [العربية](README.ar.md)

## Download the APK

Download the latest APK directly from the button above. After downloading, open the file on your Android device to start the installation.

## Requirements

- Android device compatible with manual APK installation.
- Permission to install apps from unknown sources.
- Camera permission.
- Microphone permission if audio recording is enabled.
- Notification permission to keep the foreground recording service visible.
- Enough free storage space for video files.

## How to install

1. Download the APK using the button at the top of this page.
2. Open the downloaded APK on your Android device.
3. If Android blocks the installation, tap Settings.
4. Allow installation from this source.
5. Return to the installer and tap Install.
6. Open GavetRecorder.
7. Grant the requested permissions.
8. Start recording from inside the app.

## What's new in v1.1.0-beta

- Configurable transparent telemetry overlay.
- 9x9 drag-and-drop overlay editor.
- OBD2 Bluetooth telemetry for speed, RPM and fuel consumption when supported.
- Estimated gear based on speed and RPM.
- Google Drive manual and automatic upload.
- Route review fixes so map segments match recorded videos.
- Improved metadata, route and log storage.

## Permissions used

- Camera: required to record video.
- Microphone: required only when audio recording is enabled.
- Notifications: required to keep the recording service active in the foreground.
- Storage or media access: used to save and access recorded videos.
- Location: used only if GPS, route or telemetry features are enabled.

## Basic usage

- Open the app.
- Choose the desired camera, quality and FPS.
- Start the recording.
- Keep the recording notification active.
- Stop the recording when finished.
- Find the recorded videos in the device storage.

## Where recordings are saved

Recordings are saved locally on the device in the expected folder:

```text
DCIM/GavetRecorder/
└── Videos/
```

## Privacy

GavetRecorder is designed for local recording. Recorded files remain on the device unless the user manually shares, moves or uploads them.

## Troubleshooting

- If the APK does not install, check whether unknown app installation is allowed.
- If recording does not start, verify camera and microphone permissions.
- If background recording stops, disable battery optimization for the app.
- If videos are not visible, check the GavetRecorder folder in the device storage.
- If Android shows a security warning, confirm that the APK came from the official repository.

## Install using ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Current version

v1.1.0-beta includes OBD2 telemetry, a configurable 9x9 overlay editor, transparent overlay layout, Google Drive upload, route review fixes and improved segment metadata.
