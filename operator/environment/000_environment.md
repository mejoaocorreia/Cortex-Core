# Operator — Environment

Contexto físico e locais do Operator.

## Objetivo
Registar o contexto físico e prático do Operator: onde vive, trabalha e se desloca. É a **fonte conceptual** das localizações do sistema.

## O que vai guardar aqui
- casa
- trabalho
- ginásio
- locais frequentes
- deslocações habituais
- ambiente diário

## Como o CortexCore vai usar
Serve de fonte para as routines de localização e tempo: a [[cortex/routines/locations|locations routine]] e a [[cortex/routines/weather|weather routine]] usam este contexto, e pode alimentar o [[cortex/daily/000_daily|daily]] e os [[cortex/routines/reminders|reminders]].

## Aviso de privacidade
Localizações reais são **sensíveis** e **não devem ir para o GitHub em bruto** (ver [[cortex/protocols/privacy|privacy]]). Guardar aqui o contexto de forma protegida, não moradas/coordenadas em claro.

## Ideias discutidas
- A routine é só o motor; o contexto físico vive aqui, no Operator.

## Estado atual
Base explicativa, sem dados reais.

## Próximos passos
- [ ] definir que locais são úteis ao sistema (sem dados sensíveis em bruto)
