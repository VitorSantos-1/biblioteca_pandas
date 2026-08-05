<h1 align="center">Case Varejo — Análise de Dados com pandas</h1>

<p align="center">
  <em>Métricas de negócio para uma loja de varejo, a partir das bases de vendas e clientes.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/seaborn-4C72B0?style=flat-square" alt="seaborn"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" alt="Matplotlib"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" alt="Plotly"/>
</p>

---

## 🎯 Objetivo

Criar métricas para acompanhar os resultados de uma loja de varejo, utilizando as bases de dados de **vendas** e de **clientes**.

## 📈 Métricas geradas

1. Departamentos mais vendidos
2. Média de preço com frete por nome de departamento
3. Quantidade de vendas por mês
4. Média de renda para cada tipo de canal de venda
5. Média de idade de clientes por bandeira

## 📋 Premissas de negócio

- Para compras sem UF, considera-se o estado de **MS**.
- O preço **não** pode ser maior que o preço com frete.

## 🔧 Etapas do projeto

| # | Etapa | O que é feito |
|---|-------|---------------|
| 1 | **Carregamento** | Importação das bases de vendas e clientes. |
| 2 | **Tratamento** | Correção de dados ausentes (UF → MS) e validação de preços. |
| 3 | **União (Join)** | Integração das bases por chaves em comum (ID de cliente/venda). |
| 4 | **Métricas** | Agrupamentos e cálculos para gerar os 5 indicadores. |
| 5 | **Visualização** | Gráficos com Matplotlib e Plotly. |

## 🛠️ Ferramentas

- **Linguagem:** Python
- **Bibliotecas:** pandas, seaborn, Matplotlib, Plotly

## 🚀 Como executar

```bash
# Instalar dependências
pip install pandas seaborn matplotlib plotly cufflinks

# Abrir o notebook
jupyter notebook Case_varejo.ipynb
```

## 📂 Arquivos

| Arquivo | Descrição |
|---------|-----------|
| [`Case_varejo.ipynb`](Case_varejo.ipynb) | Notebook com toda a análise, do tratamento às visualizações. |
| [`Requerimento_case_varejo.md`](Requerimento_case_varejo.md) | Enunciado / requisitos do case. |

## ✅ Conclusão

As métricas foram geradas com sucesso, fornecendo *insights* sobre os departamentos mais vendidos, preços médios com frete, vendas mensais, renda média por canal e idade média dos clientes por bandeira — informações essenciais para a tomada de decisões estratégicas da loja.

---

<p align="center">
  <sub>Feito por <a href="https://github.com/VitorSantos-1">Vitor Santos</a> · 🐼 Análise de Dados</sub>
</p>
