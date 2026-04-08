# Projeto_Dados
Projeto em Dados para utilização de diversas ferramentos de tratamento e visualização.

# 📊 Sales Analytics Pipeline: SQL + Python + Power BI

Este projeto demonstra um pipeline de dados completo, desde a extração e tratamento até a visualização estratégica de indicadores de vendas. O objetivo principal foi transformar dados brutos em insights sobre faturamento, lucratividade e eficiência operacional.

![Dashboard de Vendas](NOME_DA_SUA_FOTO.png) 
> *Substitua 'NOME_DA_SUA_FOTO.png' pelo nome exato do arquivo de imagem que você subiu no GitHub.*

## 🛠️ Tecnologias Utilizadas
* **SQL:** Extração de dados das bases relacionais.
* **Python (Pandas):** Limpeza de dados, tratamento de valores ausentes e engenharia de atributos (Cálculo antecipado de faturamento).
* **Power BI & DAX:** Modelagem de dados (Star Schema) e criação de medidas de performance.

## 📈 Indicadores de Negócio (KPIs)
O dashboard responde a perguntas críticas para a tomada de decisão:
* **Faturamento Total:** Visão macro da saúde financeira.
* **TKM (Ticket Médio):** Identificação do valor médio por transação para estratégias de upsell.
* **Performance por Categoria:** Análise de quais produtos tracionam o negócio.
* **Análise por Unidade/Gerente:** Avaliação de performance regionalizada.

## 📂 Estrutura do Repositório
* `/data`: Bases de dados utilizadas.
* `/scripts`: Jupyter Notebook com o processo de ETL em Python.
* `/dashboard`: Arquivo .pbix para visualização no Power BI Desktop.

## 💡 Diferencial Técnico
Diferente de uma análise feita apenas no Power BI, este projeto utiliza **Python** para o tratamento pesado dos dados. Isso garante:
1. **Escalabilidade:** O pipeline pode processar volumes maiores de dados.
2. **Performance:** O modelo no Power BI fica mais leve, pois os cálculos de coluna foram processados na origem.

