# 🛡️ Observatório Nacional de Segurança Pública - Brasil

![Nome Alternativo](nome-da-imagem.png)
<img width="1364" height="744" alt="Captura de tela 2026-02-18 152118" src="https://github.com/user-attachments/assets/92573d47-c8bc-4afa-a7fe-b7e1d5eb58b5" />

## 📊 Sobre o Projeto
Este dashboard foi desenvolvido para consolidar e analisar os indicadores de criminalidade em todo o território brasileiro. O principal desafio foi a **Engenharia de Dados**: transformar 27 ficheiros distintos (um para cada unidade federativa) numa base única, coesa e otimizada para análise de alta performance.

Os dados são provenientes do **Sinesp (Sistema Nacional de Informações de Segurança Pública)** do Ministério da Justiça e Segurança Pública.

## 🛠️ Tecnologias e Competências Utilizadas
- **Power BI / DAX:** Criação de métricas de acumulado, médias mensais e rankings dinâmicos.
- **Power Query (ETL):** Consolidação de 27 tabelas (unificação de abas/ficheiros) e limpeza de dados.
- **Tratamento de Big Data:** Manipulação de um dataset com aproximadamente **300.000 registos**.
- **Data Viz:** Aplicação de *Dark Mode*, Matrizes de Calor (Heatmaps) e Treemaps para análise de proporção regional.

## 📈 Principais Insights do Dashboard
1. **Análise Temporal:** Identificação de picos de ocorrências ao longo dos meses para entender a sazonalidade da violência.
2. **Ranking de Criticidade:** Filtro *Top N* para destacar os 10 municípios com maior volume de vítimas.
3. **Distribuição Regional:** Visualização clara de como a criminalidade se distribui entre as regiões Norte, Nordeste, Sudeste, Sul e Centro-Oeste.
4. **Matriz de Sazonalidade:** Cruzamento de Estados vs. Meses com formatação condicional (gradiente) para deteção rápida de anomalias.

## 🚀 Como visualizar
1. Descarregue o ficheiro `.pbix` na pasta `/dashboard`.
2. O ficheiro de dados consolidado está disponível na pasta `/data`.
