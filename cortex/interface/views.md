# Views

Filtros e modos visuais para mostrar só parte do Vault.

## Objetivo
Definir o conceito de **Views**: configurações visuais que mostram apenas as partes do Vault que interessam num dado momento, escondendo o resto.

## O que vai guardar aqui
- a ideia de cada view e o que ela mostra
- que partes do Vault inclui/exclui

## Exemplos de views
- só **Previmed**
- só **Website**
- só **Operator + Health + Car**
- só **Cortex**
- só **Queue / Daily**
- só **Professional**

## Como o CortexCore vai usar
As views ajudam a reduzir ruído (ligam-se ao [[cortex/protocols/signal_noise|signal_noise]] e aos [[cortex/modes/000_modes|modes]]). Futuramente podem apoiar-se em:
- filtros do **Obsidian Graph**
- mapas do [[cortex/interface/atlas/000_atlas|Atlas]]
- **Local Graph**
- **bookmarks**
- a futura [[cortex/interface/dashboard|interface/dashboard]]

## Diferença para modes
- [[cortex/modes/000_modes|Modes]] = lente ligada ao **momento/contexto** (manhã, foco, recovery…).
- Views = recorte ligado ao **conteúdo** (que áreas mostrar).

## Ideias discutidas
- Por agora é só ideia documentada — **sem implementação funcional**.

## Estado atual
Conceito. Sem filtros reais.

## Próximos passos
- [ ] listar as views mais úteis no dia a dia
