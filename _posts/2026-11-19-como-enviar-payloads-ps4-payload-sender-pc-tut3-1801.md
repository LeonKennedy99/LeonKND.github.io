---
layout: post
title: "Tutorial: Como enviar Payloads para o PS4 usando o PS4 Payload Sender (PC)"
description: "Aprenda a injetar arquivos .bin como GoldHEN, Linux Loader ou Fan Control via rede."
download: "https://github.com/valentinbreiz/PS4-Payload-Sender/releases"
date: 2026-11-19 18:01:46 -0300
categories: ps4 tutorial
---

Muitas vezes, as funcionalidades do PS4 desbloqueado dependem da execução de pequenos códigos chamados **Payloads**. Embora muitos hosts web já tragam opções integradas, o **PS4 Payload Sender** permite que você envie arquivos `.bin` personalizados diretamente do seu computador para o console, oferecendo maior controle sobre quais ferramentas você está carregando.

### Requisitos
* **PS4 com Exploit Kernel carregado:** O console deve estar aguardando a conexão.
* **Bin Loader:** O console deve exibir a mensagem "Waiting for Payload..." (geralmente na porta 9020 ou 9021).
* **Arquivo de Payload:** O arquivo com extensão `.bin` que você deseja enviar.
* **PC na mesma rede local que o PS4.**

### Passo a Passo
1. **No PS4:**
   - Execute o exploit inicial pelo navegador ou ferramenta de sua preferência.
   - Selecione a opção **Bin Loader**. O sistema ficará em uma tela preta ou exibirá um aviso de que está aguardando o payload.
   - Verifique o endereço IP do PS4 nas configurações de rede.

2. **No PC:**
   - Abra o `PS4 Payload Sender`.
   - No campo **IP**, digite o endereço do console.
   - No campo **Port**, verifique se está como `9020` (padrão do GoldHEN/BinLoader). Alguns hosts usam `9021`.

3. **Enviando o arquivo:**
   - Clique em **Browse** e selecione o arquivo `.bin` desejado (ex: um dumper de jogos, ativador de temperatura ou Linux Loader).
   - Clique no botão **Connect** (se disponível na sua versão) e depois em **Send Payload**.

4. **Finalização:**
   - Se o envio for bem-sucedido, você verá uma notificação no canto superior esquerdo da tela do PS4 confirmando que o payload foi carregado.

### Avisos de Risco
* **Cuidado com payloads desconhecidos:** Nunca envie arquivos `.bin` de fontes não confiáveis, pois payloads maliciosos podem causar danos permanentes ao hardware (brick).
* O envio de payloads incorretos para a versão do seu firmware resultará em um desligamento imediato (Kernel Panic) do console.

### Solução de Problemas
* **O payload não carrega e o console desliga:** Isso indica incompatibilidade. Verifique se o payload é específico para a sua versão de firmware (ex: um payload de 9.00 não funcionará no 11.00).
* **Falha de conexão:** Certifique-se de que o PS4 não entrou em modo de repouso e que você não fechou a aba do navegador antes de enviar o arquivo do PC.

## Download

[Baixar Tutorial: Como enviar Payloads para o PS4 usando o PS4 Payload Sender (PC) (página oficial)](https://github.com/valentinbreiz/PS4-Payload-Sender/releases)

Fonte: <https://psxhax.com/threads/ps4-payload-sender-pc-client-by-valentinbreiz-via-bin-loader.2933/>
