# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## Télécharger l’APK

[**⬇️ Ouvrir la page de téléchargement de l’APK**](https://github.com/MateusGavet/GavetRecorder-APK/releases/tag/v1.1.0-beta)

[**🌐 Ouvrir le guide d’installation**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->

## Enregistreur vidéo en arrière-plan pour Android

GavetRecorder est une application Android conçue pour enregistrer des vidéos en arrière-plan à l’aide d’un service de premier plan. Elle s’adresse aux utilisateurs qui ont besoin d’un enregistrement local continu, d’une installation manuelle simple et d’un stockage organisé sur l’appareil.

> **Important:** Cet APK est distribué en dehors du Google Play Store. Android peut demander l’autorisation d’installer des applications provenant de sources inconnues avant l’installation.

## Langues

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

## Télécharger l’APK

Téléchargez le dernier APK directement depuis le bouton en haut de cette page. Après le téléchargement, ouvrez le fichier sur votre appareil Android pour lancer l’installation.

## Prérequis

- Appareil Android compatible avec l’installation manuelle d’APK.
- Autorisation d’installer des applications provenant de sources inconnues.
- Autorisation d’accès à la caméra.
- Autorisation d’accès au microphone si l’enregistrement audio est activé.
- Autorisation de notifications pour garder visible le service d’enregistrement au premier plan.
- Espace de stockage suffisant pour les fichiers vidéo.

## Comment installer

1. Téléchargez l’APK avec le bouton en haut de cette page.
2. Ouvrez l’APK téléchargé sur votre appareil Android.
3. Si Android bloque l’installation, appuyez sur Paramètres.
4. Autorisez l’installation depuis cette source.
5. Revenez à l’installateur et appuyez sur Installer.
6. Ouvrez GavetRecorder.
7. Accordez les autorisations demandées.
8. Démarrez l’enregistrement depuis l’application.

## Autorisations utilisées

- Caméra : nécessaire pour enregistrer la vidéo.
- Microphone : nécessaire uniquement lorsque l’enregistrement audio est activé.
- Notifications : nécessaires pour maintenir le service d’enregistrement actif au premier plan.
- Stockage ou accès aux médias : utilisé pour enregistrer et accéder aux vidéos.
- Localisation : utilisée uniquement si les fonctions GPS, itinéraire ou télémétrie sont activées.

## Utilisation de base

- Ouvrez l’application.
- Choisissez la caméra, la qualité et les FPS souhaités.
- Démarrez l’enregistrement.
- Gardez la notification d’enregistrement active.
- Arrêtez l’enregistrement lorsque vous avez terminé.
- Retrouvez les vidéos enregistrées dans le stockage de l’appareil.

## Où les enregistrements sont sauvegardés

Les enregistrements sont sauvegardés localement sur l’appareil, dans le dossier prévu :

```text
DCIM/GavetRecorder/
└── Videos/
```

## Confidentialité

GavetRecorder est conçu pour l’enregistrement local. Les fichiers enregistrés restent sur l’appareil sauf si l’utilisateur les partage, les déplace ou les téléverse manuellement.

## Dépannage

- Si l’APK ne s’installe pas, vérifiez que l’installation depuis des sources inconnues est autorisée.
- Si l’enregistrement ne démarre pas, vérifiez les autorisations caméra et microphone.
- Si l’enregistrement en arrière-plan s’arrête, désactivez l’optimisation de batterie pour l’application.
- Si les vidéos ne sont pas visibles, vérifiez le dossier GavetRecorder dans le stockage de l’appareil.
- Si Android affiche un avertissement de sécurité, confirmez que l’APK provient du dépôt officiel.

## Installer avec ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Version actuelle

La V16 ajoute la prise en charge de l’interface multilingue et corrige les ressources traduites utilisées sur l’écran principal, y compris Qualité/FPS.
