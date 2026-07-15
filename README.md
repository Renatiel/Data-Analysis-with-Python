# Data-Analysis-with-Python

# freeCodeCamp — Data Analysis with Python

Este repositório reúne os projetos desenvolvidos na certificação **Data Analysis with Python** do freeCodeCamp. Cada projeto utiliza bibliotecas como **NumPy**, **Pandas**, **Matplotlib**, **Seaborn** e **SciPy** para resolver problemas reais de análise, limpeza e visualização de dados.

## 📂 Projetos

### 1. [Mean-Variance-Standard Deviation Calculator](./mean_var_std.py)
Função que recebe uma lista com 9 números, converte em uma matriz 3x3 usando **NumPy** e retorna média, variância, desvio padrão, máximo, mínimo e soma — calculados por linha, por coluna e para a matriz achatada.

**Principais conceitos:** manipulação de arrays com NumPy, operações por eixo (`axis=0`, `axis=1`), tratamento de exceções (`ValueError`).

---

### 2. [Demographic Data Analyzer](./demographic_data_analyzer.py)
Análise de dados demográficos do Censo dos EUA de 1994 usando **Pandas**, respondendo perguntas como distribuição por raça, idade média, nível educacional e renda.

**Principais conceitos:** filtragem de DataFrames, `value_counts()`, `groupby`, cálculos percentuais.

---

### 3. [Medical Data Visualizer](./medical_data_visualizer.py)
Criação de uma coluna calculada (`overweight`, a partir do IMC), normalização de dados e geração de dois tipos de gráfico com **Seaborn**: um gráfico categórico (`catplot`) e um mapa de calor de correlação (`heatmap`).

**Principais conceitos:** engenharia de features, `pd.melt`, `groupby` com reformatação de dados, matriz de correlação, máscaras com NumPy.

---

### 4. [Page View Time Series Visualizer](./time_series_visualizer.py)
Visualização de séries temporais de visualizações de página de um fórum, usando gráfico de linha, gráfico de barras (média mensal por ano) e box plots (tendência anual e sazonalidade mensal).

**Principais conceitos:** séries temporais com Pandas (`DatetimeIndex`), `resample`/`groupby` por data, `Matplotlib` e `Seaborn` combinados.

---

### 5. [Sea Level Predictor](./sea_level_predictor.py)
Análise da elevação do nível do mar desde 1880 e previsão para 2050 usando regressão linear.

**Principais conceitos:** regressão linear com `scipy.stats.linregress`, extrapolação de dados, gráficos de dispersão com linha de tendência.

---

## 🛠️ Tecnologias utilizadas

- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy

## ▶️ Como executar

Cada projeto é independente. Para rodar um deles localmente:

```bash
pip install numpy pandas matplotlib seaborn scipy
python3 nome_do_arquivo.py
```

> Alguns projetos exigem um arquivo `.csv` específico (fornecido no ambiente original do freeCodeCamp) na mesma pasta do script, como `adult.data.csv`, `medical_examination.csv`, `fcc-forum-pageviews.csv` e `epa-sea-level.csv`.

## 📜 Sobre

Projetos desenvolvidos como parte da certificação **Data Analysis with Python** do [freeCodeCamp](https://www.freecodecamp.org/).
