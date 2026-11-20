---
layout: post
title: "Tutorial: Como bloquear atualizações automáticas no PS4 usando DNS"
description: "Mantenha seu console em uma firmware específica bloqueando os servidores da Sony."
download: ""
date: 2026-11-20 10:01:28 -0300
categories: ps4 tutorial
---

### O que é
O bloqueio por DNS é uma técnica que redireciona as tentativas de conexão do PS4 com os servidores de atualização da Sony para um servidor vazio ou para um host de payloads. Isso evita que o console baixe e instale atualizações que poderiam remover o Jailbreak.

### Requisitos
* PS4 conectado à internet (Wi-Fi ou Cabo).
* Conhecimento dos endereços DNS da comunidade (ex: Al-Azif ou similares).

### Passo a Passo
1. No menu do PS4, vá em **Configurações** > **Rede** > **Configurar conexão à Internet**.
2. Escolha **Wi-Fi** ou **Cabo LAN** e selecione a opção **Personalizada**.
3. Em Endereço IP, selecione **Automático**.
4. Em Nome do Host DHCP, selecione **Não especificar**.
5. Em **Configurações de DNS**, escolha **Manual**.
6. Digite os seguintes endereços (comumente usados pela cena):
   - **DNS Primário:** `192.241.221.79` 
   - **DNS Secundário:** `165.227.83.145` 
7. Em Configurações de MTU, selecione **Automático**.
8. Em Servidor Proxy, selecione **Não usar**.
9. Teste a conexão. Se o bloqueio estiver funcionando, o teste de 'Conexão à Internet' deve passar, mas o acesso à PlayStation Network pode falhar propositalmente.

### Avisos de Risco
* O bloqueio por DNS não é 100% infalível se a Sony mudar os IPs de seus servidores ou se os servidores DNS ficarem offline.
* Desative as opções de "Download Automático" em **Sistema** > **Downloads Automáticos** como precaução extra.

### Solução de Problemas
* **Sem conexão à internet:** Se o console não navegar, os servidores DNS escolhidos podem estar fora do ar. Tente usar o DNS secundário como primário ou procure por endereços atualizados na comunidade.

Fonte: <https://wololo.net/2023/12/28/ps4-how-to-block-updates-on-your-ps4-and-why-you-should-do-it/>
