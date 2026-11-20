---
layout: post
title: "Tutorial: Como usar o DroidPPPwn para o Jailbreak do PS4 via Celular Android"
description: "Utilize seu smartphone Android para ativar o exploit PPPwn sem precisar de um computador."
download: "https://github.com/modern72/DroidPPPwn/releases"
date: 2026-11-20 18:01:46 -0300
categories: ps4 tutorial
---

O **DroidPPPwn** é um porte para Android do exploit de kernel PPPwn, permitindo que usuários de PS4 realizem o jailbreak utilizando apenas um smartphone. Esta é uma excelente alternativa para quem não possui um PC por perto ou um Raspberry Pi dedicado.

### O que é?
O DroidPPPwn transforma o seu celular em um servidor PPPoE que envia o payload necessário para explorar a vulnerabilidade de rede do PlayStation 4 através de uma conexão direta via cabo.

### Requisitos
* **PS4 compatível:** Firmware até 11.00.
* **Smartphone Android:** Preferencialmente com acesso Root (necessário para versões mais antigas do Android ou adaptadores específicos) e suporte a OTG.
* **Hardware:** Adaptador USB para Ethernet (compatível com seu celular) e um cabo de rede (LAN).
* **Arquivo stage2.bin:** Correspondente à sua versão de firmware.

### Passo a Passo
1. Baixe e instale o APK do **DroidPPPwn** no seu celular.
2. Coloque o arquivo `stage2.bin` da sua versão de firmware na raiz do armazenamento interno do celular ou na pasta indicada pelo app.
3. Conecte o adaptador Ethernet ao celular e ligue o cabo de rede entre o celular e o PS4.
4. No PS4, vá em **Configurações > Rede > Configurar conexão à Internet > Usar cabo de rede (LAN) > Personalizado > PPPoE**.
5. Insira qualquer nome e senha (ex: 'ppp') e deixe as outras configurações em Automático.
6. No Android, abra o aplicativo, conceda as permissões de Root (se solicitado), selecione a interface de rede (geralmente eth0) e a versão do seu firmware.
7. Clique em **Start** no aplicativo e, em seguida, clique em **Testar Conexão à Internet** no PS4.
8. Aguarde o processo terminar. Se o exploit falhar, o app tentará automaticamente novamente.

### Avisos de Risco
* O processo pode causar um **Kernel Panic** (o console desliga sozinho). Se isso acontecer, ligue o PS4 e tente novamente.
* O uso de adaptadores Ethernet de baixa qualidade pode causar falhas de comunicação.

### Solução de Problemas
* **O app não inicia:** Verifique se o seu celular suporta a função de roteamento via Ethernet ou se o Root está funcionando corretamente.
* **Falha no Stage 1:** Certifique-se de que o cabo de rede está bem conectado e que as configurações de PPPoE no PS4 foram inseridas corretamente.

## Download

[Baixar Tutorial: Como usar o DroidPPPwn para o Jailbreak do PS4 via Celular Android (página oficial)](https://github.com/modern72/DroidPPPwn/releases)

Fonte: <https://github.com/modern72/DroidPPPwn>
