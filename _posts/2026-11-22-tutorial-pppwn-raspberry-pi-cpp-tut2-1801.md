---
layout: post
title: "Tutorial: Como rodar o exploit PPPwn via Raspberry Pi (Versão C++)"
description: "Aumente a velocidade do jailbreak usando a versão otimizada em C++ no seu Pi."
download: "https://github.com/xfangfang/PPPwn_cpp/releases"
date: 2026-11-22 18:01:48 -0300
categories: ps4 tutorial
---

O exploit **PPPwn** original foi escrito em Python, o que pode ser lento em hardware modesto. A versão **PPPwn_cpp** é uma reescrita otimizada que oferece maior estabilidade e velocidade, sendo ideal para dispositivos como Raspberry Pi (3, 4 ou Zero 2W).

### Requisitos
* PlayStation 4 no firmware 9.00 até 11.00.
* Raspberry Pi com sistema Linux (Raspberry Pi OS Lite recomendado).
* Cabo Ethernet conectando o Pi diretamente ao PS4.
* Cartão SD com o binário `pppwn` compilado para a arquitetura do Pi (ARM).
* Arquivo `stage1.bin` e `stage2.bin` compatíveis com sua versão de firmware.

### Passo a Passo
1. **Preparação do Pi:** Acesse o terminal do seu Raspberry Pi via SSH ou teclado.
2. **Download:** Baixe o release mais recente do `pppwn_cpp` do GitHub oficial e coloque na pasta `/home/pi/pppwn`.
3. **Permissões:** Dê permissão de execução ao arquivo com o comando: `chmod +x pppwn`.
4. **Execução:** Conecte o cabo de rede entre o Pi e o PS4. No terminal do Pi, execute o comando:
   `sudo ./pppwn -i eth0 --fw 1100 --stage1 stage1.bin --stage2 stage2.bin -auto` 
   *(Ajuste `--fw 1100` para sua versão, ex: 900 para 9.00)*.
5. **No PS4:** Vá em Configurações > Rede > Configurar conexão à Internet > Usar cabo LAN > Personalizado > PPPoE.
6. Digite qualquer coisa para nome de usuário e senha. Escolha "Automático" para o restante e, ao final, selecione **Testar Conexão à Internet**.
7. O script no Pi detectará a tentativa de conexão e iniciará a injeção do exploit. Aguarde a mensagem de sucesso na tela do console.

### Avisos de Risco
* **Cuidado com a Energia:** Não desligue o Raspberry Pi durante a fase de injeção para evitar travamentos no sistema de arquivos do SD.
* **Superaquecimento:** Se usar um Pi Zero sem dissipador, evite múltiplas tentativas seguidas muito rápidas.

### Solução de Problemas
* **Timeout na Conexão:** Verifique se o cabo Ethernet está firme. Algumas portas do Pi exigem que o PS4 esteja ligado antes de iniciar o comando.
* **Arquivo stage2 não carrega:** Certifique-se de que o arquivo `stage2.bin` corresponde exatamente ao seu firmware e que o GoldHEN (se estiver usando) está correto para esse payload.

## Download

[Baixar Tutorial: Como rodar o exploit PPPwn via Raspberry Pi (Versão C++) (página oficial)](https://github.com/xfangfang/PPPwn_cpp/releases)

Fonte: <https://wololo.net/2024/05/13/release-pppwn_cpp-a-faster-and-more-compact-version-of-pppwn-exploit-written-in-c/>
