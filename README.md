# Trabalho de Algoritmos e Base de dados
Recolha e estruturação de dados genéticos a partir de ficheiros Genbank, com cruzamento de informação proveniente do PubMed.

## Overview

Este repositório contém os ficheiros desenvolvidos durante o projeto que visa a criação de uma base de dados relacional a partir de ficheiros Genbank, com ligação a informações relevantes do PubMed. 
Foram utilizados scripts em Python, ferramentas de modelação de dados (TerraER e MySQL Workbench) e bibliotecas como Biopython.

O objetivo principal deste trabalho foi estruturar e armazenar de forma eficiente a informação contida nos ficheiros Genbank relativos a um organismo específico, facilitando a posterior análise e extração de conhecimento útil à investigação biomédica.




## Contents

  - `Artigo_final`: Artigo final do projeto, contêm os resultados, conclusões e discussões relacionadas ao projeto.

  - `Artigos_tratados.xlsx`: Excel com as informações extraídas manualmente de 100 "abstracts" selecionados aleatoriamente da base de dados no período de 2015 a 2023.

  - `Base_de_dados.ipynb`: Scripts que permitem extrair os "Abstracts" do PubMed e povoar a base de dados.

  - `Base_de_dados_ESKAPE.mwb`: Base de dados do projeto.

  - `Processamento_de_texto.ipynb`: Scripts que permitem extrair os diferentes parâmetros pretendidos presentes nos "Abstracts" recolhidos.

  - `VOSviewer.doc.txt`: Documento usado para analisar as "Keywords" presentes nos artigos extraídos usando a ferramenta VOSviewer.
  
  - `artigos_selecionados.xlsx`: Ficheiro excel criado com os 100 "abstracts" selecionados aleatoriamente da base de dados no período de 2015 a 2023.

  - `drugbank_vocabulary.cvs`: Dicionário de drogas do DrugBank.
  
  - `todos_artigos_selecionados.xlsx`: Ficheiro excel criado com os todos os "abstracts" presentes na base de dados.
