# iFood Data Analytics Test

## **Descrição** 

Este projeto consiste em um case de Data Analytics para o iFood. A análise foi realizada utilizando Python no Jupyter Notebook via Anaconda Navigator (2.6.3).

## **Tecnologias Utilizadas**

- Python 3.12.7  
- **Jupyter Notebook** (via Anaconda Navigator 2.6.3)

## **Bibliotecas**:

* pandas  
* numpy  
* matplotlib  
* seaborn  
* os  
* scipy.stats  
* math  
* **polars** (necessário instalar separadamente)

## **Instalação do Polars**

Para esta análise, foi escolhida a biblioteca **Polars** ao invés do **PySpark**, principalmente devido a fatores de desempenho e praticidade ao rodar localmente.

O **Polars** não vem instalado por padrão no Anaconda. Para instalá-lo, utilize um dos comandos abaixo:

Se estiver usando **pip** dentro do Anaconda:

`pip install polars`

Caso utilize **conda-forge**:

`conda install -c conda-forge polars`

## Base de Dados
Devido ao tamanho das bases fornecidas, não foi possível adicionar elas ao GitHub. O link para download de cada base está abaixo. Para abrir os arquivos corretamente no Notebook, siga as etapas:

Baixe e extraia os arquivos:

* Salve os arquivos em uma nova pasta.
* Crie uma pasta chamada Data dentro dela.
* Extraia os arquivos .gz na pasta Data.
* Acesse e rode o notebook: Após extrair os arquivos, abra o Jupyter Notebook e execute o código.

* [Pedidos (order.json)](https://data-architect-test-source.s3-sa-east-1.amazonaws.com/order.json.gz) 
* [Usuários (consumers.csv)](https://data-architect-test-source.s3-sa-east-1.amazonaws.com/consumer.csv.gz)
* [Merchants (restaurant.csv)](https://data-architect-test-source.s3-sa-east-1.amazonaws.com/restaurant.csv.gz) 
* [Marcação de usuários que participaram do teste A/B (ab_- test_ref.csv)](https://data-architect-test-source.s3-sa-east-1.amazonaws.com/ab_test_ref.tar.gz) 


## **Outras Ferramentas**

Para auxiliar na criação das tabelas relacionadas à proposta de novas campanhas, foi utilizada uma planilha no Google Sheets. A planilha pode ser acessada através do link abaixo:  
[https://docs.google.com/spreadsheets/d/1azySnk4JsbT6tvl\_gDiKMAFL5bqUGpwek09SvcgsAzs/edit?gid=985188743\#gid=985188743](https://docs.google.com/spreadsheets/d/1azySnk4JsbT6tvl_gDiKMAFL5bqUGpwek09SvcgsAzs/edit?gid=985188743#gid=985188743)
