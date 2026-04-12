# Projeto de BI: Top 10 Spotify Brasil 🎧

Este projeto consiste num dashboard de Business Intelligence (BI) desenvolvido no **Power BI** para analisar as tendências, artistas e volumes de reprodução das músicas mais ouvidas no Spotify Brasil.

## 📂 Estrutura do Projeto

O repositório contém os seguintes arquivos principais:

* **`top10_spotify_brasil.pbix`**: Arquivo principal do Power BI contendo o dashboard interativo.
* **`dados.csv`**: Base de dados utilizada para alimentar o relatório (contém posições, nomes das músicas, artistas, dias na lista e total de plays).
* **Imagens (`dashboard_1.png`, `dashboard_2.png`, etc.)**: Demonstrações visuais das páginas do relatório.

## 📊 Funcionalidades do Dashboard

O relatório permite visualizar:
1.  **Ranking de Popularidade:** As músicas com maior número de plays totais.
2.  **Consistência dos Artistas:** Análise de "dias na lista" para identificar hits duradouros.
3.  **Métricas de Desempenho:** Total de plays acumulados e análise por data de coleta.
4.  **Top Artistas:** Identificação dos artistas que mais dominam o top 10.

## 🚀 Como Executar o Projeto

### Pré-requisitos
* Ter o [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) instalado.

### Passo a Passo
1.  Faça o download ou clone este repositório.
2.  Abra o arquivo `top10_spotify_brasil.pbix` no Power BI Desktop.
3.  **Importante (Vínculo de Dados):** Caso o Power BI exiba um erro de "Fonte de dados não encontrada", siga estes passos:
    * Vá ao menu **Página Inicial** > **Transformar Dados** > **Configurações da fonte de dados**.
    * Clique em **Alterar Fonte**.
    * Selecione o caminho local onde você salvou o arquivo `dados.csv`.
    * Clique em **Aplicar Alterações**.

## 🛠️ Tecnologias Utilizadas
* **Power BI**: Construção de gráficos e ETL (Power Query).
* **CSV**: Fonte de dados estruturada.

---
*Projeto desenvolvido por Millena Manuela como trabalho final de BI.*
