---
layout: post
title: "Tutorial: Como customizar a interface do console com o Orbis Toolbox"
description: "Aprenda a modificar menus e adicionar recursos extras ao sistema do PS4."
download: "https://github.com/OSM-Utilities/Orbis-Toolbox/releases"
date: 2026-11-21 15:01:34 -0300
categories: ps4 tutorial
---

O **Orbis Toolbox** é uma das ferramentas mais poderosas para usuários de PS4 com jailbreak. Ele funciona como uma modificação do sistema (UI) que adiciona um menu dedicado às configurações, permitindo monitorar o hardware em tempo real, customizar o menu principal e facilitar o carregamento de payloads.

### Requisitos

* PlayStation 4 com Jailbreak ativo (firmware compatível com GoldHEN).
* GoldHEN versão 2.2 ou superior instalado.
* Arquivo PKG do Orbis Toolbox.

### Passo a Passo

1.  **Instalação do PKG**: Baixe o arquivo PKG oficial do Orbis Toolbox e coloque-o na raiz de um dispositivo USB (exFAT ou FAT32).
2.  **Instalar via PS4**: Conecte o USB ao console, vá em **Configurações > GoldHEN > Package Installer** e instale o Orbis Toolbox.
3.  **Ativação**: Após a instalação, reinicie o console (ou apenas o GoldHEN). Um novo menu chamado 'Orbis Toolbox' aparecerá nas Configurações do PS4.
4.  **Configurar o Overlay**: Dentro do menu Orbis Toolbox, vá em **System Settings > Build Overlay**. Aqui você pode ativar a exibição de temperatura de CPU/GPU, uso de RAM e FPS no topo da tela enquanto joga.
5.  **Customização de Menu**: Em **Customization Settings**, você pode ocultar ícones indesejados da tela inicial ou alterar o comportamento de menus de energia.

### Avisos de Risco

* O Orbis Toolbox modifica processos do sistema em tempo real. Embora raro, ele pode causar travamentos na interface (UI Freeze). Se isso ocorrer, reinicie o console segurando o botão Power.
* Evite alterar configurações experimentais de 'Kernel' se não tiver conhecimento avançado.

### Solução de Problemas

* **O menu não aparece**: Certifique-se de que o GoldHEN está ativo. O Orbis Toolbox depende dos patches de memória do GoldHEN para funcionar.
* **O console trava ao abrir o menu**: Isso pode acontecer se houver conflito com outros plugins. Tente desativar outros plugins no diretório `/data/GoldHEN/plugins` temporariamente.

## Download

[Baixar Tutorial: Como customizar a interface do console com o Orbis Toolbox (página oficial)](https://github.com/OSM-Utilities/Orbis-Toolbox/releases)

Fonte: <https://github.com/OSM-Utilities/Orbis-Toolbox>
