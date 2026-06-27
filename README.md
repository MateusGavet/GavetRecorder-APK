# Gavet Recorder

**Gavet Recorder** é um aplicativo Android estilo dashcam, desenvolvido para gravar trajetos com câmera, GPS, velocidade, rota percorrida, nome da rua e overlay automático no vídeo final.

> Este repositório disponibiliza apenas o APK compilado do aplicativo.  
> O código-fonte é privado e proprietário.

## Download

Baixe a versão mais recente na aba **Releases**:

[Download do Gavet Recorder](https://github.com/MateusGavet/GavetRecorder-APK/releases/latest)

## Principais recursos

- Gravação de vídeo usando a câmera do dispositivo.
- Preview da câmera durante a gravação.
- Gravação em segundo plano com notificação fixa.
- Gravação de áudio opcional.
- GPS em tempo real.
- Velocidade em km/h.
- Nome da rua no overlay.
- Mapa circular com rota percorrida.
- Gravação em segmentos automáticos.
- Pós-processamento de overlay.
- Snapshot durante o uso.
- Biblioteca local de vídeos.
- Abrir vídeos em outro app.
- Compartilhar vídeos.
- Excluir vídeos.
- Seleção múltipla de vídeos.
- Propriedades da seleção com tamanho total e tempo total.

## Instalação

1. Acesse a página de download.
2. Baixe o arquivo APK mais recente.
3. No Android, permita instalar apps de fontes externas.
4. Abra o APK e conclua a instalação.
5. Conceda as permissões solicitadas pelo app.

## Aviso

Como o APK é distribuído fora da Google Play Store, o Android pode exibir alertas de segurança durante a instalação.

Instale apenas arquivos baixados diretamente deste repositório oficial.

## Propriedade

Gavet Recorder é um projeto privado e proprietário.

O código-fonte, identidade visual, lógica de gravação, processamento de overlay e demais implementações internas não são open source.

## Autor

Mateus Gavet  
DuoPivot  
Curitiba - PR, Brasil

## Contato

mateusgavet@gmail.com

<!-- GAVETRECORDER_V16_START -->
# GavetRecorder APK

Aplicativo Android para gravação em segundo plano com foco em uso contínuo, gravação por segmentos e armazenamento local organizado.

## Objetivo

O GavetRecorder foi criado para gravar vídeo em segundo plano usando serviço em primeiro plano, com notificação fixa para compatibilidade com versões recentes do Android.

## Recursos principais

- Gravação em segundo plano com Foreground Service.
- Notificação fixa enquanto o app está ativo.
- Seleção de câmera.
- Configuração de qualidade e FPS.
- Gravação por segmentos.
- Organização dos arquivos em `DCIM/GavetRecorder`.
- Estrutura planejada para vídeos, mapas, rotas, logs e metadados.
- Suporte a overlay de telemetria/GPS.
- Base preparada para internacionalização em múltiplos idiomas.

## Estrutura esperada

- `Videos`
- `Mapas`
- `Rotas`
- `Logs`
- `Metadados`

## V16

A versão V16 adiciona internacionalização da interface e corrige recursos traduzíveis usados na tela principal, incluindo a opção de qualidade/FPS.

<!-- GAVETRECORDER_V16_END -->
