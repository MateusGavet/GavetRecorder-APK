# GavetRecorder APK

**App Android per registrazione video in background con archiviazione locale organizzata.**

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

GavetRecorder è stato creato per registrare video in background usando un servizio in primo piano, mantenendo la compatibilità con le versioni recenti di Android tramite una notifica persistente.

## Funzionalità principali

- Registrazione in background con Foreground Service.
- Notifica persistente durante la registrazione.
- Selezione della fotocamera.
- Configurazione di qualità e FPS.
- Registrazione video a segmenti.
- Archiviazione locale organizzata in DCIM/GavetRecorder.
- Struttura preparata per video, mappe, percorsi, log e metadati.
- Base preparata per overlay GPS e telemetria.
- Interfaccia multilingue.

## Struttura di archiviazione prevista

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## Aggiornamento V16

La versione V16 aggiunge il supporto all’interfaccia multilingue e corregge le risorse traducibili usate dalla schermata principale, inclusa l’opzione Qualità/FPS.

## Compilare APK debug

```bash
./gradlew clean assembleDebug
```

## Installare con ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

Se la lingua del browser non è supportata, viene usato l’inglese come lingua predefinita.
