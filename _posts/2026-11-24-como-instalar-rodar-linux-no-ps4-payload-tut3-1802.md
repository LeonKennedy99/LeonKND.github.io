---
layout: post
title: "Tutorial: Como rodar Linux no PS4 usando o Payload PS4-Linux"
description: "Transforme seu console em um computador funcional instalando distribuições Linux."
download: "https://github.com/ps4boot/ps4-linux-payloads-archive/releases"
date: 2026-11-24 18:02:00 -0300
categories: ps4 tutorial
---

Rodar Linux no PS4 permite transformar o console em uma estação de trabalho ou central de emulação avançada. Para isso, utilizamos um payload específico que faz o "kexec" (carregamento do kernel) de uma distribuição Linux a partir de um dispositivo USB.

### Requisitos
*   PS4 com Jailbreak ativo (firmwares compatíveis até 11.00).
*   **Pendrive ou SSD Externo** (mínimo 16GB, formatado em FAT32 para os arquivos de boot).
*   Arquivos de Kernel (`bzImage`) e Sistema de Arquivos (`initramfs.cpio.gz`) compatíveis com seu modelo de PS4.
*   Uma distribuição Linux (RootFS) preparada para PS4.

### Passo a Passo
1.  **Preparar o USB:** Formate seu pendrive em FAT32 (MBR). Copie os arquivos `bzImage`, `initramfs.cpio.gz` e opcionalmente o `bootargs.txt` para a raiz do dispositivo.
2.  **Conectar o Hardware:** Insira o USB preparado na porta do PS4. Conecte um teclado e mouse USB, pois o controle do PS4 não funciona nativamente na tela de boot do Linux.
3.  **Carregar o Payload:**
    *   No PS4, abra o navegador ou o menu de payloads do GoldHEN.
    *   Envie ou selecione o payload **PS4-Linux-Loader.bin** correspondente ao seu firmware e à quantidade de RAM que deseja alocar (ex: 2GB ou 4GB de VRAM).
4.  **Boot do Sistema:** A tela do console ficará preta por alguns instantes e você verá o logotipo do Linux (pinguins) no topo da tela. Se estiver instalando pela primeira vez, o sistema carregará a partir do USB.
5.  **Configuração Final:** Siga as instruções específicas da distro escolhida (como Fedora ou Ubuntu) para completar a instalação no disco interno ou manter o uso via USB.

### Avisos de Risco
*   A instalação do Linux pode exigir a repartição do disco rígido interno se você não usar apenas o USB, o que apagará dados do sistema Orbis (PS4).
*   O suporte a Wi-Fi e Bluetooth varia drasticamente dependendo do modelo da placa-mãe (Baikal, Belize, Aeolia).

### Solução de Problemas
*   **Tela Preta Infinita:** Isso geralmente ocorre por incompatibilidade do `bzImage` com o modelo do seu console (Fat vs Slim vs Pro). Tente um kernel específico para sua revisão de hardware.
*   **Kernel Panic:** Verifique se os arquivos no USB não estão corrompidos e se o formato da partição é realmente FAT32.

## Download

[Baixar Tutorial: Como rodar Linux no PS4 usando o Payload PS4-Linux (página oficial)](https://github.com/ps4boot/ps4-linux-payloads-archive/releases)

Fonte: <https://github.com/ps4-linux/ps4-linux-payloads-archive>
