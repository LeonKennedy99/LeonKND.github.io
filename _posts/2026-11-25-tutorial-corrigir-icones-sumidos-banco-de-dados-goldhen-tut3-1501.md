---
layout: post
title: "Tutorial: Como corrigir ícones sumidos e erro de banco de dados com o GoldHEN"
description: "Recupere seus itens instalados após uma reconstrução de banco de dados acidental."
download: "https://github.com/GoldHEN/GoldHEN/releases"
date: 2026-11-25 15:01:50 -0300
categories: ps4 tutorial
---

### O que é a correção de Banco de Dados?
Quando o PS4 sofre um desligamento incorreto ou o usuário seleciona "Reconstruir Banco de Dados" no Modo de Segurança, todos os aplicativos instalados via PKG (homebrews e backups) desaparecem do menu principal. Eles continuam ocupando espaço no HD, mas o sistema "esquece" deles. O GoldHEN possui ferramentas para restaurar esses registros sem precisar reinstalar tudo.

### Requisitos
*   PS4 com GoldHEN ativo.
*   Homebrew PS4-Xplorer 2.0 instalado (opcional, para backup manual).

### Passo a Passo
1.  **Ative o GoldHEN:** Certifique-se de que o exploit foi carregado com sucesso.
2.  **Acesse as Opções:** Vá no menu de Configurações do PS4 > GoldHEN.
3.  **Debug Settings:** Navegue até as opções de Debug ou Ferramentas de Sistema (dependendo da versão do GoldHEN).
4.  **Restore DB:** Procure pela opção "Restore Database" ou "Scan for PKGs". O GoldHEN irá varrer o disco rígido em busca de arquivos que não estão indexados.
5.  **Aguarde o Processo:** O console pode parecer travado por alguns segundos enquanto reconstrói as tabelas `app.db`.
6.  **Reinicie o Shell:** Se os ícones não aparecerem imediatamente, reinicie o console e aplique o exploit novamente.
7.  **Método Alternativo:** Se o GoldHEN não resolver, use o PS4-Xplorer para navegar até `/system_data/priv/mms/` e verifique se há arquivos `.db` corrompidos que precisam ser substituídos pelos backups automáticos que o GoldHEN cria em `/data/GoldHEN/backups/`.

### Avisos de Risco
*   Sempre faça um backup da sua pasta `/system_data/priv/mms/` antes de tentar restaurar bancos de dados manualmente.
*   Não interrompa o processo de restauração para evitar corrupção real de dados.

### Solução de Problemas
*   **Ícones aparecem com cadeado:** Isso geralmente significa que as licenças (RIF) não foram restauradas. Execute o GoldHEN novamente para reativar as permissões.
*   **Espaço em disco cheio mas nada aparece:** O banco de dados está vazio. O uso do script "ItemzFlow Game Fixer" também pode ajudar neste caso.

## Download

[Baixar Tutorial: Como corrigir ícones sumidos e erro de banco de dados com o GoldHEN (página oficial)](https://github.com/GoldHEN/GoldHEN/releases)

Fonte: <https://github.com/GoldHEN/GoldHEN>
