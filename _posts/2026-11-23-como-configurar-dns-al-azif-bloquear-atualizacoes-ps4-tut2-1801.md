---
layout: post
title: "Tutorial: Como configurar o DNS de Al-Azif para bloquear atualizações automáticas"
description: "Proteja seu desbloqueio impedindo que o PS4 se conecte aos servidores da Sony."
download: ""
date: 2026-11-23 18:01:34 -0300
categories: ps4 tutorial
---

Manter um PS4 desbloqueado exige que o console nunca instale uma atualização oficial de sistema (Firmware) por acidente. A forma mais segura de fazer isso, além de desativar as opções no menu, é configurar um **DNS customizado** que redireciona os endereços da Sony para um "buraco negro", impedindo o download de updates.

### Requisitos
*   PS4 ligado e conectado à rede (Wi-Fi ou Cabo).
*   Acesso às configurações de rede do console.

### Passo a Passo

1.  **Acesse a Rede:** No seu PS4, vá em **Configurações** > **Rede** > **Configurar conexão à Internet**.
2.  **Escolha o Método:** Selecione **Wi-Fi** ou **Cabo LAN**, dependendo do que você usa.
3.  **Configuração Personalizada:** Escolha a opção **Personalizada** (Custom).
4.  **Configurações de IP:** Selecione **Automático**.
5.  **Nome do Host DHCP:** Selecione **Não especificar**.
6.  **Configurações de DNS:** Aqui está a parte crucial. Escolha **Manual** e insira os seguintes endereços (mantidos pela comunidade Al-Azif):
    *   **DNS Primário:** `165.227.83.145`
    *   **DNS Secundário:** `192.241.221.79`
7.  **Finalização:** Continue o processo selecionando **Automático** para MTU e **Não usar** para Servidor Proxy.
8.  **Teste de Conexão:** Ao final, teste a conexão. O item "Acesso ao PlayStation Network" deve resultar em **Falha**, o que é o comportamento esperado para garantir sua segurança.

### Avisos de Risco
*   O uso de DNS de terceiros depende da estabilidade dos servidores dos mantenedores. Se a internet parar de funcionar no PS4, os servidores DNS podem estar fora do ar.
*   Este método não substitui a atenção do usuário: nunca confirme um pedido de atualização de sistema.

### Solução de Problemas
*   **O PS4 continua tentando baixar o update:** Vá em **Configurações** > **Sistema** > **Downloads automáticos** e desmarque todas as opções.
*   **Erro de conexão após configurar:** Verifique se digitou os números corretamente. Um único dígito errado impedirá qualquer acesso à internet.

Fonte: <https://github.com/Al-Azif/ps4-exploit-host>
