---
layout: post
title: "Tutorial: Como recuperar Homebrews desaparecidos com o PS4 Database Rebuilder"
description: "Corrija o problema de ícones invisíveis após uma reconstrução de banco de dados do sistema."
download: "https://github.com/LightningMods/PS4-db-rebuilder/releases"
date: 2026-11-20 18:01:47 -0300
categories: ps4 tutorial
---

Um problema comum na cena de PS4 é a perda de ícones de aplicativos homebrew (PKGs instalados) após o sistema realizar uma **Reconstrução de Banco de Dados** nativa. O **PS4 Database Rebuilder** é um script que restaura esses itens sem a necessidade de reinstalar tudo.

### O que é?
Esta ferramenta verifica as pastas de instalação do PS4 e força o sistema a reconhecer novamente os aplicativos que não foram baixados pela PSN, reinserindo-os no banco de dados principal (`app.db`).

### Requisitos
* **PS4 com Jailbreak:** GoldHEN ou similar ativo.
* **Acesso ao Console:** Via PS4-Xplorer ou FTP para executar scripts, ou a versão em PKG se disponível.
* **Backup:** Recomendado ter uma cópia do arquivo `app.db` original antes de começar.

### Passo a Passo
1. Certifique-se de que o GoldHEN está ativo e o suporte a **Binloader** ou instalação de PKGs está funcionando.
2. Execute o **PS4 Database Rebuilder** (pode ser via payload ou um aplicativo instalado).
3. Ao abrir a interface, selecione a opção **Rebuild Database** ou **Fix Icons**.
4. O script iniciará uma varredura em `/user/app/` para encontrar os metadados dos jogos e aplicativos instalados.
5. Após o término, o console pode solicitar um reinício ou apenas atualizar a Dashboard (XMB).
6. Verifique se os seus aplicativos voltaram a aparecer no menu principal.

### Avisos de Risco
* Nunca interrompa o processo enquanto o script estiver modificando o banco de dados para evitar corrupção de dados.
* Esta ferramenta não recupera jogos que foram deletados do HD, apenas restaura o atalho de itens que ainda estão presentes nos arquivos do sistema.

### Solução de Problemas
* **Ícones continuam invisíveis:** Tente rodar o script novamente após desativar e reativar o GoldHEN.
* **Erro de leitura:** Verifique se o seu HD interno não possui setores defeituosos que impedem a escrita no banco de dados.

## Download

[Baixar Tutorial: Como recuperar Homebrews desaparecidos com o PS4 Database Rebuilder (página oficial)](https://github.com/LightningMods/PS4-db-rebuilder/releases)

Fonte: <https://github.com/LightningMods/PS4-db-rebuilder>
