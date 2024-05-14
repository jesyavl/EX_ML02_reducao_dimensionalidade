# Diagnóstico de Câncer: Desafios na Análise de Dados de Alta Dimensionalidade

## Descrição do Projeto
O projeto é uma iniciativa fictícia de uma startup voltada para a área da saúde, especificamente para o diagnóstico de câncer. O objetivo principal é reduzir a quantidade de exames necessários para diagnosticar um tipo específico de câncer, utilizando técnicas de análise de dados de alta dimensionalidade.

## Contexto
No contexto da medicina diagnóstica, especialmente no diagnóstico de câncer, a quantidade de variáveis a serem consideradas pode ser muito grande em relação ao número de observações disponíveis. Esse cenário é conhecido como dados de alta dimensionalidade. Nesse projeto fictício, enfrentamos esse desafio ao lidar com dados de 33 dimensões, com o objetivo de determinar se é possível reduzir a necessidade de tantos exames para chegar a um diagnóstico de maneira efetiva.

## Funcionalidades
- Pré-processamento de dados para lidar com valores nulos e constantes.
- Análise da correlação entre variáveis para compreender sua influência no processo de classificação.
- Seleção automática de features utilizando técnicas como SelectKBest, RFE e RFECV.
- Utilização de visualização de dados em alta dimensionalidade para identificar padrões e relações nos dados.

## Estrutura do Repositório
- dados_exames.csv: Arquivo CSV contendo os dados dos exames.
- exames.ipynb: Jupyter Notebook contendo o código Python do projeto.
- README.md: Arquivo de documentação do projeto contendo informações sobre o contexto, funcionalidades e estrutura do repositório.

## Requisitos
- Python 3.x
- Bibliotecas Python: pandas, numpy, seaborn, matplotlib, scikit-learn