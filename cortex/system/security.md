# Security

Segurança do CortexCore.

## Objetivo
Definir como proteger o sistema e os dados sensíveis.

## O que vai guardar aqui
- onde ficam os segredos (gestor de segredos / `.env` fora do Git)
- regras de acesso
- boas práticas (rotação de tokens, 2FA, etc.)

## Como o CortexCore vai usar
Toda a infraestrutura segue estas regras. Liga-se a [[cortex/protocols/privacy|privacy]] no plano dos dados e ao [[cortex/system/gitignore|.gitignore]] no plano do versionamento.

## Regras base
- Segredos nunca no Vault nem no GitHub em bruto.
- `.env`, tokens e credenciais ficam fora do controlo de versões.
- Dados sensíveis cifrados quando possível.

## Estado atual
Base inicial.

## Próximos passos
- [ ] escolher gestor de segredos
- [ ] definir política de acessos
