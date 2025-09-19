# Produção de Gás Natural no Brasil (1997–2025) – ANP

Este projeto analisa a produção de gás natural no Brasil entre 1997 e 2025 com base em dados disponibilizados pela **Agência Nacional do Petróleo, Gás Natural e Biocombustíveis (ANP)**.  

O trabalho foi dividido em duas etapas principais:
1. **Análise Exploratória de Dados (EDA)**  
2. **Modelagem de Séries Temporais**  

---

## 📂 Estrutura do Projeto
producao-gas-natural-1997_2025_ANP/
│
├── datasets/ # Arquivos processados em CSV
│ ├── df_producao_total.csv
│ ├── df_producao_total_sudeste.csv
│ └── ...
│
├── EDA_producao_gas_natural_1000m3_1997_2025.ipynb # Análise exploratória
├── MODELOS_producao_gas_natural_1000m3_1997_2025.ipynb # Modelagem e previsão
└── README.md

---

## 🔎 Etapa 1 – EDA (Exploratory Data Analysis)

- **Preparação de ambiente** (importação de bibliotecas e configuração inicial)  
- **Entendimento e limpeza dos dados** (checagem de nulos, tipos de dados, consistência)  
- **Análise descritiva** (estatísticas gerais da produção)  
- **Visualizações univariadas e bivariadas**  
- **Tendências e padrões** (crescimento, sazonalidade, variações regionais e estaduais)  
- **Insights principais**  
- **Geração de datasets derivados** (salvos em `datasets/`)  

---

## 📈 Etapa 2 – Modelagem de Séries Temporais

Modelos planejados/testados:  
- **Modelos clássicos**  
  - Médias Móveis / Suavização Exponencial (Holt-Winters)  
  - ARIMA / SARIMA  
- **Modelos avançados**  
  - Prophet (Meta/Facebook)  
  - Redes neurais recorrentes (LSTM / GRU)  
- **Avaliação**  
  - Comparação de métricas (RMSE, MAE, MAPE)  

---

## 🚀 Objetivos do Projeto

- Explorar e entender o comportamento da produção de gás natural no Brasil.  
- Criar modelos preditivos capazes de projetar a produção futura.  
- Comparar modelos clássicos e avançados em termos de desempenho.  
- Desenvolver experiência prática com **pandas, matplotlib/seaborn, statsmodels, Prophet e deep learning (Keras/TensorFlow)**.  

---

## 📊 Principais Insights (até agora)

- O Sudeste concentra a maior parte da produção nacional.  
- Existem variações significativas entre estados produtores (São Paulo, Rio de Janeiro, Amazonas).  
- Há tendência de crescimento, mas também períodos de queda relacionados a fatores econômicos e estruturais.  

---

## 🔧 Tecnologias Utilizadas

- **Python** (pandas, numpy, matplotlib, seaborn)  
- **Statsmodels** (ARIMA, SARIMA, Holt-Winters)  
- **Prophet** (Facebook/Meta)  
- **TensorFlow / Keras** (modelos LSTM e GRU)  
- **Jupyter Notebook**  

---

## 📌 Próximos Passos

- Concluir implementação de todos os modelos.  
- Criar comparativo de métricas em tabela e gráficos.    

---

## 📚 Fonte dos Dados

Os dados são disponibilizados pela **Agência Nacional do Petróleo, Gás Natural e Biocombustíveis (ANP)** e estão acessíveis no [portal oficial da ANP](https://www.gov.br/anp/).  



