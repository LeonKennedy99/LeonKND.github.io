---
layout: post
title: "Tutorial: Como usar o Chiaki para Remote Play no PS4 sem PSN"
description: "Aprenda a fazer streaming do seu PS4 para PC ou Steam Deck sem depender dos servidores da Sony."
download: "https://github.com/thestr4ng3r/chiaki/releases"
date: 2026-11-23 17:12:22 -0300
categories: ps4 tutorial
---

O Chiaki é um cliente de código aberto para o Remote Play da Sony, permitindo que você transmita a tela do seu PS4 para um PC (Windows, Linux, Mac) ou dispositivos portáteis como o Steam Deck. A grande vantagem é que ele não exige que o console esteja conectado à PSN para funcionar, sendo ideal para usuários com jailbreak.

### Requisitos
* Console PS4 com GoldHEN ativado.
* PC ou dispositivo portátil na mesma rede local.
* O ID da sua conta (Account ID). Para consoles com jailbreak, você pode obter isso usando o payload 'PS4 Offline Web Activator' ou verificando as configurações do seu perfil no Apollo Save Tool.
* O software Chiaki instalado no seu computador.

### Passo a Passo
1. **Obtenha seu Account ID:** No PS4, use o Apollo Save Tool para ver as informações do seu usuário atual. Anote o código de 16 caracteres (Account ID).
2. **Habilite o Remote Play no PS4:** Vá em Configurações > Configurações de conexão para o Uso remoto e marque a caixa 'Habilitar Uso remoto'.
3. **Registrar novo dispositivo:** No PS4, selecione 'Adicionar dispositivo'. Um código de 8 dígitos aparecerá na tela. Deixe essa tela aberta.
4. **Configure o Chiaki no PC:** Abra o Chiaki. Ele deve detectar seu PS4 automaticamente na rede (ícone de console). Clique duas vezes nele.
5. **Preencha os dados:** No campo 'PSN Account ID', cole o código que você obteve no passo 1. No campo 'PIN', digite o código de 8 dígitos que aparece na TV do seu PS4.
6. **Finalize o registro:** Clique em 'Register'. Se tudo estiver correto, uma mensagem de sucesso aparecerá.
7. **Inicie o streaming:** Agora, basta clicar duas vezes no ícone do console no Chiaki para iniciar a transmissão.

### Avisos de Risco
* O desempenho depende inteiramente da qualidade da sua rede Wi-Fi ou cabeada. Recomenda-se o uso de cabo Ethernet tanto no console quanto no PC para evitar latência.
* Não compartilhe seu Account ID publicamente.

### Solução de Problemas
* **Console não aparece:** Verifique se o console e o PC estão na mesma sub-rede (ex: ambos no 192.168.1.x).
* **Erro de conexão:** Certifique-se de que o GoldHEN está ativo, pois ele ajuda a contornar verificações de licença durante o streaming.

## Download

[Baixar Tutorial: Como usar o Chiaki para Remote Play no PS4 sem PSN (página oficial)](https://github.com/thestr4ng3r/chiaki/releases)

Fonte: <https://github.com/thestr4ng3r/chiaki>
