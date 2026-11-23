---
layout: post
title: "Tutorial: Como instalar e configurar o Orbis Toolbox para monitoramento de sistema"
description: "Adicione overlays de temperatura, FPS e atalhos de sistema ao seu PS4."
download: "https://github.com/OSM-Made/Orbis-Toolbox/releases"
date: 2026-11-23 18:01:33 -0300
categories: ps4 tutorial
---

O **Orbis Toolbox** é uma ferramenta essencial para usuários avançados da cena PS4. Ele modifica a interface do sistema (XMB) para adicionar menus extras que permitem monitorar o hardware em tempo real (como temperatura e uso de CPU), além de facilitar o carregamento de payloads e a personalização visual do console.

### Requisitos
*   PS4 com Jailbreak ativo (GoldHEN ou similar).
*   Firmware compatível (testado amplamente no 5.05, 6.72, 9.00 e 11.00).
*   Arquivo `.pkg` do Orbis Toolbox (disponível no GitHub oficial).
*   Pendrive formatado em exFAT.

### Passo a Passo

1.  **Preparação do arquivo:** Baixe a versão mais recente do Orbis Toolbox (arquivo PKG) e copie para a raiz do seu pendrive exFAT.
2.  **Instalação:** Insira o pendrive no PS4. Vá em **Configurações** > **GoldHEN** > **Package Installer** e instale o arquivo do Orbis Toolbox.
3.  **Reinicialização:** Após a instalação, é recomendável reiniciar o console e reativar o exploit para garantir que os hooks do sistema sejam aplicados corretamente.
4.  **Acessando o Menu:** Você notará uma nova opção chamada **Orbis Toolbox** diretamente no menu principal de Configurações do PS4.
5.  **Configurando Overlays:** Dentro do menu do Orbis Toolbox, vá em **Display Settings** > **Overlay Settings**. Aqui você pode ativar o monitor de temperatura, FPS e uso de memória que ficarão visíveis durante os jogos.
6.  **Atalhos de Sistema:** Explore a aba **System Settings** para configurar atalhos de reinicialização rápida ou para limpar o cache do navegador com um clique.

### Avisos de Risco
*   O Orbis Toolbox modifica arquivos em tempo de execução na memória do sistema. Embora raro, pode causar Kernels Panics (desligamentos repentinos). Se o console travar, basta ligá-lo novamente.
*   Sempre verifique se a versão que você está instalando é compatível com o seu firmware atual.

### Solução de Problemas
*   **O menu não aparece:** Verifique se o GoldHEN está ativo. Algumas funções exigem que o modo de depuração (Debug Settings) esteja habilitado.
*   **O console trava ao abrir o menu:** Isso geralmente ocorre por conflito com outros plugins. Tente desativar outros plugins no `boot.ini` do GoldHEN para testar.

## Download

[Baixar Tutorial: Como instalar e configurar o Orbis Toolbox para monitoramento de sistema (página oficial)](https://github.com/OSM-Made/Orbis-Toolbox/releases)

Fonte: <https://github.com/OSM-Made/Orbis-Toolbox>
