---
layout: post
title: "Tutorial: Como usar o Direct Package Installer (DPI) para instalar PKGs via URL"
description: "Instale homebrews e atualizações diretamente da internet sem baixar no PC."
download: "https://github.com/marcussacana/Direct-Package-Installer/releases"
date: 2026-11-22 18:01:47 -0300
categories: ps4 tutorial
---

O **Direct Package Installer (DPI)** é uma ferramenta utilitária para Windows que permite ao usuário enviar e instalar arquivos PKG no PlayStation 4 através de uma URL direta (link de download), eliminando a necessidade de baixar o arquivo para o PC primeiro e depois transferi-lo. Ele atua em conjunto com o Remote Package Installer no console.

### Requisitos
* PS4 com Jailbreak (GoldHEN ou similar).
* Firmware compatível (9.00 até 11.00 ou superior, conforme suporte do GoldHEN).
* Aplicativo **Remote Package Installer (RPI)** instalado e aberto no PS4.
* PC com Windows conectado na mesma rede que o console.
* Link direto do arquivo PKG (deve terminar em .pkg).

### Passo a Passo
1. **No PS4:** Certifique-se de que o console está com o exploit ativo. Abra o aplicativo *Remote Package Installer*. Uma tela preta ou com o logo do app aparecerá; mantenha-a aberta.
2. **No PC:** Baixe e extraia o Direct Package Installer.
3. Abra o executável do DPI. Na interface, localize o campo **PS4 IP** e digite o endereço IP do seu console (pode ser encontrado nas configurações de rede do PS4).
4. No campo **URL**, cole o link direto do arquivo PKG que você deseja instalar.
5. Clique no botão **Install**. O software enviará o comando para o PS4.
6. No console, uma notificação de "Adicionado aos Downloads" deve aparecer. Você pode acompanhar o progresso na área de notificações nativa do PS4.

### Avisos de Risco
* **Interrupção de Rede:** Se a conexão cair durante o processo, o download será pausado. Se o link expirar, o arquivo pode ficar corrompido, exigindo que você apague a notificação e reinicie.
* **Links Protegidos:** O DPI não funciona com links que exigem login ou captcha (como Google Drive ou Mega sem link direto).

### Solução de Problemas
* **Erro de conexão:** Verifique se o Firewall do Windows não está bloqueando o DPI e se o IP do console está correto.
* **O RPI não responde:** Feche e abra o Remote Package Installer no PS4 novamente. Certifique-se de que nenhum outro instalador remoto (como o do ItemzFlow) esteja rodando simultaneamente.

## Download

[Baixar Tutorial: Como usar o Direct Package Installer (DPI) para instalar PKGs via URL (página oficial)](https://github.com/marcussacana/Direct-Package-Installer/releases)

Fonte: <https://www.psx-place.com/threads/direct-package-installer-v1-0-2-by-marcussacana.31011/>
