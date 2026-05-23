# Queue — Muted

Itens silenciados.

## Objetivo
Guardar itens que continuam abertos mas que não devem gerar alertas nem aparecer no foco.

## O que vai guardar aqui
- itens silenciados, sem `reminder_policy` ativa

## Como o CortexCore vai usar
Diferente de `snoozed` (que volta sozinho): um item `muted` fica calado até ser reativado manualmente. Útil para coisas de fundo, sem urgência.

## Estado atual
Por preencher.

## Próximos passos
- [ ] decidir se itens muted ainda contam para `mention_count`
