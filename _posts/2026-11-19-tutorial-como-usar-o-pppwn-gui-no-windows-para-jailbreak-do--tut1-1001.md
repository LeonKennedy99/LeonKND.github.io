---
layout: post
title: "Tutorial: Como usar o PPPwn GUI no Windows para Jailbreak do PS4"
description: "Guia simplificado para executar o exploit PPPwn usando um computador com Windows."
download: "https://github.com/Buji-Soft/PPPwn-GUI/releases"
date: 2026-11-19 10:01:33 -0300
categories: ps4 tutorial
---

O **PPPwn GUI** é uma interface gráfica para o Windows que facilita a execução do exploit PPPwn, eliminando a necessidade de usar linhas de comando complexas. Este método é utilizado para ativar o GoldHEN em consoles compatíveis via conexão Ethernet.

### Requisitos
* **Firmware Compatível:** 7.00 até 11.00.
* **Hardware:** PC com Windows e uma porta Ethernet (ou adaptador USB-Ethernet).
* **Cabo:** Cabo de rede (Ethernet).
* **Software:** PPPwn GUI e os arquivos `stage1.bin` e `stage2.bin` correspondentes ao seu firmware.

### Passo a Passo
1. **Preparação do PC:** Baixe a versão mais recente do PPPwn GUI. Extraia os arquivos em uma pasta de fácil acesso.
2. **Arquivos do Exploit:** Certifique-se de ter os arquivos `stage1.bin` e `stage2.bin` para a sua versão específica de firmware dentro da pasta do programa.
3. **Configuração da Rede no PS4:**
   * Vá em Configurações > Rede > Configurar conexão à Internet.
   * Escolha 'Usar cabo de rede (LAN)' > 'Personalizada'.
   * Em Configurações de Endereço IP, escolha 'PPPoE'.
   * Digite qualquer nome de usuário e senha (ex: `ppp`).
   * Em Configurações de DNS e MTU, deixe em 'Automático'. Em Servidor Proxy, 'Não usar'.
4. **Execução no Windows:**
   * Conecte o cabo Ethernet entre o PC e o PS4.
   * Abra o `PPPwnUI.exe` como Administrador.
   * Selecione a interface de rede (sua placa Ethernet).
   * Selecione a versão do firmware do seu PS4 na interface.
   * Clique em 'Stage 1' e selecione o arquivo correspondente; faça o mesmo para o 'Stage 2'.
5. **Ativação:**
   * No PS4, clique em 'Testar conexão à Internet'.
   * No PC, clique em 'Start' ou 'Run' no PPPwn GUI assim que o PS4 começar a verificar o PPPoE.
   * O programa enviará os pacotes. Se aparecer 'PPPwned', o exploit foi bem-sucedido.

### Avisos de Risco
* O exploit pode falhar nas primeiras tentativas (Kernel Panic). Se o console desligar sozinho, ligue-o novamente e repita o processo.
* Certifique-se de que o cabo de rede esteja em boas condições para evitar falhas de handshake.

### Solução de Problemas
* **Falha no Stage 1:** Verifique se a interface de rede correta foi selecionada no Windows.
* **O PS4 não conecta ao PPPoE:** Desative o Firewall do Windows temporariamente, pois ele pode bloquear a comunicação da porta 53 ou do protocolo PPPoE.

## Download

[Baixar Tutorial: Como usar o PPPwn GUI no Windows para Jailbreak do PS4 (página oficial)](https://github.com/Buji-Soft/PPPwn-GUI/releases)

Fonte: <https://github.com/TheOfficialFloW/PPPwn>
