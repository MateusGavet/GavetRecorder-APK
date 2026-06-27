# GavetRecorder APK

**정리된 로컬 저장소를 사용하는 Android 백그라운드 동영상 녹화 앱입니다.**

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

GavetRecorder는 포그라운드 서비스를 사용해 백그라운드에서 동영상을 녹화하고, 지속 알림을 통해 최신 Android 버전과의 호환성을 유지하도록 만들어졌습니다.

## 주요 기능

- Foreground Service를 사용한 백그라운드 녹화.
- 녹화 중 지속 알림.
- 카메라 선택.
- 품질 및 FPS 설정.
- 구간별 동영상 녹화.
- DCIM/GavetRecorder에 정리된 로컬 저장소.
- 동영상, 지도, 경로, 로그, 메타데이터를 위한 구조.
- GPS 및 텔레메트리 오버레이 기반.
- 다국어 인터페이스.

## 예상 저장 구조

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## V16 업데이트

V16은 다국어 인터페이스 지원을 추가하고, Quality/FPS 옵션을 포함하여 메인 화면에서 사용하는 번역 가능한 리소스를 수정합니다.

## Debug APK 빌드

```bash
./gradlew clean assembleDebug
```

## ADB로 설치

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

브라우저 언어가 지원되지 않으면 영어가 기본 언어로 사용됩니다.
