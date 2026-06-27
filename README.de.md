# GavetRecorder APK

**Android-App für Videoaufnahmen im Hintergrund mit geordneter lokaler Speicherung.**

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

## Objetivo

GavetRecorder wurde entwickelt, um Videos im Hintergrund über einen Vordergrunddienst aufzunehmen und durch eine permanente Benachrichtigung mit aktuellen Android-Versionen kompatibel zu bleiben.

## Hauptfunktionen

- Hintergrundaufnahme mit Foreground Service.
- Permanente Benachrichtigung während der aktiven Aufnahme.
- Kameraauswahl.
- Konfiguration von Qualität und FPS.
- Segmentierte Videoaufnahme.
- Lokale Speicherung in DCIM/GavetRecorder.
- Struktur für Videos, Karten, Routen, Logs und Metadaten vorbereitet.
- Basis für GPS- und Telemetrie-Overlay vorbereitet.
- Mehrsprachige Oberfläche.

## Erwartete Speicherstruktur

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## V16-Aktualisierung

Version V16 fügt Unterstützung für eine mehrsprachige Oberfläche hinzu und korrigiert übersetzbare Ressourcen des Hauptbildschirms, einschließlich der Option Qualität/FPS.

## Debug-APK erstellen

```bash
./gradlew clean assembleDebug
```

## Mit ADB installieren

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

Wenn die Browsersprache nicht unterstützt wird, wird Englisch als Standardsprache verwendet.
