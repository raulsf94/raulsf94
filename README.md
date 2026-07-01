# 👨🏻‍💻 Raul Ferreira

**Engenheiro de Dados**

Sou um amante de tecnologia desde cedo, que aproveitou a oportunidade para sair da área de sucesso do cliente e me apaixonar por dados.

Atualmente busco empoderar com dados as tomadas de decisão das áreas de negócio, centralizando informações das ferramentas usadas por todos os setores em um datalake. Isso otimiza e facilita o trabalho dos cientistas e analistas de dados na criação de dashboards que auxiliam os stakeholders.

Utilizo todo o processo de ETL para transformar dados brutos em dados tratados, prontos para uso na camada ouro, com ferramentas como **Apache Airflow**, **PySpark** e **Python**.

---

## 👤 Perfil

- **Nome:** Raul dos Santos Ferreira  
- **Data de nascimento:** 06 de janeiro, 1994  
- **Profissão:** Engenheiro de Dados, Analista de Dados  
- **Português:** Nativo  
- **Inglês:** Razoável

---

## 🛠️ Linguagens e Tecnologias

- **SQL**  
- **Python**  
- **Apache Spark**  
- **Apache Airflow**  
- **Google Cloud Platform (GCP)**  
- **AWS**  
- **Linux / Windows**

---

## 🚀 Skills

Níveis de proficiência com tecnologias:

| Tecnologia              | Nível       |
|-------------------------|-------------|
| Apache Airflow          | Muito bom   |
| Python                  | Muito bom   |
| Apache Spark            | Muito bom   |
| Google Cloud Platform   | Muito bom   |
| SQL                     | Muito bom   |
| AWS                     | Bom         |
| Scrum                   | Muito bom   |

---

## 💼 Experiências

### 🏢 Aurum Software Brasil
- **Cargo:** Analista de Dados Pleno  
- **Período:** 01/2024 – Atual  
- **Atividades:**  
  - Criação de DAGs para extração e transformação de dados (batch e streaming)
  - Ferramentas: Apache Airflow, Apache Spark, Python, GCP, BigQuery
  - Suporte à criação de dashboards (Power BI e Looker Studio)
  - Monitoramento e escalabilidade do ambiente GCP
  - Automação com Cloud Functions e Cloud Scheduler

### 🏢 Grupo Pão de Açúcar (via Orange Fox)
- **Cargo:** Engenheiro de Dados Pleno  
- **Período:** 02/2025 – Atual  
- **Atividades:**  
  - Execução e monitoramento de rotinas em GCP (Composer) e Teradata (mainframe IBM)
  - Garantia de SLA e migração do ambiente Teradata para GCP

### 🏢 Aurum Software Brasil
- **Cargo:** Analista de Negócios Pleno  
- **Período:** 01/2022 – 01/2024  
- **Atividades:**  
  - Gestão de demandas do time de tecnologia
  - Aplicação de metodologia Scrum (dailys, plannings)
  - Documentação e definição de SLA's
  - Roadmaps de melhoria e alinhamento com clientes

---

## 🎓 Formação Acadêmica

- **Curso:** Ciência da Computação  
- **Instituição:** Universidade Nove de Julho  
- **Conclusão:** 12/2015

---

## 🌟 Portfólio

Conheça meus principais projetos. Fique à vontade para explorar e me chamar caso queira conversar sobre algum deles!

---

### 📌 **Controle Financeiro Pessoal**

🔒 *Repositório privado — disponível mediante solicitação*

**Desafio:**  
Substituir uma planilha Excel complexa de controle financeiro pessoal por uma aplicação web interativa, mantendo toda a riqueza de informações (holerites, múltiplas datas de vencimento, deduções de salário) e adicionando funcionalidades novas.

**Solução implementada:**  
- Backend em **FastAPI** + **PostgreSQL**
- Frontend em **Vanilla JS** (single-file, sem frameworks)
- Importação automática da planilha via **openpyxl**
- **Fluxo de caixa por data de vencimento** com saldo acumulado

**Funcionalidades:**  
- Dashboard com próximos 6 meses, gráficos de evolução e previsão
- CRUD de despesas, receitas e dívidas com filtros, ordenação e busca
- Marcação de despesas como pagas com reflexo visual imediato
- Deduções de holerite (INSS, IRRF, planos de saúde/odonto/pet/creche) integradas à receita bruta do salário
- Datas de vencimento individuais por lançamento com alertas de proximidade (vermelho/amarelo)
- Quebra automática de lançamentos com múltiplas datas em registros independentes
- Fluxo de caixa agrupado por data de vencimento (5, 15, 23) com saldo acumulado do período

**Tecnologias:**  
`Python` `FastAPI` `PostgreSQL` `JavaScript` `Chart.js` `openpyxl`

---

### 📌 **Aurum Datapipeline**

**Desafio:**  
Desenvolver do zero um **Data Lake** que centralizasse os dados de todas as ferramentas da empresa, promovendo uma cultura data-driven.

**Solução implementada:**  
- Orquestração com **Apache Airflow**
- Transformação com **Apache Spark**
- Linguagem **Python**
- Infraestrutura **Google Cloud Platform**

**Objetivo:**  
Centralizar dados de CRM, CS, finanças, produtos e sistemas próprios. Criar uma arquitetura escalável e disponível para aumentar a performance na entrega de dados.

#### 🔧 Configuração do ambiente GCP
- Criação do projeto GCP e ativação das APIs:
  - Cloud Composer API
  - Cloud Storage API
  - Compute Engine API
  - Cloud SQL Admin API
- Criação dos buckets (raw, processing, curated) e estrutura do Composer
- Integração com GitHub para atualização automática via pull request (feita pela equipe de DevOps)

#### 🧩 Desenvolvimento da Pipeline
- **Hooks:** conexão com as APIs e webhooks
- **Operators:** criação dos diretórios e armazenamento no GCS
- **Transformations:** `transformation.py` (camada prata) e `resume.py` (camada ouro)
- **DAGs:** orquestração das etapas e carga no BigQuery

#### 🔌 Fontes de dados integradas

Captura e transformação de dados das seguintes plataformas:

- [Aha!](https://www.aha.io/)
- [Astrea](https://www.astrea.net.br/)
- [Beamer](https://www.getbeamer.com/)
- [Microsoft Ads](https://ads.microsoft.com/)
- [Circle](https://circle.so/)
- [Google Ads](https://ads.google.com/)
- [Intercom](https://www.intercom.com/)
- [LinkedIn Ads](https://business.linkedin.com/marketing-solutions/ads)
- [Meta Ads](https://www.facebook.com/business/ads)
- [Mixpanel](https://mixpanel.com/)
- [Pipedrive](https://www.pipedrive.com/)
- [Pipefy](https://www.pipefy.com/)
- [RD Station](https://www.rdstation.com/)
- [Sensedata](https://sensedata.com.br/)

Além disso, tratamos dados de sistemas internos como:
- Plataforma financeira interna
- Robôs e automações proprietárias

---

## 🤝 Entre em contato

Caso tenha dúvidas sobre algum dos projetos ou queira conversar sobre tecnologia e dados, estou à disposição!

---

## 📫 Contato

- 📧 **E-mail:** raul.engdados@gmail.com  
- 💼 **LinkedIn:** [Raul dos Santos Ferreira](https://www.linkedin.com/in/raul-santos-ferreira/)

---
