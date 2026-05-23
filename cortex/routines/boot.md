# Boot Routine

Rotina de arranque do CortexCore.

## Objetivo
Preparar o sistema quando se inicia: atualizar o painel [[000_boot|000_boot]] e abrir o que importa.

## O que faz (futuro)
- atualiza o painel de entrada
- aciona o [[cortex/agents/cortex_supervisor|supervisor]]
- abre/prepara o [[cortex/daily/000_daily|daily]]

## Como o CortexCore vai usar
É o primeiro processo do dia/sessão. Mantém-se leve, seguindo o [[cortex/protocols/context_ladder|context_ladder]].

## Estado atual
Por definir.

## Próximos passos
- [ ] decidir o que a boot faz exatamente
