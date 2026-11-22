---
layout: post
title: "Tutorial: Como gerenciar o banco de dados do PS4 com o PS4 DB Auditor"
description: "Corrija erros de banco de dados e remova ícones fantasmas do seu menu inicial."
download: "https://github.com/Lapy05575948/PS4-DB-Auditor/releases"
date: 2026-11-22 18:01:49 -0300
categories: ps4 tutorial
---

O **PS4 DB Auditor**, desenvolvido pelo respeitado modder Lapy, é uma ferramenta essencial para manter a integridade do arquivo `app.db` do sistema. Ele é especialmente útil para quem instala e desinstala muitos homebrews e jogos, o que pode causar lentidão ou o surgimento de ícones que não abrem (ícones fantasmas).

### Requisitos
* PlayStation 4 desbloqueado com GoldHEN ou similar.
* Homebrew **PS4 DB Auditor** (arquivo .pkg) instalado no console.

### Passo a Passo
1. **Backup:** Antes de qualquer alteração, é altamente recomendável fazer um backup do seu banco de dados usando o *Apollo Save Tool* ou via FTP (copie o arquivo de `/system_data/priv/mms/app.db`).
2. **Iniciando:** Abra o PS4 DB Auditor no menu principal do console.
3. **Scan:** Selecione a opção **Audit Database**. O aplicativo irá escanear todas as entradas de aplicativos e jogos instalados.
4. **Identificação:** O app listará inconsistências, como entradas de jogos que não existem mais nos arquivos do sistema, mas ainda ocupam espaço no banco de dados.
5. **Limpeza:** Escolha a opção para remover as entradas órfãs ou corrigir as referências de ícones corrompidos.
6. **Reinicialização:** Após terminar o processo, saia do aplicativo e reinicie o console para que as alterações no menu inicial (XMB) sejam aplicadas.

### Avisos de Risco
* **Modificações Críticas:** Mexer no banco de dados (`app.db`) pode fazer com que seus jogos parem de aparecer se feito incorretamente. Nunca interrompa o processo enquanto o app estiver salvando as alterações.
* **Sempre faça backup** do arquivo original antes de usar a função de correção automática.

### Solução de Problemas
* **O App não abre:** Verifique se o GoldHEN está ativo. Homebrews que acessam o sistema exigem permissões de leitura/escrita que só o Jailbreak fornece.
* **Ícones sumiram:** Se após a limpeza ícones legítimos sumirem, use a função de *Rebuild Database* (Reconstruir Banco de Dados) nativa do PS4 no Modo de Segurança ou via GoldHEN.

## Download

[Baixar Tutorial: Como gerenciar o banco de dados do PS4 com o PS4 DB Auditor (página oficial)](https://github.com/Lapy05575948/PS4-DB-Auditor/releases)

Fonte: <https://www.psxhax.com/threads/ps4-db-auditor-playstation-4-database-utility-by-lapy.16104/>
