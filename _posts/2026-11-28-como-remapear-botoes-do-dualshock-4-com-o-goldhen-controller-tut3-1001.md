---
layout: post
title: "Tutorial: Como remapear botões do DualShock 4 com o GoldHEN Controller Remapper"
description: "Altere as funções dos botões do controle em nível de sistema para qualquer jogo ou aplicativo."
download: "https://github.com/illusion0001/PS4-Controller-Remapper/releases"
date: 2026-11-28 10:01:38 -0300
categories: ps4 tutorial
---

### O que é?
O **Controller Remapper** é um plugin para o GoldHEN que permite trocar a função de qualquer botão do DualShock 4. Útil para jogadores que preferem layouts diferentes (como inverter X e O em consoles de regiões diferentes) ou para acessibilidade em jogos que não oferecem mapeamento nativo.

### Requisitos
*   PS4 com **GoldHEN v2.3** ou superior instalado.
*   O arquivo do plugin (`ControllerRemapper.prx`).
*   Acesso ao FTP do console ou gerenciador de arquivos (PS4-Xplorer).

### Passo a Passo
1.  **Transferência:** Copie o arquivo `ControllerRemapper.prx` para a pasta `/data/GoldHEN/plugins/` no seu PS4.
2.  **Configuração do Loader:** Edite o arquivo `plugins.ini` (localizado em `/data/GoldHEN/`) e adicione a seguinte linha sob a seção `[Main]`: 
    `/data/GoldHEN/plugins/ControllerRemapper.prx`.
3.  **Configuração de Botões:** O plugin utiliza um arquivo de texto para saber quais botões trocar. Crie um arquivo chamado `remap.txt` em `/data/GoldHEN/`.
4.  **Sintaxe:** No arquivo `remap.txt`, digite as trocas. Exemplo: para trocar X por O, escreva `CROSS CIRCLE`. Para inverter os analógicos, use `L3 R3`.
5.  **Ativação:** Reinicie o console ou recarregue os plugins pelo menu do GoldHEN. As alterações serão aplicadas globalmente.

### Avisos de Risco
*   Tenha cuidado ao remapear botões essenciais; se você desabilitar o botão de confirmação, terá dificuldade para navegar nos menus do console.
*   Sempre mantenha um backup do seu `plugins.ini` original.

### Solução de Problemas
*   **O plugin não carrega:** Verifique se o caminho no `plugins.ini` está exatamente igual ao local do arquivo `.prx`.
*   **Conflito em jogos:** Alguns jogos que usam drivers de controle customizados podem ignorar o remapeamento do plugin.

## Download

[Baixar Tutorial: Como remapear botões do DualShock 4 com o GoldHEN Controller Remapper (página oficial)](https://github.com/illusion0001/PS4-Controller-Remapper/releases)

Fonte: <https://github.com/illusion0001/PS4-Controller-Remapper>
