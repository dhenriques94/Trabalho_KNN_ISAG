# Implementação do Algoritmo KNN no ambito da unidade PROGRAMMING (ISAG)

Este repositório contém o trabalho final da cadeira de PROGRAMMING. O objetivo foi implementar o algoritmo K-Nearest Neighbors (KNN) de raiz.

## Funcionalidades
Foi criada a classe KNN que permite:
- Definir o número de vizinhos (k).
- Optar pela normalização dos dados (Min-Max) antes da classificação.

## Exemplo de Utilização
Para demonstrar o funcionamento, criei um cenário de classificação de imóveis (Económica ou Luxo) através das variáveis: Área do Imóvel e Nº de quartos.
O algoritmo calcula a distância Euclidiana de uma nova casa para as existentes e classifica-as, utilizando a normalização para lidar com a diferença de escalas entre a Área (m²) e o Nº de Quartos.

### Visualização Gráfica
Abaixo apresenta-se o resultado da classificação gerado pelo nosso código:

![Gráfico do Exemplo](grafico_exemplo.png)

## Como executar
Basta abrir o ficheiro `.ipynb` e correr as células sequencialmente.
