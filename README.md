# Projeto Sistema de Recomendação 

## Sistema de Recomendação de Filmes

Este projeto implementa um sistema de recomendação de filmes baseado em similaridade de usuários. Utilizando o conjunto de dados MovieLens, o modelo KNN (K-Nearest Neighbors) é treinado para sugerir filmes a um usuário com base nas preferências de outros usuários similares. O pré-processamento dos dados inclui a limpeza, filtragem e criação de uma matriz esparsa para representar as avaliações dos usuários.

**Processo**:

1. Coleta e preparação dos dados: Os dados foram obtidos do conjunto de dados MovieLens e pré-processados para remover valores ausentes e inconsistências.
2. Criação da matriz de usuários x itens: Uma matriz esparsa foi criada para representar as avaliações dos usuários para cada filme.
3. Treinamento do modelo: O modelo KNN foi treinado utilizando a matriz esparsa.
4. Geração de recomendações: O modelo é capaz de gerar recomendações de filmes para um usuário específico com base nas preferências de usuários similares.

**LINK PARA ACESSO DA BASE DA DADOS: https://drive.google.com/drive/folders/18mCm1022MPklBST5k4eDGrLq7Y4hjZ-a?usp=drive_link**

## Tecnologias usadas
- Python
- Pandas
- Numpy
- Scikit-Learn

