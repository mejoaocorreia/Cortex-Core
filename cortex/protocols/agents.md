# Agents Protocol

Como os agentes funcionam e onde vivem.

## Objetivo
Definir as regras gerais para todos os agentes do CortexCore.

## Regras
- Agentes **não ficam todos numa pasta global**.
- Cada área pode ter a sua própria pasta `agents`.
- `cortex/agents` guarda apenas os agentes do **núcleo**.
- Todos os agentes seguem [[cortex/protocols/context_ladder|context_ladder]] e [[cortex/protocols/privacy|privacy]].
- Cada agente deve ter propósito, âmbito e limites claros.

## Como o CortexCore vai usar
Quando se cria um agente, decide-se primeiro a que área pertence e coloca-se na pasta `agents` correta. Usar o [[cortex/templates/template_agent|template de agente]].

## Ideias discutidas
- O agente do núcleo é o [[cortex/agents/cortex_supervisor|cortex_supervisor]].
- Áreas como Previmed terão supervisor próprio.

## Estado atual
Base inicial.

## Próximos passos
- [ ] definir formato padrão de um agente
