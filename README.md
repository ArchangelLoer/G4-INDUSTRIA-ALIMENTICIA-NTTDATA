# 📊 Projeto de Integração e Análise de Dados – Residência Porto Digital / NTT DATA / CESAR School

Este repositório contém toda a implementação do projeto desenvolvido pelo **Grupo 4 – Indústria Alimentícia**, durante a residência promovida pelo Porto Digital em parceria com a **NTT DATA** e a **CESAR School**.

Nosso objetivo foi construir uma solução de engenharia de dados capaz de **integrar, tratar, padronizar e analisar** três bases principais:

* **Produtos**
* **Estoque**
* **Vendas**

A solução foi estruturada seguindo o padrão da **Arquitetura Medalhão** (Bronze, Silver e Gold), garantindo rastreabilidade, consistência e clareza entre as etapas do pipeline.

---

## 🏭 Contexto do Projeto

A indústria alimentícia é um dos pilares da economia brasileira, representando **10,8% do PIB**, mais de **2 milhões de empregos formais**, e liderança mundial em exportação de alimentos industrializados.

Com isso em mente, o projeto buscou **identificar gargalos operacionais**, **reduzir desperdícios** e **gerar insights estratégicos** utilizando dados reais simulados.

---

## 🧱 Arquitetura Medalhão

A solução foi estruturada da seguinte forma:

### 🥉 Bronze — Ingestão de Dados

* Leitura direta dos arquivos brutos
* Padronização inicial
* Verificação de integridade
* Armazenamento sem transformação semântica

### 🥈 Silver — Tratamento e Padronização

* Limpeza de inconsistências
* Normalização dos campos
* Preparação para cruzamentos
* Estruturação de tabelas confiáveis

### 🥇 Gold — Regras de Negócio e Indicadores

* Cruzamento entre Estoque × Produtos × Vendas
* Cálculo de KPIs como:

  * Ranking de vendas
  * Margens
  * Necessidade de reposição
  * Distribuição de faturamento
* Base final pronta para consumo analítico

### 📊 Dashboards — Visualização Estratégica

* Painéis para acompanhamento de vendas e estoque
* Gráficos gerenciais com foco em tomada de decisão

---

## 🗂️ Estrutura do Repositório

``
📁 raiz/
 ├── bronze/
 ├── silver/
 ├── gold/
 ├── dashboards/   # <- espaço reservado para inserir os gráficos
 └── README.md
 ``

---

## ⚙️ Tecnologias Utilizadas

* **Python** (Pandas, PySpark)
* **SQL**
* **Databricks** (ingestão, processamento e versionamento de notebooks)
* **Git e GitHub** para versionamento

---

## 🧪 Funcionalidades Implementadas

### ✔️ Ingestão Automatizada de Arquivos

Leitura dos três datasets principais com manutenção da estrutura original.

### ✔️ Tratamento e Padronização

Correção de colunas, remoção de anomalias e padronização das bases.

### ✔️ Geração de Indicadores

Cálculo de métricas essenciais para o setor alimentício.

### ✔️ Base Pronta para Dashboards

Entrega da camada Gold integrada com dados tratados e relacionáveis.

---


## 👥 Equipe – Quem Fez o Quê

* **Enzo Amorim** – Ingestão e Tratamento (Bronze & Silver)
* **Arthur Ferreira** – Regras de Negócio e Agregação (Gold)
* **Andrews Queiroz** – Dashboards e Análise
* **Gustavo Veloso** – Dashboards e Visualização
* **Pedro Henrique** – Dashboards e Visualização
