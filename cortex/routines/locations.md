# Locations Routine

Rotina de localizações.

## Objetivo
Saber onde estás ou onde vais estar, para dar contexto a outras rotinas (tempo, deslocações, tempo por local).

## O que faz (futuro)
- usa o contexto físico definido em [[operator/environment/000_environment|operator/environment]]
- estima onde decorrerá o dia a partir desse contexto
- **não guarda localizações reais diretamente** — a fonte conceptual é `operator/environment`

## Como o CortexCore vai usar
Alimenta a [[cortex/routines/weather|weather routine]], o [[cortex/daily/000_daily|daily]] e os [[cortex/routines/reminders|reminders]]. A routine é só o "motor"; o contexto de locais vive em [[operator/environment/000_environment|operator/environment]].

## Notas de privacidade
Localização é dado **sensível**. Seguir [[cortex/protocols/privacy|privacy]]: localizações reais não vão para o GitHub em bruto. A routine trabalha sobre o contexto de `operator/environment`, que também protege esses dados.

## Estado atual
Por definir.

## Próximos passos
- [ ] decidir a fonte de localização (manual vs. automática)
