# Case de Varejo — Análise de Dados com Pandas

Estudo de caso de análise de dados aplicado ao varejo: a partir das bases de vendas e de clientes de
uma loja, o projeto trata os dados, integra as fontes e gera métricas de negócio que apoiam decisões
comerciais. É um exercício de análise exploratória (EDA) orientado a indicadores, não a código pelo código.

> **Nota de confidencialidade:** os dados presentes neste repositório são fictícios, gerados apenas
> para demonstração. Nenhum dado real, credencial ou informação de terceiros foi incluído aqui.

---

## Visão Geral

O case percorre o fluxo típico de uma análise de varejo: carregar as bases de vendas e clientes,
tratar inconsistências, uni-las por chaves comuns e produzir métricas que respondem perguntas de
negócio — quais departamentos vendem mais, qual o ticket com frete, como as vendas se distribuem no
tempo e qual o perfil de renda e idade por canal e bandeira.

## Contexto de Negócio

Antes de qualquer dashboard, o varejo precisa saber o básico com confiança: o que vende, para quem e a
que preço. Esse entendimento nasce de cruzar vendas com o cadastro de clientes e de tratar as
inconsistências (campos ausentes, preços incoerentes) que distorcem qualquer conclusão. O case
demonstra exatamente essa base analítica, com premissas de negócio explícitas.

## Métricas Geradas

1. Departamentos mais vendidos.
2. Preço médio com frete por departamento.
3. Quantidade de vendas por mês.
4. Renda média por canal de venda.
5. Idade média de clientes por bandeira.

## Premissas de Negócio

- Compras sem UF são atribuídas ao estado de MS.
- O preço não pode ser maior que o preço com frete (validação de consistência).

## Etapas do Projeto

| # | Etapa | O que é feito |
|---|-------|---------------|
| 1 | Carregamento | Importação das bases de vendas e clientes. |
| 2 | Tratamento | Correção de ausências (UF para MS) e validação de preços. |
| 3 | União (Join) | Integração das bases por chaves comuns (cliente/venda). |
| 4 | Métricas | Agrupamentos e cálculos para os cinco indicadores. |
| 5 | Visualização | Gráficos com Matplotlib e Plotly. |

## Stack

Python - Pandas - seaborn - Matplotlib - Plotly - Jupyter.

## Como Rodar

```bash
pip install pandas seaborn matplotlib plotly cufflinks
jupyter notebook Case_varejo.ipynb
```

## Estrutura do Projeto

```text
Case_varejo.ipynb             -> Notebook com toda a análise (tratamento até visualização)
Requerimento_case_varejo.md   -> Enunciado e requisitos do case
```

## Autor

José Vitor Santos Pinheiro — Análise de Dados e Inteligência Comercial (Varejo e Supply Chain).
Contato: vytorsantt@gmail.com
