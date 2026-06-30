# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## Scaricare l’APK

[**⬇️ Aprire la pagina di download dell’APK**](https://github.com/MateusGavet/GavetRecorder-APK/releases/tag/v1.1.0-beta)

[**🌐 Aprire la guida di installazione**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->

## Ultimo aggiornamento: v1.1.0-beta

- Interfaccia multilingue con rilevamento automatico della lingua Android.
- Richiesta centralizzata dei permessi per fotocamera, microfono, posizione, notifiche, Bluetooth e media.
- Selettore esplicito del dispositivo Bluetooth OBD2, evitando connessioni errate a CAR-KIT o sistemi multimediali.
- Supporto OBD2 migliorato per velocità, RPM e consumo quando veicolo e adattatore lo supportano.
- Editor overlay 9x9 con drag-and-drop e salvataggio persistente.
- Overlay trasparente configurabile per velocità, RPM, mappa, strada, marcia, direzione e consumo.
- Scheda Mappa corretta per associare video, metadati e percorsi GPS corretti.
- Supporto upload Google Drive per video, metadati, percorsi e log.
- Miglioramenti generali a segmenti, metadati, revisione percorsi e stabilità.


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

## Perché usare una dashcam nel veicolo?

Una dashcam aiuta a creare una registrazione visiva affidabile di ciò che accade durante un viaggio. Invece di dipendere solo dalla memoria, dai racconti o da screenshot manuali, il conducente può conservare video organizzati della strada, del percorso e dei dati di guida.

Può essere utile nell’uso quotidiano, consegne, lavoro, viaggi, parcheggio, revisione dei percorsi, test del veicolo e situazioni impreviste nel traffico. Aiuta a documentare incidenti, manovre pericolose, collisioni, condizioni della strada, orario, posizione approssimativa e comportamento del veicolo.

Gavet Recorder trasforma un telefono Android in una dashcam flessibile. Combina registrazione video, percorso GPS, overlay di telemetria configurabile, dati OBD2 Bluetooth e upload opzionale su Google Drive.

Vantaggi principali:

- registra i viaggi in segmenti più piccoli;
- rende più facile trovare un momento specifico;
- aggiunge velocità, percorso, strada, direzione e dati del veicolo al video;
- aiuta a rivedere percorsi di consegna o lavoro;
- aiuta ad analizzare consumo e comportamento di guida;
- salva video, metadati, percorsi e log in cartelle organizzate;
- può caricare file su Google Drive se attivato;
- funziona localmente per impostazione predefinita, senza server proprio.

L’overlay può mostrare velocità, RPM, mappa, nome della strada, marcia stimata, direzione, consumo, consumo medio e km/L. L’editor 9x9 permette di scegliere cosa mostrare e dove posizionarlo.

Quando veicolo e adattatore lo supportano, OBD2 Bluetooth può fornire dati più stabili come velocità, RPM e consumo. GPS e file percorso collegano il video al tragitto effettuato.

Importante: Gavet Recorder aiuta a creare registrazioni video e telemetriche, ma non sostituisce verbali, assicurazioni, perizie o consulenza legale. Usarlo rispettando leggi locali, regole stradali e privacy.

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

Versione pubblica attuale: v1.1.0-beta.

## Novità di v1.1.0-beta

- Overlay di telemetria trasparente e configurabile.
- Editor overlay 9x9 con drag-and-drop.
- Telemetria OBD2 Bluetooth per velocità, RPM e consumo se supportata.
- Marcia stimata da velocità e RPM.
- Upload manuale e automatico su Google Drive.
- Correzione mappa per allineare i segmenti registrati.
- Miglioramenti a metadati, percorsi e log.
