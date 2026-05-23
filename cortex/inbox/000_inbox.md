# Inbox

Zona de entrada bruta do CortexCore.

## Objetivo
Capturar tudo o que chega sem classificação, sem fricção. Primeiro captura-se; só depois se processa.

## O que vai guardar aqui
- `unprocessed/` — tudo o que chega sem classificação
- `quick_notes/` — notas rápidas soltas
- `archive/` — entradas já processadas que vale a pena guardar ([[cortex/inbox/archive/index|index]])

## Como o CortexCore vai usar
Fluxo de processamento:

`inbox → unprocessed → queue → daily / área específica / projeto → archive`

Tudo o que entra é triado: vira item de [[cortex/queue/000_queue|Queue]], entra no [[cortex/daily/000_daily|daily]], move-se para uma área específica, ou vai para arquivo.

## Ideias discutidas
Nomes alternativos debatidos para esta zona:
- **inbox** (escolhido por agora)
- capture
- intake
- incoming
- drop

Por agora usamos **inbox** por ser simples e óbvio. Pode mudar mais tarde.

## Estado atual
Base inicial. Pastas `unprocessed` e `quick_notes` mantidas com `.gitkeep`.

## Próximos passos
- [ ] definir como a captura entra (manual, n8n, etc.)
- [ ] criar rotina de triagem da inbox
