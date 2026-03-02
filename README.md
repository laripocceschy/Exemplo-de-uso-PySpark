# Contexto

Projeto de engenharia de dados utilizando Apache Spark para processamento e transformação de um dataset nutricional contendo informações de macronutrientes e classificação calórica.

O objetivo foi simular um mini data lake, aplicando transformações, agregações e escrita particionada em formato Parquet.

# Tecnologias utilizadas

- Python

- Apache Spark (PySpark)

- Google Colab

- Google Drive (armazenamento)

# Pipeline Implementado

- Leitura de arquivo CSV

- Tratamento de schema

- Criação de colunas derivadas:

    - Calorias calculadas por macronutrientes

    - Flag de alto açúcar

    - Classificação de nível de proteína

- Agregações por classe calórica

- Validação de dados nulos

- Escrita em formato Parquet particionado

# Escrita Particionada
Os dados foram armazenados no formato Parquet, particionados por:
- calorie_class
- protein_level

Simulando organização típica de Data Lake.
