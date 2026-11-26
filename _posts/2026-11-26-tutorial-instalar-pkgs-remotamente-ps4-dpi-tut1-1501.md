---
layout: post
title: "Tutorial: Como instalar PKGs remotamente do PC com o DirectPackageInstaller (DPI)"
description: "Aprenda a instalar arquivos PKG via rede sem precisar de HD Externo."
download: "https://github.com/skiff92/DirectPackageInstaller/releases"
date: 2026-11-26 15:01:36 -0300
categories: ps4 tutorial
---

O **DirectPackageInstaller (DPI)** é uma ferramenta para Windows que facilita a instalação de pacotes (.pkg) no PS4 através da rede local (LAN ou Wi-Fi), eliminando a necessidade de copiar arquivos para um HD Externo ou Pendrive em formato exFAT.

### Requisitos
* PlayStation 4 com exploit (GoldHEN ou similar).
* PC com Windows e o framework .NET 6.0 instalado.
* Aplicativo **Remote Package Installer (RPI)** instalado e aberto no PS4.
* Ambos os aparelhos conectados na mesma rede.

### Passo a Passo
1. **No PS4:** Abra o aplicativo *Remote Package Installer* (RPI). Verifique e anote o endereço IP do seu console nas configurações de rede do PS4.
2. **No PC:** Baixe e execute o `DirectPackageInstaller.exe`.
3. **Configuração:** No campo "PS4 IP Address" dentro do DPI no PC, digite o IP que você anotou do console.
4. **Seleção de Arquivos:** Clique no botão de adicionar ou simplesmente arraste o arquivo PKG (homebrew ou atualização) para a janela do programa.
5. **Instalação:** Clique em "Install". Uma notificação aparecerá no seu PS4 indicando que o download e a instalação começaram.
6. **Monitoramento:** Você pode acompanhar o progresso tanto no PC quanto na aba de "Downloads" (Notificações) do PS4.

### Avisos de Risco
* **Interrupção de Rede:** Se a rede oscilar, a instalação falhará e você precisará excluir o dado corrompido nas notificações do PS4 antes de tentar novamente.
* **Arquivos Grandes:** Instalações via Wi-Fi podem ser lentas e instáveis; recomenda-se o uso de cabo Ethernet (LAN) para arquivos maiores.

### Solução de Problemas
* **Erro de Conexão:** Verifique se o Firewall do Windows não está bloqueando o DPI e se o RPI está realmente aberto no PS4.
* **O PS4 não inicia o download:** Certifique-se de que o GoldHEN está ativo e que a opção "Enable BinLoader" está ligada nas configurações do GoldHEN.

## Download

[Baixar Tutorial: Como instalar PKGs remotamente do PC com o DirectPackageInstaller (DPI) (página oficial)](https://github.com/skiff92/DirectPackageInstaller/releases)

Fonte: <https://github.com/skiff92/DirectPackageInstaller>
