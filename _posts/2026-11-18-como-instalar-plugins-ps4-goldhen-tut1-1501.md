---
layout: post
title: "Tutorial: Como instalar e gerenciar Plugins no PS4 com GoldHEN"
description: "Aprenda a adicionar funcionalidades como contadores de FPS e melhorias de sistema ao seu PS4."
download: "https://github.com/GoldHEN/GoldHEN_Plugins_Repository/releases"
date: 2026-11-18 15:01:42 -0300
categories: ps4 tutorial
---

Os plugins no PS4 permitem que funções extras rodem em segundo plano enquanto você joga, como exibir a temperatura do console, contador de FPS ou até mesmo desativar notificações de troféus. Este recurso é exclusivo para consoles com o GoldHEN carregado.

### O que é
Plugins são arquivos com extensão `.prx` que modificam o comportamento do sistema Orbis OS em tempo real através do GoldHEN Plugin Loader.

### Requisitos
* PlayStation 4 com Jailbreak ativo.
* GoldHEN v2.3 ou superior instalado.
* Um computador com cliente FTP (como o FileZilla) ou o homebrew PS4 Explorer 2.0 instalado no console.
* Arquivos de plugins (.prx).

### Passo a Passo
1. **Preparar os Arquivos:** No seu PC, baixe os plugins desejados (como o `afk.prx` ou `game_counter.prx`).
2. **Acessar o Sistema de Arquivos:** Conecte-se ao PS4 via FTP ou abra o PS4 Explorer 2.0.
3. **Localizar a Pasta:** Vá até o diretório `/data/GoldHEN/plugins` (se a pasta não existir, crie-a exatamente com esse nome).
4. **Transferir os Plugins:** Copie os arquivos `.prx` para dentro da pasta `plugins`.
5. **Configurar a Inicialização:** No mesmo diretório `/data/GoldHEN/`, procure pelo arquivo `plugins.ini`. Se não existir, crie um arquivo de texto com esse nome.
6. **Editar o plugins.ini:** Abra o arquivo e adicione o caminho do plugin que deseja ativar. Exemplo:
   `[somente_um_nome]`
   `path=/data/GoldHEN/plugins/nome_do_plugin.prx`
   `enabled=1`
7. **Reiniciar:** Reinicie o console ou recarregue o GoldHEN através do menu de configurações.

### Avisos de Risco
* O uso de muitos plugins simultâneos pode causar instabilidade no sistema ou crashes em jogos pesados.
* Certifique-se de que o plugin é compatível com a sua versão de firmware para evitar loops de inicialização.

### Solução de Problemas
* **Plugin não carrega:** Verifique se o caminho no arquivo `plugins.ini` está exatamente igual ao nome do arquivo na pasta.
* **Console travando:** Delete o arquivo `plugins.ini` via FTP para forçar o sistema a iniciar sem plugins.

## Download

[Baixar Tutorial: Como instalar e gerenciar Plugins no PS4 com GoldHEN (página oficial)](https://github.com/GoldHEN/GoldHEN_Plugins_Repository/releases)

Fonte: <https://github.com/GoldHEN/GoldHEN>
