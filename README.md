# Case_varejo


O objetivo deste projeto é criar métricas para acompanhar os resultados de uma loja de varejo, utilizando as bases de dados de vendas e de clientes. As métricas a serem criadas incluem:

1. Departamentos mais vendidos
2. Média de preço com frete por Nome de Departamento
3. Quantidade de vendas por Mês
4. Média de renda para cada tipo de canal de venda
5. Média de idade de clientes por bandeira

Premissas de Negócio
1. Para compras sem UF, considere o Estado do MS.
2. Preço não pode ser maior que preço com frete.

As etapas foram:
1. Carregamento dos Dados
- Importação das bases de dados de vendas e de clientes.

2. Tratamento dos Dados
- Correção de dados ausentes:
- Para as compras sem UF, foi atribuído o Estado do MS.
- Validação de preços:
- Verificação e correção para garantir que o preço não seja maior que o preço com frete.

3. União das Bases de Dados
- Integração das bases de vendas e clientes com base em chaves comuns, como ID(cliente_Log)
 de cliente e ID(cliente_log) de venda.

4. Criação das Métricas

4.1 Departamentos mais vendidos
- Agrupamento dos dados de vendas por departamento.
- Cálculo da quantidade total de vendas para cada departamento.
- Identificação dos departamentos com maior número de vendas.

4.2 Média de preço com frete por Nome de Departamento
- Agrupamento dos dados de vendas por departamento.
- Cálculo da média de preço com frete para cada departamento.

4.3 Quantidade de vendas por Mês
- Extração do mês de cada data de venda.
- Agrupamento dos dados de vendas por mês.
- Cálculo da quantidade total de vendas para cada mês.

4.4 Média de renda para cada tipo de canal de venda
- Agrupamento dos dados de vendas por tipo de canal de venda.
- Cálculo da média de renda para cada tipo de canal de venda.

4.5 Média de idade de clientes por bandeira
- Agrupamento dos dados de clientes por bandeira.
- Cálculo da média de idade dos clientes para cada bandeira.

5. Ferramentas Utilizadas
- Linguagem de Programação: Python
- Bibliotecas: Pandas, Seaborn/Matplotlib/Plotly (para visualização de dados)

Conclusão:

As métricas foram geradas com sucesso, fornecendo insights valiosos sobre os departamentos mais vendidos, preços médios com frete, vendas mensais, renda média por canal de venda e idade média dos clientes por bandeira. Essas informações são essenciais para a tomada de decisões estratégicas pela loja de varejo.
