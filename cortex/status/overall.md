# Status — Overall

Score global do CortexCore.

## Objetivo
Resumir, num único número, o estado geral do Operator. **Não é uma média simples** dos [[cortex/status/scores|scores]] — é uma leitura ponderada que tem em conta o contexto.

## O que vai guardar aqui
- o overall score atual
- como é composto (que peso e que fatores entram)
- nota curta sobre o estado geral

## Como é composto (conceito)
O overall deve considerar, em conjunto:
- **pesos** por área (nem todas pesam igual)
- **riscos** ([[cortex/status/risks|risks]])
- **tendências** ([[cortex/status/trends|trends]])
- **áreas críticas** (uma área muito baixa pesa mais)
- **queue aberta** ([[cortex/queue/000_queue|Queue]])
- **alinhamento com objetivos** ([[cortex/status/goals_alignment|goals_alignment]])
- **drift** ([[cortex/status/drift|drift]])
- **energia / saúde** ([[health/000_health|health]])

## Exemplos conceptuais
- Se [[health/000_health|health]] estiver muito baixo, o overall **não** deve parecer ótimo, por mais alto que esteja o resto.
- Se [[professional/000_professional|professional]] estiver alto mas [[operator/000_operator|operator]] estiver baixo, há **risco de burnout** — o overall deve refletir isso.

## Como o CortexCore vai usar
É o indicador de topo do [[cortex/interface/dashboard|dashboard]] e do [[cortex/daily/000_daily|daily]]. Dá uma leitura imediata e honesta: "como estou, no geral".

## Ideias discutidas
- Ponderado, não média simples — o contexto importa.
- O overall não substitui os scores por área — complementa-os.
- Áreas críticas em baixo devem "puxar" o overall para baixo.

## Estado atual
Base explicativa. **Sem valor real.**

## Próximos passos
- [ ] definir os pesos de cada área
