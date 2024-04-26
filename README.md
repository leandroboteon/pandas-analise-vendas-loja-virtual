## Análise de Vendas de uma Loja Virtual


### Objetivo do Projeto

O objetivo deste projeto é analisar os dados de vendas do e-commerce para identificar padrões de comportamento dos clientes, avaliar o desempenho das vendas ao longo do tempo e fornecer insights para otimização das estratégias de vendas e marketing.

### Descrição dos Dados

Os dados utilizados nesta análise foram coletados do sistema de vendas do e-commerce e incluem informações sobre as transações de vendas, clientes, produtos e canais de venda.

### Metodologia Utilizada

Durante a análise, foram utilizadas técnicas de limpeza e tratamento de dados para garantir a qualidade dos dados analisados. Além disso, foram aplicadas técnicas de análise exploratória de dados e visualização para identificar padrões, tendências e insights relevantes nos dados de vendas.

### Limpeza e Tratamento de Dados

1. **Importando Bibliotecas:** Utilizamos as bibliotecas pandas, matplotlib e seaborn para análise e visualização dos dados.

2. **Leitura e Verificação do Dataset:** Carregamos o conjunto de dados e verificamos suas informações usando a função .info para entender a estrutura dos dados.

3. **Tratamento de Valores Nulos:** Verificamos valores nulos na coluna "Preço" e substituímos os valores nulos pela média geral de preços. Também tratamos valores nulos na coluna "estado", substituindo-os por "MS".

4. **Padronização de Categorias:** Agrupamos as compras por categoria e substituímos valores "APP" por "Aplicativo" para padronização.

5. **Filtragem de Dados:** Aplicamos um filtro para manter apenas as compras onde o preço é menor ou igual ao preço com frete.

6. **Criação de Colunas:** Criamos a coluna "mês" para facilitar a análise temporal das vendas.

7. **Importação e Join com Tabela de Clientes:** Importamos a tabela de clientes, alteramos o tipo da coluna "renda" para float e fizemos um join com a tabela de vendas.

### Criação de Métricas

1. **Departamentos Mais Vendidos:** Agrupamos a coluna "Nome_Departamento" com os valores únicos da coluna "idcompra" e exibimos os 5 departamentos mais vendidos.

2. **Média de Preço com Frete por Departamento:** Calculamos a média de preço com frete por departamento e exibimos os 5 departamentos com maior média de preço.

3. **Quantidade de Vendas por Mês:** Agrupamos as vendas por mês e contamos os valores únicos da coluna "idcompra". Apresentamos os resultados em um gráfico de linha.

4. **Média de Renda por Tipo de Canal de Venda:** Calculamos a média de renda para cada tipo de canal de venda e exibimos os resultados em um gráfico de barras.

5. **Média de Idade de Clientes por Bandeira:** Agrupamos as vendas por bandeira e calculamos a média de idade dos clientes. Apresentamos os resultados em um gráfico de barras.

### Resultados e Insights

Os principais resultados obtidos na análise incluem:
- Identificação dos departamentos mais vendidos e suas respectivas médias de preço com frete.
- Análise da quantidade de vendas por mês e sua variação ao longo do tempo.
- Avaliação da renda média dos clientes para cada tipo de canal de venda.
- Determinação da média de idade dos clientes por bandeira de cartão de crédito.

### Arquivos do Repositório

- **analise_vendas_ecommerce.ipynb:** Jupyter Notebook contendo o código da análise de dados em Python.
- **varejo.xlsx:** Arquivo xlsx contendo os dados de vendas da loja virtual.
- **cliente_varejo.xlsx:** Arquivo xlsx contendo os dados de clientes.
