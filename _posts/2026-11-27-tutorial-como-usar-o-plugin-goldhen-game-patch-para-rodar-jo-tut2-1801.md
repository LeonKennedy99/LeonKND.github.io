---
layout: post
title: "Tutorial: Como usar o plugin GoldHEN Game Patch para rodar jogos a 60 FPS"
description: "Desbloqueie taxas de quadros e melhore a performance de seus jogos favoritos no PS4."
download: "https://github.com/GoldHEN/GoldHEN_Plugins_Repository"
date: 2026-11-27 18:01:52 -0300
categories: ps4 tutorial
---

O plugin **GoldHEN Game Patch** permite aplicar modificações em tempo real nos jogos, como desbloquear o limite de 30 FPS para 60 FPS, alterar o Campo de Visão (FOV) ou remover o Motion Blur, tudo sem precisar modificar os arquivos originais do jogo.

### Requisitos
1.  **PS4 desbloqueado:** Com o GoldHEN v2.4b14 ou superior instalado.
2.  **Plugin Game Patch:** Arquivo `game-patch.prx`.
3.  **PS4 Cheats Manager:** Aplicativo homebrew para baixar os patches atualizados.
4.  **Acesso FTP ou USB:** Para transferir o plugin.

### Passo a Passo Numerado
1.  **Instalação do Plugin:** Via FTP, navegue até `/data/GoldHEN/plugins/`. Copie o arquivo `game-patch.prx` para esta pasta.
2.  **Configuração do Arquivo INI:** No diretório `/data/GoldHEN/`, abra ou crie o arquivo `plugins.ini`. Adicione as linhas:
    `[default]`
    `/data/GoldHEN/plugins/game-patch.prx=true`
3.  **Ativação no Console:** No menu do PS4, vá em **GoldHEN > Plugin Settings** e certifique-se de que a opção **Enable Game Patch** está marcada. Reinicie o console ou recarregue os plugins.
4.  **Download de Patches:** Abra o app **PS4 Cheats Manager**. Vá na aba "Patches", pressione **Triângulo** para filtrar pelos jogos instalados e selecione os patches desejados (ex: 60 FPS Patch).
5.  **Aplicação:** Inicie o jogo. O patch será aplicado automaticamente se a versão do jogo for compatível com o arquivo baixado.

### Avisos de Risco
*   **Superaquecimento:** Rodar jogos a 60 FPS exige mais do hardware. Monitore a temperatura e considere aumentar a velocidade da ventoinha.
*   **Bugs Gráficos:** Alguns patches de 60 FPS podem acelerar a física do jogo ou causar glitches em cutscenes.

### Solução de Problemas
*   **O jogo continua a 30 FPS:** Verifique se o CUSA (ID do jogo) e a versão do jogo instalada coincidem exatamente com os requisitos do patch no Cheats Manager.
*   **Menu GoldHEN não carrega:** Verifique se a sintaxe no `plugins.ini` está correta, sem espaços extras.

## Download

[Baixar Tutorial: Como usar o plugin GoldHEN Game Patch para rodar jogos a 60 FPS (página oficial)](https://github.com/GoldHEN/GoldHEN_Plugins_Repository)

Fonte: <https://gbatemp.net/threads/how-to-apply-60fps-patches-on-ps4-using-goldhen-plugins.640101/>
