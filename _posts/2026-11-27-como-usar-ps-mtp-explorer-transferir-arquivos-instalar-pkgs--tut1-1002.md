---
layout: post
title: "Tutorial: Como usar o PS MTP Explorer para transferir arquivos e instalar PKGs via celular"
description: "Aprenda a conectar seu Android ao PS4 via USB para gerenciar arquivos sem precisar de FTP ou pendrives."
download: "https://github.com/nueex/PS-MTP-Explorer/releases"
date: 2026-11-27 10:02:29 -0300
categories: ps4 tutorial
---

O **PS MTP Explorer** é uma ferramenta homebrew inovadora que utiliza o protocolo MTP (Media Transfer Protocol) para permitir que o PlayStation 4 acesse diretamente o armazenamento de dispositivos Android via cabo USB. Isso elimina a necessidade de servidores FTP lentos ou a constante formatação de pendrives em exFAT para transferir arquivos ou instalar pacotes.

### Requisitos

*   Console PS4 com **GoldHEN** ativado.
*   Smartphone Android com suporte a transferência de arquivos via USB (MTP).
*   Cabo USB de boa qualidade (que suporte dados).
*   Aplicativo **PS MTP Explorer v1.01** (ou superior) instalado no console.

### Passo a Passo

1.  **Instalação do Homebrew:** Baixe o arquivo PKG oficial do PS MTP Explorer e instale-o no seu PS4 através do menu *Debug Settings* > *Package Installer*.
2.  **Preparação no Console:** Abra o aplicativo PS MTP Explorer no menu principal do PS4. Você verá uma interface de explorador de arquivos dividida em colunas.
3.  **Conexão do Celular:** Conecte seu smartphone Android a uma das portas USB do PS4 usando o cabo.
4.  **Configuração no Android:** Assim que conectar, uma notificação aparecerá no seu celular perguntando o modo de uso do USB. Selecione **"Transferência de Arquivos"** ou **"MTP"**.
5.  **Acesso aos Arquivos:** No PS4, o aplicativo deverá reconhecer o dispositivo. Navegue até a unidade correspondente ao seu celular (geralmente montada em uma pasta específica dentro do app). 
6.  **Gerenciamento e Instalação:** 
    *   Para copiar arquivos: Selecione o arquivo no celular, pressione o botão de menu (Triângulo) e escolha *Copy*. Navegue até a pasta de destino no HD do PS4 e escolha *Paste*.
    *   Para instalar PKGs: Localize o arquivo `.pkg` no armazenamento do seu celular e pressione **X**. O app oferecerá a opção de instalação direta (Direct Install) sem precisar copiar para o console primeiro.

### Solução de Problemas

*   **Celular não reconhecido:** Verifique se o cabo USB suporta transferência de dados. Alguns cabos baratos servem apenas para carregamento. Certifique-se também de que a depuração USB não está impedindo o protocolo MTP em alguns modelos.
*   **Erro de Espaço:** Mesmo instalando direto do celular, o PS4 precisa de espaço livre no HD interno equivalente ao tamanho do jogo para realizar a descompactação e instalação.

### Avisos de Risco

*   Nunca desconecte o cabo USB durante uma transferência ou instalação de PKG, pois isso pode corromper os dados no console ou no banco de dados do sistema.

## Download

[Baixar Tutorial: Como usar o PS MTP Explorer para transferir arquivos e instalar PKGs via celular (página oficial)](https://github.com/nueex/PS-MTP-Explorer/releases)

Fonte: <https://www.youtube.com/watch?v=7uV8YfDzdUe>
