---
layout: post
title: "Tutorial: Como habilitar patches de 60FPS e resolução com GoldHEN Plugins"
description: "Melhore a performance de seus jogos favoritos com patches de alto desempenho."
download: "https://github.com/GoldHEN/GoldHEN_Plugins_Repository/releases"
date: 2026-11-24 18:02:00 -0300
categories: ps4 tutorial
---

O sistema de plugins do **GoldHEN** permite aplicar modificações em tempo real (Runtime Patches) em jogos comerciais. Isso possibilita destravar a taxa de quadros (60FPS), ajustar a resolução e corrigir problemas de frame pacing sem precisar modificar permanentemente os arquivos do jogo.

### Requisitos
*   PS4 com **GoldHEN v2.2.5b7** ou superior instalado.
*   **GoldHEN Cheat Manager** instalado no PS4.
*   Acesso FTP ao console (ativado nas configurações do GoldHEN).

### Passo a Passo
1.  **Baixar os Plugins:** No seu PC, baixe o arquivo `game_patch.prx` do repositório oficial de plugins do GoldHEN.
2.  **Transferência via FTP:**
    *   Conecte-se ao PS4 via FTP (usando FileZilla ou similar).
    *   Navegue até o diretório `/data/GoldHEN/plugins/`. Se a pasta `plugins` não existir, crie-a.
    *   Copie o arquivo `game_patch.prx` para dentro dessa pasta.
3.  **Configurar o Carregamento:** No diretório `/data/GoldHEN/`, verifique se existe o arquivo `plugins.ini`. Se não existir, crie um arquivo de texto com esse nome e adicione a linha:
    `[default] /data/GoldHEN/plugins/game_patch.prx`.
4.  **Atualizar Patches:** Abra o **GoldHEN Cheat Manager** no PS4, vá em **Update** e selecione **Patches** para baixar as definições mais recentes de 60FPS da comunidade.
5.  **Ativar no Jogo:**
    *   Inicie o jogo desejado.
    *   Abra o menu do GoldHEN Cheat Manager, navegue até a aba **Patches**.
    *   Selecione o patch correspondente ao seu jogo (ex: 60FPS Patch) e pressione **X** para ativar.
    *   Uma notificação no canto superior esquerdo confirmará que o patch foi aplicado.

### Avisos de Risco
*   Patches de 60FPS em modelos de PS4 Fat ou Slim podem causar superaquecimento ou quedas de resolução dinâmica. Monitore a temperatura.
*   Alguns patches podem causar bugs visuais ou instabilidade em cutscenes.

### Solução de Problemas
*   **Patch não aparece:** Verifique se o CUSA (ID do jogo) e a versão do jogo instalada coincidem com os detalhes listados no Cheat Manager.
*   **Plugin não carrega:** Certifique-se de que o caminho no arquivo `plugins.ini` está exatamente igual ao local onde o `.prx` foi colocado.

## Download

[Baixar Tutorial: Como habilitar patches de 60FPS e resolução com GoldHEN Plugins (página oficial)](https://github.com/GoldHEN/GoldHEN_Plugins_Repository/releases)

Fonte: <https://github.com/GoldHEN/GoldHEN_Patch_Repository>
