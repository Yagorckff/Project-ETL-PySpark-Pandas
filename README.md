# Projeto-de-Conclusao-de-Curso---SoulCode
![Badge em Desenvolvimento](https://img.shields.io/badge/Linguagem-Python-blue)
![Badge Pyspark](https://img.shields.io/badge/API-Pyspark-orange)
![Badge Pandas](https://img.shields.io/badge/biblioteca-Pandas-orange)
![Badge MongoDB](https://img.shields.io/badge/DB-MongoDB-brightgreen)


## Projeto individual do curso Engenharia de Dados da SoulCode Academy.


### Tecnologias utilizadas para realização do projeto:
- Google Cloud Platform (CGP)
- Cloud Storage
- Python
- Pandas
- PySpark
- SparkSQL
- MongoDB



## Descrição
Nesse projeto eu fiz um ETL de um Dataframe de supermercado, aas informações foram traduzidas e limpas.
Tanto o Dataframe original quanto o tratado foram carregados no MongoDb e no Datalake no googleCloud


## ETL

### Nivel Infra:
- O arquivo original e tratado foram salvos em MongoDB Atlas em coleções diferentes
- Os Datasets foram salvos em uma bucket do CloudStorage

### Nivel Pandas
- O arquivo estava em Inglês e foi traduzido para Português-BR
- Foi feita a Extração do dataset na bucket no Google Cloud para um Dataframe no pandas
- Foi feito limpeza de dados inconsistentes e mudança para NAN e NA e colunas irrelevantes foram dropadas 

### Nivel PySpark
- Foi montada uma estrutura do DataFrame utilizando o StructType.
- Parte da limpeza de dados inconsistentes foi feita no Pyspark
- Realizada a tradução e mudança de nome de algumas colunas
