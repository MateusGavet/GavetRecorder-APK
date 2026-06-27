# GavetRecorder APK

<!-- GAVETRECORDER_DOWNLOAD_START -->

## Download direto

[**⬇️ Abrir página de download do APK**](https://github.com/MateusGavet/GavetRecorder-APK/releases/tag/v1.0.0)

[**🌐 Abrir guia de instalação**](https://mateusgavet.github.io/GavetRecorder-APK/)

<!-- GAVETRECORDER_DOWNLOAD_END -->

## Gravador de vídeo em segundo plano para Android

GavetRecorder é um aplicativo Android desenvolvido para gravar vídeo em segundo plano usando um serviço em primeiro plano. Ele é indicado para quem precisa de gravação contínua local, instalação manual simples e armazenamento organizado no dispositivo.

> **Importante:** Este APK é distribuído fora da Google Play Store. Antes da instalação, o Android pode solicitar a liberação para instalar aplicativos de fontes desconhecidas.

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

## Baixar o APK

Baixe o APK mais recente diretamente pelo botão acima. Depois do download, abra o arquivo no celular Android para iniciar a instalação.

## Requisitos

- Celular Android compatível com instalação manual de APK.
- Permissão para instalar aplicativos de fontes desconhecidas.
- Permissão de câmera.
- Permissão de microfone se a gravação com áudio estiver ativada.
- Permissão de notificações para manter o serviço de gravação em primeiro plano visível.
- Espaço livre suficiente para armazenar os vídeos.

## Como instalar

1. Baixe o APK usando o botão no topo desta página.
2. Abra o APK baixado no celular Android.
3. Se o Android bloquear a instalação, toque em Configurações.
4. Permita instalar aplicativos por esta fonte.
5. Volte para a instalação e toque em Instalar.
6. Abra o GavetRecorder.
7. Conceda as permissões solicitadas.
8. Inicie a gravação dentro do aplicativo.

## Permissões utilizadas

- Câmera: necessária para gravar vídeo.
- Microfone: necessária apenas quando a gravação de áudio estiver ativada.
- Notificações: necessária para manter o serviço de gravação ativo em primeiro plano.
- Armazenamento ou acesso à mídia: usado para salvar e acessar os vídeos gravados.
- Localização: usada apenas se recursos de GPS, rota ou telemetria estiverem ativados.

## Uso básico

- Abra o aplicativo.
- Escolha a câmera, qualidade e FPS desejados.
- Inicie a gravação.
- Mantenha a notificação de gravação ativa.
- Pare a gravação quando finalizar.
- Encontre os vídeos gravados no armazenamento do dispositivo.

## Onde as gravações ficam salvas

As gravações são salvas localmente no dispositivo, na pasta esperada:

```text
DCIM/GavetRecorder/
└── Videos/
```

## Privacidade

O GavetRecorder foi pensado para gravação local. Os arquivos gravados permanecem no dispositivo, a menos que o próprio usuário compartilhe, mova ou envie os vídeos manualmente.

## Solução de problemas

- Se o APK não instalar, verifique se a instalação por fontes desconhecidas está liberada.
- Se a gravação não iniciar, confira as permissões de câmera e microfone.
- Se a gravação em segundo plano parar, desative a otimização de bateria para o app.
- Se os vídeos não aparecerem, verifique a pasta GavetRecorder no armazenamento do dispositivo.
- Se o Android mostrar alerta de segurança, confirme que o APK veio do repositório oficial.

## Instalar usando ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Versão atual

A V16 inclui suporte à interface multilíngue e corrige recursos traduzidos usados na tela principal, incluindo Qualidade/FPS.
