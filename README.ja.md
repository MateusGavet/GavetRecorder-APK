# GavetRecorder APK

**整理されたローカル保存に対応した Android 向けバックグラウンド動画録画アプリです。**

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

GavetRecorder は、フォアグラウンドサービスを使用してバックグラウンドで動画を録画し、常駐通知によって新しい Android バージョンとの互換性を保つために作成されました。

## 主な機能

- Foreground Service によるバックグラウンド録画。
- 録画中の常駐通知。
- カメラ選択。
- 品質と FPS の設定。
- セグメント単位の動画録画。
- DCIM/GavetRecorder に整理されたローカル保存。
- 動画、地図、ルート、ログ、メタデータ用の構造。
- GPS とテレメトリのオーバーレイに対応する基盤。
- 多言語インターフェース。

## 想定される保存構造

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## V16 更新

V16 では多言語インターフェースのサポートを追加し、メイン画面で使用される翻訳可能リソースを修正しました。Quality/FPS オプションも含まれます。

## Debug APK をビルド

```bash
./gradlew clean assembleDebug
```

## ADB でインストール

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

ブラウザの言語が対応していない場合、英語が既定言語として使用されます。
