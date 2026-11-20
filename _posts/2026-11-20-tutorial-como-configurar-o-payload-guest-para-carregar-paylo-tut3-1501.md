---
layout: post
title: "Tutorial: Como configurar o Payload Guest para carregar payloads via USB"
description: "Use o Payload Guest para injetar ferramentas .bin no PS4 sem precisar de um PC ou site."
download: "https://github.com/Al-Azif/ps4-payload-guest/releases"
date: 2026-11-20 15:01:44 -0300
categories: ps4 tutorial
---

O **Payload Guest** é um aplicativo homebrew que permite aos usuários injetar arquivos de payload (.bin) diretamente do armazenamento interno do PS4 ou de um dispositivo USB. Isso elimina a dependência de hosts de exploit online ou injetores de PC após o jailbreak inicial.

### Requisitos
* PS4 com GoldHEN ou qualquer exploit que permita rodar homebrews.
* Pendrive formatado em **ExFAT**.
* Arquivos de payload (ex: `dumper.bin`, `ftp.bin`, `kernel_clock.bin`) que você deseja usar.

### Passo a Passo
1. **Preparação do USB**: No seu PC, crie uma pasta chamada `payloads` na raiz do seu pendrive.
2. **Copiar Arquivos**: Cole todos os seus arquivos `.bin` dentro dessa pasta `payloads`.
3. **Instalação**: Instale o arquivo PKG do *Payload Guest* no seu PS4 através do menu de *Debug Settings*.
4. **Execução**: Insira o pendrive no console e abra o aplicativo **Payload Guest**.
5. **Seleção**: O app listará automaticamente os payloads encontrados no USB e na memória interna (`/data/payloads`). Use o direcional para escolher o payload que deseja executar.
6. **Injeção**: Pressione **X** sobre o payload escolhido. A tela ficará preta por um instante ou exibirá uma mensagem de confirmação indicando que o payload foi carregado com sucesso.

### Avisos de Risco
* **Payloads Incompatíveis**: Certifique-se de que o payload .bin que você está tentando carregar é compatível com a sua versão de firmware. Injetar um payload de versão diferente pode causar o desligamento imediato (kernel panic) do console.

### Solução de Problemas
* **USB não reconhecido**: Certifique-se de que o pendrive está no formato ExFAT. O formato NTFS não é reconhecido nativamente pelo PS4 para esta função.
* **Lista Vazia**: Se nenhum payload aparecer, verifique se o nome da pasta no USB está em letras minúsculas (`payloads`) e se os arquivos terminam com a extensão `.bin`.

## Download

[Baixar Tutorial: Como configurar o Payload Guest para carregar payloads via USB (página oficial)](https://github.com/Al-Azif/ps4-payload-guest/releases)

Fonte: <https://github.com/Al-Azif/ps4-payload-guest>
