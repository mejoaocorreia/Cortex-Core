# Status — Radar

Radar chart das áreas.

## Objetivo
Mostrar, num só gráfico em forma de teia, o equilíbrio entre as áreas principais do Operator.

## O que vai guardar aqui
- a definição de que eixos entram no radar (uma área por eixo)
- a forma de o gerar (futuramente, a partir de [[cortex/status/scores|scores]])

## Como o CortexCore vai usar
A interface vai desenhar o radar a partir dos scores de cada área, dando uma leitura rápida de onde há equilíbrio e onde há défice. Ver [[cortex/interface/dashboard|dashboard]].

## Ideias discutidas
- Um eixo por área: operator, professional, learning, health, wealth, car.
- O radar é só uma forma de visualizar os [[cortex/status/scores|scores]] — não guarda dados próprios.

## Estado atual
Base explicativa. **Sem gráfico real e sem valores.**

## Próximos passos
- [ ] fixar os eixos do radar
- [ ] decidir a ferramenta de visualização
