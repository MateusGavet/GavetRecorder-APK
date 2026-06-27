# GavetRecorder APK

**Android-приложение для фоновой записи видео с организованным локальным хранилищем.**

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

GavetRecorder создан для записи видео в фоновом режиме с использованием foreground service и постоянного уведомления для совместимости с современными версиями Android.

## Основные возможности

- Фоновая запись через Foreground Service.
- Постоянное уведомление во время активной записи.
- Выбор камеры.
- Настройка качества и FPS.
- Запись видео по сегментам.
- Локальное хранение в DCIM/GavetRecorder.
- Структура для видео, карт, маршрутов, логов и метаданных.
- Основа для GPS и телеметрического оверлея.
- Многоязычный интерфейс.

## Ожидаемая структура хранения

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## Обновление V16

Версия V16 добавляет поддержку многоязычного интерфейса и исправляет переводимые ресурсы главного экрана, включая параметр Качество/FPS.

## Сборка debug APK

```bash
./gradlew clean assembleDebug
```

## Установка через ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

Если язык браузера не поддерживается, по умолчанию используется английский.
