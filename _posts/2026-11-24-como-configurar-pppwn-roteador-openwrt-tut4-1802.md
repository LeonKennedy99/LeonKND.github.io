---
layout: post
title: "Tutorial: Como configurar o PPPwn em um roteador com OpenWrt"
description: "Use um roteador antigo com firmware OpenWrt para automatizar o jailbreak do seu PS4."
download: "https://github.com/MODDEDWARFARE/PPPwn_WRT/releases"
date: 2026-11-24 18:02:02 -0300
categories: ps4 tutorial
---

Configurar o PPPwn em um roteador com **OpenWrt** é uma das soluções mais estáveis para o jailbreak do PS4. O roteador atua como um servidor PPPoE dedicado que injeta o exploit assim que o console é ligado, permitindo inclusive que o console receba internet através do próprio roteador após o desbloqueio.

### Requisitos
*   Roteador compatível com **OpenWrt** (v21.02 ou superior).
*   PS4 nos firmwares 9.00 a 11.00.
*   Cabo Ethernet.
*   Acesso SSH ao roteador (via PuTTY ou terminal).

### Passo a Passo
1.  **Acesso ao Roteador:** Conecte seu PC ao roteador e acesse o terminal via SSH (geralmente no IP `192.168.1.1`).
2.  **Instalação do Script:** Execute o comando para baixar e iniciar o assistente de instalação:
    `wget https://github.com/MODDEDWARFARE/PPPwn_WRT/raw/main/install.sh && chmod +x install.sh && ./install.sh`.
3.  **Configuração:** O script fará perguntas sobre seu hardware:
    *   Selecione a interface LAN onde o PS4 será conectado.
    *   Escolha se deseja habilitar a interface web para monitoramento.
    *   Ative a opção **GoldHEN Detection** para evitar que o exploit tente rodar novamente se o console já estiver desbloqueado ou em modo de repouso.
4.  **Arquivos GoldHEN:** Coloque o arquivo `goldhen.bin` na raiz de um pendrive exFAT/FAT32 e espete-o no PS4.
5.  **Configuração no PS4:**
    *   Vá em **Configurações** > **Rede** > **Configurar conexão à Internet**.
    *   Escolha **Cabo LAN** > **Personalizado** > **PPPoE**.
    *   Use o usuário `ppp` e senha `ppp` (padrão do script).
    *   Deixe o restante no **Automático** e não use proxy.
6.  **Teste:** Selecione "Testar Conexão à Internet". O roteador detectará a tentativa de conexão e iniciará o PPPwn. O progresso pode ser acompanhado se você habilitou a interface web no passo 3.

### Avisos de Risco
*   Alterar o firmware do roteador para OpenWrt pode inutilizar o aparelho se o processo for feito incorretamente.
*   Certifique-se de que o roteador tem memória flash suficiente (mínimo 16MB recomendados para a versão completa do script).

### Solução de Problemas
*   **Conflito de IP:** Se o roteador OpenWrt estiver conectado ao seu modem principal, certifique-se de que eles usam sub-redes diferentes (ex: modem em `192.168.1.1` e OpenWrt em `192.168.2.1`).
*   **Falha no Script:** Se o roteador tiver pouco espaço, tente a instalação manual simplificada sem a interface gráfica LuCI.

## Download

[Baixar Tutorial: Como configurar o PPPwn em um roteador com OpenWrt (página oficial)](https://github.com/MODDEDWARFARE/PPPwn_WRT/releases)

Fonte: <https://github.com/MODDEDWARFARE/PPPwn_WRT>
