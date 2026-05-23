# n8n

Fluxos de automação no n8n.

## Objetivo
Documentar como o CortexCore usa o n8n para correr as suas rotinas.

## O que vai guardar aqui
- lista de fluxos n8n e o que fazem
- como cada fluxo se liga às routines deste Vault
- gatilhos (cron, webhook, evento)

## Como o CortexCore vai usar
O n8n é o "motor" que executa as [[cortex/routines/000_routines|routines]] no tempo certo e escreve resultados no Vault.

## Notas de segurança
Credenciais e tokens do n8n **não** entram no Vault nem no GitHub. Ver [[cortex/system/security|security]].

## Estado atual
Por definir.

## Próximos passos
- [ ] instalar/configurar o n8n
- [ ] criar o primeiro fluxo (ex.: morning routine)
