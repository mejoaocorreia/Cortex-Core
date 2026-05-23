# Modes

Modos de utilização e contexto do CortexCore.

## Objetivo
Os **modes** são formas de o CortexCore mostrar **apenas o contexto certo para o momento**. Em vez de mostrar tudo sempre, o sistema adapta o que apresenta ao estado do Operator (a trabalhar, a descansar, a rever, etc.).

## O que vai guardar aqui
- [[cortex/modes/boot|boot]] — arranque do sistema
- [[cortex/modes/morning|morning]] — resumo da manhã
- [[cortex/modes/work|work]] — foco profissional
- [[cortex/modes/build|build]] — projetos / código / construção
- [[cortex/modes/focus|focus]] — concentração numa tarefa
- [[cortex/modes/reflect|reflect]] — pensamentos, decisões e padrões
- [[cortex/modes/recovery|recovery]] — energia, descanso, saúde
- [[cortex/modes/review|review]] — revisão semanal / mensal
- [[cortex/modes/night|night]] — fecho do dia
- [[cortex/modes/archive/index|archive]] — modos antigos / descontinuados

## Como o CortexCore vai usar
Cada modo define que áreas, que dados e que parte da [[cortex/queue/000_queue|Queue]] mostrar. No futuro, a [[cortex/interface/dashboard|interface]] muda de aspeto conforme o modo ativo. Os modos não são automações — são **lentes de contexto**.

## Diferença para routines
- [[cortex/routines/000_routines|Routines]] = processos que *acontecem* (correm e fazem algo).
- Modes = *lentes* que filtram o que é mostrado num dado contexto.
Um modo pode ser ativado por uma routine, mas não é a mesma coisa.

## Ideias discutidas
- O sistema deve mostrar pouco e certo, não muito e disperso.
- Modos espelham o ritmo do dia do Operator.

## Estado atual
Base explicativa. **Sem automações, sem n8n, sem scripts.**

## Próximos passos
- [ ] definir, por modo, que áreas e dados aparecem
- [ ] decidir como o modo ativo é escolhido (manual vs. sugerido)
