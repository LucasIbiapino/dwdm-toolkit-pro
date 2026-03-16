# 🌐 DWDM Toolkit Pro

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)

O **DWDM Toolkit Pro** é uma ferramenta "Canivete Suíço" interativa e totalmente offline, desenvolvida para engenheiros de telecomunicações, analistas de rede e técnicos de campo. A ferramenta centraliza os cálculos mais complexos de redes ópticas DWDM (Dense Wavelength Division Multiplexing) em uma única interface rápida, intuitiva e com suporte a Tema Escuro (Dark Mode).

🔗 **[Acessar a Ferramenta Online](https://lucasibiapino.github.io/dwdm-toolkit-pro/)**

---

## ✨ Funcionalidades Principais

A aplicação conta com um sistema de **Auto-Save** (salva seus dados automaticamente no cache do navegador) e foi projetada em formato modular. Cada aba contém um **Dicionário de Conceitos** e as **Fórmulas Matemáticas** visíveis em tempo real.

* **📉 Atenuação & Perdas Passivas:** Cálculo de perdas de enlace por quilometragem e módulo dedicado para orçamento de Emendas e Conectores.
* **⚡ Potência & Ganho Ideal:** Desdobramento de Potência Total vs. Potência por Canal, limites não-lineares (SPM, SBS) e cálculo reverso para descobrir o Ganho Ideal de amplificadores.
* **🎛️ Ganho de Amplificadores:** Cálculos diretos de Pin, Pout e Ganho de EDFAs.
* **🔌 Banco de SFPs/Transceivers:** Catálogo integrado para carregar especificações de ópticas (10G, 100G, 400G Coerente) e enviá-las direto para o orçamento de qualidade.
* **📶 OSNR & Cascata (Multi-Span):** Previsão de Relação Sinal-Ruído para trechos únicos e um **Construtor de Rota** completo para simular OSNR acumulada em vários spans e EDFAs/Ramans.
* **📻 Espectro & Mapa ITU (OSA):** Calculadora de Grid ITU-T (100GHz), medição de Tilt e um **Simulador Gráfico (OSA)** que desenha o espectro DWDM na tela com base no tilt e canais ativos.
* **🌊 Dispersão & Compensação (DCF):** Avaliação de Dispersão Cromática (CD), Dispersão Modal (PMD) e um módulo interativo para dimensionar carretéis de fibra compensadora (DCM/DCF).
* **🛡️ QoT (Qualidade de Transmissão):** Orçamento Óptico (Link Budget), verificação de Perda de Retorno (ORL) e análise de viabilidade de limites FEC.
* **👁️ Fator Q e BER:** Conversor bidirecional avançado utilizando aproximação gaussiana para estimar o Pre-FEC BER a partir do Fator Q.
* **🚀 Modulação Coerente:** Simulador de Baud Rate, Largura de Banda Óptica e análise inteligente de viabilidade de formatos (QPSK, 16QAM, 64QAM).
* **⏱️ SLA e Latência:** Cálculo de RTT físico do vidro e estimativa de "Noves" (Disponibilidade Anual Contratual e SLA Apurado em 7, 15 ou 30 dias).
* **🔄 Conversor:** Transformação instantânea e bidirecional de dBm ↔ mW.

---

## 🖨️ Geração de Relatórios

O sistema possui uma função integrada nativa para compilar todas as métricas inseridas e gerar memórias de cálculo profissionais. Sem o uso de nenhum servidor (100% Client-Side):
* **Exportação para PDF:** Relatório de engenharia devidamente formatado para documentação *As-Built*.
* **Exportação para CSV:** Arquivo de dados para importação e tratamento massivo no Excel ou em scripts.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído com foco na **portabilidade máxima**. É composto por um único arquivo (`index.html`), o que significa que pode ser salvo em um pen drive ou enviado por e-mail e rodará nativamente em qualquer navegador, seja no PC ou no celular.

As tecnologias importadas via CDN incluem:
* **Vue.js 3** - Para a reatividade instantânea, Auto-Save e simulações gráficas.
* **Tailwind CSS** - Framework de estilos para a interface moderna, responsiva e com suporte a *Dark Mode*.
* **FontAwesome 6** - Iconografia gráfica vetorial.
* **jsPDF & jsPDF-AutoTable** - Geração de arquivos PDF diretamente do lado do cliente.

---

## 🚀 Como Executar Localmente

Não requer instalação de ambientes complexos (Node.js, NPM, etc.).
1. Faça o clone ou o download deste repositório.
2. Dê um duplo clique no arquivo `index.html`.
3. A aplicação abrirá no seu navegador padrão. (Uma conexão com a internet é necessária apenas na primeira vez para baixar as bibliotecas do CDN para o cache local).

---

## 🔒 Privacidade
Como o código é executado estritamente do lado do cliente (Navegador), **nenhum dado sensível de projeto ou de engenharia sai do seu computador**. Toda a matemática acontece na memória RAM da sua própria máquina.

---

## 👨‍💻 Autor

**Desenvolvido por Lucas Ibiapino**
*Engenheiro de Redes*

📧 **Contato:** [lucasalves913@gmail.com](mailto:lucasalves913@gmail.com)
