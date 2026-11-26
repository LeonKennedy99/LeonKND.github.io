---
layout: post
title: "Tutorial: Como configurar o Chiaki para Remote Play no PS4 com GoldHEN"
description: "Use o Remote Play no PC, Linux ou Android sem precisar de conta PSN ativa."
download: "https://github.com/thestr4ng3r/chiaki/releases"
date: 2026-11-26 15:01:36 -0300
categories: ps4 tutorial
---

O **Chiaki** é um cliente de código aberto para Remote Play que permite transmitir a tela do seu PS4 para um PC ou dispositivo móvel. A grande vantagem para usuários da cena é permitir o uso do recurso em consoles desbloqueados que não podem se conectar à PSN.

### Requisitos
* PS4 com GoldHEN.
* PC (Windows/Linux) ou Android na mesma rede.
* **Account ID** do seu usuário do PS4 (obtido via Apollo Save Tool ou Payload).
* Console com a função Remote Play habilitada.

### Passo a Passo
1. **Obtendo o ID da Conta:** No PS4, abra o *Apollo Save Tool*. Vá em "User Tools" e selecione "Export Account ID". Anote o código de 16 caracteres hexadecimais.
2. **Habilitando o Console:** Vá em Configurações > Configurações de Conexão para o Uso Remoto > Adicionar Dispositivo. O PS4 exibirá um código de 8 dígitos (PIN).
3. **Configuração no Chiaki:** No PC, abra o Chiaki. Ele deve detectar seu PS4 automaticamente. Dê um duplo clique no ícone do console.
4. **Registro:** No campo "PSN Account ID (base64)", você deve converter seu ID de 16 caracteres para o formato correto (existem conversores online ou use o valor direto se o Chiaki pedir o hexadecimal).
5. **PIN de Registro:** Insira o PIN de 8 dígitos que aparece na TV do seu PS4 e clique em "Register".
6. **Conectar:** Após o registro bem-sucedido, basta clicar duas vezes no console na lista do Chiaki para iniciar a transmissão.

### Avisos de Risco
* **Latência:** A experiência depende totalmente da qualidade do roteador. Use 5GHz ou cabo para evitar travamentos.
* **Segurança:** Nunca compartilhe seu Account ID publicamente.

### Solução de Problemas
* **Tela Preta:** Verifique se o PS4 está ligado ou em modo de repouso com a opção de despertar via rede ativa.
* **Erro de Registro:** Certifique-se de que o ID da conta inserido é exatamente o que está vinculado ao perfil que você está tentando controlar.

## Download

[Baixar Tutorial: Como configurar o Chiaki para Remote Play no PS4 com GoldHEN (página oficial)](https://github.com/thestr4ng3r/chiaki/releases)

Fonte: <https://github.com/thestr4ng3r/chiaki>
