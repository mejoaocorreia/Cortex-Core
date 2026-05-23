# Status

Estado atual do Operator e das áreas do CortexCore.

## Objetivo
Medir e mostrar o **estado atual** do sistema: como estão o Operator e as áreas principais num dado momento. É o "painel de saúde" do CortexCore.

## O que vai guardar aqui
- [[cortex/status/current_mission|current_mission]] — a prioridade prática ativa
- [[cortex/status/radar|radar]] — radar chart das áreas
- [[cortex/status/scores|scores]] — scores de 0 a 10 por área
- [[cortex/status/overall|overall]] — score global
- [[cortex/status/trends|trends]] — tendências ao longo do tempo
- [[cortex/status/risks|risks]] — riscos detetados
- [[cortex/status/goals_alignment|goals_alignment]] — alinhamento com objetivos
- [[cortex/status/friction|friction]] — fricção (o que trava o Operator)
- [[cortex/status/drift|drift]] — drift (afastamento do rumo)
- [[cortex/status/weekly_snapshot|weekly_snapshot]] — fotografias semanais
- [[cortex/status/archive/index|archive]] — snapshots antigos

## Como o CortexCore vai usar
No futuro, agentes e routines vão calcular estes valores a partir das áreas ([[operator/000_operator|operator]], [[professional/000_professional|professional]], [[learning/000_learning|learning]], [[health/000_health|health]], [[wealth/000_wealth|wealth]], [[car/000_car|car]]) e mostrá-los no [[cortex/interface/dashboard|dashboard]] e nas [[cortex/daily/reviews/weekly|revisões]]. Liga-se à [[cortex/queue/000_queue|Queue]] (riscos e fricção podem gerar itens).

## Ideias discutidas
- Scores de 0 a 10 por área, com um overall score.
- Radar chart para ver o equilíbrio entre áreas de relance.
- Cruzar status com goals para medir alinhamento, e detetar drift e fricção.

## Estado atual
Base explicativa. **Sem scores ou valores reais** — apenas a preparação do espaço e do conceito.

## Próximos passos
- [ ] definir como cada score é calculado
- [ ] decidir a periodicidade dos snapshots
- [ ] ligar ao dashboard quando a interface existir
