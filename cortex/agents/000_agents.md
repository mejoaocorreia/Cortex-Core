# Cortex Agents

Agentes do núcleo do CortexCore.

## Objetivo
Guardar apenas os agentes **do núcleo** — os que coordenam o sistema como um todo.

## O que vai guardar aqui
- [[cortex/agents/cortex_supervisor|cortex_supervisor]] — supervisor geral do CortexCore

## Como o CortexCore vai usar
Estes agentes seguem [[cortex/protocols/agents|o protocolo de agentes]]: cada área pode ter os seus próprios agents; aqui ficam só os do núcleo.

## Ideias discutidas
- Agentes não vivem todos numa pasta global.
- Áreas como Previmed têm supervisor próprio (ver [[professional/previmed/agents/000_agents|previmed/agents]]).

## Estado atual
Base inicial com o supervisor.

## Próximos passos
- [ ] definir as responsabilidades do supervisor
- [ ] decidir que outros agentes pertencem ao núcleo
