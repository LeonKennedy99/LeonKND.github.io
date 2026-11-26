---
layout: post
title: "Tutorial: Como carregar payloads offline usando o aplicativo Payload Guest"
description: "Envie arquivos .bin sem precisar de PC ou sites externos."
download: "https://github.com/Al-Azif/ps4-payload-guest/releases"
date: 2026-11-26 10:01:39 -0300
categories: ps4 tutorial
---

### O que é
O Payload Guest é uma ferramenta que permite ao usuário carregar arquivos de payload (.bin) diretamente do armazenamento interno do PS4 ou de um USB, eliminando a necessidade de usar o navegador do console ou um computador para injetar comandos.

### Requisitos
* PS4 com GoldHEN ativado.
* Arquivo PKG do Payload Guest.
* Payloads que você deseja usar (ex: `dumper.bin`, `ftp.bin`, etc.).

### Passo a Passo
1. **Instalação:** Instale o arquivo PKG do Payload Guest através do menu *Debug Settings > Game > Package Installer*.
2. **Preparar Payloads:** No seu PC, crie uma pasta chamada `payloads`. Coloque todos os seus arquivos `.bin` dentro dela.
3. **Transferir Arquivos:**
   * **Via USB:** Coloque a pasta `payloads` na raiz de um pendrive exFAT e espete no PS4.
   * **Via Armazenamento Interno:** Use o PS4-Xplorer para mover a pasta `payloads` para `/data/payloads/` no HD do console.
4. **Executar:** Abra o aplicativo Payload Guest no menu principal do PS4.
5. **Carregamento:** O app listará todos os arquivos encontrados. Basta selecionar o payload desejado com o botão **X** para injetá-lo instantaneamente.

### Avisos de Risco
* **Kernel Panic:** Injetar payloads antigos ou incompatíveis com sua versão de firmware pode causar o desligamento abrupto do console (Kernel Panic). Se isso ocorrer, ligue o console e deixe-o reparar o sistema de arquivos.

### Solução de Problemas
* **Lista Vazia:** Se o app não mostrar nada, certifique-se de que a pasta se chama exatamente `payloads` (em minúsculas) e está no local correto (`/data/payloads/` ou na raiz do USB).

## Download

[Baixar Tutorial: Como carregar payloads offline usando o aplicativo Payload Guest (página oficial)](https://github.com/Al-Azif/ps4-payload-guest/releases)

Fonte: <https://github.com/Al-Azif/ps4-payload-guest>
