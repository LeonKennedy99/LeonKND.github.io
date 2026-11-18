---
layout: post
title: "Tutorial: Como usar o Chiaki para Remote Play do PS4 no PC e Steam Deck"
description: "Aprenda a transmitir a tela do seu PS4 para outros dispositivos sem usar o app oficial."
download: "https://github.com/thestr4ng3r/chiaki/releases"
date: 2026-11-18 18:01:43 -0300
categories: ps4 tutorial
---

### O que é o Chiaki?
O Chiaki é um cliente gratuito e de código aberto para a função Remote Play (Reprodução Remota) do PlayStation 4 e PlayStation 5. Ao contrário do aplicativo oficial da Sony, o Chiaki funciona em diversas plataformas (Windows, Linux, macOS, Android e Steam Deck) e permite maior flexibilidade de configuração em consoles com o uso de GoldHEN.

### Requisitos
*   **Console:** PS4 com GoldHEN (compatível até firmware 14.02).
*   **ID da Conta (AccountID):** Necessário para vincular o console. Você pode obter isso usando o **Apollo Save Tool** (já presente na cena).
*   **Rede:** Console e computador/dispositivo na mesma rede local (preferência por cabo para menor latência).
*   **Software:** Instalador do Chiaki no dispositivo de destino.

### Passo a Passo
1.  **Obtenha seu AccountID:** Abra o *Apollo Save Tool* no seu PS4, vá em "User Tools" e anote o seu "Account ID" (uma sequência de 16 caracteres hexadecimais).
2.  **Prepare o PS4:** No menu do PS4, vá em **Configurações > Configurações de Conexão para o Uso Remoto > Adicionar Dispositivo**. O console exibirá um código de 8 dígitos. Mantenha essa tela aberta.
3.  **Configure o Chiaki:** No seu PC ou Steam Deck, abra o Chiaki. Ele deve detectar automaticamente o seu PS4 na rede.
4.  **Vinculação:** Clique no ícone do console detectado. No campo **Account ID**, insira o ID que você obteve no Apollo. No campo **PIN**, insira o código de 8 dígitos que aparece na TV.
5.  **Conexão:** Clique em "Register". Após a confirmação, basta dar um clique duplo no ícone do console no Chiaki para iniciar a transmissão.

### Avisos de Risco
*   O uso de Remote Play não oferece riscos de banimento em consoles offline ou com DNS de bloqueio, mas o desempenho depende totalmente da qualidade do seu roteador.
*   Não forneça seu Account ID para terceiros, pois ele é exclusivo da sua conta local.

### Solução de Problemas
*   **O PS4 não aparece no Chiaki:** Verifique se o console e o PC estão na mesma sub-rede (ex: ambos no 192.168.1.x).
*   **A imagem está travando:** Reduza a resolução para 720p e o FPS para 30 nas configurações do Chiaki se o seu Wi-Fi for 2.4GHz.

## Download

[Baixar Tutorial: Como usar o Chiaki para Remote Play do PS4 no PC e Steam Deck (página oficial)](https://github.com/thestr4ng3r/chiaki/releases)

Fonte: <https://www.psx-place.com/threads/chiaki-open-source-ps4-remote-play-client.24640/>
