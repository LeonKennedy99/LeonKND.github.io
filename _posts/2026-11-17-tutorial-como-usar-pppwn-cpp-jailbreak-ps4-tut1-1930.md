---
layout: post
title: "Tutorial: Como usar o PPPwn C++ para Jailbreak no PS4 (Firmwares compatíveis)"
description: "Guia passo a passo para realizar o exploit PPPwn usando a versão em C++ mais rápida e estável."
download: "https://github.com/xfangfang/PPPwn_cpp/releases"
date: 2026-11-17 19:30:59 -0300
categories: ps4 tutorial
---

### O que é o PPPwn C++?
O **PPPwn** é um exploit de kernel para o PlayStation 4 que utiliza uma vulnerabilidade na pilha de rede PPPoE. A versão **C++** é uma implementação otimizada da ferramenta original (feita em Python), sendo muito mais rápida e eficiente para rodar em computadores modestos ou dispositivos embarcados.

### Requisitos
*   Um PS4 em firmware compatível (até 11.00, ou versões superiores conforme suporte da cena em 2026).
*   Cabo de rede Ethernet (LAN).
*   Um computador (Windows ou Linux) ou um Raspberry Pi.
*   O arquivo `stage1.bin` e `stage2.bin` correspondentes ao seu firmware.
*   O executável do **PPPwn_cpp**.

### Passo a Passo
1.  **Preparação no PC:** Baixe a versão mais recente do PPPwn_cpp no link oficial e extraia os arquivos. Coloque o `stage1.bin` e o `stage2.bin` do seu firmware na mesma pasta do executável.
2.  **Configuração do PS4:**
    *   Vá em **Configurações** > **Rede** > **Configurar conexão à Internet**.
    *   Escolha **Usar cabo de rede (LAN)** e selecione **Personalizado**.
    *   Em **Configurações de Endereço IP**, escolha **PPPoE**.
    *   Coloque qualquer usuário e senha (ex: `admin` / `admin`).
    *   Em **Configurações de DNS** e **MTU**, deixe em **Automático**.
    *   Em **Servidor Proxy**, escolha **Não usar**.
3.  **Conexão Física:** Conecte o cabo Ethernet entre o seu PS4 e o seu PC.
4.  **Execução do Exploit:**
    *   No PC, abra o terminal ou prompt de comando na pasta do PPPwn_cpp.
    *   Execute o comando identificando sua interface de rede: `pppwn.exe --interface "NomeDaSuaInterface" --fw 1100 --stage1 stage1.bin --stage2 stage2.bin` (ajuste o número do firmware conforme o seu).
5.  **Finalização:** No PS4, clique em **Testar conexão à Internet**. O script no PC começará a enviar os pacotes. Se aparecer a mensagem "PPPwned" no console, o exploit foi bem-sucedido.

### Avisos de Risco
*   O exploit pode falhar e causar o desligamento repentino do console (Kernel Panic). Isso é normal na cena jailbreak e raramente causa danos permanentes, mas evite fazer isso repetidamente se o console estiver superaquecido.
*   Sempre verifique se está usando os arquivos `stage` corretos para a sua versão de sistema.

### Solução de Problemas
*   **Erro de Timeout:** Verifique se o cabo está bem conectado e se a interface de rede selecionada no PC é a correta.
*   **Falha no Stage 1:** Reinicie o PS4 e o aplicativo no PC e tente novamente. O exploit via rede pode exigir algumas tentativas.

## Download

[Baixar Tutorial: Como usar o PPPwn C++ para Jailbreak no PS4 (Firmwares compatíveis) (página oficial)](https://github.com/xfangfang/PPPwn_cpp/releases)

Fonte: <https://github.com/TheOfficialFloW/PPPwn>
