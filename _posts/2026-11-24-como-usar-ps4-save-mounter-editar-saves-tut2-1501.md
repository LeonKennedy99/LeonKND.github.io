---
layout: post
title: "Tutorial: Como montar e editar saves de jogos com o PS4 Save Mounter"
description: "Aprenda a acessar os arquivos internos dos seus jogos salvos para realizar edições manuais ou backups."
download: "https://github.com/ChendoChap/PS4SaveMounter/releases"
date: 2026-11-24 15:01:48 -0300
categories: ps4 tutorial
---

### O que é?
O **PS4 Save Mounter** é uma ferramenta que permite "montar" a partição criptografada de um save game diretamente no sistema de arquivos do PS4 como uma pasta legível. Com isso, você pode usar um cliente FTP para copiar os arquivos do save para o PC, editá-los e devolvê-los ao console.

### Requisitos
* PS4 com jailbreak (FW 5.05 a 11.00).
* GoldHEN ativo.
* Ferramenta PS4 Save Mounter (PC).
* Um cliente FTP (como o FileZilla) ou o PS4-Xplorer 2.0 instalado no console.

### Passo a Passo
1. **No PS4:** Abra o jogo cujo save você deseja editar e carregue o seu progresso até o menu principal ou dentro da partida. Deixe o jogo aberto (suspenso).
2. **No PC:** Inicie o PS4 Save Mounter e digite o IP do console no campo correspondente. Clique em 'Setup'.
3. **Listagem:** Clique em 'Refresh' para ver a lista de processos ativos. Selecione o processo do seu jogo (geralmente começa com CUSA).
4. **Montagem:** Na lista de saves que aparecer, selecione o arquivo de save desejado e clique em 'Mount'. O console irá montar o save no diretório `/mnt/pfs/`.
5. **Acesso aos arquivos:** Use o FileZilla no PC para se conectar ao PS4 via FTP. Navegue até a pasta `/mnt/pfs/`. Lá estarão os arquivos descriptografados do seu save.
6. **Edição:** Copie os arquivos para o PC, faça as alterações necessárias e envie-os de volta para a mesma pasta no PS4, substituindo os originais.
7. **Salvamento:** No PS4 Save Mounter, clique em 'Unmount'. Volte ao jogo no PS4 e salve o progresso novamente para garantir que as alterações foram registradas pelo sistema.

### Avisos de Risco
* **Backup:** Sempre faça uma cópia de segurança do seu save original via USB (usando o sistema do PS4) antes de tentar este procedimento.
* Se os arquivos forem editados incorretamente, o save pode aparecer como 'Corrompido' ao carregar.

### Solução de Problemas
* **Erro ao montar:** Certifique-se de que o jogo está realmente rodando em primeiro ou segundo plano.
* **Pasta /mnt/pfs vazia:** Verifique se você clicou em 'Mount' e se o status no programa indicou sucesso.

## Download

[Baixar Tutorial: Como montar e editar saves de jogos com o PS4 Save Mounter (página oficial)](https://github.com/ChendoChap/PS4SaveMounter/releases)

Fonte: <https://github.com/ChendoChap/PS4SaveMounter>
