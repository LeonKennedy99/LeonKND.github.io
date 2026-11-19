---
layout: post
title: "Tutorial: Como ativar perfis offline no PS4 com o Offline Account Activator"
description: "Ative o ID da conta local sem precisar da PSN para usar Remote Play e gerenciar saves."
download: "https://github.com/charlyzard/PS4-Offline-Account-Activator/releases"
date: 2026-11-19 18:01:45 -0300
categories: ps4 tutorial
---

O **PS4 Offline Account Activator** é uma ferramenta essencial para usuários de consoles desbloqueados que desejam utilizar funções que normalmente exigem login na PSN, como o **Remote Play** ou a exportação de saves para dispositivos USB. Ele atribui um ID de conta fictício ao seu perfil de usuário local sem conectar aos servidores da Sony.

### Requisitos
* **PS4 Jailbroken:** Testado em firmwares como 5.05, 9.00 e 11.00.
* **Payload ps4debug:** Deve ser carregado no PS4 antes de usar a ferramenta.
* **PC na mesma rede:** Para executar o programa gerenciador.
* **Novo Perfil de Usuário:** Recomenda-se criar um novo usuário no PS4 apenas para esta ativação.

### Passo a Passo
1. **Preparação no PS4:**
   - Carregue o payload **ps4debug** (disponível na maioria dos hosts de exploit ou via menu do GoldHEN).
   - Vá em *Configurações > Rede* e verifique o IP do console.

2. **Execução no PC:**
   - Abra o `PS4OfflineAccountActivator.exe` como Administrador.
   - Digite o IP do PS4 no campo correspondente e clique em **Connect**.

3. **Identificação do Usuário:**
   - Clique em **Get Users**. Uma lista com os nomes de usuário presentes no PS4 aparecerá.
   - No campo 'Account ID', você deve inserir um ID de 16 caracteres hexadecimais (ex: `1234567890ABCDEF`). Se você já tem um save oficial e quer usar o mesmo ID, pode encontrá-lo usando o Apollo Save Tool ou olhando o nome da pasta de um save antigo no PC.

4. **Ativação:**
   - Selecione o usuário desejado na lista.
   - Clique em **Set Id & Activate**.
   - O programa confirmará a ativação. Reinicie o seu PS4 completamente.

### Avisos de Risco
* **Atenção:** Se você ativar uma conta antiga que já possui troféus, eles podem parar de funcionar ou causar erros ao abrir jogos. Por isso, é altamente recomendado usar um **perfil de usuário limpo**.
* O uso indevido pode corromper os arquivos do sistema de perfis; faça um backup de seus saves importantes antes de começar.

### Solução de Problemas
* **Console trava ao ativar:** Isso ocorre frequentemente se o GoldHEN estiver interferindo com o `ps4debug`. Tente carregar o exploit básico (sem GoldHEN) e injetar apenas o `ps4debug.bin` para realizar a ativação.
* **Erro 'Failed to Connect':** Verifique se o payload ps4debug está ouvindo na porta correta (geralmente 9020) e se o PS4 não entrou em modo de repouso.

## Download

[Baixar Tutorial: Como ativar perfis offline no PS4 com o Offline Account Activator (página oficial)](https://github.com/charlyzard/PS4-Offline-Account-Activator/releases)

Fonte: <https://github.com/charlyzard/PS4-Offline-Account-Activator>
