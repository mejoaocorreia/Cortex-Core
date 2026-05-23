# Signal vs Noise Protocol

Regras para separar o que importa do ruído.

## Objetivo
Evitar que tudo vire prioridade. O CortexCore deve distinguir **sinal** (o que merece atenção) de **ruído** (o que não merece).

## O que regula
- o que entra (ou não) no [[cortex/daily/000_daily|daily]] como prioritário
- como pesar a atenção que cada coisa merece

## Regras
- **Nem tudo deve virar prioridade.**
- Separar sinal de ruído antes de mostrar.
- Liga com os campos da [[cortex/queue/000_queue|Queue]]: `attention_score`, `mention_count`, `recurring_signal`.
- Uma coisa com **score baixo mas repetida várias vezes** (alto `mention_count`) deve ser **sinalizada** — a repetição é, em si, um sinal.
- **Evitar** que tudo entre no daily como urgente.

## Como o CortexCore vai usar
Os agentes usam isto ao alimentar o [[cortex/daily/focus|foco]] e ao calcular prioridades na [[cortex/queue/rules|queue/rules]]. Liga-se ao [[cortex/status/friction|friction]] (ruído repetido é fricção) e aos [[cortex/protocols/reminders|reminders]].

## Ideias discutidas
- Repetição é sinal: se um assunto volta sempre, merece atenção mesmo com score baixo.
- Mais sinal, menos ruído — coerente com a [[cortex/self/personality|personalidade]] do sistema.

## Estado atual
Base explicativa.

## Próximos passos
- [ ] definir o limiar de `mention_count` que dispara sinalização
