# FABRICIO SOARES MENEZES · Portfólio de Dados

**Analista de Dados · Análise & Engenharia de Dados**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat&logo=googledatastudio&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Navegação:** [🇧🇷 Português](#-português) · [🇬🇧 English](#-english)

---

## 🇧🇷 Português

Bem-vindo ao meu portfólio! Reúno aqui projetos pessoais de análise e engenharia de dados, com foco em transformar dados em decisões: modelagem, qualidade de dados, automação e visualização.

### Projetos

#### 1. [raw_ecommerce — Analytics Engineering com dbt + BigQuery](https://github.com/fsemeneze/raw_ecommerce)

Pipeline completo de analytics engineering sobre o dataset público [Olist Brazilian E-commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), com cerca de 1 milhão de registros de pedidos, pagamentos, avaliações e geolocalização.

- **Arquitetura em camadas:** staging (8 views) → marts (**star schema** com surrogate keys MD5) → camada BI desnormalizada para consumo;
- **Qualidade de dados:** 40 testes automatizados com `dbt test` (unique, not_null, accepted_values, relationships) — todos passando;
- **Modelagem dimensional:** 4 dimensões e 3 fatos, com métricas como atraso de entrega, horas de aprovação e nota média de avaliação;
- **Macros Jinja customizadas:** pivot de pagamentos, classificação de performance de entrega, geração de schemas;
- **Dashboard no Looker Studio** conectado às views da camada BI: KPIs de produtos e pedidos em 2 páginas.

🔗 [Repositório](https://github.com/fsemeneze/raw_ecommerce) · [Dashboard no Looker Studio](https://datastudio.google.com/s/rWYfmpwVLJk)

**Stack:** dbt Core · Google BigQuery · SQL (dialeto BigQuery) · Jinja · Looker Studio

#### 2. [Washington sobre duas rodas — Aluguel de bicicletas (Power BI)](https://app.powerbi.com/view?r=eyJrIjoiZWUzZmEyODItZjRiOS00NjAzLTkwZGYtNTY0ZTgwODdkYjljIiwidCI6IjFlMWM5MzI3LWZhOTUtNDJjNS1hMGFkLWExNGE1ODMwOTMzMCJ9)

Análise da influência das estações do ano no aluguel de bicicletas compartilhadas em Washington, em relatório Power BI publicado com 3 páginas.

- **2,09 milhões de aluguéis** analisados, segmentados entre mensalistas (1,69 mi) e avulsos (392 mil);
- **Sazonalidade clara:** verão concentra 31% dos aluguéis; inverno cai para 15%;
- Padrões mensais de demanda por tipo de cliente, para apoiar decisões de frota e operação.

🔗 [Relatório interativo no Power BI](https://app.powerbi.com/view?r=eyJrIjoiZWUzZmEyODItZjRiOS00NjAzLTkwZGYtNTY0ZTgwODdkYjljIiwidCI6IjFlMWM5MzI3LWZhOTUtNDJjNS1hMGFkLWExNGE1ODMwOTMzMCJ9)

**Stack:** Power BI · DAX · Power Query

#### 3. [Análise de clientes inadimplentes (Python)](https://github.com/fsemeneze/Analise-de-clientes-inadimplentes)

Análise exploratória de dados de crédito de uma instituição financeira, com foco na variável `default` (adimplente × inadimplente).

- Investigação da relação entre inadimplência e atributos como salário, escolaridade e movimentação financeira;
- Tratamento e limpeza de dados, análise exploratória com visualizações e comunicação de resultados;
- Insights acionáveis para gestão de risco e redução da inadimplência.

🔗 [Repositório (notebook completo)](https://github.com/fsemeneze/Analise-de-clientes-inadimplentes)

**Stack:** Python · Pandas · Seaborn/Matplotlib · Jupyter

### Experiência aplicada (resumo profissional)

Na indústria de saúde domiciliar, atuo como Analista de Dados construindo soluções de ponta a ponta: pipelines de ETL orquestrados com LangGraph e IA generativa, API REST em FastAPI, RPA com validação de dados 1:1 entre sistemas, dashboards estratégicos em Power BI e automações que reduziram tempos de processamento de 6 horas para 15 minutos. Detalhes confidenciais sob acordo — arquitetura e resultados disponíveis em entrevista.

### Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-fabriciosmz-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fabriciosmz/)
[![GitHub](https://img.shields.io/badge/GitHub-fsemeneze-181717?style=flat&logo=github&logoColor=white)](https://github.com/fsemeneze)
[![E-mail](https://img.shields.io/badge/E--mail-fmenezes722@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:fmenezes722@gmail.com)

---

## 🇬🇧 English

Welcome to my portfolio! This is where I showcase personal data analysis and data engineering projects, focused on turning data into decisions: modeling, data quality, automation and visualization.

### Projects

#### 1. [raw_ecommerce — Analytics Engineering with dbt + BigQuery](https://github.com/fsemeneze/raw_ecommerce)

A complete analytics engineering pipeline built on the public [Olist Brazilian E-commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) dataset, with roughly 1 million records of orders, payments, reviews and geolocation.

- **Layered architecture:** staging (8 views) → marts (**star schema** with MD5 surrogate keys) → denormalized BI layer for direct consumption;
- **Data quality:** 40 automated tests via `dbt test` (unique, not_null, accepted_values, relationships) — all passing;
- **Dimensional modeling:** 4 dimensions and 3 fact tables, with metrics such as delivery delay, approval hours and average review score;
- **Custom Jinja macros:** payment pivoting, delivery performance classification, schema name generation;
- **Looker Studio dashboard** connected to the BI layer views: product and order KPIs across 2 pages.

🔗 [Repository](https://github.com/fsemeneze/raw_ecommerce) · [Looker Studio Dashboard](https://datastudio.google.com/s/rWYfmpwVLJk)

**Stack:** dbt Core · Google BigQuery · SQL (BigQuery dialect) · Jinja · Looker Studio

#### 2. [Washington on two wheels — Bike sharing (Power BI)](https://app.powerbi.com/view?r=eyJrIjoiZWUzZmEyODItZjRiOS00NjAzLTkwZGYtNTY0ZTgwODdkYjljIiwidCI6IjFlMWM5MzI3LWZhOTUtNDJjNS1hMGFkLWExNGE1ODMwOTMzMCJ9)

Analysis of how seasons influence shared bike rentals in Washington, published as a 3-page Power BI report.

- **2.09 million rentals** analyzed, segmented between members (1.69M) and casual riders (392k);
- **Clear seasonality:** summer accounts for 31% of rentals; winter drops to 15%;
- Monthly demand patterns per customer type to support fleet and operations decisions.

🔗 [Interactive Power BI report](https://app.powerbi.com/view?r=eyJrIjoiZWUzZmEyODItZjRiOS00NjAzLTkwZGYtNTY0ZTgwODdkYjljIiwidCI6IjFlMWM5MzI3LWZhOTUtNDJjNS1hMGFkLWExNGE1ODMwOTMzMCJ9)

**Stack:** Power BI · DAX · Power Query

#### 3. [Defaulting customers analysis (Python)](https://github.com/fsemeneze/Analise-de-clientes-inadimplentes)

Exploratory data analysis on credit data from a financial institution, focused on the `default` variable (paying × defaulting customers).

- Investigation of the relationship between default and attributes such as salary, schooling and financial activity;
- Data cleaning, exploratory analysis with visualizations and communication of results;
- Actionable insights for risk management and default reduction.

🔗 [Repository (full notebook)](https://github.com/fsemeneze/Analise-de-clientes-inadimplentes)

**Stack:** Python · Pandas · Seaborn/Matplotlib · Jupyter

### Applied experience (professional summary)

In the home healthcare industry, I work as a Data Analyst building end-to-end solutions: ETL pipelines orchestrated with LangGraph and generative AI, REST APIs with FastAPI, RPA with 1:1 data validation across systems, strategic Power BI dashboards, and automations that cut data refresh times from 6 hours to 15 minutes. Details are confidential under NDA — architecture and results available upon interview.

### Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-fabriciosmz-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fabriciosmz/)
[![GitHub](https://img.shields.io/badge/GitHub-fsemeneze-181717?style=flat&logo=github&logoColor=white)](https://github.com/fsemeneze)
[![E-mail](https://img.shields.io/badge/E--mail-fmenezes722@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:fmenezes722@gmail.com)
