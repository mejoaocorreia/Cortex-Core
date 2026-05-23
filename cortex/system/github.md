# GitHub

Repositório privado do CortexCore.

## Objetivo
Versionar a estrutura, o código e os templates do sistema — sem expor dados sensíveis.

## O que vai (e não vai) para o GitHub
- **Vai:** estrutura de pastas, ficheiros explicativos, templates, código, protocolos.
- **Não vai:** passwords, tokens, dados financeiros, dados de saúde, dados pessoais sensíveis, localização real, bases de dados, exports.

## Como o CortexCore vai usar
- O GitHub guarda **estrutura, código e templates**.
- O repositório será **privado por agora**.
- Mesmo sendo privado, **dados sensíveis não entram em bruto**.
- Os **dados reais** ficam em Vault privado / local / storage protegido — não no GitHub.
- O GitHub **não é** o sítio para passwords, tokens, dados financeiros, dados de saúde ou dados pessoais sensíveis.

O [[cortex/system/gitignore|.gitignore]] protege o que não pode ser commitado. Em dúvida, ver [[cortex/protocols/privacy|privacy]].

## Estado atual
Base inicial.

## Próximos passos
- [ ] criar o repositório privado
- [ ] confirmar que o .gitignore cobre tudo o que é sensível
