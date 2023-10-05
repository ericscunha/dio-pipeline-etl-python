# Processo ETL - Desafio DIO

ETL de dados do TMDb (The Movie Database) através de uso de API Pública.

Desafio do Bootcamp Santander 2023 - Ciência de Dados com Python - Elaborando um pipeline de ETL com Python

## Extração 

Os dados dos filmes mais popularese segundo o TMDb serão extraídos por um API pública e carregada em Dataframe pandas.

## Transformação

Será feita uma limpeza simples dos dados, deixando apenas os dados importanres para análise assim como a classificação das avaliações por faixas de acordo com a coluna vote_average

## Carga (Load)

 Os dados tratados serão carregados em um arquivo parquet.