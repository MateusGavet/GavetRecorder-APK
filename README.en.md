# GavetRecorder APK

**Android app for background video recording with organized local storage.**

## 🌐 Languages

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

> Automatic browser language detection is available through GitHub Pages using `docs/index.html`.

## Objective

GavetRecorder was created to record video in the background using a foreground service, keeping compatibility with modern Android versions through a persistent notification.

## Main features

- Background recording using Foreground Service.
- Persistent notification while recording is active.
- Camera selection.
- Quality and FPS configuration.
- Segmented video recording.
- Local storage organized in DCIM/GavetRecorder.
- Structure prepared for videos, maps, routes, logs and metadata.
- Base prepared for GPS and telemetry overlay.
- Multilingual interface.

## Expected storage structure

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## V16 update

Version V16 adds multilingual interface support and fixes translatable resources used by the main screen, including the Quality/FPS option.

## Build debug APK

```bash
./gradlew clean assembleDebug
```

## Install with ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

If your browser language is not supported, English is used as the default language.
