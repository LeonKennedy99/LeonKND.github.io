---
layout: post
title: "Tutorial: Como atualizar o GoldHEN manualmente via USB"
description: "Aprenda a atualizar o GoldHEN sem precisar de internet ou de um novo host de exploit."
download: "https://github.com/GoldHEN/GoldHEN/releases"
date: 2026-11-23 17:12:24 -0300
categories: ps4 tutorial
---

Muitas vezes, os hosts de exploit demoram a atualizar a versão do GoldHEN. Você pode se antecipar e garantir a versão mais estável e com mais recursos fazendo a atualização manual do arquivo binário diretamente no sistema de arquivos do console.

### O que é?
O GoldHEN armazena suas configurações e o núcleo do sistema na memória interna do PS4 após a primeira execução. Atualizar manualmente garante que você tenha suporte a novos patches e plugins.

### Requisitos
* PS4 com qualquer versão do GoldHEN já funcional.
* Pendrive em exFAT.
* Arquivo `goldhen.bin` da versão mais recente (baixado do GitHub oficial).
* PS4-Xplorer 2.0 instalado.

### Passo a Passo
1. **Preparação:** Baixe o arquivo `.7z` ou `.zip` do GoldHEN no PC e extraia o arquivo `goldhen.bin`.
2. **USB:** Copie o `goldhen.bin` para a raiz do seu pendrive.
3. **No PS4:** Insira o pendrive e abra o PS4-Xplorer.
4. **Caminho de Destino:** Navegue até o diretório `/data/GoldHEN/` no armazenamento interno do console.
5. **Substituição:** Você verá um arquivo `goldhen.bin` lá. Delete-o (ou renomeie para `goldhen_old.bin` por segurança).
6. **Cópia:** Vá até `/mnt/usb0/` (seu pendrive), copie o novo `goldhen.bin` e cole-o dentro de `/data/GoldHEN/`.
7. **Reinicialização:** Reinicie o console e execute o exploit (PPPwn ou via navegador) normalmente. O sistema carregará a nova versão que você acabou de colar na pasta `data`.

### Avisos de Risco
* Não interrompa o processo de cópia. Se o arquivo ficar incompleto, o GoldHEN não carregará no próximo boot.
* Certifique-se de baixar a versão correta (v2.4 ou superior) para garantir compatibilidade com plugins.

### Solução de Problemas
* **GoldHEN não inicia:** Se o console travar ao carregar o exploit após a troca, delete o arquivo da pasta `/data/GoldHEN/` e deixe o host do navegador carregar a versão padrão dele novamente para recuperar o acesso.

## Download

[Baixar Tutorial: Como atualizar o GoldHEN manualmente via USB (página oficial)](https://github.com/GoldHEN/GoldHEN/releases)

Fonte: <https://github.com/GoldHEN/GoldHEN>
