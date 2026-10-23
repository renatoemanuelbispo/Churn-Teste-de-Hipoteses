Repositório de Ativos Visuais (Gráficos do Projeto)

Esta pasta armazena todos os gráficos exportados durante a Análise Exploratória de Dados (EDA) e Segmentação RFM no Google Colab. Essas imagens são referenciadas na documentação principal do projeto (`README.md`).

Lista de Arquivos e Descrições

1. **`distribuicao_categorias.png`**  
   - **Tipo:** Gráfico de Barras (`sns.countplot`).  
   - **Descrição:** Mostra a contagem total de pedidos agrupados por categoria visitada pelo cliente (Eletrônicos, Moda, Casa, Outros).

2. **`histograma_monetario.png`**  
   - **Tipo:** Histograma com Curva de Densidade (`sns.histplot`).  
   - **Descrição:** Ilustra a distribuição do valor financeiro acumulado (Métrica Monetária) por cliente, destacando a assimetria do gasto.

3. **`distribuicao_r_score.png`**  
   - **Tipo:** Gráfico de Barras (`sns.countplot`).  
   - **Descrição:** Exibe o volume de clientes em cada nota do score de Recência (R_Score de 1 a 4), onde a nota 4 representa os clientes mais recentes.

4. **`heatmap_correlacao.png`**  
   - **Tipo:** Mapa de Calor de Correlação (`sns.heatmap`).  
   - **Descrição:** Apresenta a matriz de correlação linear de Pearson entre as métricas de Recência, Frequência, Monetário e a variável de Churn.

5. **`gasto_medio_churn.png`**  
   - **Tipo:** Gráfico de Barras Comparativo (`sns.barplot`).  
   - **Descrição:** Compara visualmente o ticket médio gasto entre o grupo de clientes Ativos (0) e o grupo em Churn (1).
