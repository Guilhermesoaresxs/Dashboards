🚀 A transparência e o monitoramento em tempo real são os verdadeiros motores da eficiência operacional na logística e manufatura. Apresento o Painel de Separação desenvolvido para a operação P4705 na AMBEV Jacareí (Transportador de Caixa L503/L504).

Esta ferramenta de **Gestão à Vista** foi projetada para dar controle total à equipe de operação, transformando dados brutos em ações rápidas e precisas.

Principais funcionalidades e métricas do painel:

* **Monitoramento de KPIs em Tempo Real:** Acompanhamento instantâneo dos pedidos do turno (OPs), volume de itens solicitados versus separados e a produtividade da equipe em itens por hora.


* **Controle por Zonas de Separação:** Rastreamento do progresso detalhado de áreas específicas, como Módulos (Ruas A, B, C e D) e Conjuntos (Elétricos e Mecânicos).


* **Gestão de Status e Operadores:** Identificação clara de quem está operando e do status de cada lote, categorizado como "Pendente", "Concluído", "Em Separação" ou "Divergência".


* **Módulo de Alertas e Exceções:** Visibilidade imediata de gargalos operacionais, alertando a equipe sobre pedidos bloqueados (RGO), OPs atrasadas no Cockpit, estoque insuficiente ou registros pendentes no SYNECO.


* **Integração de Dados:** O sistema unifica e lê fontes de diferentes planilhas da operação, incluindo MODULOS-CAIXA, CONJUNTOS mecânica/elétrica, RGO e COCKPIT.



A tecnologia deve estar a serviço de quem faz a operação acontecer, garantindo que o time foque no que realmente importa: produtividade e resolução ágil de problemas.

---

## 📊 Painel de Separação · Gestão à Vista (P4705)

Este repositório contém a interface de um painel de monitoramento (dashboard) voltado para a **Gestão à Vista** de processos logísticos de separação, especificamente para o escopo do P4705 (AMBEV Jacareí - Transportador de Caixa L503/L504). O projeto consolida múltiplas fontes de dados em uma única tela de alta legibilidade para chãos de fábrica e centros de distribuição.

### Funcionalidades do Projeto

* **Indicadores de Desempenho (KPIs):** Cálculo em tempo real da produtividade (itens/hora) e do balanço de itens solicitados versus separados.


* **Visualização de Progresso:** Gráfico de rosca (donut chart) que ilustra a porcentagem geral de conclusão do turno.


* **Mapeamento de Filas e Zonas:** Tabela interativa que lista o status de separação por ruas de Módulos (A, B, C, D) e Conjuntos Mecânicos/Elétricos.


* **Tratamento de Exceções:** Painel de alertas que captura e exibe gargalos críticos, como falta de estoque, bloqueios e falhas de registro (ex: "SYNECO pendente").


* **Regras de Negócio Integradas:** O script categoriza o status automaticamente: materiais "Pendente" para separar, "Em Separação" para itens sem pallet, "Concluído" para liberados ou com pallet, e "Divergência" para materiais bloqueados.


* **Suporte a Temas:** Alternância nativa entre `Claro / Escuro` para melhor visualização em monitores industriais ou ambientes com variação de luminosidade.



### Fonte de Dados

A arquitetura de dados consome informações diretamente das planilhas operacionais do projeto, abrangendo os fluxos de `MODULOS-CAIXA`, `CONJUNTOS mecânica/elétrica`, `RGO` e `COCKPIT`.
