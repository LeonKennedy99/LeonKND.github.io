---
layout: post
title: "Tutorial: Como transferir arquivos para o PS4 via FTP com GoldHEN"
description: "Gerencie os arquivos internos do seu PS4 sem precisar de cabos ou pendrives usando o servidor FTP."
download: "https://filezilla-project.org/download.php?type=client"
date: 2026-11-26 18:01:53 -0300
categories: ps4 tutorial
---

O GoldHEN possui um servidor FTP integrado que permite acessar o sistema de arquivos do PS4 remotamente através de um PC ou smartphone. Isso é útil para enviar cheats, instalar arquivos de sistema ou gerenciar saves.

### Requisitos
*   PS4 com GoldHEN ativo.
*   PC ou celular conectado na mesma rede Wi-Fi ou cabo que o console.
*   Cliente FTP (Recomendado: **FileZilla** para PC ou **ZArchiver** para Android).

### Passo a Passo
1.  **Ativar o Servidor no PS4:** No PS4, vá em Configurações > GoldHEN. Procure a opção "Enable FTP Server" e ative-a.
2.  **Identificar o IP:** No mesmo menu, ou nas configurações de rede do PS4, anote o endereço IP do console (ex: `192.168.1.15`) e a porta (geralmente é `2121`).
3.  **Configurar o Cliente (PC):** Abra o FileZilla no seu computador.
4.  **Conexão:** No campo "Host", digite o IP do PS4. No campo "Porta", digite `2121`. Deixe usuário e senha em branco.
5.  **Acesso às Pastas:** Clique em "Conexão Rápida". Você verá as pastas do PS4 no lado direito. 
    *   `/data/`: Local comum para homebrews e payloads.
    *   `/user/`: Contém dados de usuários e saves.
    *   `/mnt/usb0/`: Acesso ao pendrive conectado ao console.
6.  **Transferência:** Arraste os arquivos do seu PC (lado esquerdo) para a pasta desejada no PS4 (lado direito).

### Avisos de Risco
*   **Cuidado Crítico:** Nunca delete ou modifique arquivos nas pastas `/system/` ou `/dev/` a menos que saiba exatamente o que está fazendo, pois isso pode inutilizar o software do sistema (brick).
*   Transferências via Wi-Fi são mais lentas que via cabo Ethernet.

### Solução de Problemas
*   **Falha na Conexão:** Verifique se o Firewall do Windows não está bloqueando o FileZilla e se o IP do PS4 não mudou.
*   **Conexão Caindo:** Certifique-se de que o PS4 não entrou em modo de repouso durante a transferência. Desative o modo de repouso automático nas configurações de economia de energia.

## Download

[Baixar Tutorial: Como transferir arquivos para o PS4 via FTP com GoldHEN (página oficial)](https://filezilla-project.org/download.php?type=client)

Fonte: <https://goldhen.github.io/>
