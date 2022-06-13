# Investimentos em Real Estate - Data-Driven Decision

## Sumário
* [Overview](#overview)
* [Data Understanding](#EDA)
* [Resultados e Conclusões](#Resultados)
* [Tecnologias](#tecnologias)

## Overview
O mercado imobiliário é cíclico e muitas vezes, subjetivo. Por conta disso, inúmeras oportunidades de ganho de capital normalmente estão disponíveis no mercado. A utilização de grandes conjuntos de dados como suporte no processo decisório na compra imobiliária vem se tornando fundamental, e muitas vezes, indispensável. O presente trabalho busca auxiliar no processo decisório da Roof Imóveis na compra de 5 imóveis no Condado de County nos estados unidos, empresa especializada na aquisição de imóveis.

## Fonte dos Dados
Os dados utilizados na análise são open source e podem ser encontrados no seguinte website: https://www.kaggle.com/datasets/harlfoxem/housesalesprediction

## Data Understanding
Análises de correlação entre variáveis numéricas contínuas, e testes anova entre variáveis numéricas discretas e contínuas para obtenção de atributos associados a variável alvo ('preço_por_ft2) utilizando a lib pandas e scipy.stats.

Arquivo: projeto_parte1.ipynb

Post-hoc testes (Tukey test) para feature engenerring de variáveis discretas ('yr_built') anteriormente detectadas como importantes pelos testes anova utilizando lib scipy.stats.

Arquivo: projeto_parte2.ipynb

## Resultados e Conclusões
Agrupando os imóveis na maneira proposta produziu uma concentração de imóveis mais antigos em nossas recomendações. Dessa maneira, recomendamos em trabalhos futuros (projeto_parte2.ipynb) o estudo aprofundado da variável 'yr_built' a partir de testes anova e testes post-hoc, como o tukey test. Isso nos mostraria se essa variável possui alguma associação com a variável 'price_per_ft2', e como deveriamos agrupa-la de modo a diminuir o número de categorias nessa feature. 
	
## Tecnologias
Projeto criado com:
* Python: 3.10.4
  * Biblioteca: Numpy, Matplotlib.pyplot, pandas, scipy.stats, pprint, uszipcode
* IDE: Google Colab
* Unix: OS version 18.7.0
* Git and Github


