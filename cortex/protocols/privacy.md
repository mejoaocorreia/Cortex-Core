# Privacy

Protocolo de privacidade e proteção de dados.

## Objetivo
Garantir que dados sensíveis nunca são expostos, partilhados ou enviados para sítios errados.

## O que vai guardar aqui
- regras sobre o que é sensível (saúde, finanças, pessoas, credenciais)
- onde cada tipo de dado pode/não pode viver
- regras de partilha e exportação

## Como o CortexCore vai usar
Qualquer agente ou rotina valida estas regras antes de ler, mover ou enviar dados.

## Ideias discutidas
- Dados sensíveis **não vão para o GitHub** em bruto (ver [[cortex/system/github|github]] e [[cortex/system/security|security]]).
- Separar claramente o que é público/estrutural do que é privado.
- O `.gitignore` protege segredos, bases de dados, exports e caches.

## Estado atual
Base inicial.

## Próximos passos
- [ ] classificar cada área por nível de sensibilidade
