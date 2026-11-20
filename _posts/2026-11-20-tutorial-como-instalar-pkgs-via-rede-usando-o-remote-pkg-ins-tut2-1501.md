---
layout: post
title: "Tutorial: Como instalar PKGs via rede usando o Remote PKG Installer GUI"
description: "Envie arquivos PKG do seu computador para o PS4 sem precisar de HDs externos ou pendrives."
download: "https://github.com/irendis/PS4-Remote-PKG-Installer/releases"
date: 2026-11-20 15:01:43 -0300
categories: ps4 tutorial
---

O **Remote PKG Installer GUI** (versão de Irendis) é uma interface gráfica para PC que facilita o envio de pacotes (.pkg) para o aplicativo de instalação remota criado pelo desenvolvedor **flatz**. É ideal para quem não quer ficar movendo dispositivos USB entre o PC e o console.

### Requisitos
* PS4 com Jailbreak e o aplicativo **Remote PKG Installer** instalado e aberto.
* PC e PS4 conectados na mesma rede local (preferencialmente via cabo para maior velocidade).
* Java instalado no PC (para rodar a interface GUI).

### Passo a Passo
1. **No PS4**: Abra o aplicativo *Remote PKG Installer*. A tela ficará aguardando conexões; anote o endereço IP que aparece no menu de configurações do sistema do PS4.
2. **No PC**: Abra o executável do *Remote PKG Installer GUI*.
3. **Configuração**: No campo **PS4 IP**, digite o endereço IP do seu console. Certifique-se de que a porta (port) esteja configurada como `12800` (padrão).
4. **Adicionar Arquivos**: Clique no botão de adicionar ou simplesmente arraste os arquivos .pkg que deseja instalar para dentro da janela do programa.
5. **Iniciar Instalação**: Selecione os arquivos na lista e clique em **Install** ou **Send**. 
6. **Acompanhamento**: O PS4 começará a baixar o conteúdo como se fosse um download da PSN. Você pode acompanhar o progresso na barra de notificações do console.

### Avisos de Risco
* **Estabilidade da Rede**: Se a conexão Wi-Fi for instável, o download pode falhar e o arquivo ficar corrompido, exigindo que você apague e reinicie o processo.
* **Espaço em Disco**: O console precisa de pelo menos o dobro do tamanho do PKG em espaço livre para realizar a instalação via rede com sucesso.

### Solução de Problemas
* **Erro de Conexão**: Verifique se o Firewall do Windows está bloqueando o aplicativo no PC e se o aplicativo no PS4 está realmente aberto.
* **Falha no Envio**: Certifique-se de que o PKG não possui caracteres especiais ou espaços excessivos no nome do arquivo.

## Download

[Baixar Tutorial: Como instalar PKGs via rede usando o Remote PKG Installer GUI (página oficial)](https://github.com/irendis/PS4-Remote-PKG-Installer/releases)

Fonte: <https://github.com/flatz/ps4_remote_pkg_installer>
