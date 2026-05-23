# Cortex

Núcleo operativo do CortexCore.

## Objetivo
O CortexCore é o Vault inteiro. A pasta `cortex/` é a **zona central** onde vivem as regras, a memória, as versões, as rotinas, o sistema, a interface, a fila de atenção, o estado (status), os modos (modes), o daily e os agentes principais. É o "tronco cerebral" do sistema.

## O que vai guardar aqui
- [[cortex/self/000_self|self]] — identidade do CortexCore (visão, princípios, personalidade)
- [[cortex/protocols/000_protocols|protocols]] — regras de funcionamento
- [[cortex/memory/000_memory|memory]] — evolução, decisões, ideias, histórico
- [[cortex/versions/v0.00.0|versions]] — versões do sistema
- [[cortex/inbox/000_inbox|inbox]] — entrada bruta
- [[cortex/queue/000_queue|Queue]] — fila de coisas abertas
- [[cortex/status/000_status|status]] — estado atual do Operator e das áreas
- [[cortex/modes/000_modes|modes]] — lentes de contexto
- [[cortex/daily/000_daily|daily]] — o dia atual e revisões
- [[cortex/agents/000_agents|agents]] — agentes do núcleo
- [[cortex/routines/000_routines|routines]] — processos recorrentes / por evento
- [[cortex/system/000_system|system]] — parte técnica (GitHub, servidor, segurança, backups)
- [[cortex/interface/000_interface|interface]] — futura camada visual
- [[cortex/projects/000_projects|projects]] — índice global de projetos
- [[cortex/templates/000_templates|templates]] — modelos reutilizáveis
- [[cortex/archive/index|archive]] — arquivo do núcleo

## Como o CortexCore vai usar
Tudo o que é transversal ao sistema passa por aqui. As áreas de vida (`operator`, `professional`, etc.) seguem as regras definidas em `cortex/protocols` e podem ter os seus próprios agentes e arquivos.

## Ideias discutidas
- Não criar pasta `cortexcore` dentro do Vault — o Vault já é o CortexCore.
- `cortex` é o nome do núcleo (não confundir com o Vault todo).

## Estado atual
Base inicial. Subpastas criadas com ficheiros explicativos.

## Próximos passos
- [ ] consolidar protocolos
- [ ] definir os primeiros agentes reais
- [ ] ligar rotinas ao n8n
