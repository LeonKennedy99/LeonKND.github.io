---
layout: post
title: "Tutorial: Como atualizar o Luckfox Pico via SocToolKit"
description: "Aprenda a instalar as novas versões do PPPwn no Luckfox sem usar SSH."
download: ""
date: 2026-11-23 10:01:26 -0300
categories: ps4 tutorial
---

Com o lançamento do PPPwn-Luckfox v1.2.5, o processo de atualização tornou-se muito mais simples através do **SocToolKit**. Siga este guia para atualizar seu dispositivo:

1. **Preparação**: Coloque seu Luckfox Pico no modo **MaskRom**. Para isso, mantenha pressionado o botão 'BOOT' enquanto conecta o dispositivo ao PC via cabo USB-C.
2. **Drivers**: Certifique-se de ter os drivers da Luckfox instalados. O dispositivo deve aparecer no Gerenciador de Dispositivos como 'Rockusb Device'.
3. **Flash**: Abra o SocToolKit e selecione a aba correspondente ao chip (geralmente RV1103 ou RV1106). No campo 'Search Path', selecione a pasta onde você extraiu a nova imagem (FW correspondente ao seu PS4).
4. **Execução**: Clique em 'Download' no SocToolKit. O programa irá formatar e gravar a nova imagem automaticamente. 
5. **Configuração**: Após o término, conecte o Luckfox ao PS4. Se estiver usando a versão Web, acesse `10.1.1.1` pelo navegador do console para configurar o auto-run e a detecção de GoldHEN.

Fonte: <https://wiki.luckfox.com/Luckfox-Pico-Pro-Max/Flash-image>
