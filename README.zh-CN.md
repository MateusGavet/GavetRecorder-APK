# GavetRecorder APK

**用于后台视频录制并带有有序本地存储的 Android 应用。**

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

GavetRecorder 通过前台服务在后台录制视频，并使用持久通知来保持与新版 Android 的兼容性。

## 主要功能

- 使用 Foreground Service 进行后台录制。
- 录制时显示持久通知。
- 摄像头选择。
- 质量和 FPS 配置。
- 分段视频录制。
- 本地文件存储在 DCIM/GavetRecorder。
- 为视频、地图、路线、日志和元数据准备的结构。
- 为 GPS 和遥测叠加层准备的基础。
- 多语言界面。

## 预期存储结构

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## V16 更新

V16 添加了多语言界面支持，并修复了主界面使用的可翻译资源，包括质量/FPS 选项。

## 构建 Debug APK

```bash
./gradlew clean assembleDebug
```

## 使用 ADB 安装

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

如果浏览器语言不受支持，则默认使用英语。
