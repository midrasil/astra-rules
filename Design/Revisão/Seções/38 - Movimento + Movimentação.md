# 38 · Movimento (índice) + Movimentação

**Arquivos:** `Regras/Movimento/Movimento.md` e `Regras/Movimento/Movimentação.md` (e `en/`)
**Relacionadas:** Saltar, Correr, Manobras (Reposicionar, Q-016), Zonas (D-062), Mecânica Básica (arredondamento), Equipamentos (Sobrecarga), Armaduras (Força mínima), Lento, Caído, Características de NPC (Aquática, Voadora, Reservas de resistência)
**Status:** decidida (D-064) e aplicada; aguardando o merge do PR

## O que está estabelecido

- Movimentação base: 6 quadrados. Efeitos alteram a base, e regras que usam a base (como a Esquiva) usam o valor alterado.
- A Movimentação pode vir antes ou depois da Ação.
- 1 ponto por quadrado, diagonal inclusive. Aliados podem ser atravessados; inimigos não.
- Terreno Difícil e Movimentação Especial (nadar, escalar, rastejar) custam 2 cada, e os custos se somam.
- Sair do alcance de um inimigo não provoca nada, salvo Capacidades.
- Voo segue a fonte que o concede.

## Análise

### Mecânica

1. **O núcleo é bom.** Uma grade sem custo extra na diagonal, um único multiplicador (2) para tudo que é difícil, e nenhum ataque de oportunidade por padrão. É rápido e deixa as Competências (Sentinela) criarem as exceções.
2. **Não está claro se a Movimentação pode ser dividida (lacuna).** "Antes ou depois da Ação" pode ser lido como "toda antes ou toda depois". Outras regras já supõem a divisão: Saltar usa Movimentação antes da Ação como Impulso, e Mirar diz que você pode se mover antes de Mirar. Proponho dizer que a Movimentação pode ser dividida, parte antes e parte depois da Ação.
3. **Quem bloqueia a passagem (lacuna pequena).** A página fala de aliados e inimigos, mas Confrontar já reconhece NPCs neutros. Proponho que só aliados possam ser atravessados: qualquer outra criatura bloqueia.
4. **Ordem dos modificadores e mínimo (lacuna pequena).** A Sobrecarga reduz a base à metade; Lento e a Força mínima de armadura tiram 2. A ordem muda o resultado (6 → metade 3 → -2 = 1, ou 6 → -2 = 4 → metade 2), e nada diz que a Movimentação não fica negativa. Proponho: primeiro as reduções à metade, depois as somas e subtrações, com mínimo 0.
5. **Dano de queda não existe (Q-016, lacuna).** Reposicionar já empurra criaturas de bordas, e Voadora diz que uma criatura Caída no ar cai. A Perícia Acrobacia diz "amortecer quedas", mas nenhuma regra usa isso. Proponho tratar a queda como uma [Zona de dano](../../../Regras/Cenas%20e%20Conflitos/Zonas.md#zonas-de-dano): reaproveita uma regra existente, usa a Acrobacia como a Perícia promete e ignora a armadura, o que faz sentido para uma queda.
   - **Dano:** metade da altura em quadrados (arredondada para baixo), Tipo Contusão. Uma queda de 1 quadrado não causa dano; 4 quadrados (6 m) causam 2; 10 quadrados (15 m) causam 5.
   - **Resistência:** Agilidade + Acrobacia, como em uma Zona. Uma criatura que não pode resistir conta como 1 Sucesso.
   - **Caído:** quem sofre qualquer dano da queda termina [Caído](../../../Regras/Condições/Caído.md).
   - **Descer de propósito:** quem salta para baixo de propósito desconta da queda a altura do seu [Salto Vertical](../../../Regras/Movimento/Saltar.md#salto-vertical).
6. **"Teste separado de Vigor" não diz a Reserva (problema objetivo pequeno).** No Astra, testes são Atributo + Perícia ou dois Atributos. O padrão já decidido para resistir a efeitos no corpo (D-056) é Vigor + Determinação. Proponho usar esse.

### Texto e estrutura

7. **O índice está bom.** Movimento.md lista as três páginas e suas relações; não mudaria.
8. **A seção "Salto" em Movimentação repete o índice.** Ela só aponta para Saltar. É curta e útil para quem lê Movimentação de cima a baixo; não mudaria.

## Propostas

### P-38.1 · Divisão, passagem e modificadores (lacunas)

- No lugar de "A Movimentação pode ser realizada antes ou depois da Ação do personagem, de acordo com a ordem que ele preferir.": "A Movimentação pode ser usada antes e depois da Ação, e dividida entre os dois momentos como o personagem preferir."
- Em Deslocamento: "Um personagem pode atravessar um quadrado ocupado por um **aliado** (sem permanecer nele), mas não um quadrado ocupado por qualquer outra criatura."
- Depois do parágrafo dos efeitos que alteram a base: "Aplique primeiro as reduções à metade e depois as somas e subtrações. A Movimentação nunca fica abaixo de 0."

### P-38.2 · Queda (fecha a Q-016)

Nova seção "Queda" em Movimentação, com o texto do item 5 e um exemplo: "Uma criatura empurrada de um muro de 5 quadrados sofre uma Zona de Dano 2 de Contusão e resiste com Agilidade + Acrobacia. Se sofrer qualquer dano, termina Caída."

- **Alternativa:** dano fixo sem teste (metade da altura, agravado), sem usar a Acrobacia.

### P-38.3 · Reserva de exaustão (texto)

"Provas prolongadas de resistência ou exaustão podem exigir um teste separado de **Vigor**" vira "...podem exigir um teste de **Vigor + Determinação**".

## Decisões do autor (2026-11-03)

- **P-38.2:** substituída a pedido do autor ("queda não é uma resistência"), no modelo do D&D 5e (1d6 a cada 10 pés, máximo 20d6, sem teste): 1 de dano de Contusão a cada 2 quadrados, sem teste, sem Absorção, máximo 10; quem sofre dano termina Caído; quem salta para baixo de propósito desconta a altura do Salto Vertical (D-064). Fecha a Q-016.
- **P-38.1 e P-38.3:** aprovadas (D-064).
