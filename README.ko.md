# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## APK 다운로드

[**⬇️ 최신 APK 다운로드**](https://github.com/MateusGavet/GavetRecorder-APK/raw/main/dist/GavetRecorder-v16-debug.apk)

[**🌐 설치 가이드 열기**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->

## Android용 백그라운드 동영상 녹화 앱

GavetRecorder는 포그라운드 서비스를 사용해 백그라운드에서 동영상을 녹화하도록 설계된 Android 앱입니다. 지속적인 로컬 녹화, 간단한 수동 설치, 기기 내 정리된 저장 공간이 필요한 사용자를 위한 앱입니다.

> **Important:** 이 APK는 Google Play Store 외부에서 배포됩니다. 설치 전에 Android가 알 수 없는 앱 설치 허용을 요청할 수 있습니다.

## 언어

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

## APK 다운로드

이 페이지 상단의 버튼에서 최신 APK를 직접 다운로드하세요. 다운로드 후 Android 기기에서 파일을 열어 설치를 시작합니다.

## 요구 사항

- 수동 APK 설치를 지원하는 Android 기기.
- 알 수 없는 출처의 앱 설치 권한.
- 카메라 권한.
- 오디오 녹화가 활성화된 경우 마이크 권한.
- 포그라운드 녹화 서비스를 표시하기 위한 알림 권한.
- 동영상 파일을 저장할 충분한 여유 공간.

## 설치 방법

1. 이 페이지 상단의 버튼으로 APK를 다운로드합니다.
2. Android 기기에서 다운로드한 APK를 엽니다.
3. Android가 설치를 차단하면 설정을 누릅니다.
4. 이 출처에서 설치를 허용합니다.
5. 설치 화면으로 돌아가 설치를 누릅니다.
6. GavetRecorder를 엽니다.
7. 요청된 권한을 허용합니다.
8. 앱 안에서 녹화를 시작합니다.

## 사용되는 권한

- 카메라: 동영상 녹화에 필요합니다.
- 마이크: 오디오 녹화가 활성화된 경우에만 필요합니다.
- 알림: 녹화 서비스를 포그라운드에서 유지하는 데 필요합니다.
- 저장소 또는 미디어 접근: 녹화된 동영상을 저장하고 접근하는 데 사용됩니다.
- 위치: GPS, 경로 또는 텔레메트리 기능이 활성화된 경우에만 사용됩니다.

## 기본 사용법

- 앱을 엽니다.
- 원하는 카메라, 품질, FPS를 선택합니다.
- 녹화를 시작합니다.
- 녹화 알림을 활성 상태로 유지합니다.
- 완료되면 녹화를 중지합니다.
- 기기 저장소에서 녹화된 동영상을 확인합니다.

## 녹화 파일 저장 위치

녹화 파일은 기기에 로컬로 저장되며 예상 폴더는 다음과 같습니다:

```text
DCIM/GavetRecorder/
└── Videos/
```

## 개인정보

GavetRecorder는 로컬 녹화를 위해 설계되었습니다. 사용자가 직접 공유, 이동 또는 업로드하지 않는 한 녹화 파일은 기기에 남아 있습니다.

## 문제 해결

- APK가 설치되지 않으면 알 수 없는 앱 설치가 허용되어 있는지 확인하세요.
- 녹화가 시작되지 않으면 카메라와 마이크 권한을 확인하세요.
- 백그라운드 녹화가 중지되면 앱의 배터리 최적화를 비활성화하세요.
- 동영상이 보이지 않으면 기기 저장소의 GavetRecorder 폴더를 확인하세요.
- Android가 보안 경고를 표시하면 APK가 공식 저장소에서 온 것인지 확인하세요.

## ADB로 설치

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## 현재 버전

V16은 다국어 인터페이스 지원을 포함하며, 메인 화면에서 사용되는 번역 리소스와 Quality/FPS 항목을 수정합니다.
