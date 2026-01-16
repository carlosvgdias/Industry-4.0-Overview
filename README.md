📊 Overview – Industry 4.0 Dashboard
📌 Project Overview

This project presents an Industry 4.0 Executive Overview Dashboard, developed in Power BI, focused on industrial performance, production efficiency, maintenance reliability, and operational intelligence.

The dashboard simulates a real industrial environment using structured datasets and best practices in data modeling, KPI design, and visual storytelling, targeting decision-makers such as industrial managers, automation leaders, and data-driven executives.

🎯 Project Objectives

The main goals of this project are:

Provide a high-level operational overview of an industrial environment

Translate raw industrial data into actionable insights

Demonstrate Industry 4.0 concepts through data analytics

Apply professional Power BI modeling and visualization standards

Build a portfolio-ready project suitable for industrial analytics and automation companies

🧱 Data Modeling & Preparation
1. Data Cleaning & Transformation

All datasets were prepared using Power Query, applying the following steps:

Standardization of date formats

Creation of Year, Month, and Year-Month fields

Removal of null and inconsistent values

Alignment of numeric fields for aggregation (production, costs, downtime)

2. Calendar Table

A dedicated Calendar Table was created to ensure:

Correct time intelligence calculations

Monthly and yearly trend analysis

Proper relationship handling across fact tables

This table includes:

Date

Year

Month

Month Number

Year-Month (formatted for visuals)

🔗 Data Relationships

The data model follows a star schema, ensuring performance and clarity:

Fact tables: production, maintenance, costs

Dimension tables: calendar, plant/line, equipment

Relationships were configured as:

One-to-many (1:*)

Single-direction filtering to avoid ambiguity

Avoidance of many-to-many relationships

📐 KPI Design & DAX Measures

Key KPIs were created using DAX, focusing on industrial performance indicators:

Core KPIs

Total Production Output

Production Cost

Operational Cost

Maintenance Cost

Downtime (Hours)

Availability Rate

Efficiency Rate

OEE (Overall Equipment Effectiveness)

Time-Based Measures

Monthly Aggregations

Year-to-Date (YTD) Metrics

Trend Analysis Across Periods

Special attention was given to:

Correct filter context

Avoiding flat-line trends caused by date issues

Ensuring dynamic behavior with slicers

🖥️ Dashboard Structure
📄 Page 1 – Executive Overview

Purpose: High-level industrial performance snapshot

Includes:

KPI Cards with key metrics

Monthly trend line for production

Cost distribution visuals

Clean layout focused on readability and executive decision-making

Design principles:

Minimalism

Consistent spacing

Clear hierarchy of information

📄 Page 2 – Operational Analysis

Purpose: Detailed operational insights

Includes:

Production vs Cost comparison

Performance by plant / line

Downtime analysis

Interactive slicers for time and operational units

This page allows deeper analysis without overwhelming the executive overview.

📄 Page 3 – Performance & Efficiency

Purpose: Industry 4.0 performance indicators

Includes:

Efficiency and availability trends

OEE visualization

Comparative performance analysis across periods

Focus on continuous improvement metrics

🎨 Visual & UX Design Choices

Consistent color palette aligned with industrial/tech context

KPI Cards designed for fast interpretation

Reduced visual noise (gridlines, unnecessary labels removed)

Logical visual alignment using Power BI grid and snap features

All visuals were chosen to support storytelling, not just display data.

🧠 Key Challenges Solved

Flat-line charts caused by incorrect date relationships

Card positioning and alignment issues

Many-to-many relationship conflicts

Time intelligence measures returning identical values

Visual clutter impacting readability

Each issue was addressed using Power BI best practices.

🛠 Tools & Technologies

Power BI Desktop

DAX

Power Query (M)

Data Modeling (Star Schema)

Industry 4.0 KPI Concepts

🚀 Project Outcome

This dashboard demonstrates:

Strong understanding of industrial KPIs

Ability to structure and model complex datasets

Executive-level dashboard design

Practical application of Industry 4.0 analytics concepts

It is suitable for:

Portfolio presentation

Freelance proposals

Industrial analytics interviews

Demonstrations for automation and data-driven companies

📌 Next Steps (Optional Enhancements)

Integration with real-time IoT datasets

Predictive maintenance analytics

Alerting and threshold-based KPIs

Deployment via Power BI Service

👤 Author

📊 Overview – Industry 4.0 Dashboard
📌 Visão Geral do Projeto

Este projeto apresenta um Dashboard Executivo de Indústria 4.0, desenvolvido no Power BI, com foco em desempenho industrial, eficiência produtiva, confiabilidade da manutenção e inteligência operacional.

O dashboard simula um ambiente industrial real, aplicando boas práticas de modelagem de dados, construção de KPIs e visualização analítica, com linguagem clara para gestores, líderes industriais e tomadores de decisão.

🎯 Objetivos do Projeto

Os principais objetivos deste projeto são:

Fornecer uma visão executiva do desempenho industrial

Transformar dados operacionais em insights acionáveis

Demonstrar conceitos práticos de Indústria 4.0

Aplicar padrões profissionais de Power BI e DAX

Criar um projeto de portfólio voltado para empresas industriais e de automação

🧱 Preparação e Tratamento dos Dados
1. Limpeza e Transformação

Os dados foram tratados no Power Query, com os seguintes passos:

Padronização de formatos de data

Criação de colunas de Ano, Mês e Ano-Mês

Tratamento de valores nulos e inconsistentes

Ajuste de colunas numéricas para agregações corretas

2. Tabela Calendário

Foi criada uma Tabela Calendário dedicada, fundamental para:

Cálculos de inteligência de tempo

Análises mensais e anuais

Correto funcionamento de gráficos de tendência

A tabela contém:

Data

Ano

Mês

Número do Mês

Ano-Mês (formatado para visualizações)

🔗 Modelagem de Dados

O modelo foi estruturado em esquema estrela, garantindo desempenho e clareza:

Tabelas Fato: Produção, Custos, Manutenção

Tabelas Dimensão: Calendário, Planta/Linha, Equipamentos

Relacionamentos configurados como:

Um-para-muitos (1:*)

Direção única de filtro

Evitando relacionamentos muitos-para-muitos

📐 KPIs e Medidas em DAX

Foram criadas medidas estratégicas para análise industrial:

KPIs Principais

Produção Total

Custo de Produção

Custos Operacionais

Custo de Manutenção

Downtime (Horas Paradas)

Disponibilidade

Eficiência

OEE (Overall Equipment Effectiveness)

Análises Temporais

Totais Mensais

Análises Ano a Ano

Tendências ao longo do tempo

As medidas foram construídas com atenção especial ao contexto de filtro, evitando erros comuns como valores repetidos ou linhas retas em gráficos.

🖥️ Estrutura do Dashboard
📄 Página 1 – Visão Executiva

Objetivo: apresentar um panorama rápido e claro do desempenho industrial.

Contém:

Cartões de KPI com os principais indicadores

Gráfico de tendência mensal de produção

Análise de custos

Layout limpo e focado em tomada de decisão

📄 Página 2 – Análise Operacional

Objetivo: permitir análise detalhada da operação.

Contém:

Comparativos de Produção x Custos

Análise por planta, linha ou unidade

Análise de paradas e manutenção

Filtros interativos para exploração dos dados

📄 Página 3 – Eficiência e Performance

Objetivo: avaliar indicadores clássicos da Indústria 4.0.

Contém:

Tendência de eficiência e disponibilidade

Indicador de OEE

Comparações entre períodos

Suporte à melhoria contínua

🎨 Design e Experiência do Usuário

Paleta de cores com identidade industrial/tecnológica

Cartões de KPI focados em leitura rápida

Remoção de gridlines e ruídos visuais

Alinhamento e espaçamento padronizados

Cada visual foi escolhido para contar uma história, não apenas exibir números.

🧠 Principais Desafios Resolvidos

Gráficos com linha reta causados por erro de data

Problemas de alinhamento e movimentação de visuais

Conflitos de relacionamento muitos-para-muitos

Medidas temporais retornando valores fixos

Excesso de informação visual

Todos os desafios foram resolvidos com boas práticas do Power BI.

🛠 Ferramentas Utilizadas

Power BI Desktop

DAX

Power Query

Modelagem de Dados (Esquema Estrela)

Conceitos de KPIs Industriais / Indústria 4.0

🚀 Resultado do Projeto

Este projeto demonstra:

Visão analítica aplicada ao ambiente industrial

Capacidade de estruturar e modelar dados complexos

Design de dashboard em nível executivo

Aplicação prática de conceitos de Indústria 4.0

Ideal para:

Portfólio profissional

Apresentações comerciais

Entrevistas técnicas

Empresas de automação e análise industrial

📌 Próximos Passos (Evoluções Futuras)

Integração com dados reais de sensores (IoT)

Análise preditiva de falhas

Alertas e metas operacionais

Publicação no Power BI Service

👤 Autor

Carlos Vinícios Gonçalves Dias


