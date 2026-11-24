---
layout: post
title: "Tutorial: Como transferir arquivos via FTP usando o PS4-Xplorer 2.0"
description: "Use o servidor FTP integrado do PS4-Xplorer 2.0 para enviar arquivos do PC para o PS4 sem cabos."
download: "https://github.com/Lapy05575948/PS4-Xplorer-2.0/releases"
date: 2026-11-24 10:01:33 -0300
categories: ps4 tutorial
---

### O que é o FTP no PS4-Xplorer?
O PS4-Xplorer 2.0 possui um servidor FTP (File Transfer Protocol) embutido. Isso permite que você acesse todas as pastas internas do PlayStation 4 através de um computador ou smartphone conectado à mesma rede Wi-Fi ou cabo, facilitando a transferência de pacotes (PKGs), saves, músicas e configurações sem precisar de um pendrive.

### Requisitos
* Console PS4 com Homebrew Enabler (GoldHEN ou similar).
* Aplicativo PS4-Xplorer 2.0 instalado.
* Um cliente FTP no PC (recomendado: FileZilla ou WinSCP).
* Console e PC conectados na mesma rede local.

### Passo a Passo
1. **Iniciar o Aplicativo:** Abra o PS4-Xplorer 2.0 no seu PlayStation 4.
2. **Ativar o Servidor:** Pressione o botão **Options** (ou o ícone de engrenagem/ferramentas na interface) para abrir o menu lateral de funções.
3. **Ligar FTP:** Selecione a opção 'Enable FTP'. Uma mensagem aparecerá na tela exibindo o **Endereço IP** do console e a **Porta** (geralmente 1337).
4. **Configurar no PC:** No computador, abra o FileZilla. No campo 'Host', digite o IP mostrado no PS4. No campo 'Porta', digite 1337. Deixe usuário e senha em branco.
5. **Conectar:** Clique em 'Conexão Rápida'. As pastas do PS4 (como `/data`, `/user`, `/mnt/usb0`) aparecerão no lado direito do cliente FTP.
6. **Transferência:** Agora basta arrastar os arquivos do seu PC para a pasta desejada no PS4 (geralmente a pasta `/data` é usada para arquivos diversos).
7. **Desativar:** Ao terminar, lembre-se de desativar o FTP no PS4-Xplorer para economizar recursos do sistema.

### Avisos de Risco
* **Cuidado com Arquivos de Sistema:** Nunca delete ou modifique arquivos nas pastas `/system`, `/dev` ou root (`/`) a menos que saiba exatamente o que está fazendo, pois isso pode causar o brick do software do sistema.
* Transferências via Wi-Fi são mais lentas e podem falhar em arquivos muito grandes; prefira o cabo de rede para transferências acima de 1GB.

### Solução de Problemas
* **Falha na conexão:** Verifique se o firewall do Windows não está bloqueando o FileZilla e se o IP do PS4 não mudou nas configurações de rede.
* **Velocidade zero:** Certifique-se de que o PS4 não entrou em modo de repouso e que o PS4-Xplorer continua aberto e ativo na tela.

## Download

[Baixar Tutorial: Como transferir arquivos via FTP usando o PS4-Xplorer 2.0 (página oficial)](https://github.com/Lapy05575948/PS4-Xplorer-2.0/releases)

Fonte: <https://github.com/Lapy05575948/PS4-Xplorer-2.0>
