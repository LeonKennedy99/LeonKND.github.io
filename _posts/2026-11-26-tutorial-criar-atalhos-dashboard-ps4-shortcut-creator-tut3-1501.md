---
layout: post
title: "Tutorial: Como criar atalhos personalizados na Dashboard com o GoldHEN Shortcut Creator"
description: "Crie ícones no menu principal para sites ou comandos específicos."
download: "https://github.com/Gkiokan/GoldHEN-Shortcut-Creator/releases"
date: 2026-11-26 15:01:37 -0300
categories: ps4 tutorial
---

O **GoldHEN Shortcut Creator** é uma ferramenta para Windows que permite gerar arquivos PKG que funcionam como atalhos diretos na tela inicial (Dashboard) do PS4. Você pode criar atalhos para sites (como hosts de exploits) ou para caminhos específicos de arquivos.

### Requisitos
* PC com Windows.
* PS4 com GoldHEN e permissão para instalar PKGs.
* Imagens em PNG (512x512) para usar como ícone (opcional).

### Passo a Passo
1. **No PC:** Abra o *GoldHEN Shortcut Creator*.
2. **Informações Básicas:** Preencha o "App Title" (nome que aparecerá no menu) e o "Title ID" (deve ser único, ex: SHRT00001).
3. **Definição do Alvo:** No campo "URL / Path", digite o endereço do site que deseja abrir ou o caminho do arquivo no sistema do PS4.
4. **Personalização:** Clique nos espaços de imagem para carregar seu ícone (`icon0.png`) e a imagem de fundo (`pic1.png`).
5. **Gerar PKG:** Clique em "Build PKG". Escolha uma pasta para salvar o arquivo gerado.
6. **Instalação:** Transfira o arquivo PKG para um pendrive exFAT ou use o instalador via rede e instale no PS4 através do menu *Debug Settings* > *Package Installer*.
7. **Uso:** O novo ícone aparecerá na sua Dashboard como se fosse um jogo. Ao clicar, ele abrirá o navegador diretamente no link configurado.

### Avisos de Risco
* **Title ID Duplicado:** Se você instalar dois atalhos com o mesmo Title ID, um sobrescreverá o outro.
* **Uso Offline:** Atalhos para sites externos obviamente requerem conexão com a internet ativa no console.

### Solução de Problemas
* **O ícone não carrega:** Verifique se a imagem PNG está no tamanho correto (512x512 pixels) e não é muito pesada.
* **Erro ao abrir:** Verifique se a URL digitada no passo 3 está correta, incluindo o `http://` ou `https://`.

## Download

[Baixar Tutorial: Como criar atalhos personalizados na Dashboard com o GoldHEN Shortcut Creator (página oficial)](https://github.com/Gkiokan/GoldHEN-Shortcut-Creator/releases)

Fonte: <https://github.com/Gkiokan/GoldHEN-Shortcut-Creator>
