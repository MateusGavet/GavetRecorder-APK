# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## Download direto

[**⬇️ Descargar APK más reciente**](https://github.com/MateusGavet/GavetRecorder-APK/raw/main/dist/GavetRecorder-v16-debug.apk)

[**🌐 Abrir guía de instalación**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->


## Grabador de video en segundo plano para Android

GavetRecorder es una aplicación Android diseñada para grabar video en segundo plano mediante un servicio en primer plano. Está pensada para usuarios que necesitan grabación continua, almacenamiento local organizado y un proceso sencillo de instalación por APK.

> **Important:** Este APK se distribuye fuera de Google Play Store. Para instalarlo, Android puede solicitar permitir la instalación desde fuentes desconocidas.

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

## Descargar el APK

Descarga el archivo APK más reciente desde la release del repositorio o desde el archivo APK disponible en el proyecto.

## Requisitos

- Dispositivo Android compatible con instalación manual de APK.
- Permiso para instalar aplicaciones de fuentes desconocidas.
- Permiso de cámara.
- Permiso de micrófono si la grabación de audio está activada.
- Permiso de ubicación si se usan GPS o rutas.
- Espacio libre suficiente para guardar videos.

## Cómo instalar

1. Descarga el archivo APK en el dispositivo Android.
2. Abre el APK desde el administrador de archivos o desde la notificación de descarga.
3. Si Android bloquea la instalación, entra en Configuración y permite instalar desde esta fuente.
4. Vuelve al instalador y toca Instalar.
5. Abre GavetRecorder después de la instalación.
6. Concede los permisos solicitados por Android.
7. Inicia la grabación desde la aplicación.

## Permisos utilizados

- Cámara: necesaria para grabar video.
- Micrófono: necesario solo cuando el audio está activado.
- Ubicación: usada solo para GPS, rutas o telemetría cuando esté disponible.
- Notificaciones: necesarias para mantener visible el servicio en primer plano.
- Almacenamiento o acceso a medios: usado para guardar y acceder a videos.

## Uso básico

- Abre la aplicación.
- Elige la cámara, calidad y FPS deseados.
- Inicia la grabación.
- Mantén activa la notificación mientras la grabación esté en curso.
- Detén la grabación al finalizar.
- Accede a los videos guardados en el almacenamiento del dispositivo.

## Dónde se guardan las grabaciones

Las grabaciones se guardan localmente en el dispositivo. La carpeta esperada es:

```text
DCIM/GavetRecorder/
└── Videos/
```

## Privacidad

GavetRecorder está diseñado para grabación local. Los archivos permanecen en el dispositivo salvo que el usuario los comparta, mueva o suba manualmente.

## Solución de problemas

- Si el APK no se instala, verifica la instalación desde fuentes desconocidas.
- Si la grabación no inicia, revisa los permisos de cámara y micrófono.
- Si la grabación en segundo plano se detiene, desactiva la optimización de batería para la app.
- Si los videos no aparecen, revisa la carpeta de la aplicación en el almacenamiento.
- Si Android muestra una advertencia de seguridad, confirma que el APK proviene del repositorio oficial.

## Instalar usando ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Versión actual

La V16 incluye soporte de interfaz multilingüe y corrige recursos traducidos usados en la pantalla principal, incluida la opción Calidad/FPS.

## GitHub Pages

The web documentation can automatically detect the browser language through `docs/index.html`.
