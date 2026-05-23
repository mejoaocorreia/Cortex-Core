# Status — Drift

Drift: afastamento do rumo.

## Objetivo
Detetar quando o Operator se afasta, aos poucos, da direção que definiu — sem dar por isso.

## O que vai guardar aqui
- sinais de drift por área (objetivos a serem ignorados, hábitos a cair, áreas esquecidas)
- há quanto tempo o desvio se arrasta

## Como o CortexCore vai usar
Combina [[cortex/status/trends|tendências]] negativas com baixo [[cortex/status/goals_alignment|alinhamento de objetivos]]. Drift persistente vira [[cortex/status/risks|risco]] e pode aparecer no [[cortex/modes/reflect|Reflect Mode]].

## Ideias discutidas
- Drift é lento e silencioso — por isso é preciso medi-lo, não confiar na memória.

## Estado atual
Base explicativa. **Sem dados reais.**

## Próximos passos
- [ ] definir o limiar a partir do qual um desvio conta como drift
