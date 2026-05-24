# External Repos

Como o CortexCore lida com projetos que vivem em repositórios Git separados.

## Objetivo
Deixar claro que o sistema principal (Cortex-Core) pode coexistir com outros repositórios no mesmo workspace, e definir como o agente se orienta entre eles sem misturar contextos nem commits.

## O que é o Cortex-Core
- O **Cortex-Core** é o sistema principal — a estrutura, os protocolos e o contexto do Operator.
- É também o repositório onde vive esta documentação.

## Repositórios separados
- Alguns projetos podem viver em **repositórios Git separados**, com o seu próprio histórico, agentes, comandos e documentação.
- O repo **Previmed** está localmente dentro de `professional/previmed/` (ver [[professional/previmed|previmed]] como ponte documental).
- A pasta `professional/previmed/` é um repo embutido e está totalmente ignorada pelo `.gitignore` do Cortex-Core (ver [[cortex/protocols/privacy|privacy]]).

## Workspace partilhado (VS Code)
- O VS Code workspace pode abrir o **Cortex-Core** e o **Previmed** ao mesmo tempo.
- Isto significa que a sessão (VS Code / Claude / Codex) pode ver e trabalhar nos dois repositórios em simultâneo.
- O ficheiro de workspace (`*.code-workspace`) é local e está ignorado pelo Git.

## Regras de atuação (fase inicial)
- Nesta fase, o agente **pode consultar e alterar ambos os repos** se a tarefa o pedir.
- Antes de qualquer commit, o agente deve **confirmar claramente em que repo está**:
  - **Cortex-Core**
  - **Previmed**
- Os commits são **separados por repositório**:
  - Alterações na estrutura do Cortex-Core → commit no **Cortex-Core**.
  - Alterações no repo Previmed → commit no **repo Previmed**.
- **Nunca misturar** ficheiros de um repo num commit do outro.

## Futuro
- Futuramente, comandos/atalhos vão **encaminhar o agente para o contexto correto** (área, path, repo, ficheiros a ler primeiro, limites e permissão de commit).
- A ideia desses atalhos está descrita em [[cortex/protocols/command_routing|command_routing]].

## Como o CortexCore vai usar
Sempre que uma tarefa toca num projeto que tem repo próprio, o agente identifica primeiro o repo ativo, segue as regras de separação de commits, e só depois age.

## Estado atual
Base explicativa. Único repo externo conhecido: Previmed.

## Próximos passos
- [ ] confirmar o link final do repositório Previmed (ver [[professional/previmed|previmed]])
- [ ] desenhar os comandos de routing (ver [[cortex/protocols/command_routing|command_routing]])
- [ ] listar aqui novos repositórios externos conforme surgirem
