# 📊 Análise Estratégica de Criptoativos

## 📖 Sobre o Projeto

Este repositório contém um projeto de **Business Intelligence** focado na **análise de transações de criptoativos**.
O objetivo é transformar um grande volume de dados brutos em **insights estratégicos** por meio de um **dashboard interativo**.

A análise permite identificar:

* Tendências de mercado
* Comportamentos de negociação
* Níveis de risco
* Oportunidades de crescimento para diferentes criptomoedas

> 🎯 **Acesse o Dashboard Interativo:**
> 🔗 [Clique aqui para visualizar no Power BI](https://app.powerbi.com/view?r=eyJrIjoiY2FmNjJiNzYtOTMzNS00OTM0LWI3ODUtYmQ5OGRkMjFmN2U0IiwidCI6IjVlMGYyMmRkLWEyNmYtNDVhZi04NTBiLTZhNTRkMzE2NmUxMCJ9)

---

### 👨‍💻 Desenvolvido por

**Marcos Oliveira**

* 🔗 [LinkedIn](https://www.linkedin.com/in/marcos-oliveira-77410424a/)
* 💻 [GitHub](https://github.com/MarcosOliveira16)

---

## 🚀 Funcionalidades do Dashboard

O dashboard centraliza diversas análises visuais para **apoiar a tomada de decisão**.

### 📌 Principais Análises

#### 📈 Visão Geral do Mercado

Apresenta **indicadores-chave de desempenho (KPIs)** sobre o volume total transacionado e o número de operações, oferecendo um panorama completo do mercado.

* **Valor Total Transacionado (Geral):** \$649,148 Trilhões
* **Número Total de Operações (Geral):** 1,49 Bilhão

#### 📆 Evolução Temporal

Gráfico de linhas que demonstra a **Evolução Mensal do Valor Total Transacionado**, permitindo a identificação de **picos, vales e tendências sazonais** (Ago/2019 a Jul/2023).

#### ⚠️ Alerta de Transações Atípicas

Tabela de alertas que **sinaliza automaticamente criptoativos com comportamento atípico**, como **BTC** e **BUSD** nos primeiros meses de 2021.

#### 🧩 Segmentação por Perfil de Negociação

Gráfico de dispersão com **clusterização** de criptoativos com base no valor médio e no volume de operações.

* **Clusters Identificados:**

  * Gigantes
  * Populares
  * De Nicho
  * Alto Valor

#### 🔐 Análise de Risco por Modalidade

Gráfico de barras com a **pontuação de risco** associada às diferentes modalidades de transação.

* **Modalidades Analisadas:**

  * Via Exchange no Exterior
  * Peer-to-Peer (P2P)
  * Via Exchange Nacional

#### 📊 Matriz Estratégica (Crescimento vs. Liquidez)

Inspirada na **matriz BCG**, classifica os criptoativos em quadrantes estratégicos:

* **Estrelas (Focar):** Alto crescimento e alta liquidez
* **Promessas (Observar):** Alto crescimento e baixa liquidez
* **Estáveis (Manter):** Baixo crescimento e alta liquidez
* **Dilemas (Reavaliar):** Baixo crescimento e baixa liquidez

---

## 🛠️ Ferramentas Utilizadas

* **Microsoft Power BI** (com uso de DAX para cálculos estratégicos)
* **Google Colab** (para pré-processamento e tratamento dos dados)
* **Big Data:** Conjunto de dados massivo com registros de operações de criptoativos

---

## 📂 Fonte dos Dados

Os dados utilizados neste projeto foram obtidos no Kaggle:
🔗 [Criptoativos - Dados Abertos da Receita Federal (2023)](https://www.kaggle.com/datasets/thamiresfalbo/criptoativos-dados-abertos-receita-federal-2023)

---

## 🗂️ Fonte de Dados e Preparação

A base de dados original para este projeto era um único repositório de informações.
Para otimizar o processo de tratamento e carregamento no Power BI, os dados foram **segmentados e limpos** utilizando o **Google Colab**, resultando nos seguintes arquivos `.csv`.
Esse processo envolveu a **remoção de textos desnecessários** e a **estruturação das informações em formato puramente tabular**.

### 📁 Arquivos de Dados

#### **dados\_relatorio1.csv a dados\_relatorio4.csv**

Contêm os **dados transacionais brutos**, base para os seguintes indicadores:

* Valor Total Transacionado
* Número Total de Operações
* Evolução Mensal
* Alertas de Transações Atípicas

#### **dados\_perfil\_cripto.csv**

Métricas agregadas com:

* Valor médio por operação
* Total de operações por criptoativo
  Utilizado para o gráfico de **Segmentação de Criptoativos por Perfil de Negociação**.

#### **dados\_risco\_modalidade.csv**

Pontuação de risco consolidada por modalidade de transação.
Utilizado para o gráfico de **Nível de Risco por Modalidade de Transação**.

#### **dados\_estrategicos.csv**

Pontuações de crescimento e liquidez por criptoativo.
Base para a **Matriz Estratégica: Crescimento vs. Liquidez**.

---

## 📄 Licença

Este projeto é licenciado sob a **MIT License**.
Ela permite uso, modificação e distribuição, desde que o devido crédito seja mantido.
