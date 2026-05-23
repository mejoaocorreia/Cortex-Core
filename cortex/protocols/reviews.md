# Reviews Protocol

Regras das revisões periódicas.

## Objetivo
Definir os ciclos de revisão e o que cada um alimenta.

## O que regula
- os tipos de revisão e a sua periodicidade
- que dados cada revisão produz

## Os ciclos
- **daily review** — fecho do dia
- **weekly review** — [[cortex/daily/reviews/weekly|weekly]]
- **monthly review** — [[cortex/daily/reviews/monthly|monthly]]
- **yearly review** — [[cortex/daily/reviews/yearly|yearly]]

## Como o CortexCore vai usar
As revisões alimentam:
- [[cortex/status/trends|status/trends]] (evolução ao longo do tempo)
- [[cortex/status/weekly_snapshot|status/weekly_snapshot]] (fotografia semanal)
- [[cortex/daily/reviews/weekly|daily/reviews]] (registo das revisões)

Liga-se ao [[cortex/modes/review|Review Mode]] e à [[cortex/routines/weekly_review|weekly_review routine]].

## Ideias discutidas
- Rever com regularidade é o que evita o [[cortex/status/drift|drift]].
- Cada ciclo agrega o anterior (semana → mês → ano).

## Estado atual
Base explicativa.

## Próximos passos
- [ ] definir o guião de cada revisão
