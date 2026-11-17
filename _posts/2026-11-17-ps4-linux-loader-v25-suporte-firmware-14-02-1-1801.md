---
layout: post
title: "PS4 Linux Loader v25: Suporte para Firmware 14.02 e Detecção de Southbridge"
description: "Novo loader universal traz compatibilidade com o firmware mais recente."
download: "https://github.com/ps4-linux/ps4-linux-loader/releases"
date: 2026-11-17 18:01:31 -0300
categories: ps4 payload
---

O desenvolvedor ArabPixel lançou a versão v25 do **PS4 Linux Loader**, uma atualização crítica que estende o suporte para os firmwares 14.00 e 14.02. A grande novidade desta versão é a normalização de offsets para o kernel 12.02 e a detecção em tempo de execução dos chips Southbridge (Aeolia, Belize, Belize2, Baikal), eliminando a necessidade de loaders específicos para cada modelo de console. 

Compatível com firmwares de 5.05 até 14.02, o loader agora integra um blob kexec para cada firmware canônico suportado. Para usar, é necessário ter o GoldHEN ativo. O processo envolve enviar o arquivo `.elf` ou `.bin` através do PayLoader do GoldHEN na porta 9090, garantindo que o console identifique corretamente o hardware antes de carregar o kernel Linux via USB.

## Download

[Baixar PS4 Linux Loader v25: Suporte para Firmware 14.02 e Detecção de Southbridge (página oficial)](https://github.com/ps4-linux/ps4-linux-loader/releases)

Fonte: <https://github.com/ps4-linux/ps4-linux-loader>
