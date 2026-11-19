---
layout: post
title: "Tutorial: Como instalar Mods de Scripts no Bully (PS4) via FTP"
description: "Modifique o clássico Bully substituindo scripts para habilitar novas funções."
download: ""
date: 2026-11-19 15:02:11 -0300
categories: ps4 tutorial
---

Muitos usuários desejam personalizar a experiência no jogo Bully (PS2 on PS4). Uma das formas mais comuns é a substituição de arquivos de script para liberar menus de cheats internos ou alterar comportamentos de NPCs.

### O que é?
É a técnica de substituição de arquivos internos (`Scripts.img` e `Scripts.dir`) de um jogo já instalado no PS4 através de uma conexão FTP.

### Requisitos
*   PS4 com Jailbreak e FTP ativado.
*   Jogo Bully (CUSA03507 ou similar) instalado no HD interno.
*   Arquivos de mod compatíveis (geralmente extraídos de mods da versão de PC/PS2 que funcionam no emulador).

### Passo a Passo
1.  **Identificar o ID:** Descubra o Title ID da sua versão do Bully (Ex: CUSA03507).
2.  **Conectar via FTP:** Use o FileZilla para conectar ao seu PS4 (conforme o tutorial de FTP anterior).
3.  **Localizar o Jogo:** Navegue até o caminho `/user/app/[TITLE_ID_DO_BULLY]/`. Dentro desta pasta, procure pelo diretório que contém os arquivos do jogo (geralmente dentro de `image/` ou onde os arquivos `.img` residem).
4.  **Backup de Segurança:** Antes de substituir qualquer coisa, baixe os arquivos originais `Scripts.img` e `Scripts.dir` para o seu computador. **Nunca pule este passo.**
5.  **Substituir:** Arraste os arquivos de script modificados do seu PC para a pasta correspondente no PS4, sobrescrevendo os originais.
6.  **Testar:** Feche o FTP, reinicie o jogo no PS4 e verifique se o mod está ativo (ex: pressionando combinações de botões para abrir um menu).

### Avisos de Risco
*   **Corrupção de Save:** Mods de script podem corromper seu progresso atual. Recomenda-se começar um novo jogo para testar.
*   **Loop de Carregamento:** Se o jogo travar na tela de carregamento, os scripts instalados são incompatíveis. Restaure o backup original via FTP.

### Solução de Problemas
*   **O jogo não inicia:** Isso acontece se o tamanho dos arquivos modificados for muito diferente do original ou se a versão do jogo for diferente da do mod. Verifique a compatibilidade do mod com a versão 'PS2 on PS4'.
*   **Permissão Negada:** Certifique-se de que o jogo está fechado no PS4 antes de tentar substituir os arquivos via FTP.

Fonte: <https://www.moddb.com/games/bully-scholarship-edition/tutorials>
