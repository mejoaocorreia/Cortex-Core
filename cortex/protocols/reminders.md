# Reminders Protocol

Regras de como o CortexCore lembra o Operator.

## Objetivo
Definir como os lembretes são criados, geridos e ajustados — para lembrar sem sufocar.

## O que regula
- quando perguntar sobre lembretes
- como reagir às respostas do Operator
- a intensidade da insistência

## Regras
- Quando uma tarefa tiver **data**, o CortexCore deve **perguntar quando lembrar**.
- Se o Operator disser **"não me avises"** → o item passa a [[cortex/queue/muted|muted]].
- Se disser **"feito"** → passa a [[cortex/queue/closed|closed]].
- Se **não responder** → o sistema pode **voltar a lembrar** mais tarde.
- Se **adiar** → passa a [[cortex/queue/snoozed|snoozed]].
- Itens **importantes** podem **insistir mais**.
- Itens **leves** devem **insistir menos**.

## Como o CortexCore vai usar
Liga-se diretamente ao campo `reminder_policy` da [[cortex/queue/000_queue|Queue]] e à [[cortex/routines/reminders|reminders routine]]. O [[cortex/protocols/signal_noise|signal_noise]] ajuda a decidir o quão forte deve ser a insistência.

## Ideias discutidas
- A insistência deve ser proporcional à importância — nunca igual para tudo.
- Respeitar sempre o "não me avises" (ver [[cortex/self/operating_principles|operating_principles]]).

## Estado atual
Base explicativa.

## Próximos passos
- [ ] mapear os estados da Queue às respostas do Operator
