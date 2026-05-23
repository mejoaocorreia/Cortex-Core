# Daily Rollover

Rotina que vira o dia.

## Objetivo
Quando muda o dia, fechar o dia anterior e preparar o novo.

## O que faz (futuro)
- arquiva o [[cortex/daily/today|today]] em `daily/archive/ano/mês/data.md`
- limpa o `today` para o novo dia
- transporta o que ficou por fechar

## Como o CortexCore vai usar
Corre à meia-noite (ou ao primeiro arranque do dia), via n8n. Ver [[cortex/daily/archive/index|daily/archive]].

## Estado atual
Por definir.

## Próximos passos
- [ ] implementar a criação automática da estrutura de datas
