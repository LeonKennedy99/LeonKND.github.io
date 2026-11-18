---
layout: post
title: "Tutorial: Como instalar e rodar Linux no PS4 via USB (Guia para Iniciantes)"
description: "Transforme seu PlayStation 4 em um computador funcional com suporte a drivers gráficos."
download: "https://github.com/HiteZ/PS4-Linux-Loader/releases"
date: 2026-11-18 18:01:45 -0300
categories: ps4 tutorial
---

### O que é o Linux no PS4?
Graças a vulnerabilidades no kernel, é possível rodar distribuições Linux (como Fedora, Ubuntu ou Manjaro) no PS4. Isso permite transformar o console em um desktop completo para navegar na internet, usar emuladores de PC e até rodar jogos básicos da Steam via Steam Deck UI.

### Requisitos
*   **Console:** PS4 com suporte a Jailbreak. Modelos com Southbridge Baikal, Aeolia ou Belize são suportados.
*   **Pendrive/SSD Externo:** Mínimo de 16GB (USB 3.0 obrigatório para performance).
*   **Arquivos:** `bzImage` (Kernel), `initramfs.cpio.gz` e a imagem da distro (rootfs).
*   **Payload:** PS4 Linux Loader (v25 ou superior).

### Passo a Passo
1.  **Preparação do USB:** Formate seu pendrive em FAT32. Copie os arquivos `bzImage` e `initramfs.cpio.gz` para a raiz do dispositivo. 
2.  **Imagem do Sistema:** A imagem da distribuição Linux (arquivo maior) deve ser gravada no USB usando uma ferramenta como o *Etcher* ou através de métodos de partição manual (ext4), dependendo da distro escolhida.
3.  **Conexão:** Insira o pendrive na porta USB mais próxima do leitor de discos (geralmente a mais estável para boot).
4.  **Executar o Loader:** No navegador do PS4 ou via *Payload Guest*, execute o *PS4 Linux Loader*. Selecione a quantidade de VRAM desejada (1GB é o padrão recomendado para estabilidade).
5.  **Boot:** O console ficará com a tela preta e, em seguida, exibirá os ícones do pinguim (Tux). O sistema iniciará o ambiente gráfico em instantes.

### Avisos de Risco
*   **Superaquecimento:** O Linux pode não gerenciar a ventoinha tão bem quanto o Orbis OS. Monitore a temperatura.
*   **Corrupção de Dados:** Nunca remova o pendrive enquanto o Linux estiver rodando.

### Solução de Problemas
*   **Tela Preta Infinita:** Tente trocar o cabo HDMI ou a porta USB. Algumas TVs 4K têm dificuldade em reconhecer a resolução inicial do Linux.
*   **Teclado/Mouse não funcionam:** Use um hub USB com alimentação própria ou tente portas diferentes; drivers de certos periféricos gamers podem não ser carregados no boot.

## Download

[Baixar Tutorial: Como instalar e rodar Linux no PS4 via USB (Guia para Iniciantes) (página oficial)](https://github.com/HiteZ/PS4-Linux-Loader/releases)

Fonte: <https://wololo.net/2024/05/ps4-linux-guide-how-to-run-linux-on-firmware-11-00/>
