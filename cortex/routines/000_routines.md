# Routines

Processos recorrentes ou acionados por eventos. (`routines` substitui `automations`.)

## Objetivo
Definir o que o CortexCore faz de forma automática ou agendada.

## O que vai guardar aqui
- [[cortex/routines/boot|boot]] — arranque do sistema
- [[cortex/routines/morning|morning]] — preparação da manhã
- [[cortex/routines/reminders|reminders]] — lembretes
- [[cortex/routines/weather|weather]] — tempo por localização
- [[cortex/routines/locations|locations]] — onde estás / onde vais estar
- [[cortex/routines/daily_rollover|daily_rollover]] — virar o dia
- [[cortex/routines/weekly_review|weekly_review]] — revisão semanal
- [[cortex/routines/n8n|n8n]] — fluxos no n8n

## Como o CortexCore vai usar
Routines arrancam funcionalidades (ex.: a morning routine prepara o [[cortex/daily/000_daily|daily]]). Muitas serão implementadas como fluxos n8n.

## Ideias discutidas
- "routines" descreve melhor o conceito (processos) do que "automations".
- Routines podem ser por tempo (cron) ou por evento.

## Estado atual
Base inicial.

## Próximos passos
- [ ] mapear cada routine para um fluxo n8n
