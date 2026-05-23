# Previmed

Ficheiro ponte do Cortex-Core para o projeto Previmed.

A pasta `professional/previmed/` contém um repositório Git separado, mantido dentro da árvore local do Cortex-Core por conveniência de navegação e trabalho no VS Code. Este ficheiro vive **fora** desse repo (em `professional/previmed.md`) porque o Git não permite que o Cortex-Core versione ficheiros dentro de um repositório embutido sem o transformar em submodule.

## Repositório
Repo principal da Previmed:
<!-- colocar aqui o link do repositório Previmed quando estiver definido -->

## Relação com CortexCore
O CortexCore usa este ficheiro apenas como ponte documental.

O CortexCore guarda:
- contexto geral;
- ligação ao projeto;
- regras de navegação;
- referência ao repositório real.

O repositório Previmed guarda:
- código;
- agentes próprios;
- comandos;
- skills;
- records;
- documentação própria;
- histórico Git próprio.

## Regras
- Commits do Cortex-Core não devem incluir ficheiros internos do repo Previmed (a pasta `professional/previmed/` está totalmente ignorada).
- Commits da Previmed devem ser feitos dentro do repo Previmed.
- Este ficheiro `previmed.md` é versionado pelo Cortex-Core e vive em `professional/previmed.md` (ao lado da pasta, não dentro dela).
- Antes de fazer commit, confirmar sempre qual é o repo ativo no VS Code ou no terminal.

## Estado atual
Ligação documental inicial entre Cortex-Core e o repo Previmed.

## Próximos passos
- [ ] adicionar link final do repositório Previmed
- [ ] documentar como o CortexCore deve chamar ou referenciar este projeto
- [ ] confirmar que o Cortex-Core só vê este ficheiro (e não o conteúdo de `professional/previmed/`)
