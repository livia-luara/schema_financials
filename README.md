# Desafio de Construção de Modelo Star Schema

O desafio consistiu em transformar a tabela única de dados fictícios financeiros em um modelo otimizado, com tabelas fato e dimensões separadas. Todo o processo foi realizado no **Power BI Desktop**, utilizando:

- Criação de **tabelas dimensão** e **tabela fato**.
- Utilização de **DAX** para criação da tabela calendário e cálculos.
- Organização do modelo de dados e configuração de relacionamentos.

---

## 📂 Tabelas Criadas

| Tabela               | Descrição |
|---------------------|-------------|
| **Financials_origem** | Backup da tabela original (oculta no modelo) |
| **D_Produtos** | Tabela dimensão com informações e métricas de produtos |
| **D_Produtos_Detalhes** | Tabela dimensão com detalhes de preços, unidades vendidas e faixas de desconto |
| **D_Descontos** | Tabela dimensão com informações de descontos |
| **D_Detalhes** | Tabela com demais informações de vendas não contempladas nas outras dimensões |
| **D_Calendário** | Tabela calendário criada via **DAX** usando a função `CALENDAR()` |
| **F_Vendas** | Tabela fato com informações consolidadas de vendas, produtos, preços, lucros e datas |

---

## 🛠️ Funcionalidades e Etapas

- Criação de tabelas por agrupamento e seleção de colunas relevantes.
- Criação de colunas calculadas usando **DAX**.
- Criação da **tabela calendário** via DAX com a função `CALENDAR()`.
- Aplicação do conceito de **Star Schema** para otimização de análises.
- Configuração de relacionamentos entre tabelas.

---

## 🧰 Ferramentas Utilizadas

- Power BI Desktop
- DAX (Data Analysis Expressions)
- GitHub para publicação

