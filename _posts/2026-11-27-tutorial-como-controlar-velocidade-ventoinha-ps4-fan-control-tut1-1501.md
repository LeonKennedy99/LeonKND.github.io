---
layout: post
title: "Tutorial: Como controlar a velocidade da ventoinha no PS4 com o PS4 Fan Control"
description: "Aprenda a configurar a temperatura ideal do seu console para evitar superaquecimento."
download: "https://github.com/Sistro/PS4-Fan-Control/releases"
date: 2026-11-27 15:01:34 -0300
categories: ps4 tutorial
---

O superaquecimento é um dos maiores vilões da vida útil do PlayStation 4. Por padrão, a Sony prioriza o silêncio, permitindo que o console atinja temperaturas altas antes de acelerar a ventoinha. O **PS4 Fan Control** permite que o usuário defina um limite de temperatura (Threshold) para que o sistema mantenha o hardware resfriado de forma mais agressiva.

### Requisitos

* PS4 com exploit (GoldHEN ou similar) em firmware compatível (até 11.00).
* Aplicativo **PS4 Fan Control** (PKG) instalado.
* Acesso ao instalador de PKGs no menu de configurações do GoldHEN.

### Passo a Passo

1. **Instalação**: Baixe o arquivo PKG oficial e instale-o no seu PS4 através de um pendrive formatado em exFAT, usando a opção *Package Installer* nas configurações do GoldHEN.
2. **Abertura do App**: Inicie o PS4 Fan Control pela Dashboard.
3. **Modos de Operação**: 
   * **Auto**: O sistema original da Sony controla a velocidade.
   * **Payload**: O aplicativo assume o controle com base nas suas configurações.
   * **Manual**: Você define uma velocidade fixa (ex: 40% ou 50%).
4. **Configurando a Temperatura Alvo**: Selecione o modo **Payload** e ajuste o campo *Threshold* (Limite). O recomendado para maior durabilidade é entre **65°C e 70°C**. Assim que o PS4 atingir essa temperatura, a ventoinha acelerará automaticamente para resfriá-lo.
5. **Ativar ao Iniciar**: Para que a configuração persista, certifique-se de que a opção de carregar as configurações ao iniciar o console esteja ativa (se disponível na sua versão).
6. **Monitoramento**: Observe a temperatura exibida no canto da tela para garantir que o ajuste está sendo eficaz.

### Solução de Problemas

* **Ventoinha muito barulhenta**: Se você definir uma temperatura muito baixa (ex: 55°C), a ventoinha ficará em alta velocidade constantemente. Ajuste para um valor equilibrado.
* **App fecha sozinho**: Certifique-se de que o GoldHEN está ativo antes de abrir o aplicativo.

### Aviso de Risco

Alterar a velocidade da ventoinha para níveis muito baixos manualmente pode causar superaquecimento e desligamento súbito do console. Use sempre o modo Payload com um limite de temperatura seguro.

## Download

[Baixar Tutorial: Como controlar a velocidade da ventoinha no PS4 com o PS4 Fan Control (página oficial)](https://github.com/Sistro/PS4-Fan-Control/releases)

Fonte: <https://github.com/Sistro/PS4-Fan-Control>
