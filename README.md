# 🚀 Projeto ERP Universal - Inteligência de Negócios e Governança Corporativa

Este repositório contém a documentação de arquitetura de um **ERP Multifuncional** integrado a uma solução avançada de Business Intelligence no Power BI. O sistema foi projetado para centralizar as operações e unificar a tomada de decisão em três grandes pilares de mercado: **Industrial, Varejo e Serviço**.

O core business inicial do projeto é uma **indústria de pão de queijo** focada em expansão escalável.

---

## 📈 A Jornada de Evolução do Negócio (2025 - 2026)

### 🔹 Fase 1 (2025): Operação Manual e Sustentável
Em 2025, a fábrica iniciou suas atividades com foco em sustentabilidade e validação de produto. O processo produtivo era **totalmente manual e limitado**, gerando um teto produtivo baixo e um faturamento anual de **R\$ 28,08 Mil**. Durante todo esse ciclo, a empresa operou de forma segura dentro das regras fiscais do **MEI (Microempreendedor Individual)**.

### 🔹 Fase 2 (2026): A Virada de Chave para a Automação
Em janeiro de 2026, a empresa implementou uma transformação radical: a **automação completa dos processes fabris**. A introdução de maquinários industriais eliminou os gargalos produtivos. Como consequência direta, a capacidade de entrega multiplicou-se e o faturamento escalou rapidamente para **R\$ 265,68 Mil**, fazendo com que a empresa **superasse com folga a meta anual de crescimento estipulada pelo CEO**.

---

## 🛡️ Inteligência Fiscal e Transição de Regime (MEI para ME)

O ERP Universal foi programado para monitorar a saúde tributária da empresa em todas as frentes. O modelo de dados prevê e executes a **mudança automatizada de MEI para ME (Microempresa)** no Simples Nacional. 

Através de motores de cálculo dinâmicos em DAX, o sistema cruza o faturamento acumulado e dispara alarmes visuais automáticos:
* **Em 2025:** O painel manteve o status de conformidade dentro do teto de R\$ 81 mil.
* **Na transição para 2026:** Com a explosão do faturamento fabril, o sistema detectou o estouro do limite do MEI, acionou o alerta fiscal e recalculou a nova margem de segurança para o teto de **R\$ 4,8 Milhões** do Simples Nacional, mostrando em tempo real o saldo restante para o planejamento tributário estratégico (atualmente com **R\$ 4,53 Mi** livres para expansão).

---

## 📊 Mapa Visual do Fluxo (Pipeline de Dados)

```text
[ 1. FONTES DE DADOS (Excel) ]
       │
       ├── 📁 08_Vendas (Movimentação)
       ├── 📁 02_Cad_Produto (Cadastro Técnico)
       ├── 📁 14_Parametros_RH (Mão de Obra)
       └── 📁 10_Investimentos_Equipamentos (Ativos)
       │
       ▼
[ 2. CAMADA DE ENGENHARIA (Power Query) ]
       │
       ├── ⚙️ Ingestão e Conexão Automatizada
       ├── ⚙️ Higienização (Tratamento de Nulos)
       └── ⚙️ Padronização Textual (Ex: Correção de "Industrial")
       │
       ▼
[ 3. MODELAGEM E ESTRUTURA (Star Schema) ]
       │
       ├── 🔗 Relacionamentos Cruzados (Fatos e Dimensões)
       └── 🔗 Chaves Primárias e Estratégicas (IDs)
       │
       ▼
[ 4. INTELIGÊNCIA DE CÁLCULO (DAX Avançado) ]
       │
       ├── 🧮 Isolamento de Contexto (KEEPFILTERS)
       ├── 🧮 Simulador Fiscal Dinâmico (Teto Simples Nacional)
       └── 🧮 Calibrador de Metas (%_Meta_CEO)
       │
       ▼
[ 5. ENTREGA EXECUTIVA (Dashboard Front-End) ]
       │
       ├── 📊 Gráficos por Regional de Faturamento
       ├── 📉 Cartão de Faturamento Realizado (265,68 K)
       ├── 🛡️ Alerta de Saldo Fiscal Restante (4,53 Mi)
       └── 🧠 Matriz Consultiva Inteligente (Status de Meta)
```

## 🧠 Tomada de Decisão Baseada em Dados: A Matriz Consultiva

O grande diferencial deste projeto é a sua capacidade de não apenas mostrar o passado, mas indicar o futuro. O ERP foi desenhado para **responder perguntas de negócio críticas de todos os departamentos da empresa** (Financeiro, Comercial, RH, Produção e Logística).

O banco de dados alimenta de forma contínua uma **Matriz Consultiva** inteligente. Essa matriz analisa os cruzamentos de dados e **sugere ações estratégicas automáticas** na tela para o usuário, indicando exatamente o que deve ser feito em cenários como:
* Alocação de investimentos em maquinários por setor.
* Ajuste de preços praticados por canal de venda.
* Remanejamento de equipes com base no custo de mão de obra do RH.
* Direcionamento de esforços e capital para a expansão comercial em bairros e regionais de maior volume.

---

## 🛠️ Recursos Técnicos Utilizados
* **Modelagem de Dados:** Star Schema com tabelas fato e dimensões unificadas no Power Query.
* **Linguagem DAX Avançada:** Criação de parâmetros dinâmicos de simulação (`What-if`), filtros virtuais isolados (`KEEPFILTERS`) e inteligência de tempo dinâmica.
* **Layout Executivo:** Design voltado para a experiência do usuário (UX/UI), focado na velocidade de leitura da diretoria (Foco no CEO).
# ERP-Universal-PowerBI
