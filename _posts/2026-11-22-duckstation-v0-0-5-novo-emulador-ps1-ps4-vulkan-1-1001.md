---
layout: post
title: "DuckStation v0.0.5: Novo Emulador de PS1 para PS4 com Suporte a Vulkan"
description: "Porte do aclamado emulador chega ao PS4 com alta performance."
download: "https://github.com/NeomaMonroy/DuckStation-PS4/releases"
date: 2026-11-22 10:01:23 -0300
categories: ps4 homebrew
---

O desenvolvedor Neoma lançou uma atualização significativa para o porte de **DuckStation** no PlayStation 4. Baseado no fork de Nintendo Switch da RSDuck, este homebrew permite a emulação de jogos de PlayStation 1 com melhorias visuais impressionantes. A versão v0.0.5 traz correções críticas para o sistema de RetroAchievements, resolvendo o erro de conexão HTTPS, e habilita o teclado nativo do PS4 para login e configurações.

### Principais Características:
- **Renderização via Vulkan:** Utiliza o driver Mesa RADV para rodar jogos em 1080p nativo.
- **Upscaling:** Suporte para aumento de resolução interna em até 16x.
- **Correção Geométrica (PGXP):** Reduz o efeito de 'polígonos trêmulos' e texturas distorcidas típicas do hardware original.
- **Funcionalidades Extras:** Suporte a Save States, Rebobinamento (Rewind), filtragem de textura e vibração nos controles DualShock 4.

### Como Instalar:
1. Certifique-se de estar com o **GoldHEN** ativo no console.
2. Coloque o arquivo `.pkg` na raiz de um pendrive formatado em exFAT ou FAT32.
3. Instale através do menu **Settings > Debug Settings > Game > Package Installer**.
4. Na primeira execução, o app criará a pasta `/data/DuckStation/`. Coloque suas BIOS em `/data/DuckStation/bios/` e as ROMs em `/data/DuckStation/games/`.

## Download

[Baixar DuckStation v0.0.5: Novo Emulador de PS1 para PS4 com Suporte a Vulkan (página oficial)](https://github.com/NeomaMonroy/DuckStation-PS4/releases)

Fonte: <https://www.brewology.com/ps4/>
