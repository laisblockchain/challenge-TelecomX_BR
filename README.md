# 📊 Telecom X — Análise de Evasão de Clientes (Churn)

## 📌 Descrição do Projeto

Este projeto tem como objetivo analisar os fatores que influenciam a evasão de clientes (churn) na empresa Telecom X. A análise foi realizada utilizando Python e bibliotecas de análise de dados para identificar padrões que possam explicar por que alguns clientes cancelam seus serviços.

A partir da análise exploratória dos dados, foram identificadas variáveis importantes associadas ao churn, como tipo de contrato, método de pagamento, tempo de permanência do cliente e valor das cobranças.

Este projeto faz parte do programa **Oracle Next Education (ONE)** em parceria com a **Alura**, no curso de **Data Science**.

---

# 🎯 Objetivos

- Compreender o comportamento dos clientes da Telecom X
- Identificar fatores associados à evasão de clientes
- Explorar padrões nos dados através de análise exploratória
- Gerar insights que possam auxiliar na retenção de clientes
- Preparar os dados para possíveis modelos preditivos de churn

---


---

# ⚙️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

# 🔄 Etapas do Projeto

O projeto foi desenvolvido seguindo o processo **ETL (Extract, Transform, Load)**.

## 1️⃣ Extração de Dados
- Importação do dataset em formato JSON
- Carregamento dos dados utilizando Pandas

## 2️⃣ Transformação de Dados
- Normalização da estrutura do JSON
- Tratamento de valores ausentes
- Padronização de variáveis
- Conversão de tipos de dados

## 3️⃣ Análise Exploratória de Dados (EDA)

Foram realizadas análises para entender o comportamento dos clientes:

- Distribuição da variável **churn**
- Relação entre churn e **variáveis categóricas**
- Relação entre churn e **variáveis numéricas**
- Análise de **correlação entre variáveis**

---

# 📊 Principais Insights

A análise revelou alguns fatores importantes associados ao churn:

- Clientes com **contrato mensal** apresentam maior taxa de cancelamento
- Clientes com **menor tempo de permanência** têm maior probabilidade de churn
- **Cobranças mensais mais altas** estão associadas a maior evasão
- Alguns **métodos de pagamento** apresentam maior incidência de churn
- Clientes com mais serviços contratados tendem a permanecer por mais tempo

Esses insights podem ajudar a empresa a desenvolver estratégias de retenção de clientes.

---

# 🚀 Como Executar o Projeto

1. Clone este repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
