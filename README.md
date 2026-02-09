# 📊 Análise Comercial e Pipeline de Vendas – Power BI

Projeto de análise comercial e pipeline de vendas, desenvolvido em **Power BI**, utilizando dados armazenados em **SQL Server**.  
O dashboard permite acompanhar desempenho de vendas, funil comercial, metas, conversões e evolução temporal, com foco em **apoio à tomada de decisão**.

---

## 🎯 Objetivo do Projeto
Transformar dados brutos de vendas em **insights claros e acionáveis**, permitindo:

- Avaliar desempenho comercial
- Identificar gargalos no funil de vendas
- Acompanhar metas e resultados
- Comparar períodos (YoY)
- Analisar performance por vendedor, produto e país

---

## 📈 Principais Análises e KPIs

- 💰 Valor total de vendas  
- 🎯 Meta anual x realizado  
- 🔄 Taxa de conversão por estágio  
- 🧩 Funil comercial (Lead → Pipeline → Commit → Closed)  
- 📅 Evolução mensal, trimestral e semanal  
- 🌍 Análise por país  
- 👤 Desempenho por vendedor  
- 📦 Análise por produto  

---

## 🛠️ Tecnologias Utilizadas

- Power BI Desktop  
- SQL Server  
- DAX  
- Excel (dados de origem)  
- Modelagem dimensional  
- Git & GitHub  

---

🧱 Arquitetura e Pipeline de Dados

Todo o processo de dados deste projeto foi desenvolvido de ponta a ponta. Os dados de origem em Excel passaram por etapas de organização e tratamento antes de serem carregados em um banco de dados relacional no SQL Server, criado especificamente para este estudo.

O banco de dados foi modelado com definição de tabelas, chaves primárias e estrangeiras, relacionamentos e integridade referencial, seguindo boas práticas de modelagem para análise. Após essa etapa, os dados foram integrados ao Power BI, onde também foi realizado tratamento adicional, criação de medidas em DAX e ajustes no modelo semântico para garantir consistência e performance nas análises.

Essa abordagem permitiu simular um cenário real de ambiente corporativo, desde a estruturação da base de dados até a visualização final dos indicadores estratégicos.

---


## 📸 Preview do Dashboard
> *(imagens ilustrativas)*

![Visão Geral](docs/Visão_Comercial.png)
![Performance](docs/Performance.png)
![Funil Comercial](docs/Processo_de_Vendas.png)
---

Estudo de Caso – Análise Comercial e Tomada de Decisão Executiva
[Relatório Executivo de Performance Comercial](docs/Projeto.Análise.Comercial.pdf)

---
## ▶️ Como visualizar o dashboard
1. Faça o download do arquivo `.pbix` na pasta `powerbi`
2. Abra o arquivo no **Power BI Desktop**
3. Caso necessário, ajuste o caminho da fonte de dados SQL

---

## 📌 Observações
Os dados utilizados neste projeto são **fictícios** e têm finalidade **educacional e demonstrativa**.
