# CortexCore

CortexCore é um sistema pessoal de memória, contexto, automação e agentes — um "cérebro digital" pessoal.

## O que é
- **Obsidian** como base de memória (este Vault).
- **GitHub** para código, estrutura e templates; dados sensíveis não entram no repositório.
- **n8n** para rotinas e automações.
- Uma futura **interface / dashboard** estilo Obsidian.

## Estrutura mental
- O **Vault inteiro** representa o CortexCore. Por isso não existe uma pasta `cortexcore` dentro do Vault.
- A pasta **`cortex/`** é o núcleo operativo: regras, memória, versões, rotinas, sistema, interface, fila de atenção (queue), status, modes, daily e agentes principais.
- As restantes pastas de topo (`operator`, `professional`, `learning`, `health`, `wealth`, `car`, `archive`) são as áreas principais. O `operator` representa a pessoa real por trás do sistema (o utilizador).

## Aviso importante
- Esta é uma **base inicial explicativa** (versão `0.00.0`). São rascunhos e orientação, não conteúdo final.
- **Não contém dados reais**, pessoais ou sensíveis.
- **Dados sensíveis não devem ir para o GitHub** em bruto. Ver [[cortex/system/security|security]] e [[cortex/system/github|github]].

## Por onde começar
- [[000_boot|000_boot]] — painel de entrada do Vault.
- [[cortex/000_cortex|cortex]] — núcleo operativo.
- [[cortex/versions/v0.00.0|versão 0.00.0]] — estado atual.

## Estado atual
Estruturação inicial: pastas e ficheiros `.md` explicativos.

## Próximos passos
- [ ] preencher contexto real, quando fizer sentido
- [ ] configurar GitHub e n8n
- [ ] desenhar a interface / dashboard
