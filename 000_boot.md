# CortexCore Boot

Ponto de entrada do Vault. Este ficheiro é o painel inicial do CortexCore: a partir daqui chega-se a todas as áreas e zonas do sistema.

## Objetivo
Servir como ecrã de arranque e navegação rápida. Sempre que abres o Vault, começa aqui.

## Painel de entrada

### Núcleo
- [[cortex/000_cortex|Cortex]] — núcleo operativo
- [[cortex/daily/000_daily|Daily]] — o dia atual
- [[cortex/inbox/000_inbox|Inbox]] — entrada bruta
- [[cortex/qo/000_qo|QO]] — fila de coisas abertas
- [[cortex/projects/000_projects|Project index]] — índice global de projetos

### Áreas de vida
- [[life/000_life|Life]]
- [[work/000_work|Work]]
- [[knowledge/000_knowledge|Knowledge]]
- [[health/000_health|Health]]
- [[finance/000_finance|Finance]]
- [[car/000_car|Car]]

### Prioridade atual
- [[work/previmed/website/000_website|Previmed Website]] — prioridade prática seguinte

## Como o CortexCore vai usar
A routine de boot ([[cortex/routines/boot|boot routine]]) pode atualizar este painel e abrir o daily. Este ficheiro mantém-se curto e estável: serve para navegar, não para guardar conteúdo.

## Estado atual
Base inicial. Links principais definidos.

## Próximos passos
- [ ] ligar a boot routine a este painel
- [ ] adicionar atalhos para o que estiver ativo em cada momento
