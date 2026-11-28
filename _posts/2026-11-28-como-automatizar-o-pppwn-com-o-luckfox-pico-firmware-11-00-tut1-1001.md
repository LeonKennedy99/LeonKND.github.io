---
layout: post
title: "Tutorial: Como automatizar o PPPwn com o Luckfox Pico (Firmware 11.00)"
description: "Use um microcontrolador de baixo custo para ativar o exploit automaticamente ao ligar o console."
download: "https://github.com/0x192/pppwn-luckfox/releases"
date: 2026-11-28 10:01:37 -0300
categories: ps4 tutorial
---

### O que é?
O **Luckfox Pico** é um microcontrolador extremamente acessível que pode ser programado para executar o exploit **PPPwn** de forma autônoma. Diferente de usar um computador ou celular, o Luckfox fica conectado permanentemente ao PS4 via cabo Ethernet e USB, realizando o jailbreak segundos após o console ser ligado.

### Requisitos
*   Console PS4 no **Firmware 11.00** (ou anterior compatível).
*   Placa **Luckfox Pico** (versões Mini, Plus ou Pro).
*   Cartão MicroSD (mínimo 4GB).
*   Cabo Ethernet e cabo USB-C para alimentação.
*   Software **Rufus** ou **BalenaEtcher** no PC.

### Passo a Passo
1.  **Preparação do SD:** Baixe a imagem `.img` mais recente do repositório oficial do `pppwn-luckfox` compatível com o seu modelo de placa.
2.  **Gravação:** Use o Rufus para gravar a imagem no cartão MicroSD. Insira o cartão no Luckfox.
3.  **Conexão:** Conecte o Luckfox ao PS4. O cabo Ethernet vai da placa à porta LAN do console. O cabo USB-C vai da placa a uma porta USB do PS4 (apenas para energia).
4.  **Configuração no PS4:** Vá em `Configurações` > `Rede` > `Configurar conexão à Internet`.
5.  Escolha `Usar cabo LAN` > `Personalizado` > `PPPoE`.
6.  Em `Usuário PPPoE` e `Senha PPPoE`, digite qualquer coisa (ex: `ppp`).
7.  Em `Configurações de DNS` e `MTU`, deixe em `Automático`. Em `Servidor Proxy`, escolha `Não usar`.
8.  **Execução:** Reinicie o PS4. O Luckfox detectará a tentativa de conexão PPPoE e iniciará o envio do exploit automaticamente. O GoldHEN será carregado se o arquivo `stage2.bin` estiver correto no dispositivo.

### Avisos de Risco
*   Certifique-se de usar a imagem correta para o seu modelo de Luckfox (o modelo Plus tem porta Ethernet nativa, o Mini exige adaptações).
*   Não interrompa o fornecimento de energia durante o primeiro boot da placa.

### Solução de Problemas
*   **O exploit falha repetidamente:** Verifique se o cabo Ethernet está bem encaixado ou tente trocar o cabo.
*   **LED do Luckfox não acende:** Verifique se a porta USB do PS4 está fornecendo energia (configurações de repouso).

## Download

[Baixar Tutorial: Como automatizar o PPPwn com o Luckfox Pico (Firmware 11.00) (página oficial)](https://github.com/0x192/pppwn-luckfox/releases)

Fonte: <https://github.com/0x192/pppwn-luckfox>
