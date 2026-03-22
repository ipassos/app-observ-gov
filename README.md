# 🏛️ Observatório de Apps Governamentais [Espelho / Mirror]

[![Acesso ao Dashboard](https://img.shields.io/badge/Acessar_Dashboard-ShinyApps.io-blue?style=for-the-badge)](https://ipassos.shinyapps.io/app-observ-gov/)

*(Scroll down for the English version)*

Bem-vindo! Este é um repositório espelho. O **Observatório de Apps Governamentais** é um painel analítico interativo que monitora a percepção cidadã sobre a digitalização dos serviços públicos no Brasil. Este projeto é fruto do Trabalho de Conclusão de Curso (TCC) do MBA em Data Science e Analytics da ESALQ/USP.

## 🛠️ Engenharia de Dados e Big Data
Para viabilizar a análise de Processamento de Linguagem Natural (NLP) em larga escala em um ambiente com severas restrições de memória (Servidor com 1 GB de RAM), o projeto empregou:
* **Armazenamento Colunar (Apache Parquet):** compressão extrema dos dados extraídos via scraping (`google-play-scraper`).
* **Consultas Lazy In-Memory (Apache Arrow):** o painel em R (Shiny) filtra milhões de linhas diretamente no disco rígido do servidor, extraindo para a RAM apenas resumos cirúrgicos (< 15MB) no exato momento da renderização.
* **NLP em Batch:** processamento multilingue prévio utilizando a arquitetura Transformer (`cardiffnlp/twitter-xlm-roberta-base-sentiment` via Hugging Face) para evitar sobrecarga na interface visual em tempo real.

## 🚀 Código Fonte e Soberania Digital

Em defesa da soberania digital, das infraestruturas tecnológicas autônomas e do ecossistema de software livre, **o desenvolvimento principal e o código fonte completo deste projeto estão hospedados exclusivamente no Codeberg.**

🔗 **[CLIQUE AQUI PARA ACESSAR O REPOSITÓRIO OFICIAL NO CODEBERG](https://codeberg.org/ipassos/app-observ-gov.git)**

---

<br>

# 🏛️ Government Apps Observatory [Mirror]

[![Dashboard Access](https://img.shields.io/badge/Acessar_Dashboard-ShinyApps.io-blue?style=for-the-badge)](https://ipassos.shinyapps.io/app-observ-gov/)

Welcome! This is a mirror repository. The **Government Apps Observatory** is an interactive analytical dashboard that monitors citizen perception regarding the digitalization of public services in Brazil. This project is the final thesis for the MBA in Data Science and Analytics at ESALQ/USP.

## 🛠️ Data Engineering & Big Data
To enable large-scale Natural Language Processing (NLP) analysis in an environment with severe memory constraints (1 GB RAM server), the project utilized:
* **Columnar storage (Apache Parquet):** extreme compression of data extracted via scraping (`google-play-scraper`).
* **Lazy in-memory queries (Apache Arrow):** the R (Shiny) dashboard filters millions of rows directly on the server's hard drive, extracting to RAM only surgical summaries (< 15MB) at the exact moment of rendering.
* **Batch NLP:** prior multilingual processing using Transformer architecture (`cardiffnlp/twitter-xlm-roberta-base-sentiment` via Hugging Face) to prevent real-time visual interface overload.

## 🚀 Source code & digital sovereignty

In defense of digital sovereignty, autonomous technological infrastructures, and the free software ecosystem, **the main development and the complete source code of this project are hosted exclusively on Codeberg.**

🔗 **[CLICK HERE TO ACCESS THE OFFICIAL REPOSITORY ON CODEBERG](https://codeberg.org/ipassos/app-observ-gov.git)**

---

**Iara Passos** - sociologist, final-year Statistics undergraduate, and Data Engineer.