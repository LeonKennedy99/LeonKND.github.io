---
layout: post
title: "Tutorial: Como configurar o Linux Fedora 42 no PS4 com Kernel 7.33"
description: "Guia para rodar a distro Fedora com aceleração gráfica total no PS4 Pro e Slim."
download: "https://github.com/ps4linux-com/ps4-linux-distros/releases"
date: 2026-11-19 10:01:07 -0300
categories: ps4 tutorial
---

Com o lançamento do **Strawberry Kernel 7.33.3**, tornou-se possível rodar distros modernas como o **Fedora 42** no PS4 com suporte aprimorado para a GPU. Este tutorial explica como preparar seu dispositivo externo.

**Requisitos:**
- PS4 com Jailbreak ativo (até firmware 11.00 ou 14.02).
- Pendrive USB 3.0 ou SSD Externo (mínimo 64GB).
- Imagem do Fedora 42 para PS4 e arquivos bzImage/initramfs.

**Instalação:**
1. Formate o drive USB com uma partição FAT32 (Boot) e uma EXT4 (Sistema).
2. Copie o `bzImage` e o `initramfs.cpio.gz` para a partição FAT32.
3. Extraia o sistema de arquivos (rootfs) do Fedora na partição EXT4.
4. No console, utilize o *Payload Guest* para carregar o Linux Loader v25.
5. O sistema iniciará no ambiente GNOME, com Wi-Fi e aceleração 3D habilitados por padrão.

## Download

[Baixar Tutorial: Como configurar o Linux Fedora 42 no PS4 com Kernel 7.33 (página oficial)](https://github.com/ps4linux-com/ps4-linux-distros/releases)

Fonte: <https://ps4linux.com/>
