---
layout: post
title: "Tutorial: Como Configurar o PPPwn-Server no Windows para Jailbreak Automático"
description: "Aprenda a deixar o seu PC pronto para injetar o exploit sempre que ligar o console."
download: ""
date: 2026-11-23 18:00:55 -0300
categories: ps4 tutorial
---

Com o avanço do exploit PPPwn para o firmware 11.00, o uso de servidores locais no Windows tornou-se a forma mais estável de desbloqueio. Este tutorial ensina a configurar o ambiente necessário.

**Requisitos:**
- PC com Windows e porta Ethernet.
- Cabo de rede (LAN).
- Arquivos do PPPwn (C++ ou Python).
- Npcap instalado no Windows.

**Passo a Passo:**
1. Instale o **Npcap** com a opção 'Loopback Adapter' marcada.
2. Baixe a versão mais recente do PPPwn GUI ou Loader.
3. Conecte o cabo de rede entre o PC e o PS4.
4. No PS4, vá em Configurações > Rede > Configurar conexão à Internet > Usar cabo LAN > Personalizado > PPPoE.
5. Coloque qualquer nome e senha (ex: 'ppp').
6. No PC, execute o Loader, escolha sua placa de rede e a versão do firmware.
7. No PS4, escolha 'Não usar' para Servidor Proxy e, ao final, selecione 'Testar Conexão'.
8. O script no PC detectará a solicitação e enviará o payload automaticamente.

Fonte: <https://github.com/TheOfficialFloW/PPPwn>
