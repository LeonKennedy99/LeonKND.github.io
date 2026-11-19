---
layout: post
title: "Tutorial: Como usar o DirectPackageInstaller para instalar PKGs via rede (PC)"
description: "Instale backups e homebrews no PS4 diretamente do seu PC via rede com alta velocidade."
download: "https://github.com/direct-package-installer/direct-package-installer/releases"
date: 2026-11-19 18:01:44 -0300
categories: ps4 tutorial
---

O **DirectPackageInstaller** é uma ferramenta para Windows que facilita a instalação de arquivos PKG no PS4 através da rede local. Ele utiliza a API do *Remote Package Installer* e se destaca por possuir um servidor proxy integrado, que contorna as limitações de velocidade de download do hardware original do console, permitindo transferências muito mais rápidas.

### Requisitos
* **PS4 com Jailbreak:** Firmware compatível (como 9.00, 11.00 ou 14.02).
* **GoldHEN:** Com o 'Payload Server' ativado OU o homebrew **Remote Package Installer (RPI)** instalado e aberto no PS4.
* **PC e PS4 na mesma rede:** Preferencialmente conectados via cabo Ethernet para velocidade máxima.
* **DirectPackageInstaller:** Baixado no seu computador.

### Passo a Passo
1. **No PS4:**
   - Se estiver usando o **GoldHEN**, vá em *Configurações > GoldHEN > Server Settings* e ative o 'Binloader Server' ou 'Payload Server'.
   - Alternativamente, abra o aplicativo **Remote Package Installer** no menu inicial do seu PS4 e mantenha-o aberto.
   - Anote o endereço IP do seu console em *Configurações > Rede > Exibir Status da Conexão*.

2. **No Computador:**
   - Abra o `DirectPackageInstaller.exe`.
   - Vá em **Options > Settings** e insira o endereço IP do seu PS4.
   - Ative a opção **Proxy Downloads** (recomendado para maior velocidade).

3. **Preparando o arquivo:**
   - Você pode arrastar um arquivo PKG local para a janela do programa ou colar um link direto (URL) de um servidor de backup.
   - Clique em **Load** para que a ferramenta leia as informações do pacote (ícone, nome e tamanho).

4. **Iniciando a instalação:**
   - Clique no botão **Install**.
   - O PS4 receberá o comando e começará a baixar/instalar o conteúdo. Você pode acompanhar o progresso pela aba de 'Downloads' no menu de notificações do sistema do PS4.

### Avisos de Risco
* Certifique-se de que o PKG é compatível com o seu firmware; tentar instalar conteúdos incompatíveis pode causar erros de banco de dados no console.
* Não desligue o PC ou o console durante o processo de transferência para evitar arquivos corrompidos.

### Solução de Problemas
* **O programa não conecta:** Verifique se o firewall do Windows está permitindo a conexão do DirectPackageInstaller e se o IP do PS4 está correto.
* **Velocidade lenta:** Se estiver usando Wi-Fi, mude para cabos Ethernet. O proxy do programa geralmente resolve gargalos de velocidade, mas depende da estabilidade da sua rede local.

## Download

[Baixar Tutorial: Como usar o DirectPackageInstaller para instalar PKGs via rede (PC) (página oficial)](https://github.com/direct-package-installer/direct-package-installer/releases)

Fonte: <https://github.com/direct-package-installer/direct-package-installer>
