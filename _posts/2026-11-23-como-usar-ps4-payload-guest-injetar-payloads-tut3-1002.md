---
layout: post
title: "Tutorial: Como usar o PS4 Payload Guest para injetar payloads diretamente no console"
description: "Execute arquivos .bin (como Fan Control e FTP) sem precisar de um PC ou celular."
download: "https://github.com/Al-Azif/ps4-payload-guest/releases"
date: 2026-11-23 10:02:08 -0300
categories: ps4 tutorial
---

O PS4 Payload Guest é uma aplicação homebrew que permite ao usuário carregar e executar payloads (arquivos .bin) armazenados no próprio HD interno ou em um USB, eliminando a dependência de um navegador ou injetores externos (PC/Android).

### Requisitos
*   PS4 com GoldHEN ativado.
*   Aplicação PS4 Payload Guest instalada.
*   Payloads em formato `.bin` (ex: `ps4-fan-control.bin`, `dumper.bin`).

### Passo a Passo
1.  **Instalação:** Baixe e instale o `.pkg` do PS4 Payload Guest através do menu de instalação oficial do seu exploit.
2.  **Preparação das Pastas:** 
    *   No USB (exFAT): Crie uma pasta chamada `payloads` na raiz.
    *   No HD Interno: Use um explorador de arquivos (como o PS4-Xplorer) para criar a pasta `/data/payloads/`.
3.  **Transferência:** Copie seus arquivos `.bin` favoritos para uma dessas pastas.
4.  **Execução:** Abra o aplicativo no menu principal do PS4. Ele detectará automaticamente todos os payloads nas pastas mencionadas.
5.  **Injeção:** Basta navegar pela lista com o direcional e apertar **X** sobre o payload que deseja ativar. O sistema processará a injeção instantaneamente.

### Avisos de Risco
*   **Compatibilidade de Firmware:** Certifique-se de que o payload `.bin` que você está tentando injetar foi compilado para a versão específica do seu firmware. Injetar um payload de FW 9.00 em um console 11.00 pode causar um kernel panic (desligamento súbito).
*   **Congelamentos:** Se o console travar durante a injeção, será necessário puxar o cabo de energia (procedimento não recomendado, mas às vezes inevitável).

### Solução de Problemas
*   **Lista vazia:** Verifique se o nome da pasta é exatamente `payloads` (em minúsculas) e se os arquivos terminam com a extensão `.bin`.
*   **Erro de Memória:** Se o payload falhar ao carregar, reinicie o console e ative o GoldHEN novamente antes de abrir o Guest.

## Download

[Baixar Tutorial: Como usar o PS4 Payload Guest para injetar payloads diretamente no console (página oficial)](https://github.com/Al-Azif/ps4-payload-guest/releases)

Fonte: <https://github.com/Al-Azif/ps4-payload-guest>
