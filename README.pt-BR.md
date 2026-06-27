# GavetRecorder APK

## Gravador de vídeo em segundo plano para Android

GavetRecorder é um aplicativo Android desenvolvido para gravar vídeo em segundo plano usando um serviço em primeiro plano. Ele é indicado para usuários que precisam de gravação contínua, armazenamento local organizado e um processo simples de instalação por APK.

> **Important:** Este APK é distribuído fora da Google Play Store. Para instalar, o Android pode solicitar a liberação da instalação por fontes desconhecidas.

## Languages

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

Baixe o arquivo APK mais recente pela release do repositório ou pelo arquivo APK disponibilizado no projeto.

## Requisitos

- Celular Android compatível com instalação manual de APK.
- Permissão para instalar aplicativos de fontes desconhecidas.
- Permissão de câmera.
- Permissão de microfone, caso a gravação com áudio esteja ativada.
- Permissão de localização, caso recursos de GPS ou rota sejam usados.
- Espaço livre suficiente para armazenar os vídeos.

## Como instalar

1. Baixe o arquivo APK no celular Android.
2. Abra o APK pelo gerenciador de arquivos ou pela notificação de download do navegador.
3. Se o Android bloquear a instalação, toque em Configurações e permita instalar por esta fonte.
4. Volte para a tela de instalação e toque em Instalar.
5. Abra o GavetRecorder após a instalação.
6. Conceda as permissões solicitadas pelo Android.
7. Inicie a gravação dentro do aplicativo.

## Permissões utilizadas

- Câmera: necessária para gravar vídeo.
- Microfone: necessária apenas quando a gravação de áudio estiver ativada.
- Localização: usada apenas para GPS, rotas ou telemetria quando o recurso estiver disponível.
- Notificações: necessária para manter o serviço de gravação em primeiro plano visível.
- Armazenamento ou acesso à mídia: usado para salvar e acessar os vídeos gravados.

## Uso básico

- Abra o aplicativo.
- Escolha a câmera, qualidade e FPS desejados.
- Inicie a gravação.
- Mantenha a notificação de gravação ativa enquanto o app estiver gravando.
- Pare a gravação quando finalizar.
- Acesse os vídeos gravados no armazenamento do dispositivo.

## Onde as gravações ficam salvas

As gravações são salvas localmente no dispositivo. A pasta esperada é:

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
- Se os vídeos não aparecerem, verifique a pasta do aplicativo no armazenamento.
- Se o Android mostrar alerta de segurança, confirme que o APK veio do repositório oficial do projeto.

## Instalar usando ADB

```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

## Versão atual

A V16 inclui suporte à interface multilíngue e corrige recursos traduzidos usados na tela principal, incluindo Qualidade/FPS.

## GitHub Pages

The web documentation can automatically detect the browser language through `docs/index.html`.
