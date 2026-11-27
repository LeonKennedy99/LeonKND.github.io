---
layout: post
title: "Tutorial: Como gerenciar plugins dinamicamente no GoldHEN usando o Plugin Manager"
description: "Ative e desative extensões como medidores de FPS e cheats sem precisar de um PC."
download: "https://github.com/GoldHEN/GoldHEN/releases"
date: 2026-11-27 15:01:36 -0300
categories: ps4 tutorial
---

As versões recentes do **GoldHEN** (2.4+) introduziram uma interface amigável chamada **Plugin Manager**. Antes, era necessário editar arquivos de texto via FTP para carregar plugins. Agora, é possível gerenciar quais extensões o sistema deve carregar diretamente pelo menu oficial do console.

### Requisitos

* PS4 com **GoldHEN v2.4** ou superior instalado e ativo.
* Plugins no formato `.prx` armazenados na pasta correta do console.
* Conhecimento básico de navegação nos menus do PS4.

### Passo a Passo

1. **Preparação dos Arquivos**: Certifique-se de que os seus plugins (arquivos `.prx`) foram copiados para o diretório `/data/GoldHEN/plugins/` no armazenamento interno do PS4 (você pode usar o PS4-Xplorer para isso).
2. **Acessar o Menu**: No menu principal do PS4, vá em *Configurações* > *GoldHEN*.
3. **Entrar no Plugin Manager**: Selecione a opção *Plugin Manager*. Uma lista com todos os arquivos `.prx` encontrados na pasta de plugins será exibida.
4. **Ativação**: 
   * Marque a caixa de seleção ao lado do plugin que deseja ativar (ex: `counter.prx` para ver o FPS).
   * Plugins marcados serão carregados automaticamente na próxima vez que o sistema iniciar ou que um jogo for aberto (dependendo do plugin).
5. **Configurações Individuais**: Alguns plugins permitem configurações extras pressionando o botão de opções sobre o nome deles no menu.
6. **Desativar Plugins**: Se um jogo estiver travando, volte ao Plugin Manager e desmarque a extensão suspeita para isolar o problema.

### Solução de Problemas

* **Plugin não aparece na lista**: Verifique se o arquivo está na pasta exata `/data/GoldHEN/plugins/` e se a extensão é minúscula (`.prx`).
* **Console trava ao ativar**: Nem todos os plugins são compatíveis entre si. Tente ativar um por um para descobrir qual está causando conflito.

### Aviso de Risco

Plugins de sistema rodam com privilégios elevados. Use apenas arquivos de fontes confiáveis para evitar corrupção de dados ou instabilidade no kernel do PS4.

## Download

[Baixar Tutorial: Como gerenciar plugins dinamicamente no GoldHEN usando o Plugin Manager (página oficial)](https://github.com/GoldHEN/GoldHEN/releases)

Fonte: <https://wololo.net/2024/05/04/ps4-goldhen-2-4b17-released-with-plugin-manager-and-more/>
