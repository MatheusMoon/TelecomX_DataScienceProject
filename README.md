# 📊 TelecomX - Análise de Churn  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![Status](https://img.shields.io/badge/Status-Concluído-success)

---

## 🎯 Propósito da Análise
O objetivo deste projeto é compreender **quais fatores influenciam o Churn** (cancelamento de serviço) em uma empresa de telecomunicações.  
A partir de um dataset contendo informações demográficas, de serviços contratados e dados de faturamento, aplicamos **análise exploratória** e **correlação de variáveis** para identificar padrões e possíveis causas de cancelamento.

---

## 📂 Estrutura do Projeto
- **`TelecomX_BR.ipynb`** → Notebook Jupyter com todo o fluxo de análise (extração, transformação, exploração e visualização de dados).
- **`TelecomX_Data.json`** → Base de dados dos clientes em formato JSON, com informações aninhadas.
- **`TelecomX_dicionario.md`** → Dicionário de dados descrevendo cada campo do dataset.

---

## 📊 Exemplos de Gráficos e Insights

### 1. Distribuição do Churn
Gráfico de barras mostrando a proporção de clientes que cancelaram versus os que permaneceram.  
**Insight:** A taxa de Churn é significativamente maior em clientes com contrato mensal.

### 2. Correlação entre variáveis e Churn
Mapa de calor de correlação.  
**Insight:** 
- Contratos de longo prazo estão associados a menor probabilidade de cancelamento.
- O pagamento via "Electronic check" apresenta maior índice de Churn.

### 3. Análise por tipo de serviço
Gráficos de barras comparando presença de serviços adicionais e Churn.  
**Insight:** Clientes sem serviços como **OnlineSecurity** ou **TechSupport** tendem a cancelar mais.

---

## 🛠 Instruções para Executar o Notebook

### Requisitos
- Python 3.8+
- Jupyter Notebook ou Google Colab
- Bibliotecas:  
  ```bash
  pip install pandas matplotlib seaborn requests
Passos
Clone ou baixe o repositório.

Abra o arquivo TelecomX_BR.ipynb no Jupyter Notebook ou Google Colab.

Execute as células na ordem, começando pelo carregamento dos dados.

Os gráficos e análises serão gerados ao longo da execução.

📌 Resumo:
Este projeto auxilia na identificação de fatores de risco para Churn, permitindo que a empresa desenvolva estratégias de retenção mais eficazes.

---
✍️ Autor: Matheus Cordeiro
📅 Data: 08/2025
