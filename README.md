# 📊 Análise de Dados do YouTube com PySpark

Este é meu **primeiro projeto utilizando PySpark**, desenvolvido como exercício prático para explorar leitura, escrita e manipulação de dados em grandes volumes utilizando a API do Spark.

## 🎯 Objetivo

O projeto simula uma situação real onde um analista de dados precisa:

- Ler arquivos CSV com e sem inferência de tipos
- Visualizar dados e entender seu esquema
- Escrever dados em formato Parquet
- Criar uma tabela temporária com Spark SQL
- Realizar consultas com SQL no Spark
- Trabalhar com múltiplas fontes de dados (vídeos e comentários)

## 🛠️ Tecnologias utilizadas

- Python
- PySpark
- Google Colab

## 📂 Estrutura do Projeto

📁 youtube-pyspark-estudo
├── leitura-escrita.ipynb # Notebook principal do projeto
├── README.md # Este arquivo
└── data/
├── videos-stats.csv # Dados de estatísticas de vídeos (amostra)
└── comments.csv # Comentários dos vídeos (amostra)


## 🚀 Como executar

1. Clone este repositório ou baixe os arquivos.
2. Abra o notebook `leitura-escrita.ipynb` no [Google Colab](https://colab.research.google.com).
3. Faça upload dos arquivos `.csv` da pasta `data/` quando solicitado.
4. Execute as células do notebook e acompanhe o passo a passo.

## 🧠 O que aprendi

- Como iniciar um projeto PySpark no Google Colab
- Leitura e escrita de arquivos em diferentes formatos (CSV e Parquet)
- Criação de *DataFrames* e visualização com `.show()` e `.printSchema()`
- Uso de `createOrReplaceTempView` para consultas SQL
- Organização de projetos de dados no GitHub

## 📌 Observação

Os dados usados neste projeto são de domínio público (licença CC0) e foram reduzidos para fins de estudo. Você pode usá-los livremente.

---

### 💼 Projeto de Estudo – Portfólio de Dados

Este projeto faz parte do meu aprendizado em **Análise de Dados com PySpark**. Feedbacks são bem-vindos!
