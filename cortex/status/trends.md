# Status — Trends

Tendências ao longo do tempo.

## Objetivo
Mostrar como os [[cortex/status/scores|scores]] e o [[cortex/status/overall|overall]] evoluem — se sobem, descem ou estagnam.

## O que vai guardar aqui
- evolução dos scores por área no tempo
- direção de cada tendência (a melhorar / a piorar / estável)

## Como o CortexCore vai usar
Cruza os [[cortex/status/weekly_snapshot|snapshots semanais]] para detetar padrões e alimentar as [[cortex/daily/reviews/weekly|revisões]]. Uma tendência negativa persistente pode virar [[cortex/status/risks|risco]].

## Ideias discutidas
- A tendência importa mais do que o valor isolado: um 6 a subir é melhor que um 7 a cair.

## Estado atual
Base explicativa. **Sem dados reais.**

## Próximos passos
- [ ] definir a janela temporal das tendências (semanas? meses?)
