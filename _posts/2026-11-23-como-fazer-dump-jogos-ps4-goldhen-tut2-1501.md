---
layout: post
title: "Tutorial: Como realizar o dump de seus próprios jogos com o GoldHEN Game Dumper"
description: "Crie backups de seus discos físicos e jogos digitais em formato fPKG."
download: "https://github.com/GoldHEN/GoldHEN/releases"
date: 2026-11-23 15:01:50 -0300
categories: ps4 tutorial
---

Fazer o "dump" de um jogo significa extrair os arquivos do disco ou da instalação digital para criar um backup (fPKG) que pode ser instalado em qualquer PS4 com jailbreak. Isso protege sua mídia física contra riscos e permite backups em HDs externos.

### O que é?
O **GoldHEN Game Dumper** é um recurso integrado (ou disponível via payload) que automatiza a cópia e descriptografia de jogos instalados no PS4 para um dispositivo USB externo.

### Requisitos
*   **PS4 com GoldHEN ativado.**
*   **HD Externo ou Pendrive:** Formatado em **exFAT** com espaço suficiente para o tamanho total do jogo.
*   **Jogo Original:** O disco deve estar inserido ou o jogo digital deve estar licenciado no console.

### Passo a Passo
1.  **Conexão do USB:** Insira seu dispositivo USB em uma das portas frontais do PS4.
2.  **Configuração do GoldHEN:** Vá ao menu de configurações do **GoldHEN** no topo da lista de configurações do sistema.
3.  **Ativar o Dumper:** Procure pela opção **Enable Game Dumper** ou inicie o payload de dumper através de um servidor de payloads local.
4.  **Iniciar o Jogo:** Abra o jogo do qual deseja fazer o backup e permaneça no menu principal (não é necessário jogar, apenas deixar o processo rodando em segundo plano).
5.  **Monitoramento:** O GoldHEN exibirá notificações no canto superior esquerdo da tela informando o progresso da cópia (ex: `Dumping... 10%`).
6.  **Conclusão:** Quando o processo terminar, uma notificação dirá `Dump Complete`. Você pode fechar o jogo e remover o HD.
7.  **Pós-Processamento (PC):** Os arquivos estarão em uma pasta no seu USB. Você precisará usar o software **GP4 Generator** e o **Orbis-pub-gen** no PC para criar o arquivo PKG final instalável.

### Avisos de Risco
*   Não remova o dispositivo USB enquanto o progresso de dump estiver ativo, pois isso pode corromper os arquivos copiados.
*   Certifique-se de que o console não entre em modo de repouso durante a cópia.

### Solução de Problemas
*   **Notificação de Espaço Insuficiente:** Verifique se o seu dispositivo USB tem espaço livre maior que o tamanho do jogo listado nas informações do sistema.
*   **O Dump não inicia:** Verifique se o arquivo `dumper.cfg` está presente na raiz do USB (em algumas versões do payload, ele é necessário para definir se você quer copiar apenas a base, updates ou DLCs).

## Download

[Baixar Tutorial: Como realizar o dump de seus próprios jogos com o GoldHEN Game Dumper (página oficial)](https://github.com/GoldHEN/GoldHEN/releases)

Fonte: <https://github.com/GoldHEN/GoldHEN>
