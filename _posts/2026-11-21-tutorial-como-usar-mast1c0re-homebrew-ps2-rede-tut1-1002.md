---
layout: post
title: "Tutorial: Como usar o Mast1c0re para carregar Homebrews de PS2 via rede"
description: "Execute código de PS2 em firmwares recentes do PS4 via rede."
download: "https://github.com/McCaulay/mast1c0re/releases"
date: 2026-11-21 10:02:10 -0300
categories: ps4 tutorial
---

### O que é o Mast1c0re?
O **Mast1c0re** é um exploit que utiliza uma vulnerabilidade no emulador oficial de PlayStation 2 dentro do PS4. Diferente do GoldHEN, ele não desbloqueia o sistema inteiro, mas permite rodar arquivos ELF e ISO de PS2 (homebrews) em firmwares muito mais recentes, inclusive aqueles que ainda não possuem Jailbreak completo (como o 11.50 e superiores).

### Requisitos
*   Um PS4 com firmware compatível (testado até 12.00).
*   O jogo **Okage Shadow King** (PS2 Classics) instalado legalmente no PS4.
*   Um PC na mesma rede que o console.
*   O arquivo de save modificado do Mast1c0re correspondente à sua região.
*   **Mast1c0re Network Loader** (para enviar os arquivos via PC).

### Passo a Passo
1.  **Preparação do Save:** Baixe o arquivo de save do Mast1c0re no GitHub oficial. Use uma ferramenta como o Apollo Save Tool (se tiver jailbreak) ou o PS4 Save Wizard para importar o save modificado para o seu perfil no PS4.
2.  **Iniciar o Exploit:** Abra o jogo *Okage Shadow King*. Carregue o save modificado. O jogo irá travar e abrir uma tela preta ou uma interface simples; isso indica que o carregador (loader) está aguardando uma conexão.
3.  **Configuração no PC:** Abra o programa `mast1c0re-file-loader` no seu computador.
4.  **Conexão:** Digite o endereço IP do seu PS4 no campo indicado no programa do PC.
5.  **Envio do Homebrew:** Selecione o arquivo `.elf` ou a imagem de PS2 que deseja executar e clique em "Send".
6.  **Execução:** O PS4 receberá o arquivo e iniciará o carregamento do conteúdo de PS2 automaticamente.

### Avisos de Risco
*   Este método não permite rodar jogos de PS4, apenas conteúdo de PS2.
*   Certifique-se de usar o save correto para a região do seu jogo (EUA, EUR ou JPN), ou o exploit não funcionará.

### Solução de Problemas
*   **O jogo fecha com erro CE-34878-0:** Isso acontece se o save não foi injetado corretamente ou se a versão do firmware não é suportada pelo save específico.
*   **Falha na conexão:** Verifique se o Firewall do Windows está bloqueando o carregador e se o PS4 e o PC estão no mesmo roteador.

## Download

[Baixar Tutorial: Como usar o Mast1c0re para carregar Homebrews de PS2 via rede (página oficial)](https://github.com/McCaulay/mast1c0re/releases)

Fonte: <https://github.com/McCaulay/mast1c0re>
