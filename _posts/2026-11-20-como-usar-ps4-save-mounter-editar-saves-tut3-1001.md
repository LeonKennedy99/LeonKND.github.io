---
layout: post
title: "Tutorial: Como usar o PS4 Save Mounter para editar arquivos de save no PC"
description: "Extraia e modifique saves diretamente do console usando seu computador."
download: "https://github.com/chendoau/ps4-save-mounter/releases"
date: 2026-11-20 10:01:29 -0300
categories: ps4 tutorial
---

### O que é
O PS4 Save Mounter é uma ferramenta que permite montar os arquivos de save do seu PlayStation 4 como unidades virtuais no PC via conexão de rede. Isso permite que você acesse, copie ou substitua arquivos internos do save (como arquivos de configuração ou inventário) sem precisar descriptografar tudo manualmente.

### Requisitos
* PS4 com Jailbreak (GoldHEN ou similar).
* PC na mesma rede que o console.
* Ferramenta PS4 Save Mounter instalada no PC.
* Um payload de servidor FTP ou o FTP nativo do GoldHEN ativo.

### Passo a Passo
1. **No PS4:** Inicie o GoldHEN e certifique-se de que o Servidor FTP está ativado nas configurações.
2. **No PC:** Abra o programa `ps4-save-mounter.exe`.
3. No campo **PS4 IP**, digite o endereço IP do seu console e clique em **Connect**.
4. Se a conexão for bem-sucedida, o programa listará todos os jogos instalados. Clique no jogo desejado para ver os saves disponíveis.
5. Selecione o save que deseja editar e clique em **Mount**. O programa criará uma nova unidade de disco no seu Windows (ex: Unidade Z:).
6. Abra o Explorador de Arquivos do Windows e vá até a unidade montada. Agora você pode copiar os arquivos de save para o PC, editá-los com editores hexadecimais ou substituir por outros.
7. Após terminar as edições, volte ao programa no PC e clique em **Unmount** para salvar as alterações no console.

### Avisos de Risco
* Sempre faça uma cópia de segurança do seu save original antes de qualquer modificação.
* Editar valores incorretos pode corromper o save, impedindo que o jogo o carregue.

### Solução de Problemas
* **Falha na conexão:** Verifique se o firewall do Windows não está bloqueando o programa e se o IP do PS4 está correto.
* **Lista de jogos vazia:** Certifique-se de que o jogo foi executado pelo menos uma vez no console antes de tentar montar o save.

## Download

[Baixar Tutorial: Como usar o PS4 Save Mounter para editar arquivos de save no PC (página oficial)](https://github.com/chendoau/ps4-save-mounter/releases)
