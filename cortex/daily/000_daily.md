# Daily

A área do dia atual. Fica **dentro de `cortex`** porque é uma funcionalidade do CortexCore.

## Objetivo
Dar uma visão clara do dia: resumo, foco, lembretes, reuniões, tempo, tarefas e estatísticas.

## O que vai guardar aqui
- [[cortex/daily/today|today]] — o dia atual
- [[cortex/daily/focus|focus]] — o foco principal
- [[cortex/daily/reminders|reminders]] — lembretes
- [[cortex/daily/weather|weather]] — tempo por localização
- [[cortex/daily/stats|stats]] — estatísticas e evolução
- `reviews/` — [[cortex/daily/reviews/weekly|semanal]], [[cortex/daily/reviews/monthly|mensal]], [[cortex/daily/reviews/yearly|anual]]
- [[cortex/daily/archive/index|archive]] — dias passados

## Daily vs Routines
As [[cortex/routines/000_routines|routines]] **podem arrancar** o daily (ex.: a morning routine prepara o `today`), mas o daily é uma **área própria**. Routines = processos; daily = conteúdo do dia.

## O que o daily deve servir
- resumo do dia
- foco
- lembretes
- reuniões
- tempo por localização
- tarefas prioritárias (vindas de [[priority|qo/priority]])
- histórico do dia
- estatísticas e evolução ao longo do tempo

## Ideia futura: rollover
Quando muda o dia, o `today.md` pode ser arquivado em `daily/archive/ano/mês/data.md`. Não é preciso criar os ficheiros datados agora — ver [[cortex/routines/daily_rollover|daily_rollover]].

## Estado atual
Base inicial.

## Próximos passos
- [ ] ligar o daily à boot/morning routine
- [ ] definir o formato do `today` (ver [[cortex/templates/template_daily|template]])
