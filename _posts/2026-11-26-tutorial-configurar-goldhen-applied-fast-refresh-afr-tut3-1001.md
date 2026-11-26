---
layout: post
title: "Tutorial: Como configurar o plugin GoldHEN Applied Fast Refresh (AFR) para taxas de quadros customizadas"
description: "Force 60Hz ou sincronias específicas em jogos compatíveis."
download: "https://github.com/GoldHEN/GoldHEN_Plugins_Repository/releases"
date: 2026-11-26 10:01:40 -0300
categories: ps4 tutorial
---

### O que é
O Applied Fast Refresh (AFR) é um plugin para o GoldHEN que permite ajustar a taxa de atualização da tela (refresh rate). Ele é essencial para remover o limite de 30FPS em jogos que possuem patches de performance, permitindo uma experiência mais fluida em 60Hz.

### Requisitos
* PS4 com GoldHEN v2.3 ou superior.
* Plugin `afr.prx` e arquivo de configuração `afr.ini` (disponíveis no repositório de plugins).
* Conhecimento básico de edição de texto.

### Passo a Passo
1. **Localizar Pastas:** Conecte-se ao PS4 via FTP ou use o PS4-Xplorer. Navegue até `/data/GoldHEN/plugins/`.
2. **Instalar Plugin:** Copie o arquivo `afr.prx` para esta pasta.
3. **Habilitar no Sistema:** Edite o arquivo `plugins.ini` que está em `/data/GoldHEN/`. Adicione a seguinte linha sob a seção `[default]`:
   `/data/GoldHEN/plugins/afr.prx`
4. **Configurar o AFR:** Abra o arquivo `afr.ini`. Nele, você encontrará opções como `target_refresh_rate`. 
   * Para forçar 60Hz, certifique-se de que o valor esteja definido corretamente de acordo com as instruções do arquivo.
5. **Reiniciar:** Reinicie o console ou recarregue os plugins através do GoldHEN Menu.
6. **Uso:** Ao iniciar um jogo compatível com patches de 60FPS (como Bloodborne ou Red Dead Redemption), o plugin ajustará a sincronia da TV automaticamente.

### Avisos de Risco
* **Tela Preta:** Algumas TVs antigas não suportam mudanças forçadas de refresh rate, o que pode resultar em perda de vídeo temporária. Se isso acontecer, apague o plugin via FTP para restaurar a imagem.

### Solução de Problemas
* **Plugin não ativa:** Verifique se o caminho no `plugins.ini` está escrito corretamente e se não há espaços extras.
* **FPS não muda:** O AFR apenas ajusta a taxa de atualização da saída de vídeo; para o jogo rodar mais rápido, você ainda precisa do patch de 60FPS específico do jogo aplicado via GoldHEN Cheat Manager.

## Download

[Baixar Tutorial: Como configurar o plugin GoldHEN Applied Fast Refresh (AFR) para taxas de quadros customizadas (página oficial)](https://github.com/GoldHEN/GoldHEN_Plugins_Repository/releases)

Fonte: <https://github.com/GoldHEN/GoldHEN_Plugins_Repository>
