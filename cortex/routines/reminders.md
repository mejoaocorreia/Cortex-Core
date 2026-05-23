# Reminders Routine

Rotina de lembretes.

## Objetivo
Detetar e disparar lembretes no momento certo.

## O que faz (futuro)
- verifica itens com `reminder_policy` em [[000_queue|qo]]
- traz `snoozed` que voltam hoje
- alimenta [[cortex/daily/reminders|daily/reminders]]

## Como o CortexCore vai usar
Corre periodicamente (via n8n) e sinaliza o que precisa de atenção.

## Estado atual
Por definir.

## Próximos passos
- [ ] definir canais de notificação
