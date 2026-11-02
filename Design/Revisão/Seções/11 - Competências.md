# 11 · Competências (regras gerais)

**Arquivo:** `Regras/Competências/Competências.md` (e `en/`)
**Relacionadas:** Progressão, Criação de Personagem (4 - Competências), `Design/Competências/Fundamento.md`
**Status:** concluída (PR #33, mergeado em 2026-11-02)

## O que está estabelecido

- **Competências** são formas de agir com identidade e uma progressão fixa de até 5 Níveis (menos, se a progressão indicar). Cada Nível concede seu conteúdo automaticamente, e é preciso ter os Níveis anteriores.
- **Capacidades** são os efeitos dos Níveis. Podem modificar qualquer regra e substituir um Atributo, uma Perícia ou uma fórmula. Em caso de conflito, a Capacidade prevalece no seu contexto.
- **Várias Competências** podem ser combinadas, como multiclasse. O **Nível Total** é a soma dos Níveis e serve só para calcular o custo.
- **Criação:** 2 Pontos de Competência (Nível 2 em uma ou Nível 1 em duas).
- **Campanha:** cada novo Nível custa novo Nível Total × 3 XP, sem limite de Nível Total.
- **Formato** de uma Competência e **lista** das 14 Competências.

## Análise

### Mecânica

1. **O modelo é sólido.** O custo pelo Nível Total impede comprar vários Níveis 1 baratos, e não há escolhas em catálogo. É coerente com a Progressão revisada na seção 10 (D-036). Não proponho mudança mecânica.
2. **A Capacidade prevalece sobre tudo no seu contexto.** É o mesmo princípio de Reserva de Dados ("uma Capacidade sempre prevalece"). Está coerente.

### Texto e estrutura

3. **A seção Nível repete a mesma regra três vezes:**
   - "de 0 a 5, salvo quando sua progressão indicar um máximo menor";
   - "Competências mais simples podem possuir menos Níveis...";
   - "nenhuma Competência pode ultrapassar o Nível 5 nem o máximo indicado".

   Ter os Níveis anteriores também aparece duas vezes.
4. **A criação está escrita duas vezes.** A seção "Criação de personagem" repete quase palavra por palavra `Criação de Personagem/4 - Competências.md`. A regra de criação é da Criação.
5. **"Formato de uma Competência" é orientação de autoria.** Diz como uma Competência é escrita, assunto que o `Fundamento` já cobre com mais detalhe. Para quem joga, ajuda só a saber que a página tem tabela e seções por Nível. Isso cabe em uma frase.
6. **O rodapé está errado (problema objetivo).** É a única página de área que volta para Personagens. Todas as outras voltam para o Astra (Readme). Provavelmente sobrou de quando Competências ficava dentro de Personagens.
7. **A lista de Competências pode desatualizar.** Cada linha resume uma Competência, e as seções 12 a 25 podem mudar o conteúdo. Proponho que cada PR de Competência também atualize a sua linha da lista.
8. **O `Fundamento` está desatualizado** (fora da wiki). O aviso de "estado da reestruturação" e os exemplos com Escaramuçador e Atirador de Guerra, que não existem, são de uma fase anterior. Ele é leitura obrigatória antes de mexer em Competências (pelo `CLAUDE.md`), então vale corrigir. Registro na Q-003 (resíduos em `Design/`) e não mexo agora.

## Propostas

### P-11.1 · Rodapé (problema objetivo)

Trocar "← Voltar para Personagens" por "← Voltar ao Astra", como nas outras áreas.

### P-11.2 · Enxugar a página (texto e estrutura)

- **Nível:** uma frase para o máximo e uma para a exigência dos Níveis anteriores.
- **Criação de personagem:** uma frase com link ("Na criação, o personagem recebe 2 Pontos de Competência; ver Criação de Personagem"). A regra completa fica na Criação.
- **Formato de uma Competência:** uma frase dizendo que cada Competência traz uma tabela de Progressão e uma seção por Nível.
- **Mantêm-se:** Capacidades, Mais de uma Competência, Nível Total, Aquisição durante a campanha (com a tabela, que é onde a Progressão agora aponta) e a lista.

Nenhuma regra muda.

### P-11.3 · Lista atualizada a cada Competência (processo)

Nas seções 12 a 25, cada PR de Competência também revisa a linha dela na lista.

## Decisões do autor (2026-11-02)

- **P-11.1, P-11.2 e P-11.3:** aprovadas (D-037).
