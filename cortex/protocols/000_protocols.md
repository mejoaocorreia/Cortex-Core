# Protocols

Protocolos de funcionamento do CortexCore.

## Objetivo
Reunir as regras que definem como o sistema lê contexto, protege dados, organiza agentes e nomeia ficheiros.

## O que vai guardar aqui
- [[cortex/protocols/context_ladder|context_ladder]] — regra de leitura por camadas (o mais importante)
- [[cortex/protocols/privacy|privacy]] — proteção de dados sensíveis
- [[cortex/protocols/agents|agents]] — como os agentes funcionam e onde vivem
- [[cortex/protocols/naming|naming]] — convenções de nomes
- [[cortex/protocols/archive|archive]] — onde arquivar e por que ordem procurar
- [[cortex/protocols/assets|assets]] — onde vivem ficheiros e anexos
- [[cortex/protocols/capture_flow|capture_flow]] — fluxo de captura e processamento
- [[cortex/protocols/reminders|reminders]] — como o sistema lembra o Operator
- [[cortex/protocols/reviews|reviews]] — ciclos de revisão
- [[cortex/protocols/signal_noise|signal_noise]] — separar sinal de ruído

## Como o CortexCore vai usar
Antes de qualquer ação, agentes e rotinas seguem estes protocolos. São a "constituição" operacional do sistema.

## Estado atual
Base explicativa com os protocolos principais.

## Próximos passos
- [ ] consolidar o context_ladder
- [ ] adicionar novos protocolos conforme surgirem
