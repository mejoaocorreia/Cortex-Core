# Status — Scores

Scores de 0 a 10 por área.

## Objetivo
Atribuir a cada área principal um score de **0 a 10** que resume o seu estado atual.

## O que vai guardar aqui
- um score por área (operator, professional, learning, health, wealth, car)
- a justificação curta de cada score
- a data da última atualização

## Como o CortexCore vai usar
Os scores alimentam o [[cortex/status/radar|radar]], o [[cortex/status/overall|overall]] e as [[cortex/status/trends|tendências]]. Agentes vão sugerir scores a partir dos dados de cada área; o Operator confirma.

## Ideias discutidas
- Escala 0–10 (simples de ler).
- Cada score deve ter um "porquê" para não ser um número vazio.

## Estado atual
Base explicativa. **Não preencher scores reais agora — não inventar valores.**

## Próximos passos
- [ ] definir critérios de pontuação por área
