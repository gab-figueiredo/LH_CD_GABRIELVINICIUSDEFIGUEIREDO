# Desafio Cientista de Dados - Indicium
Repositório com a entrega do Desafio proposto pelo Programa LIGHTHOUSE da Indicium.
O objetivo do desafio de Cientista de Dados é realizar uma análise em cima de um banco de dados 
cinematográfico para orientar qual tipo de filme deve ser o próximo a ser desenvolvido. Para tal análise
forão utilizados base de dados com as informações básicas sobre os filmes. Além disso, foram incluídas
informações financeiras para análise de negício do site do [Kaggle.com](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) 
como meio de enriquecer os dados.  

## Conteúdos

:small_blue_diamond:  [Estrutura do projeto](#estrutura-do-projeto)
:small_blue_diamond:  [Requisitos](#requisitos)
:small_blue_diamond:  [Execução do Código](#execução-do-código)
:small_blue_diamond:  [Autor](#autor)

## Estrutura do projeto 

- `[Lighthouse] Desafio Ciência de Dados 2025-11.pdf`: arquivo com o desafio;
- `desafio_indicium_imdb.csv`: conjunto de dados principal do desafio;
- `imdb_tmdb_enriched.csv` e `imdb_fully_featured.csv`: arquivos gerados durante a análise para visualizadas das features/dados enriquecidos;
- `LH_CD_GABRIELVINICIUSDEFIGUEIREDO.ipynb`: jupyter notebook com todo o fluxo do processo e respostas solicitados pelo desafio;
- `LH_CD_GABRIELVINICIUSDEFIGUEIREDO.pkl`: saída do modelo final;
- `requirements.txt`: requisitos para execução do projeto;
- `tmdb_5000_movies.csv`: dados extras para análise;

## Requisitos

Certifique-se de ter o Python em versão 3 ou superior para correta execução do desafio, ademais
também será necessário a instalação do gerenciador de pacotes PIP e do Jupyter Notebook para execução do notebook
orquestrador da lógica do desafio. Os outros pacotes necessários para a execução/análise do projeto serão instalados na etapa posterior.

- [Jupyter Notebook](https://jupyter.org/install)
- [Python](https://www.python.org/downloads/)
- [PIP](https://pip.pypa.io/en/stable/installation/)


## Execução do Código

Para executar o projeto com sucesso, é necessário que, previamente seu ambiente tenha instalado
as bibliotecas da etapa anterior, como python e o pip (usado para gerenciar os pacotes python). Após isso, podemos seguir os segintes passos:

- Obtendo o repositório e acessando a pasta:

    ```sh
     # Clone o repositório:
     git clone https://github.com/gab-figueiredo/LH_CD_GABRIELVINICIUSDEFIGUEIREDO.git

     # Entre no diretório do repositório:
     cd LH_CD_GABRIELVINICIUSDEFIGUEIREDO/
    ```

- Criando ambiente para instalação das dependências

    ```sh
     # Instalando virtualenv:
     pip install virtualenv
     
     # Criando ambiente virtual:
     python3 -m venv <nome_do_ambiente>
    ```

- Ativando ambiente virtual, de acordo com o seu sistema

    a. Windows:
    
    ```sh
     <name_do_ambientet>\Scripts\activate
    ```
    b. Linux:

    ```sh
     source <nome_do_ambiente>/bin/activate
    ```

- Após a criação e devida ativação do ambiente virtual, instale os requisitos:
```sh
    pip install -r requirements.txt
```

- Execute o Jupyter Notebook para visualizar o processo relacionado as entregas do desafio:
```sh
    jupyter notebook
```

Após isso uma nova aba será aberta e pasta executar o arquivo LH_CD_GABRIELVINICIUSDEFIGUEIREDO.ipynb para visualizar/executar
todas as etapas do projeto, como exemplo, EDA, respostas as perguntas soliticadas e as saídas
do desafio:

- Arquivo LH_CD_GABRIELVINICIUSDEFIGUEIREDO.pkl contendo o modelo treinado;

## Autor

👤 **Gabriel Figueiredo**

[![Linkedin Badge](https://img.shields.io/badge/-Gabriel-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/gabrielvinifigueiredo/)](https://www.linkedin.com/in/gabrielvinifigueiredo/) [![Gmail Badge](https://img.shields.io/badge/-gabrielfigueiredo158@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:gabrielfigueiredo158@gmail.com)](mailto:gabrielfigueiredo158@gmail.com)
