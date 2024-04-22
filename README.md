## Análise de Vendas de uma Loja Virtual

Este arquivo apresenta uma análise de informações conduzida em um conjunto de dados de vendas de uma loja virtual que atua em todo o país, comercializando itens de variados setores e por meio de múltiplos canais de venda.

### Premissas de Negócio

Durante a análise, levou-se em conta as seguintes premissas:
- Por causa de uma falha no sistema, algumas transações não contêm dados referentes ao estado (Unidade Federativa), sendo então classificadas como MS (Mato Grosso do Sul).
- O valor total de um item não pode exceder o preço com o frete incluso.

### Métricas

Durante a análise, foram calculadas as seguintes métricas:

1. **Departamentos Mais Vendidos:**  Identificação dos setores com maior volume de vendas.
2. **Média de Preço com Frete por Departamento:** Cálculo da média de preço com frete para cada setor.
3. **Quantidade de Vendas por Mês:** Análise da quantidade de vendas realizadas em cada período mensal.
4. **Média de Renda por Canal de Venda:** Cálculo da renda média dos clientes para cada tipo de canal de vendas.
5. **Média de Idade de Clientes por Bandeira:** Análise da idade média dos clientes associada a cada bandeira.

### Conjunto de Dados

Os dados usados nesta análise podem ser acessados [aqui](https://github.com/leandroboteon/biblioteca_pandas/blob/main/varejo.xlsx). Eles fornecem detalhes sobre as vendas da loja virtual, incluindo informações sobre produtos, clientes, vendas e canais de venda.

### Arquivos do Repositório

- **Case_2_Varejo.ipynb:** Jupyter Notebook contendo o código da análise de dados em Pandas.
- **varejo.xlsx:** Arquivo xlsx contendo os dados de vendas da loja virtual.
