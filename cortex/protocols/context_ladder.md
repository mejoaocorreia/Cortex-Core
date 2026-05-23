# Context Ladder

Regra de leitura de contexto por camadas. É o protocolo mais importante do CortexCore.

## Objetivo
Evitar carregar tudo de uma vez. Ler apenas o necessário, na ordem certa, protegendo dados sensíveis e poupando contexto.

## A regra (por ordem)
1. **Ler primeiro o contexto mínimo** — o essencial para perceber o pedido.
2. **Identificar a área afetada** — life, work, health, etc.
3. **Só depois ler o contexto específico** dessa área.
4. **Nunca carregar tudo sem necessidade.**
5. **Proteger dados sensíveis** — ver [[cortex/protocols/privacy|privacy]].
6. **Arquivos só devem ser lidos quando forem relevantes.**

## Como o CortexCore vai usar
Cada agente segue esta escada antes de agir: começa estreito, expande só se for preciso. Isto mantém as respostas rápidas, baratas e seguras.

## Ideias discutidas
- A maioria dos pedidos resolve-se com contexto mínimo + uma área.
- O archive é a última camada, não a primeira.

## Estado atual
Base inicial com a regra definida.

## Próximos passos
- [ ] mapear que ficheiros contam como "contexto mínimo" de cada área
