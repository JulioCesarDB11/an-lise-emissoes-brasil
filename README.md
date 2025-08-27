# an-lise-emissoes-brasil

Análise de Emissões de Gases de Efeito Estufa no Brasil (1970-2021)

Este repositório contém um projeto de análise de dados realizado em um notebook do Google Colab, que explora as emissões de gases de efeito estufa no Brasil no período de 1970 a 2021. Os dados foram extraídos do SEEG (Sistema de Estimativa de Emissões e Remoções de Gases de Efeito Estufa).

O projeto segue as seguintes etapas:

1. Leitura e Limpeza de Dados
Os dados brutos são carregados a partir de um arquivo em formato .xlsx.

O notebook realiza o tratamento e a limpeza do conjunto de dados, removendo valores irrelevantes como remoções de gases, emissões não contempladas no inventário nacional (NCI) e emissões de transporte internacional (bunkers).

A base de dados é transformada para um formato mais adequado para análise.

2. Análise e Visualização
É realizada uma análise da emissão total por tipo de gás, revelando que os gases da família CO2e representam mais de 99% das emissões totais.

A emissão de CH4 (metano) e N2O (óxido nitroso) é identificada como sendo predominantemente do setor de Agropecuária.

É incluída a análise das emissões per capita por estado, utilizando dados de população obtidos no Censo do IBGE.

A visualização dos dados é feita através de gráficos de barras e de dispersão (scatter plot) para facilitar a interpretação das informações.

Este projeto demonstra como manipular e analisar dados ambientais, oferecendo insights sobre a distribuição das emissões de gases de efeito estufa no Brasil.
