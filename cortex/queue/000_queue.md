# Queue

Fila organizada de coisas abertas. A pasta chama-se **`queue.

## Objetivo
Reunir, num só sítio, tudo o que está em aberto e precisa de atenção, ordenado por importância real.

## Significado
Ainda vamos debater o significado final. Por agora pode ser entendido como **"Queue of Open items"** — uma fila organizada de coisas abertas.

## O que vai guardar aqui
- [[open|open]] — itens abertos (em curso)
- [[priority|priority]] — o que precisa de atenção agora
- [[waiting|waiting]] — à espera de terceiros
- [[snoozed|snoozed]] — adiados para depois
- [[muted|muted]] — silenciados (sem alertas)
- [[closed|closed]] — fechados / resolvidos
- [[rules|rules]] — regras de triagem e prioridade
- [[cortex/queue/archive/index|archive]] — arquivo de itens antigos

## Fluxo
`inbox → unprocessed → qo → daily / área / projeto → archive`

## Attention Score
Cada item pode ter um **Attention Score** que mede a atenção que precisa.

- **Escala:** 0 a 100.
- **Considera:** urgência, importância, idade, prazo, impacto e risco de esquecimento.
- **mention_count:** quantas vezes o mesmo assunto foi mencionado. Um item com score baixo mas mencionado várias vezes deve **subir ou ser sinalizado**.

### Campos futuros possíveis
- `attention_score`
- `mention_count`
- `last_mentioned`
- `recurring_signal`
- `status`
- `due_date`
- `reminder_policy`

## Como o CortexCore vai usar
O QO é onde o sistema decide o que mostrar no [[cortex/daily/focus|foco]] do dia. As [[rules|regras]] definem como calcular o score e mover itens entre estados.

## Estado atual
Base inicial com os estados e o conceito de Attention Score.

## Próximos passos
- [ ] fechar o significado de `qo`
- [ ] definir a fórmula do Attention Score
- [ ] decidir como `mention_count` é incrementado
