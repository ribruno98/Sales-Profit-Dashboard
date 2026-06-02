# Sales-Profit-Dashboard

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
 ### Páginas do Dashboard

#### 1. Visão Geral
<img width="1875" height="1053" alt="image" src="https://github.com/user-attachments/assets/47488890-a0ed-4736-9fc6-5322076e2515" />

#### 2. Análise de Produtos
<img width="1874" height="1052" alt="image" src="https://github.com/user-attachments/assets/b928d4c7-6266-4f3d-baf6-dee5c835c028" />

#### 3. Análise de Lucro
<img width="1876" height="1055" alt="image" src="https://github.com/user-attachments/assets/5e0c8696-b501-4ed8-9213-c20554678104" />

 
