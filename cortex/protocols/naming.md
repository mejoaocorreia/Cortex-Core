# Naming

Convenções de nomes do CortexCore.

## Objetivo
Manter nomes simples, óbvios, limpos e consistentes em todo o Vault.

## Regras
- Nomes em **minúsculas**.
- **underscore** quando necessário (`golf_gti`, `quick_notes`, `daily_rollover`).
- "agents" sempre no **plural**.
- Cada pasta-área tem um ficheiro de entrada `000_<nome>.md` (o `000_` mantém-no no topo).
- Arquivos de cada área ficam em `archive/` com um `index.md`.
- Versões em `versions/` no formato `vX.YY.Z.md`.

## Como o CortexCore vai usar
Ao criar novas pastas ou ficheiros, seguir este protocolo para que tudo seja previsível e fácil de navegar.

## Ideias discutidas
- Prefixo `000_` para ficheiros de entrada/índice.
- Nomes de áreas no singular (`car`, `health`); subpastas descritivas.

## Estado atual
Base inicial.

## Próximos passos
- [ ] documentar exceções, se surgirem
