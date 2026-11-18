---
layout: post
title: "Tutorial: Como configurar o PPPwn no Raspberry Pi para Jailbreak Automático"
description: "Transforme seu Raspberry Pi em um injetor de exploit automático via porta Ethernet."
download: "https://github.com/PSXIT/PPPwn-Pi/releases"
date: 2026-11-18 15:01:43 -0300
categories: ps4 tutorial
---

O PPPwn é um exploit de kernel via PPPoE. Usar um Raspberry Pi é a forma mais eficiente de automatizar o processo, permitindo que o console seja desbloqueado assim que for ligado, sem precisar de um PC ou celular.

### O que é
O PPPwn-Pi é uma implementação do exploit PPPwn otimizada para rodar em microcomputadores Raspberry Pi, agindo como um servidor PPPoE falso que injeta o payload GoldHEN.

### Requisitos
* Raspberry Pi (Modelos 3, 4 ou Zero 2 W recomendados).
* Cartão MicroSD (mínimo 4GB).
* Cabo Ethernet (RJ45).
* PS4 em firmware compatível (até 11.00 ou versões suportadas por versões recentes do PPPwn).
* Software 'Raspberry Pi Imager' no PC.

### Passo a Passo
1. **Gravar a Imagem:** No PC, baixe a imagem `.img` do PPPwn-Pi. Use o Raspberry Pi Imager para gravá-la no cartão MicroSD.
2. **Configurar o Payload:** Antes de ejetar o cartão do PC, verifique se o arquivo `payload.bin` (GoldHEN) está na partição principal do cartão. Se não, renomeie o GoldHEN para `payload.bin` e coloque-o lá.
3. **Conexão Física:** Insira o cartão no Raspberry Pi. Conecte o cabo Ethernet entre o Pi e o PS4. Ligue o Pi.
4. **Configurar o PS4:** No console, vá em Configurações > Rede > Configurar conexão à Internet > Usar cabo de rede (LAN) > Personalizado.
5. **Ajustes de IP:** Escolha 'PPPoE'. Insira qualquer caractere para o usuário e senha (ex: 'admin').
6. **Finalização:** Deixe as outras configurações (DNS, MTU) em Automático. Selecione 'Testar Conexão à Internet'.
7. **Exploit:** O Raspberry Pi detectará a tentativa de conexão e iniciará a sequência de invasão automaticamente. Aguarde a mensagem de 'GoldHEN loaded' no canto superior da tela do PS4.

### Avisos de Risco
* Não desligue o Raspberry Pi durante a fase de 'PPPwn sequence' para evitar corrupção de dados no cartão SD.
* Certifique-se de que o console não tente atualizar o sistema enquanto estiver conectado ao Pi.

### Solução de Problemas
* **Falha ao obter endereço IP:** Verifique se o cabo Ethernet está bem encaixado e se o Pi terminou de inicializar (geralmente leva 30 segundos).
* **Exploit falha repetidamente:** Verifique se a versão do firmware selecionada na configuração do Pi coincide com a do seu PS4.

## Download

[Baixar Tutorial: Como configurar o PPPwn no Raspberry Pi para Jailbreak Automático (página oficial)](https://github.com/PSXIT/PPPwn-Pi/releases)

Fonte: <https://github.com/TheOfficialFloW/PPPwn>
