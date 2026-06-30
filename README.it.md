# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## Scaricare l’APK

[**⬇️ Aprire la pagina di download dell’APK**](https://github.com/MateusGavet/GavetRecorder-APK/releases/tag/v1.1.0-beta)

[**🌐 Aprire la guida di installazione**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->

## Registratore video in background per Android

GavetRecorder è un’app Android progettata per registrare video in background tramite un servizio in primo piano. È pensata per utenti che hanno bisogno di registrazione locale continua, installazione manuale semplice e archiviazione organizzata sul dispositivo.

> **Important:** Questo APK è distribuito fuori dal Google Play Store. Android potrebbe chiedere di consentire l’installazione da origini sconosciute prima dell’installazione.

## Lingue

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

## Scaricare l’APK

Scarica l’APK più recente direttamente dal pulsante in alto. Dopo il download, apri il file sul dispositivo Android per avviare l’installazione.

## Requisiti

- Dispositivo Android compatibile con installazione manuale di APK.
- Autorizzazione a installare app da origini sconosciute.
- Autorizzazione fotocamera.
- Autorizzazione microfono se la registrazione audio è attiva.
- Autorizzazione notifiche per mantenere visibile il servizio di registrazione in primo piano.
- Spazio libero sufficiente per i file video.

## Come installare

1. Scarica l’APK usando il pulsante in alto in questa pagina.
2. Apri l’APK scaricato sul dispositivo Android.
3. Se Android blocca l’installazione, tocca Impostazioni.
4. Consenti l’installazione da questa origine.
5. Torna all’installazione e tocca Installa.
6. Apri GavetRecorder.
7. Concedi le autorizzazioni richieste.
8. Avvia la registrazione dall’app.

## Autorizzazioni utilizzate

- Fotocamera: necessaria per registrare video.
- Microfono: necessario solo quando la registrazione audio è attiva.
- Notifiche: necessarie per mantenere attivo il servizio di registrazione in primo piano.
- Archiviazione o accesso ai media: usato per salvare e accedere ai video registrati.
- Posizione: usata solo se sono attive funzioni GPS, percorso o telemetria.

## Uso di base

- Apri l’app.
- Scegli fotocamera, qualità e FPS desiderati.
- Avvia la registrazione.
- Mantieni attiva la notifica di registrazione.
- Ferma la registrazione quando hai finito.
- Trova i video registrati nell’archiviazione del dispositivo.

## Dove vengono salvate le registrazioni

Le registrazioni vengono salvate localmente sul dispositivo, nella cartella prevista:

```text
DCIM/GavetRecorder/
└── Videos/
```

## Privacy

GavetRecorder è progettato per la registrazione locale. I file registrati restano sul dispositivo salvo condivisione, spostamento o caricamento manuale da parte dell’utente.

## Risoluzione dei problemi

- Se l’APK non si installa, verifica che l’installazione da origini sconosciute sia consentita.
- Se la registrazione non parte, controlla le autorizzazioni di fotocamera e microfono.
- Se la registrazione in background si interrompe, disattiva l’ottimizzazione batteria per l’app.
- Se i video non sono visibili, controlla la cartella GavetRecorder nella memoria del dispositivo.
- Se Android mostra un avviso di sicurezza, conferma che l’APK provenga dal repository ufficiale.

## Installare con ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Versione attuale

La V16 include il supporto all’interfaccia multilingue e corregge risorse tradotte usate nella schermata principale, inclusa Qualità/FPS.
