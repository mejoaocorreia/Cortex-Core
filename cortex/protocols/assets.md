# Assets Protocol

Regras para ficheiros e anexos.

## Objetivo
Definir onde vivem os ficheiros e anexos, e como tratá-los com segurança.

## O que regula
- onde guardar cada anexo
- o que pode/não pode ir para o GitHub
- triagem de ficheiros por tratar

## Regras
- Ficheiros e anexos devem ficar **junto da área/projeto** a que pertencem (ex.: ficheiros do website em `professional/previmed/website/`).
- [[cortex/assets/_temp|cortex/assets/]] é **só para assets do núcleo** CortexCore/interface/sistema.
- Anexos **sensíveis não vão para o GitHub em bruto** (ver [[cortex/protocols/privacy|privacy]]).
- Ficheiros temporários ou por tratar devem ter uma **regra futura de triagem** (mover para o sítio certo ou apagar).

## Como o CortexCore vai usar
Agentes que criam ou movem ficheiros seguem estas regras. Liga-se ao [[cortex/protocols/capture_flow|capture_flow]] (anexos também são "capturas") e ao [[cortex/protocols/archive|archive]].

## Ideias discutidas
- Manter o anexo perto do seu contexto evita pastas globais difíceis de gerir.

## Estado atual
Base explicativa.

## Próximos passos
- [ ] definir a regra de triagem de anexos por tratar
