# GavetRecorder APK

**Aplicativo Android para gravação de vídeo em segundo plano com armazenamento local organizado.**

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

O GavetRecorder foi criado para gravar vídeo em segundo plano usando serviço em primeiro plano, mantendo compatibilidade com versões recentes do Android por meio de uma notificação persistente.

## Recursos principais

- Gravação em segundo plano usando Foreground Service.
- Notificação persistente enquanto a gravação está ativa.
- Seleção de câmera.
- Configuração de qualidade e FPS.
- Gravação de vídeo por segmentos.
- Armazenamento local organizado em DCIM/GavetRecorder.
- Estrutura preparada para vídeos, mapas, rotas, logs e metadados.
- Base preparada para overlay de GPS e telemetria.
- Interface multilíngue.

## Estrutura de armazenamento esperada

```text
DCIM/GavetRecorder/
├── Videos/
├── Mapas/
├── Rotas/
├── Logs/
├── Metadados/
```

## Atualização V16

A versão V16 adiciona suporte à interface multilíngue e corrige recursos traduzíveis usados pela tela principal, incluindo a opção Qualidade/FPS.

## Gerar APK debug

```bash
./gradlew clean assembleDebug
```

## Instalar com ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Fallback

Caso o idioma do navegador não seja suportado, o inglês será usado como idioma padrão.
