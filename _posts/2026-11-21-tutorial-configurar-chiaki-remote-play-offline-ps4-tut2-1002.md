---
layout: post
title: "Tutorial: Como configurar o Chiaki para Remote Play offline no PS4"
description: "Use o Remote Play no PC ou Steam Deck sem precisar de conexão com a PSN."
download: "https://github.com/thestr4ng3r/chiaki/releases"
date: 2026-11-21 10:02:10 -0300
categories: ps4 tutorial
---

### O que é o Chiaki?
O **Chiaki** é um cliente de código aberto para o Remote Play da Sony. No PS4 com Jailbreak, ele é essencial porque permite que você transmita a tela do console para um PC, Android ou Steam Deck sem a necessidade de estar logado na PlayStation Network (PSN).

### Requisitos
*   PS4 com GoldHEN ativado.
*   PC, Linux ou dispositivo portátil na mesma rede local.
*   **Account ID (Base64):** Você precisará do ID da sua conta local (obtido via GoldHEN ou Apollo Save Tool).

### Passo a Passo
1.  **Obter seu Account ID:** No PS4, abra o **Apollo Save Tool**, vá em "User Tools" e anote o seu "Account ID" de 16 caracteres hexadecimais.
2.  **Instalação:** Baixe e instale o Chiaki no seu dispositivo (PC ou Steam Deck).
3.  **Descoberta do Console:** Abra o Chiaki. Se o PS4 estiver ligado e na mesma rede, ele aparecerá automaticamente na lista. Caso contrário, adicione manualmente pelo IP.
4.  **Registro:** Clique duas vezes no ícone do PS4 no Chiaki. Uma janela de registro será aberta.
5.  **Configuração de PIN:** No PS4, vá em `Configurações > Configurações de Conexão para o Uso Remoto > Adicionar Dispositivo`. Um código de 8 dígitos será exibido.
6.  **Finalização no Chiaki:** No Chiaki, insira o código de 8 dígitos do PS4 e, no campo "Account ID", insira o ID que você obteve no passo 1. Clique em **Register**.
7.  **Uso:** Uma vez registrado, basta clicar no console para iniciar a transmissão.

### Avisos de Risco
*   A performance depende totalmente da qualidade da sua rede Wi-Fi ou cabo. Recomenda-se usar cabo de rede no PS4 para evitar latência (lag).

### Solução de Problemas
*   **Erro de Registro:** Verifique se o Account ID está correto. Se o ID hexadecimal não funcionar, tente convertê-lo para Base64 usando conversores online.
*   **Tela Verde/Artefatos:** Reduza a resolução de 1080p para 720p nas configurações do Chiaki.

## Download

[Baixar Tutorial: Como configurar o Chiaki para Remote Play offline no PS4 (página oficial)](https://github.com/thestr4ng3r/chiaki/releases)

Fonte: <https://sr.ht/~thestr4ng3r/chiaki/>
