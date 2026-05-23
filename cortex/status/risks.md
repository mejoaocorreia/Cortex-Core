# Status — Risks

Riscos detetados.

## Objetivo
Sinalizar áreas ou situações em risco antes que se tornem problemas.

## O que vai guardar aqui
- riscos por área (ex.: score baixo persistente, prazo a aproximar-se, área esquecida)
- nível do risco e o que o desencadeia

## Como o CortexCore vai usar
Agentes detetam riscos a partir de [[cortex/status/scores|scores]], [[cortex/status/trends|tendências]] e [[cortex/status/drift|drift]]. Um risco relevante pode gerar um item na [[cortex/queue/000_queue|Queue]] e aparecer no [[cortex/daily/000_daily|daily]].

## Ideias discutidas
- Prevenir em vez de remediar: melhor avisar cedo.
- Risco ≠ urgência — algo pode ser arriscado sem ser urgente.

## Estado atual
Base explicativa. **Sem riscos reais listados.**

## Próximos passos
- [ ] definir os sinais que disparam um risco
