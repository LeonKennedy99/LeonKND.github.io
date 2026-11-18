---
layout: post
title: "Tutorial: Como instalar Jogos e Homebrews via Rede com o PS4 PKG Linker"
description: "Instale arquivos PKG diretamente do seu PC para o PS4 sem usar HDs externos ou pendrives."
download: "https://github.com/marcelo-macedo/ps4-pkg-linker/releases"
date: 2026-11-18 15:01:44 -0300
categories: ps4 tutorial
---

Instalar jogos grandes via USB pode ser demorado devido à velocidade de transferência e à necessidade de formatar drives em exFAT. O PS4 PKG Linker facilita o processo enviando os arquivos diretamente pela rede local.

### O que é
Uma ferramenta para PC Windows que cria um servidor web local para que o console baixe e instale arquivos fPKG através do app 'Remote Package Installer'.

### Requisitos
* PC e PS4 conectados na mesma rede (preferencialmente via cabo).
* Homebrew 'Remote Package Installer' (RPI) instalado no PS4.
* .NET Framework 4.7.2 ou superior no PC.
* Arquivos PKG que você deseja instalar.

### Passo a Passo
1. **Configurar o PC:** Abra o PS4 PKG Linker no seu computador.
2. **Selecionar Pasta:** Clique em 'Setup' e aponte para a pasta onde estão seus arquivos PKG.
3. **Obter IP:** O programa mostrará o IP do seu PC. Certifique-se de que é o IP correto da sua rede local.
4. **Preparar o PS4:** No console, abra o aplicativo Remote Package Installer e deixe-o aberto na tela principal.
5. **Vincular Ferramenta:** No PC, insira o endereço IP do seu PS4 no campo correspondente do PS4 PKG Linker.
6. **Iniciar Servidor:** Clique em 'Start Server'. A lista de PKGs da sua pasta aparecerá na tela.
7. **Instalar:** Selecione o arquivo desejado na lista e clique em 'Install'. O PS4 iniciará o download e instalação automaticamente na área de notificações.

### Avisos de Risco
* Use apenas em redes domésticas confiáveis.
* Se a conexão cair durante a instalação, o arquivo poderá ficar corrompido, sendo necessário deletar o ícone na dashboard e recomeçar.

### Solução de Problemas
* **PS4 não encontrado:** Verifique se o Firewall do Windows está bloqueando o PS4 PKG Linker. Adicione uma exceção para o programa.
* **Velocidade lenta:** Evite usar Wi-Fi. Conecte tanto o PC quanto o PS4 ao roteador via cabo Ethernet Cat5e ou Cat6 para atingir velocidades de até 1Gbps.

## Download

[Baixar Tutorial: Como instalar Jogos e Homebrews via Rede com o PS4 PKG Linker (página oficial)](https://github.com/marcelo-macedo/ps4-pkg-linker/releases)

Fonte: <https://www.psxhax.com/threads/ps4-pkg-linker-v2-0-send-pkgs-to-ps4-remotely-by-marcelo-macedo.7123/>
