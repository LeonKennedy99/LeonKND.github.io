---
layout: post
title: "Tutorial: Como gerenciar e instalar plugins via FTP no GoldHEN"
description: "Aprenda a organizar seus plugins .prx sem precisar de um computador ou pendrive o tempo todo."
download: ""
date: 2026-11-26 15:01:05 -0300
categories: ps4 tutorial
---

Com o amadurecimento da cena, o uso de plugins (.prx) no GoldHEN tornou-se padrão para funções como overlay de FPS, cheats e controle de ventoinha. Este tutorial ensina como organizar esses arquivos via FTP.

### Passo a Passo:
1. **Ative o Servidor FTP:** Vá nas configurações do GoldHEN e habilite o 'FTP Server'.
2. **Acesse via Cliente:** No seu PC ou Smartphone, use um cliente como FileZilla e conecte no IP do PS4 (porta 1337).
3. **Caminho dos Arquivos:** Navegue até `/data/GoldHEN/plugins/`. É aqui que todos os arquivos `.prx` devem ficar.
4. **Configuração do arquivo .ini:** Edite ou crie o arquivo `plugins.ini` dentro da mesma pasta para listar quais plugins devem ser carregados (ex: `[exemplo_plugin.prx]`).
5. **Reinicie:** Para que as mudanças tenham efeito, reinicie o console ou use a função 'Reload Plugins' no menu do GoldHEN.

Fonte: <https://github.com/GoldHEN/GoldHEN_Plugins_Repository>
