# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## Download direto

[**⬇️ 最新 APK をダウンロード**](https://github.com/MateusGavet/GavetRecorder-APK/raw/main/dist/GavetRecorder-v16-debug.apk)

[**🌐 インストールガイドを開く**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->


## Background video recorder for Android

GavetRecorder is an Android application designed to record video in the background using a foreground service. It is intended for users who need continuous, local video recording with a simple installation process and organized file storage.

> **Important:** This APK is distributed outside the Google Play Store. To install it, Android may ask you to allow installation from unknown apps.

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

Download the latest APK file from the repository release or from the APK file provided in the project.

## Requirements

- Android device compatible with manual APK installation.
- Permission to install apps from unknown sources.
- Camera permission.
- Microphone permission, if audio recording is enabled.
- Location permission, if GPS or route data is used.
- Enough free storage space for video files.

## How to install

1. Download the APK file to your Android device.
2. Open the APK file using the file manager or browser download notification.
3. If Android blocks the installation, tap Settings and allow installation from this source.
4. Return to the installer and tap Install.
5. Open GavetRecorder after installation.
6. Grant the requested permissions when Android asks.
7. Start recording from inside the app.

## Permissions used

- Camera: required to record video.
- Microphone: required only when audio recording is enabled.
- Location: used only for GPS, route or telemetry features when available.
- Notifications: required to keep the foreground recording service visible.
- Storage or media access: used to save and access recorded files.

## Basic usage

- Open the app.
- Choose the desired camera, quality and FPS options.
- Start the recording.
- Keep the foreground notification active while recording.
- Stop the recording when finished.
- Access the recorded videos in the device storage.

## Where recordings are saved

Recordings are saved locally on the device. The expected folder is:

```text
DCIM/GavetRecorder/
└── Videos/
```

## Privacy

GavetRecorder is designed for local recording. Recorded files remain on the device unless the user manually shares, moves or uploads them.

## Troubleshooting

- If the APK does not install, check whether installation from unknown apps is allowed.
- If recording does not start, verify camera and microphone permissions.
- If background recording stops, disable battery optimization for the app.
- If videos are not visible, check the app folder in the device storage.
- If Android shows a security warning, confirm that the APK came from the official project repository.

## Install using ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Current version

V16 includes multilingual interface support and fixes translated resources used in the main screen, including Quality/FPS.

## GitHub Pages

The web documentation can automatically detect the browser language through `docs/index.html`.
