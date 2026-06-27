# GavetRecorder APK

**Application Android pour l’enregistrement vidéo en arrière-plan avec stockage local organisé.**

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

GavetRecorder a été créé pour enregistrer des vidéos en arrière-plan à l’aide d’un service de premier plan, tout en restant compatible avec les versions récentes d’Android grâce à une notification persistante.

## Fonctionnalités principales

- Enregistrement en arrière-plan avec Foreground Service.
- Notification persistante pendant l’enregistrement.
- Sélection de la caméra.
- Configuration de la qualité et des FPS.
- Enregistrement vidéo par segments.
- Stockage local organisé dans DCIM/GavetRecorder.
- Structure prévue pour vidéos, cartes, itinéraires, journaux et métadonnées.
- Base prévue pour overlay GPS et télémétrie.
- Interface multilingue.

## Structure de stockage attendue

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## Mise à jour V16

La version V16 ajoute la prise en charge d’une interface multilingue et corrige les ressources traduisibles utilisées par l’écran principal, y compris l’option Qualité/FPS.

## Compiler l’APK debug

```bash
./gradlew clean assembleDebug
```

## Installer avec ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

Si la langue du navigateur n’est pas prise en charge, l’anglais est utilisé par défaut.
