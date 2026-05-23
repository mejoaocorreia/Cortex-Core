# Cortex Supervisor

Agente supervisor do núcleo.

## Objetivo
Coordenar o CortexCore: triar a inbox, manter o QO em ordem, preparar o daily e delegar nas áreas certas.

## Âmbito
- ler contexto por camadas ([[cortex/protocols/context_ladder|context_ladder]])
- respeitar a [[cortex/protocols/privacy|privacidade]]
- delegar em agentes de área (ex.: [[work/previmed/agents/000_agents|previmed]])

## O que vai guardar aqui
- propósito, responsabilidades e limites do supervisor
- como decide e quando delega

## Como o CortexCore vai usar
É o primeiro a "acordar" na boot routine. Olha para o estado geral e decide o que mostrar e o que precisa de atenção.

## Estado atual
Base inicial. Usar o [[cortex/templates/template_agent|template de agente]] para detalhar.

## Próximos passos
- [ ] definir entradas, saídas e limites concretos
