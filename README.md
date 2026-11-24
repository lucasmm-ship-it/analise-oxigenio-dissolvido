
# Análise de Oxigênio Dissolvido em Águas Brasileiras

## 1. Sobre o projeto

Este projeto apresenta uma análise exploratória de dados de oxigênio dissolvido em estações de monitoramento de águas brasileiras, utilizando Python para organizar, explorar, visualizar e comparar informações ambientais, com destaque para o estado do Maranhão.

## 2. Objetivo

Investigar os registros de oxigênio dissolvido disponíveis na base do Sistema Nacional de Informações sobre Recursos Hídricos (SNIRH), analisando sua distribuição temporal e comparando as médias registradas no Maranhão com as demais unidades da Federação em 2020.

## 3. Base de dados

**Fonte:** Sistema Nacional de Informações sobre Recursos Hídricos (SNIRH).

A base utilizada contém 5.642 registros e 139 colunas, incluindo informações sobre estações de monitoramento, localização e medições anuais de oxigênio dissolvido.

## 4. Ferramentas utilizadas

- Python
- Google Colab
- Pandas
- Matplotlib
- SciPy

## 5. Pergunta de análise

Existe diferença significativa nas médias de oxigênio dissolvido entre as estações de monitoramento do Maranhão e as dos demais estados brasileiros em 2020?

Essa investigação é relevante para o monitoramento da qualidade da água e pode contribuir para estudos e ações de gestão dos recursos hídricos.

## 6. Preparação e análise dos dados

Foram verificadas as dimensões da base, os tipos de dados, a distribuição das estações por estado e a presença de valores ausentes.

Os registros foram organizados para análises temporais e comparações entre o Maranhão e as demais unidades da Federação. Os valores ausentes foram excluídos dos cálculos correspondentes, sem preenchimento artificial.

## 7. Principais resultados

- Média do Maranhão em 2020: 6,84.
- Média das demais UFs: 6,62.
- Desvio padrão do Maranhão: 4,02.
- Desvio padrão das demais UFs: 2,13.
- Estatística t de Welch: 0,4192.
- Valor-p: 0,6766.

Não foram encontradas evidências estatísticas suficientes de diferença entre as médias dos dois grupos.

## 8. Conclusão

A comparação não identificou diferença estatisticamente significativa entre as médias de oxigênio dissolvido dos grupos analisados em 2020.

Apesar disso, as estações maranhenses apresentaram maior dispersão dos valores, indicando maior variabilidade nos registros analisados.

Os resultados devem ser interpretados considerando as diferenças na quantidade de observações e a presença de possíveis valores extremos.

## 9. Reflexão

O Python facilitou a organização, a análise estatística e a visualização dos dados, permitindo automatizar operações e trabalhar com uma quantidade maior de registros do que seria conveniente em uma planilha.

O trabalho foi desenvolvido individualmente, desde a obtenção e organização da base até a interpretação dos resultados.

## 10. Autoria

Lucas Moraes

Trabalho individual.

