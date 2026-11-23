---
layout: post
title: "Tutorial: Como usar o PPPwn GUI no Windows para o exploit 11.00"
description: "Execute o exploit PPPwn de forma simples através de uma interface visual no seu computador."
download: "https://github.com/xfangfang/PPPwn_GUI/releases"
date: 2026-11-23 18:01:35 -0300
categories: ps4 tutorial
---

O exploit **PPPwn** revolucionou a cena do PS4 ao permitir o desbloqueio de firmwares até o 11.00. Embora existam versões para Android e Raspberry Pi, a versão **PPPwn GUI para Windows** é a mais acessível para quem possui um computador ou notebook próximo ao console.

### Requisitos
*   PS4 no firmware 11.00 ou inferior (compatível com 9.00, 9.60, 10.00, 10.01, 11.00).
*   Cabo de rede Ethernet (conectando o PC diretamente ao PS4).
*   Computador com Windows e o software **PPPwn GUI** instalado.
*   Npcap instalado no Windows (necessário para a injeção de pacotes via rede).

### Passo a Passo

1.  **Instalação do Driver:** Baixe e instale o **Npcap** no seu Windows. Durante a instalação, certifique-se de marcar a opção "Install Npcap in WinPcap API-compatible Mode".
2.  **Preparação do Software:** Abra o `PPPwn_GUI.exe`. Na interface, selecione a sua interface de rede (Ethernet) na lista suspensa.
3.  **Seleção do Firmware:** Escolha a versão do firmware correspondente ao seu PS4 (ex: 11.00) e selecione o arquivo `stage1.bin` e `stage2.bin` (geralmente já inclusos na pasta do programa).
4.  **Configuração no PS4:** No console, vá em **Configurações** > **Rede** > **Configurar conexão à Internet** > **Cabo LAN** > **Personalizado** > **PPPoE**.
5.  **Credenciais:** Digite qualquer coisa para o nome de usuário e senha (ex: `ppp`).
6.  **Execução:** No computador, clique em **Ready** ou **Start**. No PS4, selecione **Seguinte** para testar a conexão.
7.  **Aguarde o Processo:** O programa no PC mostrará o progresso dos "stages". Se aparecer a mensagem "PPPwned", o exploit foi carregado. Se o GoldHEN estiver no pendrive na porta USB do PS4, ele será ativado automaticamente.

### Avisos de Risco
*   O exploit PPPwn não é 100% estável e pode exigir várias tentativas até funcionar.
*   O uso de cabos Ethernet de má qualidade pode causar falhas na injeção do estágio 1.

### Solução de Problemas
*   **Erro 'Waiting for PADI':** Verifique se o cabo está bem conectado e se você selecionou a placa de rede correta no PC.
*   **O PS4 desliga durante o processo:** Isso é um Kernel Panic. Ligue o console, espere ele verificar o armazenamento e tente novamente. É um comportamento normal do exploit.

## Download

[Baixar Tutorial: Como usar o PPPwn GUI no Windows para o exploit 11.00 (página oficial)](https://github.com/xfangfang/PPPwn_GUI/releases)

Fonte: <https://github.com/xfangfang/PPPwn_GUI>
