# 📊 Projeto de Análise de Dados - Hackday

## 📝 Descrição

Este projeto foi desenvolvido durante um Hackday e tem como objetivo realizar uma análise detalhada dos dados extraídos de um banco de dados, aplicando técnicas de tratamento, limpeza e junção de tabelas em Python. O resultado final é exportado para arquivos .csv e utilizado para construir um relatório interativo no Power BI, que apresenta insights estratégicos sobre as vendas de livros por gênero e formato.


## 🏗️ Fluxo do Projeto

1. Extração dos dados: Conexão ao banco de dados e consulta das tabelas relevantes.

2. Tratamento e limpeza:

    * Remoção de valores nulos e duplicados.

    * Padronização de colunas.

    * Transformação de dados para melhor análise.

3. Junção de tabelas: Unificação de datasets para consolidar as informações.

4. Exportação: Salvamento dos dados tratados em arquivos .csv.

5. Criação do relatório no Power BI:

    * Construção de gráficos e dashboards interativos.

    * Geração de insights baseados nos dados analisados.

## 🔍 Insights Obtidos

A análise revelou tendências importantes sobre as vendas de livros, permitindo identificar padrões de demanda conforme o gênero literário e o formato do livro:

* Incentivar a venda de livros na faixa de 20 a 30 dólares.

* Aumentar a divulgação de livros bem avaiados e com faturamento baixo.

* Focar esforços em livros com alto faturamento e avaliação.

* Livros de Ficção Científica/Fantasia têm maior volume de vendas no formato Mass Market Paperback e Hardcover.

* Gênero Infantil apresenta forte demanda por Board Books e Trade Paperbacks.

* Romances e Mistérios são mais vendidos no formato Mass Market Paperback.

* Young Adult tem boa aceitação no formato Trade Paperback.

* Com base nesses insights, recomenda-se priorizar a produção e distribuição de livros conforme a demanda por gênero e formato, maximizando as vendas e otimizando estoques.


## 🛠️ Tecnologias Utilizadas

Python (Pandas, SQLAlchemy, etc.) para tratamento e manipulação de dados.

SQL para extração de dados do banco, junções de tabelas e trastamentos iniciais.

Power BI para visualização e criação do relatório interativo.


## 📂 Estrutura do Projeto

📁 hackday-projeto

│-- 📂 data                                                # Arquivos CSV gerados

    |-- full-data.csv                                      # Dados gerais

    |-- sales-data.csv                                     # Dados de Vendas

│-- Biblioteca de Insights.pbix                            # Arquivo do relatório Power BI

│-- data-import.ipynb                                      # Scripts Python para extração e tratamento de dados

│-- Problema de negocio hackday 9 Oficial - Copia.pdf      # Documentação do projeto

│-- README.md                                              


## 🚀 Link para o Relatório

* https://app.powerbi.com/view?r=eyJrIjoiZDY2YTFhMWMtNDE5OS00YzgxLTk3NzktMjFjMmE1MTVjY2QwIiwidCI6ImU1YjA4ZjY3LWFmNDYtNGUyNy1hY2ZmLTRlOWVjNjcwZDU3NyJ9


Autor: Gabriel Ganassin 

[LinkedIn](https://www.linkedin.com/in/gabriel-ganassin/)

[Portfólio](https://ganassin.github.io/portfolio_projetos/)
