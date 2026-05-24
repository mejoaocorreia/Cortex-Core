# Command Routing

Ideia futura de comandos/atalhos que encaminham o agente para o contexto certo.

## Objetivo
Preparar (sem implementar) uma forma simples de o Operator dizer ao agente **em que contexto trabalhar**, reduzindo ambiguidade sobre área, path, repo e limites de atuação.

## Importante (estado atual)
- Estes comandos **não são automações** nem comandos funcionais ainda.
- **Nada está implementado** em `.claude/commands/`.
- Este ficheiro descreve apenas a **ideia conceptual**.

## Comandos conceptuais
- `/cortex` → trabalhar no núcleo CortexCore
- `/operator` → contexto pessoal / operator
- `/professional` → contexto profissional geral
- `/previmed` → entrar no contexto Previmed
- `/website` → entrar no website principal da Previmed
- `/careview` → entrar no projeto Careview
- `/car` → contexto do carro
- `/health` → contexto de saúde
- `/wealth` → contexto financeiro / wealth
- `/learning` → contexto de aprendizagem

## O que cada comando deve indicar (no futuro)
Quando forem desenhados, cada comando deverá declarar:
- **área** — a que parte do sistema pertence;
- **path local** — onde vivem os ficheiros;
- **repo correto** — Cortex-Core ou um repo externo (ver [[cortex/protocols/external_repos|external_repos]]);
- **ficheiros de contexto a ler primeiro** — seguindo a [[cortex/protocols/context_ladder|context_ladder]];
- **limites de atuação** — o que pode e não pode tocar;
- **se pode ou não fazer commit** — e em que repo;
- **que agente/supervisor usar** — ver [[cortex/protocols/agents|agents]].

## Porquê
- Reduzir **ambiguidade**: o Operator diz o contexto numa palavra.
- Evitar misturar áreas e, sobretudo, **misturar commits entre repos**.
- Garantir que o agente lê o contexto certo antes de agir.

## Como o CortexCore vai usar
Por agora, serve de referência mental: quando o Operator menciona uma destas áreas, o agente trata-a como o contexto-alvo, mesmo sem comando real. Quando os comandos forem implementados, passam a formalizar esta orientação.

## Estado atual
Apenas ideia documentada. Sem implementação.

## Próximos passos
- [ ] definir, para cada comando, os campos acima (área, path, repo, contexto, limites, commit, agente)
- [ ] decidir quais áreas têm repo próprio vs. vivem dentro do Cortex-Core
- [ ] só depois avaliar implementação real em `.claude/commands/`
