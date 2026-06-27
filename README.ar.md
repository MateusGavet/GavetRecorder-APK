# GavetRecorder APK

**تطبيق Android لتسجيل الفيديو في الخلفية مع تخزين محلي منظم.**

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

تم إنشاء GavetRecorder لتسجيل الفيديو في الخلفية باستخدام خدمة في المقدمة، مع الحفاظ على التوافق مع إصدارات Android الحديثة عبر إشعار دائم.

## الميزات الرئيسية

- التسجيل في الخلفية باستخدام Foreground Service.
- إشعار دائم أثناء التسجيل.
- اختيار الكاميرا.
- إعداد الجودة و FPS.
- تسجيل الفيديو على شكل مقاطع.
- تخزين محلي منظم داخل DCIM/GavetRecorder.
- هيكل جاهز للفيديوهات والخرائط والمسارات والسجلات والبيانات الوصفية.
- قاعدة جاهزة لتراكب GPS والقياسات.
- واجهة متعددة اللغات.

## هيكل التخزين المتوقع

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## تحديث V16

يضيف الإصدار V16 دعم الواجهة متعددة اللغات ويصحح الموارد القابلة للترجمة المستخدمة في الشاشة الرئيسية، بما في ذلك خيار الجودة/FPS.

## بناء APK debug

```bash
./gradlew clean assembleDebug
```

## التثبيت باستخدام ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

إذا لم تكن لغة المتصفح مدعومة، فسيتم استخدام الإنجليزية كلغة افتراضية.
