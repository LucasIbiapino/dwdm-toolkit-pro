# 🌐 DWDM Toolkit Pro

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)

O **DWDM Toolkit Pro** é uma ferramenta "Canivete Suíço" interativa e totalmente offline, desenvolvida para engenheiros de telecomunicações, analistas de rede e técnicos de campo. A ferramenta centraliza os cálculos mais complexos de redes ópticas DWDM (Dense Wavelength Division Multiplexing) numa única interface rápida e intuitiva.

🔗 **[Aceder à Ferramenta Online](https://lucasibiapino.github.io/dwdm-toolkit-pro/)**
---

## ✨ Funcionalidades Principais

A ferramenta está desenhada num formato modular (separadores), sendo que cada módulo contém um **Dicionário de Conceitos** e as **Fórmulas Matemáticas** visíveis em tempo real.

* **📉 Atenuação:** Cálculo de perdas de enlace (km, emendas, passivos).
* **⚡ Potência:** Desdobramento de Potência Total vs. Potência por Canal com alertas dinâmicos de limites não-lineares (SPM, SBS).
* **🎛️ Ganho de Amplificadores:** Cálculos de Pin, Pout e Ganho de EDFAs.
* **📶 OSNR:** Previsão de Relação Sinal-Ruído para *spans* únicos ou em cascata (EDFA e Raman).
* **📻 Espectro:** Calculadora de Grid ITU-T (100GHz) e medição de Tilt Espectral.
* **🌊 Dispersão:** Avaliação de tolerâncias a Dispersão Cromática (CD) e Dispersão de Modo de Polarização (PMD).
* **🛡️ QoT (Qualidade de Transmissão):** Orçamento Óptico (Link Budget), verificação de ORL e análise de limites FEC.
* **👁️ Fator Q e BER:** Conversor bidirecional avançado utilizando aproximação gaussiana para estimar a Pre-FEC BER a partir do Fator Q.
* **🚀 Modulação Coerente:** Simulador de Baud Rate, Largura de Banda Óptica e análise de viabilidade de formatos (QPSK, 16QAM, 64QAM).
* **⏱️ SLA e Latência:** Cálculo de RTT físico do vidro e estimativa de "Noves" (Disponibilidade Anual e Apurada a 7, 15 ou 30 dias).
* **🔄 Conversor:** Transformação instantânea e bidirecional de dBm ↔ mW.

---

## 🖨️ Geração de Relatórios

O sistema possui uma função integrada nativa para compilar todas as métricas inseridas e gerar memórias descritivas. Sem recurso a qualquer servidor (100% Client-Side):
* **Exportação para PDF:** Relatório de engenharia devidamente formatado para documentação *As-Built*.
* **Exportação para CSV:** Ficheiro de dados para importação e tratamento massivo em Excel/Scripts.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído focando-se na **portabilidade máxima**. É composto por um único ficheiro (`index.html`), o que significa que pode ser guardado numa pen drive ou enviado por e-mail e correrá nativamente em qualquer browser.

As tecnologias importadas via CDN incluem:
* **Vue.js 3** - Para a reatividade instantânea dos cálculos sem recarregar a página.
* **Tailwind CSS** - Para a interface moderna, limpa e responsiva (Mobile-first).
* **FontAwesome 6** - Iconografia gráfica vetorial.
* **jsPDF & jsPDF-AutoTable** - Geração de ficheiros PDF diretamente do lado do cliente.

---

## 🚀 Como Executar Localmente

Não requer instalação de ambientes complexos (Node.js, NPM, etc.).
1. Faça o clone ou o download deste repositório.
2. Dê um duplo clique no ficheiro `index.html`.
3. A aplicação abrirá no seu browser predefinido. (Uma ligação à internet é necessária apenas na primeira abertura para descarregar as bibliotecas do CDN para a cache local).

---

## 🔒 Privacidade
Como o código é executado estritamente do lado do cliente (Browser), **nenhum dado sensível de projeto ou de engenharia sai do seu computador**. Toda a matemática acontece na memória RAM da sua máquina.

---

## 👨‍💻 Autor

**Desenvolvido por Lucas Ibiapino**
*Engenheiro de Redes*

📧 **Contacto:** [lucasalves913@gmail.com](mailto:lucasalves913@gmail.com)
