# .gitignore (notas)

Documentação do que o Git deve ignorar.

## Objetivo
Explicar a lógica do ficheiro `.gitignore` na raiz do Vault.

## O que protege
- segredos e credenciais (`.env`, `*.env`, tokens, chaves)
- bases de dados (`*.sqlite`, `*.db`)
- dados privados (`private/`)
- uploads e exports
- caches e temporários
- estado local do Obsidian (`workspace.json`)

## O que NÃO ignora
- os ficheiros `.md` explicativos da estrutura
- os `.gitkeep` necessários para manter pastas vazias

## Como o CortexCore vai usar
Sempre que se adiciona um novo tipo de dado sensível, atualiza-se o `.gitignore` e regista-se aqui o porquê. Ver [[cortex/system/security|security]] e [[cortex/protocols/privacy|privacy]].

## Estado atual
`.gitignore` criado na raiz.

## Próximos passos
- [ ] rever regras à medida que surgem novos dados
