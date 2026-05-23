# Queue — Waiting

Itens à espera de terceiros.

## Objetivo
Separar o que está bloqueado por algo ou alguém externo, para não poluir a fila ativa.

## O que vai guardar aqui
- itens em pausa à espera de resposta, entrega ou condição externa
- de quem/de quê se espera e desde quando

## Como o CortexCore vai usar
Itens aqui não pesam no foco diário, mas devem ser revistos periodicamente. Se a espera se arrastar, o `attention_score` pode subir.

## Estado atual
Por preencher.

## Próximos passos
- [ ] definir periodicidade de revisão dos itens em espera
