---
layout: post
title: "Tutorial: Como instalar e rodar Linux no PS4"
description: "Transforme seu console em um computador completo com Linux."
download: "https://github.com/whitey-v/PS4-Linux-Loader/releases"
date: 2026-11-21 18:01:38 -0300
categories: ps4 tutorial
---

O Linux no PlayStation 4 permite que o console funcione como um PC, possibilitando o uso de navegadores, emuladores avançados (como o RPCS3 para alguns testes ou Steam) e suítes de escritório. Isso é possível graças aos payloads que carregam o kernel Linux diretamente na memória do sistema.

### Requisitos
*   PS4 com Jailbreak funcional (GoldHEN instalado).
*   Firmware compatível (comumente 5.05, 6.72, 9.00 ou 11.00).
*   Pendrive ou HD Externo USB 3.0 de pelo menos 16GB (recomendado 32GB ou mais).
*   Arquivos da distribuição Linux (imagem `.img`), o Kernel (`bzImage`) e o `initramfs.cpio.gz` específicos para o seu modelo de PS4.
*   Teclado e mouse USB.

### Passo a Passo
1.  **Preparação do Dispositivo USB:** Formate seu pendrive/HD no PC. Use ferramentas como o `Rufus` ou `BalenaEtcher` para gravar a imagem da distribuição Linux escolhida no dispositivo.
2.  **Arquivos de Boot:** Após gravar a imagem, certifique-se de que os arquivos `bzImage` e `initramfs.cpio.gz` estão na raiz da partição FAT32 criada no USB (algumas distros já os incluem automaticamente).
3.  **Conexão:** Insira o dispositivo USB na porta mais próxima do leitor de discos do PS4. Conecte também o teclado e o mouse.
4.  **Injeção do Payload:** No PS4, acesse seu host de exploits habitual e selecione o payload **Linux Loader**. Escolha a versão que corresponde à sua quantidade de memória VRAM (geralmente 1GB, 2GB ou 3GB – 2GB é o padrão equilibrado).
5.  **Inicialização:** A tela ficará preta e você verá linhas de código (o "Penguin Boot"). O sistema Linux será carregado. Na primeira vez, pode levar alguns minutos para redimensionar as partições.

### Avisos de Risco
*   **Kernel Panics:** É comum o console desligar subitamente ao injetar o payload. Se isso ocorrer, retire o cabo de força, aguarde 30 segundos e tente novamente.
*   **Superaquecimento:** O Linux pode não gerenciar a ventoinha tão bem quanto o Orbis OS. Monitore a temperatura.

### Solução de Problemas
*   **Tela Preta Estática:** Verifique se o `bzImage` é compatível com o modelo da sua placa-mãe (Baal, Belize, Aeolia, etc).
*   **USB não reconhecido:** Certifique-se de que o dispositivo está formatado corretamente e que a porta USB do PS4 não está frouxa.

## Download

[Baixar Tutorial: Como instalar e rodar Linux no PS4 (página oficial)](https://github.com/whitey-v/PS4-Linux-Loader/releases)

Fonte: <https://ps4linux.com/setup-ps4-linux-guide/>
