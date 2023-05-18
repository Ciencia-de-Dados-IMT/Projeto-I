# Projeto I - **EDA (Exploratory Data Analysis)**
---

O objetivo do projeto é a construção completa de um **EDA (Exploratory Data Analysis)** sobre um conjunto de dados original fornecendo ***insights* relevantes sobre tema dos dados selecionados**. 

**Integrantes**:
* MATHEUS ROSSINI DE SOUZA 18.01060-0
* JOAO VITOR QUIRINO SARTI 18.01224-8
* FERNANDO OLIVEIRA DE SOUZA 19.00617-9
* FELIPE FREITAS VILLANI 19.01370-0
* RENAN SCHEIDT RESCHKE 19.02009-0

O projeto principal se encontra no arquivo `Projeto_S1.ipynb`, usando como base de dados inicial um csv de listagens de imóveis para aluguel no Rio de Janeiro, disponibilizado pelo Airbnb.

Os dados são atualizados pelo detentor quadrimestralmente, com histórico de 12 meses no arquivo.

#### Sumário do projeto:
Projeto de Data Science aplicado à dataset do Airbnb Rio
```
|_ 1 Bibliotecas
|   |_ 1.1 Funções Auxiliares
|_ 2 Importação das bases de dados
|   |_ 2.1 Obtenção dos dados
|   |_ 2.2 Visualização de quais dados estão disponíveis
|_ 3 Tratar os Dados (Análise Qualitativa)
|   |_ 3.1 Excluir informações não relevantes
|   |_ 3.2 Tratar valores vazios
|   |_ 3.3 Verificar Tipos de Dados em cada coluna
|_ 4 Análise Exploratória e Tratar Outliers
|   |_ 4.1 Tratamento de valores numéricos
|   |   |_ 4.1.1 price
|   |   |_ 4.1.2 calculated_host_listings_count
|   |   |_ 4.1.3 minimum_nights
|   |   |_ 4.1.4 number_of_reviews
|   |   |_ 4.1.5 accommodates
|   |_ 4.2 Tratamento de Colunas de Valores de Texto
|   |   |_ 4.2.1 bathrooms_text
|   |   |_ 4.2.2 property_type
|   |   |_ 4.2.3 room_type
|   |   |_ 4.2.4 host_response_time
|   |   |_ 4.2.5 neighbourhood_cleansed
|   |   |_ 4.2.6 host_response_rate e host_acceptance_rate
|   |_ 4.3 Visualização da correlação entre as variáveis numéricas
|_ 5 Encoding
|_ 6 Visualização dos dados
|   |_ 6.1 Visualização de Mapa das Propriedades e Seus Preços
|   |_ 6.2 Distribuição de preços
|   |_ 6.3 Quantidade de listagens do host
|   |_ 6.4 Quantidade mínima de noites dos anúncios
|   |_ 6.5 Número de pessoas que o imóvel acomoda
|   |_ 6.6 Quantidade de banheiros no imóvel
|   |_ 6.7 Tipo de Propriedade
|_ 7 Modelo de Previsão de Preço
|   |_ 7.1 Métricas de Avaliação
|   |_ 7.2 Escolha dos Modelos de Regressão
|   |_ 7.3 Análise dos Modelos de Regressão
|   |_ 7.4 Tentativa de melhorar o modelo
|   |_ 7.5 Prevendo o preço de um imóvel
```