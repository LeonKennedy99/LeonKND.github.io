---
layout: post
title: "Tutorial: Como configurar o NanoDNS no GoldHEN para bloquear atualizações do sistema"
description: "Use este payload para criar uma barreira local contra servidores da Sony e evitar atualizações acidentais."
download: "https://github.com/drakmor/nanoDNS/releases"
date: 2026-11-27 10:02:31 -0300
categories: ps4 tutorial
---

O **NanoDNS** é um payload leve e eficiente projetado para rodar dentro do ambiente GoldHEN. Ele funciona como um servidor DNS interno que intercepta requisições para domínios da Sony (como os de atualização de sistema), bloqueando-os localmente. Isso permite que você use a internet no console com mais segurança, sem depender apenas de DNS públicos de terceiros.

### Requisitos

*   PS4 com **GoldHEN v2.4b18** ou superior.
*   Arquivo `nanoDNS.bin` baixado do repositório oficial.
*   Acesso ao sistema de arquivos do PS4 (via FTP ou PS4-Xplorer).

### Passo a Passo

1.  **Preparação do Arquivo:** Baixe o arquivo `nanoDNS.bin` no seu computador.
2.  **Transferência para o Console:**
    *   Conecte-se ao PS4 via FTP ou use um pendrive com o PS4-Xplorer.
    *   Navegue até o diretório: `/data/GoldHEN/payloads/`.
    *   Copie o arquivo `nanoDNS.bin` para dentro desta pasta.
3.  **Ativação Manual:**
    *   No PS4, vá ao menu de configurações do **GoldHEN**.
    *   Selecione a opção **Payloads**.
    *   Localize o **NanoDNS** na lista e pressione **X** para injetá-lo. Uma notificação confirmará que o servidor DNS local está ativo.
4.  **Configuração de Inicialização Automática (Recomendado):**
    *   No menu GoldHEN, procure por **Auto-run Payloads**.
    *   Adicione o NanoDNS à lista de execução automática. Assim, toda vez que você ativar o jailbreak, a proteção contra atualizações será ligada instantaneamente.
5.  **Verificação:** Tente acessar as configurações de rede e verificar por atualizações de sistema. Se o payload estiver funcionando, o console retornará um erro de conexão com os servidores da Sony, confirmando que o bloqueio está ativo.

### Avisos de Risco

*   O NanoDNS bloqueia **todos** os serviços oficiais da Sony. Isso significa que você não conseguirá acessar a PlayStation Store ou sincronizar troféus enquanto o payload estiver ativo.
*   Embora seja altamente eficaz, nenhuma proteção é 100% infalível. Sempre mantenha as opções de "Downloads Automáticos" desmarcadas nas configurações de sistema do PS4 como precaução adicional.

### Solução de Problemas

*   **O payload não aparece na lista:** Verifique se o arquivo está com a extensão `.bin` e se foi colocado na pasta correta (`/data/GoldHEN/payloads/`). Se a pasta `payloads` não existir, você pode criá-la manualmente.

## Download

[Baixar Tutorial: Como configurar o NanoDNS no GoldHEN para bloquear atualizações do sistema (página oficial)](https://github.com/drakmor/nanoDNS/releases)

Fonte: <https://github.com/drakmor/nanoDNS>
