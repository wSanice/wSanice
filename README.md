# Hi there, I'm Sanice 🖖🏽
![2nd arrow](https://github.com/Nagakburos/Nagakburos/assets/103370604/ef04fd97-07d5-47f8-9676-624997ef3094)
 
### Estudante de Data Science | Desenvolvedor Python | Univesp

Sou um estudante de Ciência de Dados apaixonado por transformar dados em soluções práticas. Combinando meu background em suporte de TI com desenvolvimento Python, estou focado em criar modelos de Machine Learning robustos e ferramentas que automatizam processos de dados, resolvendo problemas de forma criativa e definitiva.

<div style="display:inline_block">
  <a href="https://www.linkedin.com/in/wantruil-sanice/?locale=en_US" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://annyia.com" target="_blank">
    <img src="https://img.shields.io/badge/Website-FF5722?style=for-the-badge&logo=html5&logoColor=white" alt="Website"/>
  </a>
</div>

---

## Projetos em Destaque (Data Science & ML)

### Bibliotecas & Ferramentas
- **[Leblanc](https://github.com/wSanice/leblanc)**
  > *Synthetic Data Generator for Business Contexts*
  > Biblioteca Python open-source disponível no **PyPI** (`pip install leblanc`), desenvolvida para agilizar a etapa de coleta de dados em projetos.
  > * **Propósito:** Elimina o boilerplate de criar geradores manuais com `Faker`, entregando datasets estruturados e coerentes para contextos de negócio (Varejo, Agro, Finanças).
  > * **Tech:** Abstração de alto nível construída sobre **Pandas** e **NumPy** para performance na geração de grandes volumes de dados.
- **[Sanice](https://github.com/wSanice/sanice)**
  > *Fluent Python Wrapper for Data Science Acceleration*
  > Toolkit disponível no **PyPI** (`pip install sanice`), projetado para acelerar o fluxo de trabalho de ponta a ponta (ETL ➡️ AutoML ➡️ Deploy).
  > * **Propósito:** Abstrai a complexidade do **Pandas**, **Scikit-Learn** e **FastAPI** em uma interface fluente (*Method Chaining*). Permite limpar dados, treinar modelos e subir APIs em minutos, focando na lógica de negócio em vez da sintaxe.
  > * **Diferencial:** Arquitetura encapsulada com suporte nativo a comandos multilíngues (PT, EN, ZH, HI) e CLI integrada para verificação rápida (`sanice ajuda | sanice `).
  
- **[Generative-Catalog-Engine](https://github.com/wSanice/Generative-Catalog-Engine)**
  > *NLP-Driven Product Generation & Automation*
  > Projeto nascido da exploração avançada de **GenAI** e **NLP**. Trata-se de uma engine capaz de "criar" produtos estruturados a partir de inputs de linguagem natural.
  > * **Discovery:** Durante estudos sobre automação de dados, desenvolvi este pipeline que replica o conceito de **Generative Commerce**, permitindo a criação de catálogos *just-in-time*.
  > * **Tech:** Orquestração de LLMs com **Python**, focado na conversão de *prompts* semânticos em objetos **JSON** validados para integração com backends de e-commerce.
  
### Machine Learning & Visão Computacional
- **[Plant-AI](https://github.com/wSanice/Plant-AI)** (Em desenvolvimento)
  > *Diagnóstico de Doenças em Plantas*
  > Projeto de Visão Computacional utilizando Deep Learning para identificar doenças em plantas através de imagens. O modelo atingiu uma acurácia superior a **90%**, visando auxiliar na agricultura de precisão.

- **[CSIRO Biomass Prediction (Deep Learning)](https://github.com/wSanice/Biomass_Prediction_multi-imput)**
  > *Computer Vision & Transfer Learning Strategy*
  > Pipeline completo de Deep Learning para prever biomassa a partir de imagens aéreas (Kaggle), atingindo score competitivo (0.40):
  > * **Data Engineering:** Transformação de dados complexos ("long-to-wide") utilizando **Pandas** para estruturar o dataset de treino.
  > * **Modeling:** Arquitetura **TensorFlow/Keras** baseada na **EfficientNetB0**. Implementação de estratégia de **Transfer Learning** em duas fases (Feature Extraction + Fine-Tuning progressivo) para evitar overfitting.
  > * **Deployment:** Protótipo em **Streamlit** demonstrando o conceito "Multi-Input" (processamento simultâneo de Imagem + Metadados como NDVI).
- **[Análise de E-commerce (Python)](https://github.com/wSanice/ecommerce-analysis)**
  > *Data Analytics & Business Intelligence*
  > Estudo de caso focado em transformar dados brutos de transações em estratégia de negócio para escalabilidade.
  > * **Data Engineering:** Geração de dataset sintético complexo com o módulo *Leblanc* e processamento de dados com **Pandas**.
  > * **EDA & Visualization:** Análise exploratória profunda com **Matplotlib** e **Seaborn** para identificar tendências de sazonalidade e curva ABC de produtos.
  > * **Business Value:** Mapeamento de oportunidades de expansão logística (PR/CE) e otimização de estoque de alto giro, consolidado em um relatório executivo (Storytelling).
- **[Universal Churn Prediction Pipeline](https://www.kaggle.com/code/nagakaburos/churn-prediction-wsanice?scriptVersionId=281502326)**
  > *Automated ML Pipeline & Business Analytics*
  > Sistema inteligente de previsão de cancelamento (Churn) capaz de operar com dados reais e sintéticos (Gerados via leblanc).
  > * **Modeling:** Treinamento automatizado de modelos **Random Forest** para identificar padrões de comportamento de risco.
  > * **Smart Pipeline:** Algoritmo que detecta automaticamente a estrutura do dataset de entrada e adapta o pré-processamento (ETL).
  > * **Business Value:** Entrega não apenas a previsão (0/1), mas um diagnóstico visual dos produtos e fatores financeiros que mais causam prejuízo.
- **[Adaptive Image Classification (IALM)](https://github.com/wSanice/Adaptive-Image-Classification-IALM)**
  > *Imbalanced Adversarial Learning*
  > Estudo focado em classificação de imagens utilizando TensorFlow e Keras. O diferencial deste projeto é o tratamento de **datasets desbalanceados** usando técnicas de aprendizado adversarial (IALM), melhorando a performance do modelo em classes minoritárias.

### Engenharia de Dados & Analytics
- **[ETL Vendas Varejo & Dashboard](https://github.com/wSanice/etl_vendas_varejo_olist_sheets)**
  > *Automated Data Pipeline (Python ➡️ Google Sheets)*
  > Solução de Business Intelligence completa (End-to-End) baseada no dataset Olist:
  > * **Back-end (ETL):** Script Python que extrai e processa dados brutos usando **Pandas**. A automação carrega os dados tratados diretamente na nuvem via **Google Sheets API (gspread)**.
  > * **Front-end (Analytics):** Dashboard interativo construído com funções avançadas (`QUERY`, `SUMIFS`) para monitoramento de KPIs (Faturamento, Ticket Médio) com filtros dinâmicos.
  > [🔗 Ver Dashboard ao Vivo](https://docs.google.com/spreadsheets/d/1...seu_link_aqui...)

- **[QuemCarrega.lol](https://quemcarrega.lol/)**
  > *League of Legends Meta Analyzer & Dashboard*
  > Aplicação web Data-Driven (SPA) desenvolvida para análise de Win Rate e Pick Rate de campeões. O projeto integra todo o ciclo de dados:
  > * **ETL & Ingestion:** Web Scraping e Engenharia Reversa de APIs (`requests`) para extração de dados em tempo real, contornando a ausência de endpoints públicos agregados.
  > * **Processing:** Limpeza e agregação complexa de JSONs aninhados utilizando Pandas. Integração com Riot Games Data Dragon para versionamento.
  > * **Frontend:** Dashboard interativo construído com **Streamlit**.
  > * **Infra:** Deploy containerizado na **Railway** com **Cloudflare** (CDN/SSL).
---

## Technologies & Tools

### 🔹 Programming Languages
<div style="display:inline_block"><br/>
  <img align="center" alt="python" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"/>
  <img align="center" alt="SQL" src="https://img.shields.io/badge/SQL-0078D4?style=for-the-badge&logo=sql&logoColor=white"/>
</div>

### 🔹 Data Science & Machine Learning Libraries
<div style="display:inline_block"><br/>
  <img align="center" alt="numpy" src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img align="center" alt="pandas" src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img align="center" alt="scikit-learn" src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img align="center" alt="tensorflow" src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img align="center" alt="opencv" src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
</div>

### 🔹 Data Visualization & Analysis
<div style="display:inline_block"><br/>
  <img align="center" alt="powerbi" src="https://img.shields.io/badge/Power%20BI-ED8B00?style=for-the-badge&logo=powerbi&logoColor=white"/>
  <img align="center" alt="matplotlib" src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white"/>
</div>

---

## Tools & Platforms

### 🔹 Cloud & Virtual Machines
<div style="display:inline_block"><br/>
  <img align="center" alt="aws" src="https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img align="center" alt="google-cloud" src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white"/>
  <img align="center" alt="azure" src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=azure&logoColor=white"/>
</div>

### 🔹 Databases
<div style="display:inline_block"><br/>
  <img align="center" alt="mysql" src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img align="center" alt="postgresql" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img align="center" alt="mongodb" src="https://img.shields.io/badge/MongoDB-4DB33D?style=for-the-badge&logo=mongodb&logoColor=white"/>
</div>

### 🔹 Development Environments
<div style="display:inline_block"><br/>
  <img align="center" alt="jupyter" src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img align="center" alt="colab" src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"/>
  <img align="center" alt="kaggle" src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white"/>
  <img align="center" alt="pycharm" src="https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white"/>
  <img align="center" alt="vs-code" src="https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
</div>

---

## Operating Systems & Environment

<div style="display:inline_block"><br/>
  <img align="center" alt="ubuntu" src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>
  <img align="center" alt="windows" src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"/>
</div>

---

## Interests
- **Full-Cycle Data Science**: Interesse em atuar em todas as etapas do fluxo de dados: desde a **Criação de ETLs** e **Análise Exploratória** até o **Treinamento** e **Fine-tuning** de modelos complexos.
- **AI Research**: Exploração de últimas tendências em IA, especialmente Reinforcement Learning e Generative Models.
- **Data Engineering**: Foco em criar pipelines eficientes e bibliotecas personalizadas para facilitar o fluxo de trabalho de dados.
- **Web Development**: Aplicação de conhecimentos de Data Science em projetos Web, como o [uuno.me](https://uuno.me/) e o [quemcarrega.lol](https://quemcarrega.lol/).

---
<p align="center">
  <i>"Blind faith is the tool of monsters and fools. Analyze the data."</i>
</p>
