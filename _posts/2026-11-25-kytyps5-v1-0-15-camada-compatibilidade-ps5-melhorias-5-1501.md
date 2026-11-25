---
layout: post
title: "KytyPS5 v1.0.15: Camada de Compatibilidade PS5 Recebe Melhorias no PS4"
description: "O projeto que traz apps de PS5 para o PS4 ganha boost de performance."
download: "https://github.com/blue0x1/KytyPS5/releases"
date: 2026-11-25 15:01:25 -0300
categories: ps4 homebrew
---

O **KytyPS5**, projeto de blue0x1 que atua como uma camada de tradução para rodar homebrews de PS5 no hardware do PS4, foi atualizado para a versão **v1.0.15**. Esta versão foca em performance bruta, reescrevendo instruções AVX2 (do PS5) para SSE4.2/AVX compatíveis com o processador Jaguar do PS4.

### O que mudou:
- **GPU Submit Thread:** Novo motor de submissão de tarefas para a GPU que aumenta o FPS em apps 3D (exemplo: *Another Crab's Treasure* subiu de 4 para 17 FPS).
- **Crash Reporting:** Agora o app gera logs detalhados em `/user/app/PS5-reports` em caso de erro.
- **Gestão de Memória:** Avisos nativos quando a memória RAM está próxima do limite.

## Download

[Baixar KytyPS5 v1.0.15: Camada de Compatibilidade PS5 Recebe Melhorias no PS4 (página oficial)](https://github.com/blue0x1/KytyPS5/releases)

Fonte: <https://github.com/blue0x1/KytyPS5>
