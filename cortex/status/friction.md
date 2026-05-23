# Status — Friction

Fricção: o que trava o Operator.

## Objetivo
Identificar o atrito que torna as coisas difíceis ou lentas — o que gasta energia sem produzir avanço.

## O que vai guardar aqui
- pontos de fricção por área (bloqueios, repetições, tarefas adiadas)
- onde o Operator perde tempo ou energia

## Como o CortexCore vai usar
Cruza itens parados na [[cortex/queue/000_queue|Queue]] (muito `snoozed` ou alto `mention_count`) com os [[cortex/status/scores|scores]]. Fricção alta sinaliza onde simplificar ou automatizar.

## Ideias discutidas
- Fricção recorrente é candidata a virar [[cortex/routines/000_routines|routine]] ou a ser eliminada.

## Estado atual
Base explicativa. **Sem dados reais.**

## Próximos passos
- [ ] definir como detetar fricção a partir da Queue
