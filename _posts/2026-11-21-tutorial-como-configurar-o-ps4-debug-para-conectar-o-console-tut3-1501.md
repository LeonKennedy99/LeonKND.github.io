---
layout: post
title: "Tutorial: Como configurar o PS4 Debug para conectar o console ao PC"
description: "Habilite a comunicação remota entre seu computador e o PlayStation 4."
download: "https://github.com/GoldHEN/ps4debug/releases"
date: 2026-11-21 15:01:36 -0300
categories: ps4 tutorial
---

O **PS4 Debug** (ps4debug) é um payload que estabelece um servidor de depuração no console. Ele é fundamental para desenvolvedores de homebrew e para o uso de ferramentas de PC que interagem diretamente com a memória do console, como editores de memória e gerenciadores de arquivos externos.

### Requisitos

* PS4 com Jailbreak.
* PC conectado na mesma rede local que o PS4.
* Um injetor de payload (como Netcat ou o injetor do GoldHEN).

### Passo a Passo

1.  **Ativar o Payload**: No PS4, se você usa o GoldHEN, o **ps4debug** geralmente já vem integrado. Vá em **Configurações > GoldHEN > Service Settings** e ative a opção 'Enable ps4debug'.
2.  **Verificar IP**: Vá em **Configurações > Rede > Exibir Status da Conexão** e anote o endereço IP do seu PS4.
3.  **Conexão via PC**: No computador, abra a ferramenta que deseja usar (como um editor de cheats ou o PS4 Trainer). Insira o IP do console e a porta padrão (geralmente 9099).
4.  **Uso em Jogos**: Com o ps4debug ativo, você pode iniciar um jogo e o software no PC detectará automaticamente o processo rodando, permitindo a leitura e escrita na memória.

### Avisos de Risco

* **Segurança**: O ps4debug abre uma porta de comunicação na sua rede. Nunca use o console em redes públicas com este serviço ativo.
* **Estabilidade**: Manipular a memória do console de forma incorreta via PC causará o desligamento imediato do sistema (Kernel Panic).

### Solução de Problemas

* **Falha na Conexão**: Verifique se o firewall do Windows não está bloqueando a comunicação. Certifique-se de que o PS4 e o PC não estão em sub-redes diferentes (ex: um no Wi-Fi 2.4Ghz e outro no 5Ghz de roteadores diferentes).
* **Porta Ocupada**: Certifique-se de que outros payloads de rede (como o FTP) não estão tentando usar a mesma porta de depuração.

## Download

[Baixar Tutorial: Como configurar o PS4 Debug para conectar o console ao PC (página oficial)](https://github.com/GoldHEN/ps4debug/releases)

Fonte: <https://github.com/GoldHEN/ps4debug>
