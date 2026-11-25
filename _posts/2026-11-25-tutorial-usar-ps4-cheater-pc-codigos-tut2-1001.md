---
layout: post
title: "Tutorial: Como usar o PS4 Cheater no PC para criar e buscar cheats"
description: "Aprenda a buscar e editar valores de jogos (vida, dinheiro, munição) em tempo real via rede."
download: "https://github.com/ctn123/PS4Cheater/releases"
date: 2026-11-25 10:01:22 -0300
categories: ps4 tutorial
---

### O que é?
O PS4 Cheater é uma ferramenta para Windows que se comunica com o PS4 para realizar buscas na memória RAM do console. Ele funciona de forma similar ao 'Cheat Engine' do PC, permitindo encontrar endereços de memória de valores específicos em jogos para alterá-los.

### Requisitos
*   **PS4:** Com GoldHEN ativado.
*   **PC:** Com Windows e conectado na mesma rede local que o console.
*   **Configuração:** O 'Bin Loader' deve estar ativado nas configurações do GoldHEN no PS4.
*   **Payload:** `ps4debug.bin` (geralmente incluído no GoldHEN ou injetado via PC).

### Passo a Passo
1.  **Inicie o Jogo:** Abra o jogo que deseja modificar no PS4 e carregue seu save.
2.  **Ative o Debug:** No PS4, nas configurações do GoldHEN, certifique-se de que o servidor Bin Loader está rodando. Se o GoldHEN não incluir o ps4debug nativamente, injete o payload `ps4debug.bin` usando um injetor de payloads para o IP do seu console na porta 9090.
3.  **Conexão no PC:** Abra o `PS4Cheater.exe` no computador. Digite o endereço IP do seu PS4 e clique em 'Send Payload' (se necessário) ou 'Connect'.
4.  **Selecionar Processo:** Clique em 'Refresh' na lista de processos e selecione o processo principal do jogo (geralmente o maior, ex: `eboot.bin`).
5.  **Busca de Valores:** Digite o valor atual (ex: quantidade de ouro que você tem) em 'Value', escolha o 'Data Type' (geralmente 4 Bytes para números simples) e clique em 'First Scan'.
6.  **Filtragem:** Mude o valor dentro do jogo (gaste ou ganhe ouro), digite o novo valor no programa e clique em 'Next Scan'.
7.  **Edição:** Repita até sobrarem poucos endereços. Dê um duplo clique no endereço correto para adicioná-lo à lista inferior, mude o valor e marque a caixa 'Lock' para torná-lo infinito.

### Avisos de Risco
*   Alterar valores aleatórios na memória pode causar o travamento imediato do jogo ou do console (CE-34878-0).
*   Não use cheats em funcionalidades online, pois isso resultará em banimento permanente da conta e do console.

### Solução de Problemas
*   **Não conecta ao IP:** Verifique se o Firewall do Windows não está bloqueando o programa e se o PS4 e o PC estão na mesma sub-rede (mesmo roteador).
*   **Nenhum valor encontrado:** Tente mudar o 'Data Type' para '2 Bytes' ou '8 Bytes', ou utilize a busca 'Unknown Value' se o valor não for visível numericamente no jogo.

## Download

[Baixar Tutorial: Como usar o PS4 Cheater no PC para criar e buscar cheats (página oficial)](https://github.com/ctn123/PS4Cheater/releases)

Fonte: <https://www.psxhax.com/threads/ps4-cheater-ps4-game-trainer-homebrew-app-by-ctn.4035/>
