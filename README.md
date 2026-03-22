[PROJETO TITANIC - Análise e Machine Learning.md](https://github.com/user-attachments/files/26168128/PROJETO.TITANIC.-.Analise.e.Machine.Learning.md)
# PROJETO TITANIC - Análise e Machine Learning

## Descrição do Projeto

Este repositório contém um projeto de análise de dados e machine learning focado no famoso desafio do Titanic. O objetivo principal é aplicar técnicas de limpeza de dados e construir modelos de aprendizado de máquina para prever a sobrevivência dos passageiros do Titanic.

## Objetivo

O projeto foi desenvolvido com o intuito de aprofundar o conhecimento em Machine Learning e seus conceitos, desde a preparação dos dados até a avaliação dos modelos.

## Estrutura do Repositório

O repositório está organizado da seguinte forma:

- `Material de Estudo/`: Contém materiais e recursos utilizados para o estudo e aprendizado.
- `analise/limpeza/`: Inclui os notebooks Jupyter para a etapa de análise e limpeza de dados, bem como a implementação dos modelos de Machine Learning.
  - `limpeza.ipynb`: Notebook dedicado à exploração e pré-processamento dos dados.
  - `marchine_learning.ipynb`: Notebook onde os modelos de Machine Learning são construídos e avaliados.
- `datasets_modificados/`: Armazena os datasets após o processo de limpeza e transformação.
- `datasets_originais/`: Contém os datasets brutos originais do desafio do Titanic.

## Análise e Limpeza de Dados

A etapa de análise e limpeza de dados foi realizada utilizando a biblioteca **Pandas** no notebook `limpeza.ipynb`. As principais operações incluíram:

- Tratamento de valores ausentes.
- Engenharia de features para criar novas variáveis relevantes.
- Transformação de variáveis categóricas.

## Machine Learning

No notebook `marchine_learning.ipynb`, foram implementados e avaliados modelos de Machine Learning para prever a sobrevivência dos passageiros. O modelo utilizado foi o **DecisionTreeClassifier**, que alcançou uma acurácia de aproximadamente **80%**.

## Visualização de Dados

Para a visualização dos resultados e insights obtidos, foi utilizada a ferramenta **Power BI**.

## Tecnologias Utilizadas

- **Python**
- **Pandas** (para manipulação e limpeza de dados)
- **Scikit-learn** (para Machine Learning)
- **Jupyter Notebook**
- **Power BI** (para visualização de dados)

## Como Executar o Projeto

Para executar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/B1730/PROJETO_TITANIC.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd PROJETO_TITANIC
   ```
3. Instale as dependências necessárias (recomenda-se usar um ambiente virtual):
   ```bash
   pip install pandas scikit-learn jupyter
   ```
4. Abra os notebooks Jupyter:
   ```bash
   jupyter notebook
   ```
   Em seguida, navegue até `analise/limpeza/limpeza.ipynb` e `analise/limpeza/marchine_learning.ipynb` para explorar o código.

## Autor

- **B1730** (Gabriel de Oliveira Teixeira)
