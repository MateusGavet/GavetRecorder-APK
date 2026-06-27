# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## 下载 APK

[**⬇️ 下载最新 APK**](https://github.com/MateusGavet/GavetRecorder-APK/raw/main/dist/GavetRecorder-v16-debug.apk)

[**🌐 打开安装指南**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->

## 适用于 Android 的后台视频录制应用

GavetRecorder 是一款 Android 应用，通过前台服务在后台录制视频。它适合需要连续本地录制、简单手动安装以及在设备上有序保存文件的用户。

> **Important:** 此 APK 在 Google Play 商店之外分发。安装前，Android 可能会要求允许安装未知来源的应用。

## 语言

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

## 下载 APK

请通过本页顶部的按钮直接下载最新 APK。下载完成后，在 Android 设备上打开该文件即可开始安装。

## 要求

- 支持手动安装 APK 的 Android 设备。
- 允许安装未知来源应用。
- 相机权限。
- 如果启用音频录制，则需要麦克风权限。
- 通知权限，用于保持前台录制服务可见。
- 足够的可用存储空间用于保存视频文件。

## 安装方法

1. 使用本页顶部的按钮下载 APK。
2. 在 Android 设备上打开下载的 APK。
3. 如果 Android 阻止安装，请点击设置。
4. 允许从此来源安装应用。
5. 返回安装界面并点击安装。
6. 打开 GavetRecorder。
7. 授予请求的权限。
8. 在应用内开始录制。

## 使用的权限

- 相机：用于录制视频。
- 麦克风：仅在启用音频录制时需要。
- 通知：用于让录制服务保持在前台运行。
- 存储或媒体访问：用于保存和访问录制的视频。
- 位置：仅在启用 GPS、路线或遥测功能时使用。

## 基本使用

- 打开应用。
- 选择所需的相机、质量和 FPS。
- 开始录制。
- 保持录制通知处于活动状态。
- 完成后停止录制。
- 在设备存储中查找录制的视频。

## 录制文件保存位置

录制文件会保存在设备本地，预期文件夹为：

```text
DCIM/GavetRecorder/
└── Videos/
```

## 隐私

GavetRecorder 专为本地录制设计。除非用户手动分享、移动或上传，录制文件会保留在设备上。

## 故障排除

- 如果 APK 无法安装，请检查是否允许安装未知来源应用。
- 如果无法开始录制，请检查相机和麦克风权限。
- 如果后台录制停止，请关闭此应用的电池优化。
- 如果找不到视频，请检查设备存储中的 GavetRecorder 文件夹。
- 如果 Android 显示安全警告，请确认 APK 来自官方仓库。

## 使用 ADB 安装

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## 当前版本

V16 增加了多语言界面支持，并修复了主屏幕使用的翻译资源，包括质量/FPS。
