---
layout: post
title: "Tutorial: Como configurar o PPPwn em um microcontrolador ESP32-S3"
description: "Automatize o jailbreak do seu PS4 11.00 usando uma placa ESP32-S3 barata e eficiente."
download: "https://github.com/uberguled/ESP32-S3-PPPwn/releases"
date: 2026-11-24 15:01:49 -0300
categories: ps4 tutorial
---

### O que é?
Este tutorial ensina como transformar um microcontrolador **ESP32-S3** em um injetor automático para o exploit **PPPwn**. Ao conectar a placa ao PS4 via USB e cabo LAN, o exploit é executado assim que o console liga, eliminando a necessidade de um PC ou Raspberry Pi caro.

### Requisitos
* Placa ESP32-S3 (deve ter suporte a USB nativo).
* Cabo de rede (Ethernet) e um adaptador LAN para USB (ou conectar a placa diretamente se for um modelo específico com Ethernet).
* Firmware do PS4 compatível (9.00 a 11.00).
* PC para gravar o firmware inicial na placa.

### Passo a Passo
1. **Flash da Placa:** Conecte o ESP32-S3 ao PC. Use um gravador de firmware (como o ESP Web Flasher) para carregar o arquivo `.bin` do projeto ESP32-S3-PPPwn.
2. **Configuração de Rede:** No PS4, vá em Configurações > Rede > Configurar conexão à Internet > Usar cabo de rede (LAN) > Personalizado.
3. **Configuração PPPoE:** Em 'Configurações de Endereço IP', escolha 'PPPoE'. Digite qualquer nome de usuário e senha (ex: `ppp`).
4. **DNS e MTU:** Deixe o DNS em Automático e o MTU em Automático. Em Servidor Proxy, escolha 'Não usar'.
5. **Conexão Física:** Conecte o cabo LAN entre o PS4 e o adaptador de rede ligado ao ESP32-S3. Conecte o ESP32-S3 em uma porta USB do PS4 para alimentação.
6. **Execução:** Teste a conexão à Internet no PS4. O ESP32-S3 detectará a tentativa de conexão PPPoE e iniciará a injeção do payload automaticamente. A mensagem 'PPPwned' aparecerá no canto da tela quando o GoldHEN for carregado.

### Avisos de Risco
* Certifique-se de comprar a versão **S3** do ESP32, pois as versões comuns (como a WROOM-32) podem não ter os recursos necessários para este exploit específico sem hardware adicional.
* O processo é seguro, mas falhas na gravação do firmware podem 'brickar' temporariamente a placa (resolvível com novo flash).

### Solução de Problemas
* **Falha no PPPoE:** Verifique se o cabo LAN está funcionando e se o adaptador de rede é compatível com o ESP32.
* **Exploit não inicia:** Verifique se o arquivo `stage2.bin` correto para a sua versão de firmware está configurado na placa.

## Download

[Baixar Tutorial: Como configurar o PPPwn em um microcontrolador ESP32-S3 (página oficial)](https://github.com/uberguled/ESP32-S3-PPPwn/releases)

Fonte: <https://github.com/uberguled/ESP32-S3-PPPwn>
