# CortexCore Boot

Ponto de entrada do Vault. Este ficheiro é o painel inicial do CortexCore: a partir daqui chega-se a todas as áreas e zonas do sistema.

## Objetivo
Servir como ecrã de arranque e navegação rápida. Sempre que abres o Vault, começa aqui.

## Painel de entrada

### Núcleo
- [[cortex/000_cortex|Cortex]] — núcleo operativo
- [[cortex/daily/000_daily|Daily]] — o dia atual
- [[cortex/inbox/000_inbox|Inbox]] — entrada bruta
- [[cortex/queue/000_queue|Queue]] — fila de coisas abertas
- [[cortex/status/000_status|Status]] — estado atual do Operator e das áreas
- [[cortex/modes/000_modes|Modes]] — lentes de contexto
- [[cortex/projects/000_projects|Project index]] — índice global de projetos

### Áreas principais
- [[operator/000_operator|Operator]]
- [[professional/000_professional|Professional]]
- [[learning/000_learning|Learning]]
- [[health/000_health|Health]]
- [[wealth/000_wealth|Wealth]]
- [[car/000_car|Car]]

### Prioridade atual
- [[professional/previmed/website/000_website|Previmed Website]] — prioridade prática seguinte

## Como o CortexCore vai usar
A routine de boot ([[cortex/routines/boot|boot routine]]) pode atualizar este painel e abrir o daily. Este ficheiro mantém-se curto e estável: serve para navegar, não para guardar conteúdo.

## Estado atual
Base inicial. Links principais definidos.

## Próximos passos
- [ ] ligar a boot routine a este painel
- [ ] adicionar atalhos para o que estiver ativo em cada momento
