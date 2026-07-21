flowchart LR
    %% Estilos e Cores para Organização Visual
    classDef root fill:#1e293b,stroke:#0f172a,stroke-width:2px,color:#fff,font-weight:bold;
    classDef parte fill:#0284c7,stroke:#0369a1,stroke-width:2px,color:#fff,font-weight:bold;
    classDef sub fill:#334155,stroke:#1e293b,stroke-width:1px,color:#f8fafc;

    ROOT(("📘 MANUAL DE GESTÃO<br/>E CRESCIMENTO")):::root

    %% INTRODUÇÃO
    ROOT --> INTRO["🎯 INTRODUÇÃO"]:::parte
    INTRO --> I1["• Objetivo do Manual"]:::sub
    INTRO --> I2["• Como Utilizar"]:::sub
    INTRO --> I3["• Processo de Revisão"]:::sub
    INTRO --> I4["• Melhoria Contínua"]:::sub

    %% PARTE I
    ROOT --> P1["🏛️ PARTE I - IDENTIDADE"]:::parte
    P1 --> P1_1["1. História (Origem / Evolução / Marcos)"]:::sub
    P1 --> P1_2["2. Visão, Missão e Valores"]:::sub
    P1 --> P1_3["3. Cultura & Filosofia da Empresa"]:::sub

    %% PARTE II
    ROOT --> P2["💼 PARTE II - O NEGÓCIO"]:::parte
    P2 --> P2_1["7. Modelo de Negócio<br/><i>(KPIs: Receita, Ticket Médio, LTV)</i>"]:::sub
    P2 --> P2_2["8. Mercado (ICP / Personas / Concorrência)<br/><i>(KPIs: Quota, CAC, Retenção)</i>"]:::sub
    P2 --> P2_3["9. Serviços (Atuais / Estratégicos)<br/><i>(KPIs: Margem, Receita)</i>"]:::sub

    %% PARTE III
    ROOT --> P3["🚀 PARTE III - ESTRATÉGIA"]:::parte
    P3 --> P3_1["10. Diagnóstico Atual (SWOT)"]:::sub
    P3 --> P3_2["11. Objetivos (1, 3, 5 e 10 Anos)"]:::sub
    P3 --> P3_3["12. Modelo de Crescimento<br/>• Mais Clientes (Leads, Conversão)<br/>• Ticket Médio & Retenção<br/>• Margem Bruta/Líquida"]:::sub
    P3 --> P3_4["13. Escalabilidade (Gargalos, Delegação, IA)"]:::sub

    %% PARTE IV & V
    ROOT --> P4["📣 PARTE IV - MARKETING"]:::parte
    P4 --> P4_1["14. Estratégia de Mkt (SEO, Ads, Redes)<br/><i>(KPIs: Visits, CPL, CAC, ROAS, ROI)</i>"]:::sub

    ROOT --> P5["🤝 PARTE V - COMERCIAL"]:::parte
    P5 --> P5_1["15. Estratégia Comercial (CRM, Funil, Pós-venda)<br/><i>(KPIs: Propostas, Taxa Aprovação, Pipeline)</i>"]:::sub

    %% PARTE VI & VII
    ROOT --> P6["⚙️ PARTE VI - OPERAÇÕES"]:::parte
    P6 --> P6_1["16. Workflow Geral (Lead ➔ Entrega)"]:::sub
    P6 --> P6_2["17. SOP - Procedimentos Operacionais"]:::sub
    P6 --> P6_3["18. Gestão de Projetos (Qualidade, Prazos)"]:::sub

    ROOT --> P7["📊 PARTE VII - FINANÇAS"]:::parte
    P7 --> P7_1["19. Gestão Financeira (Receita, Cash Flow)"]:::sub
    P7 --> P7_2["20. Política Financeira (Salários, Lucros)"]:::sub

    %% PARTE VIII, IX, X, XI, XII
    ROOT --> P8["🤖 PARTE VIII - TECNOLOGIA & IA"]:::parte
    P8 --> P8_1["21-23. Ferramentas, IA & Automatizações"]:::sub

    ROOT --> P9["👥 PARTE IX - GOVERNAÇÃO"]:::parte
    P9 --> P9_1["24-27. Organograma, Societário & Decisão"]:::sub

    ROOT --> P10["📈 PARTE X - DASHBOARD EXECUTIVO"]:::parte
    P10 --> P10_1["Métricas de Crescimento, Mkt, Vendas & Finanças"]:::sub

    ROOT --> P11["📅 PARTE XI - PLANEAMENTO"]:::parte
    P11 --> P11_1["Planos 90 Dias / Anual / OKRs"]:::sub

    ROOT --> P12["📚 PARTE XII - BASE DE CONHECIMENTO"]:::parte
    P12 --> P12_1["Templates, Checklists, SOPs & Contratos"]:::sub
