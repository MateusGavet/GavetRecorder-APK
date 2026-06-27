# GavetRecorder APK

**Aplicación Android para grabación de video en segundo plano con almacenamiento local organizado.**

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

GavetRecorder fue creado para grabar video en segundo plano usando un servicio en primer plano, manteniendo compatibilidad con versiones recientes de Android mediante una notificación persistente.

## Funciones principales

- Grabación en segundo plano usando Foreground Service.
- Notificación persistente mientras la grabación está activa.
- Selección de cámara.
- Configuración de calidad y FPS.
- Grabación de video por segmentos.
- Almacenamiento local organizado en DCIM/GavetRecorder.
- Estructura preparada para videos, mapas, rutas, registros y metadatos.
- Base preparada para superposición de GPS y telemetría.
- Interfaz multilingüe.

## Estructura de almacenamiento esperada

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## Actualización V16

La versión V16 añade soporte de interfaz multilingüe y corrige recursos traducibles usados por la pantalla principal, incluida la opción Calidad/FPS.

## Compilar APK debug

```bash
./gradlew clean assembleDebug
```

## Instalar con ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

Si el idioma del navegador no es compatible, se usará inglés como idioma predeterminado.
