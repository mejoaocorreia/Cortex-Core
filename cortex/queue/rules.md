# QO — Rules

Regras de triagem e prioridade da fila.

## Objetivo
Definir como os itens entram, mudam de estado e recebem o Attention Score.

## O que vai guardar aqui
- regras de cálculo do `attention_score`
- regras de transição entre estados (open, priority, waiting, snoozed, muted, closed)
- como `mention_count` afeta a prioridade

## Como o CortexCore vai usar
Agentes e rotinas seguem estas regras para manter a fila ordenada sem intervenção manual constante.

## Ideias discutidas
- Score 0–100 a partir de urgência, importância, idade, prazo, impacto e risco de esquecimento.
- Item com score baixo mas muito mencionado deve subir ou ser sinalizado (`recurring_signal`).

## Estado atual
Base inicial, regras por definir.

## Próximos passos
- [ ] escrever a fórmula concreta do score
- [ ] definir gatilhos de mudança de estado
