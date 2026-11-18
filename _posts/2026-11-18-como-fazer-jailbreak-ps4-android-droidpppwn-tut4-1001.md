---
layout: post
title: "Tutorial: Como realizar o Jailbreak do PS4 usando um celular Android (DroidPPPwn)"
description: "Use seu smartphone para enviar o exploit PPPwn sem precisar de um computador por perto."
download: "https://github.com/lucas0101/DroidPPPwn/releases"
date: 2026-11-18 10:01:55 -0300
categories: ps4 tutorial
---

Com a evolução do exploit **PPPwn**, agora é possível desbloquear o PS4 usando apenas um celular Android e um cabo de rede. O **DroidPPPwn** é uma interface móvel que automatiza o processo de envio do payload via PPPoE.

### Requisitos
* Console PS4 em firmware compatível (ex: 9.00, 11.00).
* Smartphone Android (preferencialmente com Root, mas existem versões sem Root).
* Adaptador Ethernet para USB (OTG) para conectar o cabo de rede no celular.
* Cabo de rede Ethernet (RJ45).

### Passo a Passo
1. **Conexão Física**: Conecte o cabo de rede no PS4 e a outra ponta no adaptador OTG do seu celular Android.
2. **Configuração no Android**: Instale o APK do **DroidPPPwn**. No app, selecione a interface de rede (geralmente eth0) e a versão do seu firmware do PS4.
3. **Configuração no PS4**: Vá em **Configurações** > **Rede** > **Configurar conexão à Internet**. Selecione **Cabo de rede (LAN)** > **Personalizado** > **PPPoE**.
4. **Credenciais**: Digite qualquer coisa para nome de usuário e senha (ex: 'ppp').
5. **DNS e MTU**: Deixe tudo em Automático, mas em **Proxy**, selecione 'Não usar'.
6. **Execução**: No celular, clique em **Start Exploit**. No PS4, clique em 'Testar Conexão à Internet'.
7. **Aguarde**: O app enviará os estágios do exploit. Se falhar, repita o teste de conexão no PS4.

### Avisos de Risco
* Certifique-se de que o celular tem bateria suficiente; se ele desligar durante o envio, o processo falhará.
* O exploit PPPwn não é 100% estável e pode causar desligamentos inesperados (Kernel Panic) em algumas tentativas.

### Solução de Problemas
* **Falha no estágio 1**: Verifique se o cabo de rede está bem encaixado ou tente trocar o adaptador OTG.
* **O app não detecta a interface**: Reinicie o celular com o adaptador já conectado.

## Download

[Baixar Tutorial: Como realizar o Jailbreak do PS4 usando um celular Android (DroidPPPwn) (página oficial)](https://github.com/lucas0101/DroidPPPwn/releases)

Fonte: <https://wololo.net/2024/05/10/droidpppwn-ps4-jailbreak-for-android/>
