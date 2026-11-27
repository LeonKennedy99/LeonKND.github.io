---
layout: post
title: "Tutorial: Como configurar o backup automático de saves via WebDAV no Apollo Save Tool"
description: "Proteja seus dados salvos enviando-os para nuvem privada via protocolo WebDAV."
download: "https://github.com/bucanero/apollo-ps4/releases"
date: 2026-11-27 15:01:35 -0300
categories: ps4 tutorial
---

O **Apollo Save Tool** é a ferramenta definitiva para gerenciar saves no PS4. Uma de suas funções mais poderosas, adicionada na versão 1.8.0, é o suporte ao protocolo **WebDAV**, que permite conectar o console a serviços de nuvem como Nextcloud, OwnCloud ou até mesmo servidores locais, facilitando o backup e a restauração de saves sem precisar de pendrives.

### Requisitos

* PS4 com GoldHEN e acesso à internet.
* **Apollo Save Tool v1.8.0** ou superior instalado.
* Conta ou servidor com suporte a **WebDAV** (URL, usuário e senha).

### Passo a Passo

1. **Acessar as Configurações**: Abra o Apollo Save Tool e navegue até o menu *Settings*.
2. **Configurar WebDAV**: Procure pela opção *WebDAV Server Configuration*.
3. **Preencher os Dados**: 
   * Digite a **URL** do seu servidor (ex: `http://192.168.1.10/remote.php/dav/files/user/`).
   * Insira o seu **Username** (Usuário).
   * Insira o seu **Password** (Senha ou Token de aplicativo).
4. **Testar Conexão**: Selecione a opção para testar a conexão. Se os dados estiverem corretos, o Apollo confirmará o acesso.
5. **Realizar o Backup**: 
   * Vá em *HDD Saves*.
   * Escolha o jogo desejado e selecione *Export Save*.
   * Escolha a opção *Upload to WebDAV*.
6. **Restauração**: Para baixar um save da nuvem para o PS4, vá no menu *Online DB / Cloud* e selecione seu servidor WebDAV para listar e baixar os arquivos.

### Solução de Problemas

* **Erro de Conexão**: Verifique se a URL termina com `/` e se o protocolo (http ou https) está correto. Alguns servidores exigem portas específicas (ex: `:8080`).
* **Certificado SSL**: Se estiver usando HTTPS com certificado autoassinado, o Apollo pode recusar a conexão por segurança.

### Aviso de Risco

Nunca compartilhe sua URL e senha de WebDAV com terceiros, pois isso dá acesso total aos seus saves e arquivos no servidor de nuvem configurado.

## Download

[Baixar Tutorial: Como configurar o backup automático de saves via WebDAV no Apollo Save Tool (página oficial)](https://github.com/bucanero/apollo-ps4/releases)

Fonte: <https://github.com/bucanero/apollo-ps4>
