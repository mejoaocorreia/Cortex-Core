# Archive Protocol

Regras de arquivo e de onde procurar informação.

## Objetivo
Definir como se arquiva e, sobretudo, **por que ordem** se procura informação — para não desperdiçar contexto a ler arquivos cedo demais.

## O que regula
- onde vive o arquivo de cada coisa
- a ordem de procura ao responder
- a diferença entre arquivo temporal e contextual

## Regras
- Cada área tem o **seu próprio archive**.
- O **archive global** ([[archive/index|/archive]]) é o **último recurso**.
- Os agentes **não devem começar pelo archive**. A ordem de procura é:
  1. **contexto ativo** (o que está em cima da mesa)
  2. **área relevante** (ex.: [[professional/000_professional|professional]])
  3. **archive da área**
  4. **archive global**
- O **daily archive** deve ser **temporal** (por ano/mês/data) — ver [[cortex/daily/archive/index|daily/archive]].
- O **archive de projeto** deve ser **contextual** (organizado pelo tema do projeto).

## Como o CortexCore vai usar
Liga-se ao [[cortex/protocols/context_ladder|context_ladder]]: ler por camadas, do mais próximo ao mais distante. Agentes e [[cortex/routines/000_routines|routines]] seguem esta ordem antes de tocar em arquivos.

## Ideias discutidas
- Arquivo é memória de longo prazo, não a primeira fonte de consulta.

## Estado atual
Base explicativa.

## Próximos passos
- [ ] definir a estrutura temporal do daily archive
