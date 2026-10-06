# 📦 WMS & PCP Command Center Dashboard

## 📖 Sobre o Projeto
Este projeto apresenta o design e a modelação de dados para um dashboard analítico focado no Planeamento e Controlo da Produção (PCP) e na gestão espacial de um armazém (WMS). 

O principal objetivo desta ferramenta é fornecer total visibilidade sobre o endereçamento logístico, rastrear a diversidade de SKUs (Stock Keeping Units) e prevenir erros críticos de análise de dados, como a agregação indevida de diferentes unidades de medida (ex: somar Quilos com Metros ou Peças).
<img width="1538" height="679" alt="image" src="https://github.com/user-attachments/assets/6c7e3ff3-f86b-4c59-a315-587c84bafeac" />


## ✨ Principais Funcionalidades
*   **Identificação de Gargalos de Endereçamento:** Visualização rápida das localizações (posições no armazém) com maior concentração e variedade de itens, ajudando a prevenir a sobrelotação física e a confusão no *picking*.
*   **Auditoria de Unidades de Medida (U.M.):** Segmentação rigorosa do inventário pela sua natureza de medição, garantindo a integridade dos KPIs.
*   **Métricas de Alto Nível:** Monitorização em tempo real do Total de SKUs e da taxa de ocupação dos endereços do armazém.
*   **Design 'Clean Tech':** Interface de utilizador (UI) moderna, desenvolvida com uma estética "White Futuristic", garantindo clareza visual e foco nos dados essenciais para as equipas de operação.

## 🛠️ Tecnologias e Conceitos
*   **Análise de Dados:** Python (Pandas, Numpy)
*   **Visualização de Dados:** Matplotlib (Mockup) / Estruturado para Power BI, Tableau ou Dash.
*   **Conceitos de Negócio:** Logística, PCP, Supply Chain Analytics.

## 📂 Estrutura dos Dados
O modelo de dados consome informações baseadas em: `Nº do item` (SKU), `Descrição`, `Código da posição` (Endereçamento físico), `Quantidade disponível` e `Unidade de medida de stock`.
