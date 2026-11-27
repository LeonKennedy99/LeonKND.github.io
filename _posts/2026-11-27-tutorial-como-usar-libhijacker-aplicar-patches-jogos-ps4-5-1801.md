---
layout: post
title: "Tutorial: Como usar o Libhijacker para aplicar patches em jogos de PS4"
description: "Aprenda a instalar e configurar o Libhijacker para melhorar o desempenho dos seus jogos."
download: ""
date: 2026-11-27 18:01:06 -0300
categories: ps4 tutorial
---

Para utilizar o Libhijacker e aplicar patches de performance, siga estes passos: 1) Certifique-se de estar com o GoldHEN ativo. 2) Baixe o arquivo `libhijacker.elf` e os arquivos de patch (.json) compatíveis com o ID do seu jogo. 3) Transfira o arquivo `.elf` para a pasta /data/daemons/ ou use um enviador de payloads (como Netcat) na porta 9020. 4) No menu de configurações do GoldHEN, certifique-se de que o suporte a plugins está ativado. 5) Ao iniciar o jogo, o Libhijacker detectará automaticamente o Title ID e aplicará as correções de FPS ou resolução definidas nos arquivos de configuração localizados em `/data/patches/`. É a forma mais segura de rodar jogos a 60 FPS sem corromper os arquivos de instalação.

Fonte: <https://github.com/illusion0001/libhijacker>
