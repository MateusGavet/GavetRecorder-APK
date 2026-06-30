# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## APK herunterladen

[**⬇️ APK-Downloadseite öffnen**](https://github.com/MateusGavet/GavetRecorder-APK/releases/tag/v1.1.0-beta)

[**🌐 Installationsanleitung öffnen**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->

## Videoaufnahme im Hintergrund für Android

GavetRecorder ist eine Android-App zur Videoaufnahme im Hintergrund über einen Vordergrunddienst. Sie richtet sich an Nutzer, die kontinuierliche lokale Aufnahmen, eine einfache manuelle Installation und eine geordnete Speicherung auf dem Gerät benötigen.

> **Important:** Diese APK wird außerhalb des Google Play Store verteilt. Android kann vor der Installation verlangen, dass die Installation aus unbekannten Quellen erlaubt wird.

## Sprachen

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

## APK herunterladen

Laden Sie die neueste APK direkt über die Schaltfläche oben herunter. Öffnen Sie anschließend die Datei auf Ihrem Android-Gerät, um die Installation zu starten.

## Voraussetzungen

- Android-Gerät mit Unterstützung für manuelle APK-Installation.
- Erlaubnis zur Installation von Apps aus unbekannten Quellen.
- Kameraberechtigung.
- Mikrofonberechtigung, wenn Audioaufnahme aktiviert ist.
- Benachrichtigungsberechtigung, damit der Aufnahmedienst im Vordergrund sichtbar bleibt.
- Ausreichend freier Speicherplatz für Videodateien.

## Installation

1. Laden Sie die APK über die Schaltfläche oben auf dieser Seite herunter.
2. Öffnen Sie die heruntergeladene APK auf dem Android-Gerät.
3. Wenn Android die Installation blockiert, tippen Sie auf Einstellungen.
4. Erlauben Sie die Installation aus dieser Quelle.
5. Kehren Sie zum Installationsbildschirm zurück und tippen Sie auf Installieren.
6. Öffnen Sie GavetRecorder.
7. Erteilen Sie die angeforderten Berechtigungen.
8. Starten Sie die Aufnahme in der App.

## Verwendete Berechtigungen

- Kamera: erforderlich für die Videoaufnahme.
- Mikrofon: nur erforderlich, wenn Audioaufnahme aktiviert ist.
- Benachrichtigungen: erforderlich, um den Aufnahmedienst im Vordergrund aktiv zu halten.
- Speicher- oder Medienzugriff: wird zum Speichern und Öffnen der aufgenommenen Videos verwendet.
- Standort: nur verwendet, wenn GPS-, Routen- oder Telemetriefunktionen aktiviert sind.

## Grundlegende Nutzung

- Öffnen Sie die App.
- Wählen Sie Kamera, Qualität und FPS.
- Starten Sie die Aufnahme.
- Lassen Sie die Aufnahmenachricht aktiv.
- Beenden Sie die Aufnahme nach Bedarf.
- Finden Sie die aufgenommenen Videos im Gerätespeicher.

## Speicherort der Aufnahmen

Die Aufnahmen werden lokal auf dem Gerät im vorgesehenen Ordner gespeichert:

```text
DCIM/GavetRecorder/
└── Videos/
```

## Datenschutz

GavetRecorder ist für lokale Aufnahmen konzipiert. Aufgenommene Dateien bleiben auf dem Gerät, sofern der Nutzer sie nicht manuell teilt, verschiebt oder hochlädt.

## Fehlerbehebung

- Wenn die APK nicht installiert wird, prüfen Sie, ob Installationen aus unbekannten Quellen erlaubt sind.
- Wenn die Aufnahme nicht startet, prüfen Sie Kamera- und Mikrofonberechtigungen.
- Wenn die Hintergrundaufnahme stoppt, deaktivieren Sie die Akkuoptimierung für die App.
- Wenn Videos nicht sichtbar sind, prüfen Sie den Ordner GavetRecorder im Gerätespeicher.
- Wenn Android eine Sicherheitswarnung anzeigt, stellen Sie sicher, dass die APK aus dem offiziellen Repository stammt.

## Installation mit ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Aktuelle Version

V16 enthält Unterstützung für eine mehrsprachige Oberfläche und korrigiert übersetzte Ressourcen auf dem Hauptbildschirm, einschließlich Qualität/FPS.
