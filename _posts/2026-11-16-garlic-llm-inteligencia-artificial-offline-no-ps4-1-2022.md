---
layout: post
title: "Garlic LLM: Inteligência Artificial Offline rodando nativamente no PS4"
description: "Rode o modelo Qwen3.5-9B diretamente na GPU do seu console jailbroken."
date: 2026-11-16 20:22:29 -0300
categories: ps4 homebrew
---

O desenvolvedor Leonardo Alegría lançou o **Garlic LLM**, um projeto inovador que permite rodar modelos de linguagem de grande escala (LLM) offline no PlayStation 4. O homebrew utiliza a GPU do console de 2013 para processar o modelo **Qwen3.5-9B** da Alibaba, alcançando velocidades de 31 a 39 tokens por segundo em chat de texto e até 43 tokens por segundo em geração de código.

O grande diferencial do Garlic LLM é que ele conversa diretamente com a GPU através de kernels OpenCL C otimizados para a arquitetura GCN, ignorando as camadas de drivers tradicionais. O modelo foi quantizado para 4 bits e 3 bits para caber nos 8GB de memória compartilhada do sistema. Além do chat, o app suporta conversação por voz em sete idiomas (incluindo Português) e ditado local usando o modelo Parakeet da Nvidia.

**Compatibilidade:**
* Firmware testado: 11.52 (relatado funcionando em 9.04, 11.00 e 14.00).
* Requer GoldHEN ativo.
* Necessário cerca de 6GB a 12GB de espaço livre no HD interno.

**Como usar:**
Basta instalar o arquivo PKG oficial através do *Package Installer* nas configurações de Debug do GoldHEN. Uma vez instalado, o Garlic LLM funciona de forma 100% offline, sem necessidade de PC ou conexão com a internet.

## Download

[Baixar Garlic LLM: Inteligência Artificial Offline rodando nativamente no PS4 (página oficial)](https://github.com/leonardo-alegria/garlic-llm)

Fonte: <https://huggingface.co/leonardo-alegria/garlic-llm>
