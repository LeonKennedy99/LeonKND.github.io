---
layout: post
title: "Tutorial: Como enviar Payloads para o PS4 usando o Netcat GUI"
description: "Envie arquivos .bin como o Linux Loader ou FTP via rede local de forma simples."
download: "https://github.com/Modded-Warfare/Netcat-GUI/releases"
date: 2026-11-22 10:01:52 -0300
categories: ps4 tutorial
---

### O que é?
O **Netcat GUI** é uma interface simplificada para computadores que facilita o envio de Payloads (arquivos .bin) para o PlayStation 4. É útil para carregar ferramentas que não estão inclusas no seu host habitual, como versões específicas de depuradores ou carregadores de sistemas alternativos.

### Requisitos
* PS4 e PC conectados na mesma rede local.
* Console com exploit ativado e a opção "Bin Loader" (porta 9020 ou 9021) ligada.
* Payload em formato `.bin` que você deseja enviar.

### Passo a Passo
1.  **Prepare o PS4:** Ative o GoldHEN e vá no menu de configurações do exploit. Procure pela opção "Bin Loader Server" e ative-a. O PS4 exibirá uma notificação dizendo que está aguardando um payload.
2.  **Identifique o IP:** Anote o endereço IP do seu console (disponível em Configurações > Rede > Exibir Status da Conexão).
3.  **Configure o Netcat GUI no PC:** Abra o programa e, no campo "IP Address", digite o IP do seu PS4.
4.  **Defina a Porta:** Geralmente, a porta padrão é a `9020`. Verifique no seu console se o Bin Loader está usando essa porta.
5.  **Selecione o arquivo:** Clique em 'Browse' ou arraste o arquivo `.bin` para dentro da ferramenta.
6.  **Envie:** Clique no botão 'Inject Payload' ou 'Send'.
7.  **Sucesso:** Se tudo estiver correto, o console exibirá uma mensagem de sucesso e executará a função do payload imediatamente.

### Avisos de Risco
* **Payloads Incompatíveis:** Nunca envie um payload destinado a uma versão de firmware diferente da sua, pois isso causará um Kernel Panic e desligará o console abruptamente.

### Solução de Problemas
* **Falha na conexão:** Verifique se o Firewall do Windows está bloqueando o Netcat GUI. Desative-o temporariamente ou crie uma exceção.
* **Console trava ao receber:** Certifique-se de que não há outro payload rodando simultaneamente que possa causar conflitos de memória.

## Download

[Baixar Tutorial: Como enviar Payloads para o PS4 usando o Netcat GUI (página oficial)](https://github.com/Modded-Warfare/Netcat-GUI/releases)

Fonte: <https://github.com/Modded-Warfare/Netcat-GUI>
