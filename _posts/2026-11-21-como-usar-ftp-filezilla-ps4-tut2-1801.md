---
layout: post
title: "Tutorial: Como transferir arquivos para o PS4 via FTP usando FileZilla"
description: "Transfira saves, músicas e arquivos sem precisar de pendrives."
download: "https://filezilla-project.org/download.php?show_all=1"
date: 2026-11-21 18:01:39 -0300
categories: ps4 tutorial
---

O protocolo FTP (File Transfer Protocol) é a forma mais eficiente de gerenciar os arquivos internos do seu PS4 sem precisar remover o HD ou usar dispositivos USB constantemente. Com ele, você acessa as pastas do sistema diretamente pelo seu computador.

### Requisitos
*   PS4 com GoldHEN ou um payload de FTP ativado.
*   Computador e PS4 conectados na mesma rede local (preferencialmente via cabo).
*   Cliente FTP instalado no PC (o FileZilla é o mais recomendado).

### Passo a Passo
1.  **Ativar o Servidor no PS4:** No menu do GoldHEN, vá em **Settings** > **Servers** e ative a opção **FTP Server**. Anote o endereço IP e a porta (geralmente 1337) que aparecerão na notificação.
2.  **Configurar o FileZilla:** No seu PC, abra o FileZilla. No campo 'Host', digite o IP do PS4. No campo 'Porta', digite 1337 (ou a informada pelo console). Deixe usuário e senha em branco.
3.  **Conexão:** Clique em 'Conexão Rápida'. Se aparecer um aviso sobre conexão não segura, confirme em OK.
4.  **Navegação:** O lado direito do FileZilla mostrará as pastas do PS4. As pastas mais comuns são:
    *   `/data`: Onde ficam salvos os dados de homebrews.
    *   `/user/home`: Local dos perfis e saves.
    *   `/mnt/usb0`: O pendrive espetado no console.
5.  **Transferência:** Para enviar um arquivo, basta arrastá-lo do seu PC (lado esquerdo) para a pasta desejada no PS4 (lado direito).

### Avisos de Risco
*   **Arquivos do Sistema:** Nunca delete ou modifique arquivos nas pastas `/system`, `/dev` ou na raiz, a menos que saiba exatamente o que está fazendo. Isso pode causar um brick lógico, exigindo a reinstalação do firmware.

### Solução de Problemas
*   **Conexão Recusada:** Verifique se o Firewall do Windows está bloqueando o FileZilla e se o PS4 não entrou em modo de repouso.
*   **Velocidade Baixa:** O Wi-Fi do PS4 (especialmente no modelo FAT) é lento. Use cabo de rede para transferências de arquivos grandes.

## Download

[Baixar Tutorial: Como transferir arquivos para o PS4 via FTP usando FileZilla (página oficial)](https://filezilla-project.org/download.php?show_all=1)

Fonte: <https://www.psxhax.com/threads/ps4-ftp-server-payload-guide-for-playstation-4-homebrew.4172/>
