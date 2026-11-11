# Modelagem-de-processo-de-negocios-em-BPMN-
Projeto prático desenvolvido para a disciplina de Análise e Modelagem de Sistemas, com foco no redesenho, rastreabilidade e automação de fluxos de trabalho corporativos de ponta a ponta.

-----------------------//------------------------

Título do Projeto
Mapeamento e Modelação de Processos de Negócio em BPMN (Agendamento e Aprovação de Viagens Corporativas)

Descrição e Contexto
Projeto prático desenvolvido para a disciplina de Análise e Modelagem de Sistemas, com foco no redesenho, rastreabilidade e automação de fluxos de trabalho corporativos de ponta a ponta.

Pontos Chave e Metodologia Aplicada
Estruturação Visual (BPMN 2.0): Emprego de Pools (Piscinas) e divisões por Lanes (Raias) para segregar responsabilidades de forma clara entre três papéis corporativos: Funcionário, Gestor e Agente de Viagens.

Regras de Negócio e Gateways Condicionais:

Primeira validação de mérito pelo Gestor (Gateway exclusivo para aprovação ou comunicação de recusa ao funcionário).

Pesquisa de cotações pelo Agente de Viagens e geração do artefato de dados "Orçamento".

Segunda validação financeira pelo Gestor, permitindo a compra de bilhetes e emissão de vouchers ou o cancelamento/desistência formal do processo.

Componentes Técnicos Utilizados: Eventos de início e fim, tarefas operacionais, fluxos de mensagens inter-raias e portas lógicas de decisão.

Referências Teóricas: Fundamentado nos padrões da Object Management Group (OMG) - BPMN 2.0.2 e em literaturas de modelagem de sistemas orientada a objetos e processos.
