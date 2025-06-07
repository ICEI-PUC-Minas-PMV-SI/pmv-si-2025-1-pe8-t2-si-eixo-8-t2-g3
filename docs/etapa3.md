# ETAPA 3

## 12	CONEXÃO COM O PLANO DE IC E PLANEJAMENTO DA SOLUÇÃO

• Como a disponibilidade de equipe e materiais impacta o cronograma?<br/>
•	Quais são os principais fatores que influenciam a priorização das obras na Garonce Soluções Fotovoltaicas?<br/>
•	Quais desafios atuais na gestão de obras precisam ser superados?<br/>
•	Quais tecnologias podem automatizar e melhorar o processo?<br/>
•	Como prever e mitigar possíveis atrasos?<br/>

### Dados Críticos:

•	Status das obras (não iniciadas, em andamento, finalizadas)<br/>
•	Cronogramas e prazos contratuais<br/>
•	Localização e logística das obras<br/>

**Processo atual**: Entrada de demandas e acompanhamento de obras via planilhas Excel, com baixa automação, visibilidade e padronização.<br/>

**Processos a resolver**:
•	Cadastro estruturado das obras a serem executadas. <br/>
•	Monitoramento em tempo real do status das obras<br/>
•	Geração de alertas e relatórios automáticos<br/>

**Funcionalidades iniciais a serem desenvolvidas** 

•	Módulo de cadastro de obras e demandas (Forms/Planner integrados).<br/>

•	Visão Kanban do pipeline de projetos (status: “novo”, “em execução”, “concluído”).<br/>

•	Dashboard inicial com KPIs principais (número de obras por status, prazos críticos).<br/>

### Quadro-resumo:

![Quadro Resumo](img/quadro.png)

## 13	LEVANTAMENTO DE REQUISITOS E MODELAGEM INICIAL

**Proprietário**, quero cadastrar uma nova obra com dados completos (cliente, localização, prazo), para iniciar o planejamento.<br/>

**Gestor de projetos**, quero visualizar o pipeline de obras em Kanban, para acompanhar status e prioridades.<br/>

**Coordenador de equip**e, quero receber alertas de atrasos ou falta de recursos, para agir preventivamente.<br/>

**Analista**, quero gerar relatório de desempenho mensal, para avaliar eficiência e gargalos.<br/>

### Requisitos Funcionais

**RF01:** Cadastro de obras (cliente, endereço, prazo, equipe).<br/>

**RF02:** Fluxo Kanban de status de obra.<br/>

**RF03:** Gatilhos e alertas automáticos por condição de prazo e disponibilidade.<br/>

**RF04:** Dashboards com KPIs (quantidade de obras, percentuais de atraso, alocação de recursos).<br/>

**RF05:** Relatórios exportáveis (PDF/Excel).<br/>

### Requisitos Não Funcionais

**RNF01:** Tempo de resposta dos dashboards ≤ 3s.<br/>

**RNF02:** Acesso as ferramentas com usuário e senha.<br/>

**RNF03:** Conformidade com LGPD (procedimentos de anonimização e consentimento). <br/>

**RNF04:** Licença Pro do Power BI para publicação do dashboard pensando na privacidade dos dados.<br/>

**RNF05:** Segurança do usuário.<br/>

## 14	FERRAMENTAS 

• Coleta: Microsoft Forms, Planner, Power Automate<br/>
• Armazenamento de Dados: Excel, Onedrive<br/>
•	Análise & Visualização: Power BI.<br/>

## 15	PREPARAÇÃO DO DESENVOLVIMENTO

### Forms para cadastro das obras:

![Forms](img/forms.png)

### Planner para Quadro Kanban:


![Planner](img/planner.png)

### Fluxo no Automate:

![Fluxo](img/automate.png)

### Relatório no Power BI:

![Dashboard](img/relatorio.png)

## 16 	PLANO DE EXECUÇÃO

**1.	Sprint 1:** Coleta de dados (Forms + Power Automate).<br/>

**2.	Sprint 2:** Kanban (Planner + integração).<br/>

**3.	Sprint 3:** Dashboard inicial (Power BI – versão MVP).<br/>

**4.	Sprint 4:** Alertas e relatórios avançados.<br/>

## 17	DIVISÃO DE TAREFAS

**•	Desenvolvimento na Power Platform:** Forms, Planner, Automate.<br/>

**•	Análise e Visualização dos dados:** Modelagem e relatórios Power BI.<br/>

**•	Testes:** Validação de requisitos e testes.<br/>

**•	Documentação**.<br/>

## 18	INÍCIO DO DESENVOLVIMENTO 

•	Configuração do ambiente Power Platform com a criação do Forms para preenchimento das obras, automação com o Power Automate e Quadro Kanban para gerenciamento das obras.

•	Dashboards Internos:

1	Visão Geral de Obras: Total por status, tempo médio de conclusão.<br/>
2	Tendências de Prazo: Linha do tempo de início/fim previsto vs. efetivo.<br/>
3	Comparativo Mensal: Obras iniciadas/concluídas.<br/>

## Link do Dashboard Publicado

https://app.powerbi.com/view?r=eyJrIjoiYWU0ZWExZTctNWM4Zi00ZGM2LWE2OWUtMDIyMTBkYWVmYWJkIiwidCI6IjE0Y2JkNWE3LWVjOTQtNDZiYS1iMzE0LWNjMGZjOTcyYTE2MSIsImMiOjh9


Obs: Todos os dados do dashboard estão devidamente mascarados, em virtude da LGPD. 

## REFERÊNCIAS

GARONCE FOTOVOLTAICA. Garonce Fotovoltaica, 2025. Disponível em: https://garoncefotovoltaica.com/ Acesso em: 25 fev. 2025.

ASSOCIAÇÃO BRASILEIRA DE ENERGIA SOLAR FOTOVOLTAICA (ABSOLAR). Energia solar atinge 40% a mais de capacidade em 2024. BE News, 2024. Disponível em: https://portalbenews.com.br/energia-solar-atinge-40-a-mais-de-capacidade-em-2024/. Acesso em: 25 fev. 2025.

GREENER. Boletim M&A: confira análise de 2024 e projeções para 2025. Canal Solar, 2024. Disponível em: https://canalsolar.com.br/boletim-ma-confira-analise-2024/. Acesso em: 25 fev. 2025.

YELLOT. Energia Solar em 2024: 5 tendências para o mercado. Yellot, 2024. Disponível em: https://yellot.com.br/tecnologia-e-inovacao/energia-solar-em-2024-5-tendencias-para-o-mercado/. Acesso em: 25 fev. 2025.

REUTERS. Brazil's grid caps power from wind and solar, threatening renewable projects. Reuters, 2024. Disponível em: https://www.reuters.com/business/energy/brazils-grid-caps-power-wind-solar-threatening-renewable-projects-2024-08-22/. Acesso em: 25 fev. 2025.

REUTERS. Enel cautious on US solar panel project, committed to Brazil grids. Reuters, 2024. Disponível em: https://www.reuters.com/business/energy/enel-cautious-us-solar-panel-project-committed-brazil-grids-2024-11-18/. Acesso em: 25 fev. 2025.

ABREU, Jacqueline de Souza. Proteção de dados pessoais e persecução criminal à luz da LGPD. Revista do Advogado, São Paulo, v. 39, n. 144, p. 149-153, nov. 2019.

VOIGT, Paul, and Axel von dem Bussche. The EU General Data Protection Regulation (GDPR): A Practical Guide. Springer, 2017.

CALDER, Alan. ISO/IEC 27001:2013: An Introduction to Information Security and the ISO27001 Standard. IT Governance Publishing, 2013.

