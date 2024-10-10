# Relatório de Desenvolvimento de Vendas e Lucros com DATA ANALYTICS com Power BI

## Introdução
Este documento descreve as etapas seguidas para criar o Report Financeiro utilizando o Power BI, desde a coleta e transformação dos dados até a visualização final.

## 1. Importação dos Dados
- Origem: Dados de amostras do Power bi

## 2. Limpeza e Transformação dos Dados
-Ações:
  - Alteração do tipo de dado.
  - Colunas condicionais de semestres 1 e 2 adcionadas.

## 3. Modelagem de Dados
-Relacionamentos:
  - Nenhum relacionamento entre tabelas
-Medidas:
  - Criação da medida:'financials'[Semestre].
  - Criação da medida:'financials'[MaximoSold].
  - Criação de agrupamento:'financials'[buckets].
  - Criação de agrupamento:'financials'[Segments].
  - Criação de agrupamento:'financials'[Profit].

## 4. Criação de Visualizações
##Página 1 (Principal)
-VIZUALIZAÇÕES UTILIZADAS:

-Botões de navegação de páginas
-Gráfico de rosca para Segments
-Gráfico de barras clusterizado para soma por produtos
-Gráfico de mapa para venda por países
-Cartões para somas e unidades vendidas

##Página 2 (Detalhes)
-Botões de navegação de páginas
-Gráfico de colunas clusterizado para histograma de unidades vendidas
-Gráfico de barras clusterizado para vendidos x produtos
-Tabela de venda por trimestre
-Gráfico de colunas clusterizado para vendas por semestre

##Página 3 (TOPN & OUTLERS)
-Botões de navegação de páginas
-Gráfico de dispersão por produto e período
-Gráfico de colunas empilhadas para soma do Top 3 produtos por país
-Gráfico de colunas empilhadas para soma do Top 3 produtos

##Página 4 (Data Analytics)
-Botões de navegação de páginas
-Gráfico de dispersão de Soma de Units Solds e somas de Sales por mês
-Gráfico de barras empilhada para soma de sales e profit por país por 5 meses
-Cartões de máximo sold e government
-Gráfico de barras clusterizado top 3 countrys

##Página 5 (Categoria & Cluter)
-Botões de navegação de páginas
-Gráfico de dispersão de soma de unit sold
-Gráfico de colunas clusterizado de soma de sales por country e continents
-Gráfico de colunas clusterizado de soma de sales por segments e agrupado

## 5. Aplicação de Filtros
- Filtros Adicionados:
  - Filtro de Country, deixando apenas top 3 max sold.

## Conclusão
Este relatório descreveu todas as etapas para desenvolver o dashboard de 'Report_Financeiro' no Power BI, incluindo a importação, transformação de dados, modelagem e criação de visualizações.

