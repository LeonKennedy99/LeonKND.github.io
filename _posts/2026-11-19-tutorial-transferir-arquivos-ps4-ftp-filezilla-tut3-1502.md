---
layout: post
title: "Tutorial: Como transferir arquivos para o PS4 via FTP (FileZilla)"
description: "Aprenda a acessar as pastas internas do seu console para gerenciar arquivos sem usar USB."
download: "https://filezilla-project.org/download.php?show_all=1"
date: 2026-11-19 15:02:10 -0300
categories: ps4 tutorial
---

O uso de FTP (File Transfer Protocol) é a forma mais eficiente de gerenciar arquivos no PS4, permitindo enviar mods, backups de saves ou organizar pastas internas sem precisar remover HDs externos ou usar pen drives.

### O que é?
Um protocolo de comunicação que permite que seu computador 'enxergue' o disco rígido interno do PlayStation 4 como se fosse uma pasta comum no Windows.

### Requisitos
*   PS4 com GoldHEN ou PS4 Explorer (ambos possuem servidores FTP integrados).
*   Computador com o cliente **FileZilla** instalado.
*   Ambos os dispositivos na mesma rede Wi-Fi ou cabo.

### Passo a Passo
1.  **Ativar o Servidor no PS4:** Se estiver usando o **GoldHEN**, vá nas configurações dele e ative a opção 'Enable FTP'. Se usar o **PS4 Explorer**, o FTP é ativado automaticamente ao abrir o app.
2.  **Anotar IP e Porta:** No canto superior da tela (ou nas configurações do GoldHEN), aparecerá algo como `IP: 192.168.1.15 Port: 2121`.
3.  **Configurar o FileZilla:** No PC, abra o FileZilla. No campo 'Host', digite o IP do PS4. No campo 'Porta', digite o número informado (geralmente 2121 ou 1337).
4.  **Conectar:** Clique em 'Conexão Rápida'. Se aparecer um aviso sobre conexão não segura, aceite para continuar.
5.  **Navegar:** As pastas do PS4 aparecerão no lado direito. A pasta principal para usuários é `/user/`. Para instalar mods em jogos, o caminho costuma ser `/user/app/[CUSA_DO_JOGO]`.
6.  **Transferir:** Arraste os arquivos do seu PC (lado esquerdo) para a pasta desejada no PS4 (lado direito).

### Avisos de Risco
*   **CUIDADO:** Nunca delete ou modifique arquivos nas pastas `/system/` ou `/dev/`, a menos que saiba exatamente o que está fazendo. Isso pode causar o brick (morte) do software do console.
*   Evite transferir milhares de arquivos pequenos de uma vez (como pastas de jogos de retroemulação) via Wi-Fi; prefira compactar ou usar cabo de rede.

### Solução de Problemas
*   **Conexão recusada:** Verifique se o PS4 não entrou em modo de repouso e se o servidor FTP ainda está ativo.
*   **Erro de escrita:** Algumas pastas do sistema são 'apenas leitura'. Você só conseguirá escrever em pastas dentro do diretório `/user/`.

## Download

[Baixar Tutorial: Como transferir arquivos para o PS4 via FTP (FileZilla) (página oficial)](https://filezilla-project.org/download.php?show_all=1)

Fonte: <https://www.psx-place.com/threads/guide-how-to-use-ftp-on-ps4.13115/>
