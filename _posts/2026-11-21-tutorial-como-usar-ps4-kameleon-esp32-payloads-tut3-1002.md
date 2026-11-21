---
layout: post
title: "Tutorial: Como usar o PS4-Kameleon para injetar Payloads via ESP32"
description: "Automatize o envio de payloads e host de exploits usando uma placa ESP32."
download: "https://github.com/KameleonMan/ESP32-Server-900u-Collections/releases"
date: 2026-11-21 10:02:11 -0300
categories: ps4 tutorial
---

### O que é o PS4-Kameleon?
O **PS4-Kameleon** é um firmware personalizado para placas **ESP32** (microcontroladores baratos). Ele transforma a placa em um servidor web Wi-Fi portátil que hospeda o exploit do PS4 e todos os payloads necessários (GoldHEN, FTP, BinLoader), eliminando a necessidade de usar a internet do roteador ou sites de terceiros que podem sair do ar.

### Requisitos
*   Uma placa **ESP32** (modelo comum DevKit V1).
*   Cabo USB para conexão no PC.
*   **ESP32 Flash Download Tool** (ferramenta oficial da Espressif).
*   Arquivos binários (.bin) do PS4-Kameleon.

### Passo a Passo
1.  **Gravação do Firmware:** Conecte o ESP32 ao PC. Abra o *Flash Download Tool*, selecione o arquivo `.bin` do Kameleon e clique em "Start" para gravar o firmware na placa.
2.  **Ligando no PS4:** Desconecte o ESP32 do PC e conecte-o em qualquer porta USB do seu PS4 (serve apenas para energia).
3.  **Conexão Wi-Fi:** No PS4, vá em `Configurações > Rede > Configurar conexão à Internet`. Escolha **Wi-Fi** e procure pela rede chamada `PS4-KAMELEON` (a senha padrão costuma ser `12345678`).
4.  **Acesso ao Host:** Abra o **Guia do Usuário** nas configurações do PS4. O menu do Kameleon será carregado instantaneamente.
5.  **Execução:** Selecione a versão do seu firmware (ex: 9.00 ou 11.00) e escolha o payload desejado (ex: GoldHEN). Siga as instruções na tela (como inserir o pendrive, se for o caso do exploit 9.00).

### Avisos de Risco
*   Certifique-se de que o PS4 não esteja configurado para conectar-se automaticamente a outras redes Wi-Fi, ou ele pode tentar baixar atualizações de sistema da Sony.

### Solução de Problemas
*   **A rede Wi-Fi não aparece:** Verifique se a placa ESP32 está recebendo energia suficiente (o LED interno deve estar aceso).
*   **Página não carrega:** Limpe os cookies e o cache do navegador do PS4 nas opções do browser antes de tentar acessar o Guia do Usuário novamente.

## Download

[Baixar Tutorial: Como usar o PS4-Kameleon para injetar Payloads via ESP32 (página oficial)](https://github.com/KameleonMan/ESP32-Server-900u-Collections/releases)

Fonte: <https://github.com/KameleonMan/ESP32-Server-900u-Collections>
