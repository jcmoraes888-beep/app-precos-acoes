# 📈 App Preço de Ações

App em Python + Streamlit para acompanhar a cotação das ações do **Ibovespa** desde 2010 e simular o desempenho de uma carteira.

**App no ar:** [app-precos-acoes.streamlit.app](https://app-precos-acoes-eq92tagqzbciuynbyxdc8m.streamlit.app)

> Projeto feito durante o curso de Streamlit da Hashtag Treinamentos.

## O que faz

- Seleção de uma ou várias ações do Ibovespa (lista em `IBOV.csv`)
- Gráfico de fechamento com filtro de período por slider de datas
- Cálculo da performance de cada ativo e da carteira no período escolhido
- Dados do Yahoo Finance (`yfinance`), com cache diário para abrir rápido

## Como rodar

```bash
pip install -r requirements.txt
streamlit run CURSO_STREAMLIT.py
```

## Stack

Python · Streamlit · pandas · yfinance
