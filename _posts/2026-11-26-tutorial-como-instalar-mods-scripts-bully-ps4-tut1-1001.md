---
layout: post
title: "Tutorial: Como instalar menus de mods e scripts no Bully (Canis Canem Edit) do PS4"
description: "Aprenda a modificar o clássico da Rockstar no seu console desbloqueado."
download: "https://github.com/Slinky-0/Bully-Mod-Menu/releases"
date: 2026-11-26 10:01:38 -0300
categories: ps4 tutorial
---

### O que é
Este tutorial ensina como injetar scripts personalizados e menus de mods na versão de PlayStation 4 do jogo Bully (Canis Canem Edit). Com isso, é possível ativar trapaças, mudar modelos de personagens e acessar ferramentas de depuração.

### Requisitos
* PS4 com GoldHEN ativo (qualquer firmware compatível).
* Aplicativo **PS4-Xplorer 2.0** instalado no console.
* Arquivos do Mod (geralmente denominados `Scripts.img` e `Scripts.dir`).
* Jogo instalado (este tutorial foca na região CUSA03507, a mais comum para mods).

### Passo a Passo
1. **Baixar o Mod:** Baixe os arquivos do menu de mods no link oficial. Descompacte os arquivos no seu PC.
2. **Transferência:** Copie os arquivos `Scripts.img` e `Scripts.dir` para a raiz de um pendrive formatado em exFAT ou transfira via FTP para o PS4.
3. **Localização do Jogo:** No PS4, abra o **PS4-Xplorer 2.0**. Navegue até o diretório: `/user/app/CUSA03507/data/` (ou o ID correspondente à sua região).
4. **Backup:** Localize os arquivos originais `Scripts.img` e `Scripts.dir` dentro da pasta `data`. Pressione **R1** e escolha a opção de renomear para adicionar `.bak` ao final do nome. Isso garante que você possa restaurar o jogo original depois.
5. **Instalação:** Copie os arquivos do mod do seu pendrive (`/mnt/usb0/`) e cole-os dentro da pasta `/user/app/CUSA03507/data/`.
6. **Execução:** Inicie o jogo. O menu de mods costuma ser ativado por uma combinação de botões (como L1 + Direcional para cima), dependendo do mod escolhido.

### Avisos de Risco
* **Corrupção de Save:** Mods podem corromper seus dados salvos. Sempre faça backup do seu save com o Apollo Save Tool antes de testar scripts.
* **Crash:** Se os arquivos não forem compatíveis com a versão/região do jogo, ele fechará com erro (CE-34878-0).

### Solução de Problemas
* **Mod não carrega:** Verifique se o Title ID da sua pasta em `/user/app/` coincide exatamente com a versão do seu jogo.
* **Jogo trava na tela inicial:** Delete os arquivos modificados e restaure os backups `.bak` originais usando o PS4-Xplorer.

## Download

[Baixar Tutorial: Como instalar menus de mods e scripts no Bully (Canis Canem Edit) do PS4 (página oficial)](https://github.com/Slinky-0/Bully-Mod-Menu/releases)

Fonte: <https://github.com/Slinky-0/Bully-Mod-Menu>
