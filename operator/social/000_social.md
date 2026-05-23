# Operator — Social

Contexto humano: pessoas e relações. (`social` substitui `circle`.)

## Objetivo
Guardar o contexto humano do Operator — não apenas uma lista de contactos, mas as relações, o histórico e o que importa nas pessoas à volta do Operator.

## Nome da área
A área chama-se **`social`**. Decisão fechada: não usar `circle`, `people` nem `relationships`.

## O que vai guardar aqui
- pessoas importantes e o seu contexto
- relações e histórico relevante
- preferências e notas sobre cada pessoa
- lembretes sociais (datas, follow-ups)
- ligações profissionais/pessoais, quando fizer sentido

## Como o CortexCore vai usar
Dá contexto humano a lembretes, ao [[cortex/daily/000_daily|daily]] e às decisões. Pode cruzar com [[professional/000_professional|professional]] (ligações profissionais). Dados sociais são **sensíveis**: seguir [[cortex/protocols/privacy|privacy]] e nunca versionar dados pessoais em bruto no GitHub.

## Ideias discutidas
- "social" descreve melhor o âmbito do que "circle": é contexto humano, não só um círculo de contactos.
- Substitui a antiga `circle`; nomes alternativos (`people`, `relationships`) foram postos de parte.

## Estado atual
Base explicativa, sem dados reais.

## Próximos passos
- [ ] definir que campos guardar por pessoa (sem dados sensíveis em bruto)
- [ ] decidir como entram os lembretes sociais
