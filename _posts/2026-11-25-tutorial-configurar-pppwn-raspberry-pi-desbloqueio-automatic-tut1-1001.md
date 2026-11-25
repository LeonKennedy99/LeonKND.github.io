---
layout: post
title: "Tutorial: Como configurar o PPPwn no Raspberry Pi para desbloqueio automático"
description: "Automatize o exploit do seu PS4 usando um Raspberry Pi com a versão C++ de alto desempenho."
download: "https://github.com/xfangfang/PPPwn_cpp/releases"
date: 2026-11-25 10:01:21 -0300
categories: ps4 tutorial
---

### O que é?
O PPPwn é um exploit de kernel baseado em PPPoE para o PlayStation 4 que afeta firmwares do 7.00 ao 11.00. Usar um Raspberry Pi permite que o console seja desbloqueado automaticamente assim que é ligado, sem a necessidade de um computador ou celular conectado permanentemente.

### Requisitos
*   **Console:** PS4 nos firmwares 7.00 até 11.00.
*   **Hardware:** Raspberry Pi (Modelos 3B, 3B+, 4B ou Zero 2W recomendados).
*   **Cartão SD:** Mínimo de 4GB.
*   **Cabo Ethernet:** Para conectar o Pi ao PS4.
*   **Software:** Imagem do sistema (como Raspbian Lite) e o binário `pppwn_cpp` (versão mais rápida em C++).
*   **Payload:** Arquivo `stage1.bin` e `stage2.bin` correspondentes ao seu firmware.

### Passo a Passo
1.  **Preparação do SD:** Instale o Raspberry Pi OS Lite no cartão SD usando o Raspberry Pi Imager.
2.  **Arquivos Necessários:** Baixe o `pppwn_cpp` para a arquitetura do seu Pi e os arquivos `stage1.bin` e `stage2.bin` do repositório oficial.
3.  **Configuração do Script:** Crie um script de inicialização (.sh) que execute o comando: `sudo ./pppwn --interface eth0 --fw 1100 --stage1 stage1.bin --stage2 stage2.bin -a` (substitua `1100` pela sua versão de firmware, ex: `900` para 9.00).
4.  **Automação:** Adicione o script ao `crontab` ou crie um serviço no `systemd` para que ele inicie com o sistema.
5.  **Conexão Física:** Conecte o cabo Ethernet entre o Raspberry Pi e o PS4.
6.  **Configuração no PS4:** Vá em Configurações > Rede > Configurar conexão à Internet > Usar cabo de rede (LAN) > Personalizado > PPPoE. Digite qualquer usuário e senha (ex: `ppp`). Em configurações de DNS e MTU, deixe em Automático.
7.  **Execução:** Clique em 'Testar Conexão à Internet'. O Raspberry Pi detectará a solicitação PPPoE e iniciará a injeção do exploit.

### Avisos de Risco
*   O processo de injeção pode falhar nas primeiras tentativas (Kernel Panic), o que fará o PS4 desligar abruptamente. Isso é normal do exploit, mas evite fazer repetidamente se o console estiver superaquecido.
*   Certifique-se de usar a voltagem correta para o seu Raspberry Pi para evitar corrupção de dados no SD.

### Solução de Problemas
*   **Erro de 'Timed Out':** Verifique se o cabo Ethernet está bem encaixado e se a interface de rede no script está correta (`eth0` na maioria dos modelos).
*   **O exploit trava no Stage 1:** Verifique se os arquivos `stage1.bin` e `stage2.bin` são exatamente para a sua versão de firmware.

## Download

[Baixar Tutorial: Como configurar o PPPwn no Raspberry Pi para desbloqueio automático (página oficial)](https://github.com/xfangfang/PPPwn_cpp/releases)

Fonte: <https://github.com/TheFloW/PPPwn>
