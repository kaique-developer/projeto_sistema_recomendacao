# Projeto Sistema de Recomendação 

## Sistema de Recomendação de Filmes

Este repositório apresenta um sistema de recomendação de filmes desenvolvido em Python, utilizando as bibliotecas Pandas e Scikit-learn. O modelo de recomendação é baseado na técnica de filtragem colaborativa, especificamente o algoritmo KNN.

**Processo**:

1. Coleta e preparação dos dados: Os dados foram obtidos do conjunto de dados MovieLens e pré-processados para remover valores ausentes e inconsistências.
2. Criação da matriz de usuários x itens: Uma matriz esparsa foi criada para representar as avaliações dos usuários para cada filme.
3. Treinamento do modelo: O modelo KNN foi treinado utilizando a matriz esparsa.
4. Geração de recomendações: O modelo é capaz de gerar recomendações de filmes para um usuário específico com base nas preferências de usuários similares.

## Tecnologias usadas
- Python
- Pandas
- Numpy
- Scikit-Learn

