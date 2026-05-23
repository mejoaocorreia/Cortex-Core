# Capture Flow Protocol

O fluxo de captura e processamento da informação.

## Objetivo
Definir, de forma clara, por onde a informação entra e como percorre o sistema até ao seu lugar final.

## O que regula
- o papel de cada zona no fluxo
- a ordem do processamento

## Os papéis
- **daily** = registo do dia ([[cortex/daily/000_daily|daily]])
- **inbox** = entrada bruta ([[cortex/inbox/000_inbox|inbox]])
- **queue** = coisas abertas que exigem atenção ([[cortex/queue/000_queue|queue]])
- **área** = contexto organizado (operator, professional, etc.)
- **archive** = histórico ([[cortex/protocols/archive|archive]])

## O fluxo geral
`inbox → unprocessed → queue → daily / área / projeto → archive`

Tudo entra bruto pela inbox; é triado para a queue quando exige atenção; daí vai para o daily, para a área/projeto certo, ou para arquivo.

## Como o CortexCore vai usar
Agentes e [[cortex/routines/000_routines|routines]] de triagem seguem este fluxo. Liga-se ao [[cortex/protocols/signal_noise|signal_noise]] (decidir o que merece atenção) e ao [[cortex/protocols/archive|archive]].

## Ideias discutidas
- Capturar sem fricção primeiro; organizar depois.

## Estado atual
Base explicativa.

## Próximos passos
- [ ] definir quem faz a triagem da inbox (manual vs. agente)
