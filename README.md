# Visualizacao_Informacao
# Habitação e a Evolução da Situação de Sem-Abrigo em Portugal (2018-2023)
Estado Atual: Fase 1 - Exploração Inicial e Prototipagem Experimental

## Contexto e Motivação
O tema central deste projeto é a habitação, um domínio crítico em Portugal marcado pelo aumento contínuo dos preços, pressão no arrendamento e dificuldades crescentes das famílias. O cenário atual é alarmante: o aumento da inflação tem contribuído para o surgimento de novos casos de sem-abrigo e Portugal ocupa posições preocupantes nos rankings europeus de exclusão habitacional.

Face à relevância social e económica destes fatores, este projeto foca-se na interseção entre a crise habitacional e a população em situação de sem-abrigo, procurando identificar padrões e relações através da visualização de dados.

## Metodologia
O tratamento de dados seguiu um pipeline estruturado:
1. **Recolha e Curadoria:** Dados da Pordata, INE, ENIPSSA e Idealista.
2. **Pré-processamento (Data Wrangling):** Limpeza manual de formatações inconsistentes e dados em falta ('x').
3. **Transformação:** Normalização dos valores pela população residente.
4. **Visualização:** Criação de Matrix Plots (Heatmaps) para análise espaciotemporal.

## Ferramentas Utilizadas
* **Python:** Para limpeza de dados e geração de gráficos.
* **Google Colab:** Ambiente de desenvolvimento de gráficos.
* **Excel:** Para triagem inicial.
* **RAWGraphs:** Para prototipagem rápida.

## Estrutura do Repositório
* `/data`: Contém os datasets originais e os processados.
* `/notebooks`: Código Python utilizado para gerar as visualizações.
* `/visualizations`: Imagens exportadas em alta resolução.
* `/report`: Relatórios em PDF.

## Visualizações
1. A Geografia da Exclusão
Visualização da Taxa de Sem-Abrigo por 10.000 Habitantes. 
[Preview](https://github.com/smonteiro461/Visualizacao_Informacao/blob/f9ad8fee93900fd515830d6d5ce283438d186053/visualizacoes/finais%20fase%201/1.Taxa%20de%20Sem-Abrigo%20por%2010.000%20Habitantes.png). 
*(Link para a imagem acima)*

3. Desigualdade na distribuição do rendimento
Visualização da desigualdade na distribuição do rendimento bruto declarado por distrito. 
[Preview](https://github.com/smonteiro461/Visualizacao_Informacao/blob/f9ad8fee93900fd515830d6d5ce283438d186053/visualizacoes/finais%20fase%201/2.Desigualdade%20na%20distribui%C3%A7%C3%A3o%20do%20rendimento%20bruto%20declarado%20dos%20agregados%20fiscais.png)
*(Link para a imagem acima)*

5. Poder de compra
Visualização do poder de compra por distrito.
[Preview](visualizations/heatmap_azul_final.png)
*(Link para a imagem acima)*


---
**Autores:** Sophia Pamella Rufina Ribeiro - 2024118280
Sofia Margarida de Sousa Monteiro - 2024112980
José Daniel Sottolano Velar - 

**Unidade Curricular:** Visualização de Informação 2025-26
