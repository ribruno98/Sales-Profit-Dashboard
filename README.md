# Sales-Profit-Dashboard

---

# Sales & Profit Dashboard (Power BI)

## Project Overview (Visão Geral do Projeto)
Este dashboard foi desenvolvido para analisar o desempenho financeiro de uma empresa de comércio. O objetivo é dar total visibilidade sobre o faturamento, os custos operacionais e, principalmente, a margem de lucro real por produto, região e representante.

---

## ETL & Data Cleaning (Power Query)
Os dados brutos de vendas foram tratados no **Power Query** para garantir relatórios precisos.
* **Principais ações:**
  * Correção de tipos de dados e remoção de erros.
  * Organização das colunas de texto (como Métodos de Pagamento e Categorias).
  * Limpeza de nomes de colunas para melhor leitura visual.

---

## Data Modeling & DAX (Modelação e Fórmulas)
Criei regras de negócio utilizando fórmulas em **DAX** para extrair os indicadores financeiros mais importantes.
* **Fórmula principal criada:**
  ```dax
  Lucro Total = [Faturamento] - [Custo Total]

  ---

# Dashboard
