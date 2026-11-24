---
layout: post
title: "Garlic LLM: Executando Modelos de IA de 9 Bilhões de Parâmetros Offline no PS4"
description: "Inteligência Artificial offline rodando diretamente na GPU do PS4."
download: "https://github.com/leonardo-alegria/garlic-llm/releases"
date: 2026-11-24 18:01:19 -0300
categories: ps4 homebrew
---

O desenvolvedor Leonardo Alegría lançou o **Garlic LLM**, um projeto inovador que permite ao PlayStation 4 executar o modelo de linguagem **Qwen3.5-9B** da Alibaba de forma totalmente offline. O homebrew ignora as camadas de drivers padrão para se comunicar diretamente com a GPU do console (arquitetura GCN), alcançando velocidades impressionantes de até 43 tokens por segundo em geração de código.

Para contornar a limitação de 8GB de memória compartilhada do PS4, o modelo foi comprimido usando quantização de 4-bit e 3-bit, resultando em um arquivo de aproximadamente 4,5 GB. Além do chat de texto, o aplicativo suporta conversação por voz através do modelo *Chatterbox* e ditado com o *Parakeet TDT* da Nvidia, suportando diversos idiomas, incluindo o português.

**Compatibilidade:**
* Firmware: 9.00, 9.04, 11.00, 11.52, 12.02, 12.50, 13.52 e 14.00.
* Requer GoldHEN ativo.

**Como usar:**
1. Instale o arquivo PKG através do *Package Installer*.
2. Inicie o app pela home screen. No primeiro uso, o sistema carregará os modelos na memória.
3. Para usar um teclado físico, conecte-o via USB e pressione OPTIONS para abrir o console de digitação.

## Download

[Baixar Garlic LLM: Executando Modelos de IA de 9 Bilhões de Parâmetros Offline no PS4 (página oficial)](https://github.com/leonardo-alegria/garlic-llm/releases)

Fonte: <https://www.tomshardware.com/news/jailbroken-ps4-runs-9-billion-parameter-ai-model>
