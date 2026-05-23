# Queue Archive

Arquivo de itens antigos da fila.

## Objetivo
Guardar itens já fechados há algum tempo, fora da fila ativa.

## O que vai guardar aqui
- itens encerrados, organizados por data quando fizer sentido

## Como o CortexCore vai usar
Depois de um período em [[closed|closed]], os itens vêm para aqui. Servem de histórico de longo prazo, mas não são lidos no dia a dia (ver [[cortex/protocols/context_ladder|context_ladder]]).

## Estado atual
Vazio. Por preencher.

## Próximos passos
- [ ] definir estrutura do arquivo (por ano/mês?)
