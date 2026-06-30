# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## Descargar el APK

[**⬇️ Abrir página de descarga del APK**](https://github.com/MateusGavet/GavetRecorder-APK/releases/tag/v1.1.0-beta)

[**🌐 Abrir guía de instalación**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->

## Actualización más reciente: v1.1.0-beta

- Interfaz multilingüe con detección automática del idioma de Android.
- Solicitud centralizada de permisos para cámara, micrófono, ubicación, notificaciones, Bluetooth y medios.
- Selector explícito de dispositivo Bluetooth para OBD2, evitando conexión incorrecta con CAR-KIT o sistemas multimedia.
- Mejor soporte OBD2 para velocidad, RPM y consumo cuando el vehículo y el adaptador lo permitan.
- Editor de overlay 9x9 con arrastrar/soltar y guardado persistente.
- Overlay transparente configurable para velocidad, RPM, mapa, calle, marcha, dirección y consumo.
- Pestaña Mapa corregida para relacionar videos grabados con metadatos y rutas GPS correctas.
- Soporte de subida a Google Drive para videos, metadatos, rutas y registros.
- Mejoras generales en segmentos, metadatos, revisión de rutas y estabilidad.


## Grabador de video en segundo plano para Android

GavetRecorder es una aplicación Android diseñada para grabar video en segundo plano mediante un servicio en primer plano. Está pensada para usuarios que necesitan grabación local continua, instalación manual sencilla y almacenamiento organizado en el dispositivo.

> **Important:** Este APK se distribuye fuera de Google Play Store. Android puede solicitar permiso para instalar aplicaciones de fuentes desconocidas antes de la instalación.

## Idiomas

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

Descarga el APK más reciente directamente desde el botón superior. Después de descargarlo, abre el archivo en tu dispositivo Android para iniciar la instalación.

## ¿Por qué usar una dashcam en el vehículo?

Una dashcam ayuda a crear un registro visual confiable de lo que ocurre durante un trayecto. En lugar de depender solo de la memoria, relatos o capturas manuales, el conductor puede mantener videos organizados de la carretera, la ruta y datos importantes de conducción.

Puede ser útil para uso diario, entregas, rutas de trabajo, viajes, estacionamiento, revisión de recorridos, pruebas del vehículo y situaciones inesperadas en el tráfico. Ayuda a documentar incidentes, maniobras peligrosas, colisiones, condiciones de la vía, horario, ubicación aproximada y comportamiento del vehículo.

Gavet Recorder convierte un teléfono Android en una dashcam flexible. Combina grabación de video, ruta GPS, overlay de telemetría configurable, datos OBD2 Bluetooth y subida opcional a Google Drive.

Beneficios principales:

- graba viajes en segmentos más pequeños;
- facilita encontrar un momento específico;
- agrega velocidad, ruta, calle, dirección y datos del vehículo al video;
- ayuda a revisar rutas de entrega o trabajo;
- ayuda a analizar consumo de combustible y conducción;
- guarda videos, metadatos, rutas y registros en carpetas organizadas;
- puede subir archivos a Google Drive cuando está activado;
- funciona localmente por defecto, sin depender de un servidor propio.

El overlay puede mostrar velocidad, RPM, mapa, nombre de calle, marcha estimada, dirección, consumo de combustible, consumo medio y km/L. El editor 9x9 permite elegir qué aparece y dónde se ubica cada elemento.

Cuando el vehículo y el adaptador lo permiten, OBD2 Bluetooth puede proporcionar datos más estables como velocidad, RPM y consumo. El GPS y los archivos de ruta conectan el video con el recorrido realizado.

Importante: Gavet Recorder ayuda a crear registros de video y telemetría, pero no reemplaza informes policiales, aseguradoras, peritajes ni asesoría legal. Úselo respetando leyes locales, normas de tránsito y privacidad.

## Requisitos

- Dispositivo Android compatible con instalación manual de APK.
- Permiso para instalar aplicaciones de fuentes desconocidas.
- Permiso de cámara.
- Permiso de micrófono si la grabación con audio está activada.
- Permiso de notificaciones para mantener visible el servicio de grabación en primer plano.
- Espacio libre suficiente para almacenar los videos.

## Cómo instalar

1. Descarga el APK usando el botón superior de esta página.
2. Abre el APK descargado en el dispositivo Android.
3. Si Android bloquea la instalación, toca Configuración.
4. Permite instalar aplicaciones desde esta fuente.
5. Vuelve al instalador y toca Instalar.
6. Abre GavetRecorder.
7. Concede los permisos solicitados.
8. Inicia la grabación desde la aplicación.

## Permisos utilizados

- Cámara: necesaria para grabar video.
- Micrófono: necesario solo cuando la grabación de audio está activada.
- Notificaciones: necesarias para mantener activo el servicio de grabación en primer plano.
- Almacenamiento o acceso a medios: usado para guardar y acceder a videos grabados.
- Ubicación: usada solo si las funciones de GPS, ruta o telemetría están activadas.

## Uso básico

- Abre la aplicación.
- Elige la cámara, calidad y FPS deseados.
- Inicia la grabación.
- Mantén activa la notificación de grabación.
- Detén la grabación al finalizar.
- Encuentra los videos grabados en el almacenamiento del dispositivo.

## Dónde se guardan las grabaciones

Las grabaciones se guardan localmente en el dispositivo, en la carpeta esperada:

```text
DCIM/GavetRecorder/
└── Videos/
```

## Privacidad

GavetRecorder está diseñado para grabación local. Los archivos grabados permanecen en el dispositivo salvo que el usuario los comparta, mueva o suba manualmente.

## Solución de problemas

- Si el APK no se instala, verifica si está permitida la instalación desde fuentes desconocidas.
- Si la grabación no inicia, revisa los permisos de cámara y micrófono.
- Si la grabación en segundo plano se detiene, desactiva la optimización de batería para la app.
- Si los videos no aparecen, revisa la carpeta GavetRecorder en el almacenamiento del dispositivo.
- Si Android muestra una advertencia de seguridad, confirma que el APK proviene del repositorio oficial.

## Instalar usando ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Versión actual

Versión pública actual: v1.1.0-beta.

## Novedades de v1.1.0-beta

- Overlay de telemetría transparente y configurable.
- Editor de overlay 9x9 con arrastrar y soltar.
- Telemetría OBD2 Bluetooth para velocidad, RPM y consumo cuando sea compatible.
- Marcha estimada por velocidad y RPM.
- Subida manual y automática a Google Drive.
- Corrección del mapa para coincidir con los segmentos grabados.
- Mejoras en metadatos, rutas y registros.
