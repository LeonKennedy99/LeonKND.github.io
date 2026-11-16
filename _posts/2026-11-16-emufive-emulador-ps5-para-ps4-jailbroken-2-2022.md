---
layout: post
title: "EmuFive v1.0.0: Emulador Experimental de PS5 chega ao PlayStation 4"
description: "Projeto baseado no KytyPS5 permite rodar jogos de PS5 via Linux no PS4 Pro."
date: 2026-11-16 20:22:30 -0300
categories: ps4 homebrew
---

O desenvolvedor blue0x1 (Chokri Hammedi) disponibilizou o **EmuFive**, um emulador experimental de PlayStation 5 projetado para rodar em consoles PS4 com jailbreak. O sistema opera através de uma distribuição Linux customizada, carregada pelo **PS4 Multiboot**, e utiliza o núcleo do KytyPS5 com patches específicos para traduzir instruções de CPU modernas (AVX2/FMA) para as capacidades do processador Jaguar do PS4.

Em testes iniciais no PS4 Pro, o jogo indie *God of War: Sons of Sparta* (exclusivo de PS5) foi executado a aproximadamente 40 FPS. O emulador conta com uma interface otimizada para o DualShock 4 e permite carregar jogos de dispositivos USB ou pastas compartilhadas via SMB.

**Instalação e Requisitos:**
* PS4 com GoldHEN e suporte a payloads de Linux.
* Instalação via PS4 Multiboot em uma partição de aproximadamente 28GB.
* O software não inclui arquivos de jogos; o usuário deve fornecer seus próprios dumps no formato eboot.bin ou .zar.

**Nota:** O projeto ainda é altamente experimental e muitos jogos 3D comerciais podem apresentar performance extremamente baixa ou incompatibilidade total.

## Download

[Baixar EmuFive v1.0.0: Emulador Experimental de PS5 chega ao PlayStation 4 (página oficial)](https://github.com/blue0x1/EmuFive)

Fonte: <https://github.com/blue0x1/EmuFive/releases>
