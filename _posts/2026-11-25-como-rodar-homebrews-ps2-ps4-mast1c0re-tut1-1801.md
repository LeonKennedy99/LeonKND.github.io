---
layout: post
title: "Tutorial: Como rodar homebrews de PS2 no PS4 via exploit Mast1c0re"
description: "Aprenda a usar a vulnerabilidade do emulador de PS2 para rodar códigos no PS4."
download: "https://github.com/McCaulay/mast1c0re/releases"
date: 2026-11-25 18:01:17 -0300
categories: ps4 tutorial
---

### O que é o Mast1c0re?
O **Mast1c0re** é um exploit que utiliza uma vulnerabilidade no emulador oficial de PlayStation 2 dentro do PS4. Diferente do PPPwn ou GoldHEN, ele não é um jailbreak completo do sistema, mas permite executar código não assinado e homebrews de PS2 em praticamente qualquer firmware, incluindo versões recentes.

### Requisitos
*   **Jogo Necessário:** Uma cópia original do jogo *Okage: Shadow King* (disponível na PS Store).
*   **Firmware:** Compatível com quase todas as versões de software do sistema.
*   **Ferramentas:** Um PC e o arquivo de save modificado do Mast1c0re.
*   **Rede:** PC e PS4 devem estar na mesma rede local.

### Passo a Passo
1.  **Prepare o Save:** Baixe o arquivo de save correspondente à região do seu jogo (EUA ou Europa) no link oficial.
2.  **Transfira o Save:** Utilize um pendrive formatado em FAT32 ou exFAT. Você precisará de um método para transferir esse save para o armazenamento do PS4 (como o PS4 Save Mounter ou via PS Plus Cloud, se tiver acesso).
3.  **Inicie o Jogo:** Abra o *Okage: Shadow King* no seu PS4.
4.  **Ative o Exploit:** Dentro do jogo, vá até o menu de carregar save e escolha o arquivo modificado. Isso fará com que o jogo trave momentaneamente e carregue a interface do Mast1c0re.
5.  **Envie o Homebrew:** No PC, utilize a ferramenta `mast1c0re-send-file` para enviar arquivos ISO de PS2 ou arquivos ELF para o endereço IP do seu console que aparecerá na tela.

### Avisos de Risco
*   O processo envolve a manipulação de saves; sempre faça backup do seu save original antes de sobrescrever.
*   Não garante 100% de compatibilidade com todos os jogos de PS2.

### Solução de Problemas
*   **O jogo fecha sozinho:** Certifique-se de que a versão do save corresponde exatamente à região do seu jogo.
*   **Erro de conexão:** Verifique se o firewall do seu PC não está bloqueando a comunicação com o IP do PS4.

## Download

[Baixar Tutorial: Como rodar homebrews de PS2 no PS4 via exploit Mast1c0re (página oficial)](https://github.com/McCaulay/mast1c0re/releases)

Fonte: <https://github.com/McCaulay/mast1c0re>
