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


## How Gavet Recorder helps

Gavet Recorder is designed to turn an Android phone into a vehicle recording system. It combines video recording, GPS route tracking, visual overlays, OBD2 telemetry and optional Google Drive upload.

### Segment recording

The app records in segments, making it easier to find a specific part of a trip. Instead of creating one huge video file, recordings are split into smaller files that are easier to review, copy or share.

Benefits:

- easier to find a specific moment;
- lower risk of losing one very long recording;
- better file organization;
- easier sharing of only the needed segment.

### Telemetry overlay

The overlay can show useful information directly on top of the recorded video, helping explain the context of the trip.

Available overlay items:

- speed;
- RPM;
- map;
- street name;
- estimated gear;
- direction;
- fuel consumption;
- average consumption;
- km/L.

The 9x9 overlay editor lets the user choose what appears and where each item is placed. The final overlay is transparent for a cleaner and more professional recording.

### GPS, map and route

Gavet Recorder can save GPS points during recording. This allows later route review and helps connect the video with the approximate location.

Useful for:

- delivery drivers;
- rideshare drivers;
- travel;
- vehicle testing;
- route review;
- checking completed paths;
- analyzing where something happened.

### Street name and direction

The app can show street name and driving direction, making it easier to identify where a recording happened.

### Bluetooth OBD2

When supported by the vehicle and adapter, Gavet Recorder can read OBD2 Bluetooth data such as speed, RPM and fuel consumption.

Possible data:

- OBD2 speed;
- RPM;
- instant fuel consumption;
- average consumption;
- km/L;
- fuel level, when supported;
- estimated gear based on speed and RPM.

> OBD2 data depends on the adapter, the vehicle and the PIDs exposed by the ECU. Not every vehicle provides every value.

### Optional Google Drive upload

Google Drive upload helps keep copies of videos, metadata, routes and logs. This is useful if the phone is lost, damaged or runs out of space.

Available modes:

- manual upload;
- automatic upload;
- Wi-Fi only option;
- configurable upload for videos, metadata, routes and logs.

### Metadata, routes and logs

Besides video, the app organizes auxiliary files with segment information. This helps with review, diagnostics and history.

Generated files:

- videos in `DCIM/GavetRecorder/Videos`;
- metadata in `Documents/GavetRecorder/Metadados`;
- routes in `Documents/GavetRecorder/Rotas`;
- logs in `Documents/GavetRecorder/Logs`.

### Local privacy and user control

Gavet Recorder saves everything locally by default. The user decides when to record, which data to enable and whether to upload anything to Google Drive.

The app does not need its own server to work as a local recorder.

## Practical everyday benefits

Using Gavet Recorder as a dashcam can help with:

- personal safety;
- trip organization;
- delivery records;
- route review;
- time and route history;
- fuel consumption analysis;
- vehicle behavior tracking;
- unexpected traffic situations.

For users who already have an available Android phone, Gavet Recorder can be an accessible alternative before buying a dedicated dashcam.

## Why use a dashcam in your vehicle?

A dashcam helps create a reliable visual record of what happens during a trip. Instead of depending only on memory, verbal reports or manual screenshots, the driver can keep organized video evidence of the road, the route and important driving information.

A dashcam can be useful for daily driving, deliveries, work routes, travel, parking situations, route review, vehicle testing and unexpected traffic events. It can help document incidents, dangerous maneuvers, collisions, road conditions, time, approximate location and vehicle behavior.

Gavet Recorder turns an Android phone into a flexible dashcam-style recorder. It combines video recording, GPS route tracking, configurable telemetry overlay, OBD2 Bluetooth data and optional Google Drive upload.

Main benefits:

- records trips in smaller video segments;
- makes it easier to find a specific moment;
- adds speed, route, street, direction and vehicle data to the recording;
- helps review delivery or work routes;
- helps analyze fuel consumption and driving behavior;
- saves videos, metadata, routes and logs in organized folders;
- can upload files to Google Drive when enabled;
- works locally by default, without depending on a private server.

The telemetry overlay can show speed, RPM, map, street name, estimated gear, direction, fuel consumption, average consumption and km/L. The 9x9 overlay editor lets the user choose what appears and where each item is placed.

When supported by the vehicle and adapter, OBD2 Bluetooth can provide more stable vehicle data such as speed, RPM and fuel consumption. GPS and route files help connect the video with the path traveled.

Important: Gavet Recorder helps create video and telemetry records, but it does not replace police reports, insurance procedures, expert analysis or legal advice. Use it according to local laws, traffic rules and privacy regulations.

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
