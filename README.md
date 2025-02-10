# Análise de Vendas Globais - Power BI  

Este repositório contém um dashboard em Power BI focado na análise de métricas de vendas globais. A base de dados utilizada, **vendas-globais.csv**, oferece informações sobre pedidos, categorias de produtos, prioridade de entrega, descontos e lucros. O arquivo principal do Power BI, **vendas-globais.pbix**, apresenta visualizações interativas para explorar insights sobre o desempenho das vendas globais.

---

## Objetivo do Projeto  

Os relatórios estão divididos em 5 visões principais:  
- **Visão Geral das Vendas**  
- **Visão por Categoria de Produto**  
- **Visão por País e Prioridade de Entrega**  
- **Visão de Descontos por Subcategoria de Produto**  
- **Visão Geográfica de Média de Valor de Venda**  

Para cada visão, apresentamos variáveis, gráficos e medidas que fornecem análises completas sobre o valor total vendido, distribuição por categorias, prioridades de entrega e padrões geográficos.

---

## Objetivos das Análises  

- **Monitoramento de Vendas:** Acompanhar o desempenho das vendas ao longo do tempo, identificando tendências sazonais.  
- **Segmentação por Categoria:** Explorar o desempenho de diferentes categorias de produtos para ajustar estratégias de marketing.  
- **Análise de Prioridade de Entrega:** Observar como a prioridade de entrega impacta as vendas em diferentes países.  
- **Avaliação de Descontos:** Analisar o impacto dos descontos nas vendas por subcategoria de produto.  
- **Mapeamento Geográfico:** Identificar os países com maior média de valor de venda para direcionar esforços comerciais.  

---

## Visões do Dashboard  

### 1. Visão Geral das Vendas  
**Objetivo:** Proporcionar uma visão consolidada do valor total vendido e da quantidade de vendas.  
**Métricas Principais:**  
- Valor Total Vendido: Soma de todas as vendas.  
- Quantidade de Vendas: Total de unidades vendidas.  
- Lucro Total: Soma dos lucros gerados.  
- Filtros: Análise por ano, segmento e país.  

---

### 2. Visão por Categoria de Produto  
**Objetivo:** Explorar o desempenho das vendas por categoria de produto.  
**Métricas Principais:**  
- Valor Total Vendido por Categoria: Distribuição de vendas entre categorias (ex.: Eletrônicos, Luxo).  
- Ticket Médio por Categoria: Média de valor gasto por transação em cada categoria.  
- Filtros: Segmentação por região e país.  

---

### 3. Visão por País e Prioridade de Entrega  
**Objetivo:** Analisar como a prioridade de entrega influencia as vendas em diferentes países.  
**Métricas Principais:**  
- Vendas por País: Total de vendas realizadas em cada país.  
- Distribuição por Prioridade: Percentual de vendas com prioridade alta, média ou baixa.  
- Países com Maior Volume de Vendas: Ranking dos países com maior número de vendas.  

---

### 4. Visão de Descontos por Subcategoria de Produto  
**Objetivo:** Avaliar o impacto dos descontos nas vendas por subcategoria de produto.  
**Métricas Principais:**  
- Média de Desconto por Subcategoria: Comparação de descontos aplicados em diferentes subcategorias.  
- Relação entre Desconto e Volume de Vendas: Correlação entre descontos e aumento nas vendas.  
- Filtros: Análise por categoria e país.  

---

### 5. Visão Geográfica de Média de Valor de Venda  
**Objetivo:** Mapear os países com maior média de valor de venda.  
**Métricas Principais:**  
- Média de Valor de Venda por País: Visualização geográfica dos países com maior ticket médio.  
- Países Premium: Identificação de mercados com maior valor agregado.  
- Filtros: Segmentação por ano e categoria.  

---

## Principais Insights de Dados  

| **Insight**                              | **Descrição**                                                                 |
|------------------------------------------|-------------------------------------------------------------------------------|
| **Distribuição de Vendas por Categoria** | A categoria **Eletrônicos** liderou em volume de vendas, enquanto a categoria **Luxo** apresentou o maior ticket médio por transação. |
| **Prioridade de Entrega**                | Países como **Estados Unidos** e **Alemanha** concentraram **60% das vendas com prioridade alta**, indicando uma demanda significativa por entregas rápidas. |
| **Impacto de Descontos**                 | Subcategorias como **Acessórios Tecnológicos** tiveram uma média de desconto de **12%**, possivelmente para incentivar vendas complementares. |
| **Países Premium**                       | Os países com maior média de valor de venda foram **Austrália** e **Suíça**, com valores médios superiores a **US$ 1.500 por transação**. |
| **Tendências Temporais**                 | As vendas aumentaram significativamente no último trimestre de cada ano, sugerindo um impacto positivo das campanhas de fim de ano. |

---

## Estrutura do Projeto  

- **vendas-globais.pbix:** Arquivo principal do Power BI com as 5 visões detalhadas.  
- **vendas-globais.csv:** Base de dados utilizada para as análises.  

---

## Como Utilizar  

1. **Clone este repositório:**  
   ```bash  
   git clone https://github.com/seu-usuario/dashboard-vendas-globais
   ```

2. **Pré-requisitos:**  
   - Instale o [Power BI Desktop](https://powerbi.microsoft.com/).  
   - Certifique-se de ter acesso ao arquivo **vendas_globais.csv**.  

3. **Abrindo o Arquivo:**  
   - Baixe o arquivo **Dashboard-Vendas-Globais.pbix** e abra-o no Power BI Desktop.  
   - Conecte o arquivo **vendas_globais.csv** ao Power BI caso necessário.  

4. **Exploração do Dashboard:**  
   - Utilize os filtros e segmentadores para personalizar as análises.  

---

## Contribuição  

Contribuições são bem-vindas! Siga os passos abaixo:  
1. Faça um fork deste repositório.  
2. Crie uma branch com suas alterações:  
   ```bash  
   git checkout -b feature/nova-funcionalidade  
   ```  
3. Envie suas alterações:  
   ```bash  
   git push origin feature/nova-funcionalidade  
   ```  
4. Abra um pull request explicando suas modificações.  

---

## Contato  

- **LinkedIn:** [Rafael Santos](https://www.linkedin.com/in/rafaelsantosti/)  
- **Portfólio:** [GitHub](https://github.com/knotheadmetal)  
- **E-mail:** [rafaelsantosti@outlook.com](mailto:rafaelsantosti@outlook.com)  
