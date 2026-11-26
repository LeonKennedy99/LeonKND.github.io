---
layout: post
title: "Tutorial: Como usar o PPPwnUI para desbloquear o PS4 (Firmware 11.00)"
description: "Guia para iniciantes sobre como executar o exploit PPPwn via Windows usando uma interface gráfica."
download: "https://github.com/theOfficialFloW/PPPwn"
date: 2026-11-26 18:01:51 -0300
categories: ps4 tutorial
---

O PPPwnUI é uma interface gráfica para Windows que facilita a execução do exploit PPPwn, desenvolvido por TheFloW, permitindo o desbloqueio do PlayStation 4 em firmwares até o 11.00 através de uma conexão Ethernet (LAN).

### Requisitos
*   PS4 no firmware 11.00 ou inferior.
*   Computador com Windows e porta Ethernet.
*   Cabo de rede (LAN).
*   **Npcap** instalado no Windows.
*   Arquivo `stage1.bin` e `stage2.bin` correspondentes ao seu firmware.
*   Um pendrive formatado em exFAT contendo o payload `goldhen.bin` (renomeado adequadamente se necessário).

### Passo a Passo
1.  **Preparação do PS4:** Vá em Configurações > Rede > Configurar conexão à Internet > Usar cabo de rede (LAN) > Personalizado > PPPoE. Insira qualquer usuário e senha (ex: `admin`). Em DNS e MTU, deixe no Automático e em Servidor Proxy coloque "Não usar". **Não teste a conexão ainda.**
2.  **Preparação do PC:** Baixe e extraia o PPPwnUI. Instale o driver Npcap caso ainda não o tenha.
3.  **Conexão:** Conecte o cabo de rede do seu PC diretamente ao PS4.
4.  **Configuração do Software:** Abra o PPPwnUI. Selecione a interface de rede que está conectada ao PS4 (ex: Ethernet).
5.  **Seleção do Firmware:** Selecione a versão do firmware do seu console no programa.
6.  **Execução:** Clique no botão "Run Exploit" ou "Start".
7.  **Finalização no PS4:** No console, agora clique em "Testar Conexão à Internet". O software no PC começará a enviar os pacotes.
8.  **Sucesso:** Se tudo correr bem, você verá mensagens de sucesso no PC e, após alguns instantes, a notificação do GoldHEN aparecerá no canto superior esquerdo da tela do PS4.

### Avisos de Risco
*   O processo de exploração pode falhar e causar um desligamento repentino (kernel panic). Se isso acontecer, ligue o console, deixe-o verificar o armazenamento e tente novamente.
*   Certifique-se de que as atualizações automáticas de sistema estão desativadas para evitar perder o firmware compatível.

### Solução de Problemas
*   **Erro de Conexão:** Verifique se o cabo de rede está bem encaixado e se a placa de rede do PC está ativa.
*   **Exploit trava em "Waiting for PADI":** Reinicie o processo de configuração de rede no PS4 e clique em testar conexão novamente.
*   **Falha no Stage 2:** Tente trocar o cabo de rede ou usar uma porta USB diferente para o pendrive do GoldHEN.

## Download

[Baixar Tutorial: Como usar o PPPwnUI para desbloquear o PS4 (Firmware 11.00) (página oficial)](https://github.com/theOfficialFloW/PPPwn)

Fonte: <https://github.com/theOfficialFloW/PPPwn>
