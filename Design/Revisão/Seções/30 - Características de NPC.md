# 30 · Características de NPC

**Arquivo:** `Regras/Criaturas/Características de NPC.md` (e `en/`)
**Relacionadas:** Atributos (Escala; seção 02), Vida (Trilha de Vida Preenchida), Vontade (D-026), Movimentação, Zonas, Armaduras (Absorção), Armas (Alcance), Tamanho, Condições (Medo, Envenenado, Paralisado, Atordoado, Agarrado), Iluminação, Q-007, Q-011
**Status:** decidida (D-056) e aplicada; aguardando o merge do PR

## O que está estabelecido

- Características próprias de NPCs, fora do sistema de Competências, com valores padrão entre parênteses, configuráveis em cada criatura. A **Potência** é a Dificuldade do teste para resistir.
- **Movimentos especiais:** Aquática, Voadora, Escavadora, Escaladora.
- **Efeitos ao acertar** (ao vencer um Ataque com um Ataque natural corpo a corpo): Venenosa (Vigor + Determinação), Paralisante (Vigor + Força), Atordoante (Determinação + Astúcia), Infecciosa (tudo definido na criatura).
- **Ataques especiais:** Frenesi, Frenesi Aprimorado, Sopro, Investida, Ir para a Garganta, Constritora, Aterrorizante (Determinação + Astúcia, causa Medo), Teia, Emboscada Subterrânea, Enxame.
- **Recuperação:** Regeneração. **Sentidos:** Visão no Escuro.

## Análise

### Mecânica

1. **O catálogo está bem feito.** Cada característica é curta, tem valores padrão configuráveis e usa regras que já existem (Zonas, Condições, Margem, Absorção). Ele dá ao Narrador ferramentas sem criar um sistema paralelo.
2. **"Ataque natural" não está definido em lugar nenhum (lacuna).** Os Efeitos ao acertar e a Constritora dependem dele, mas nenhuma página diz o que é, nem de onde vêm seu Dano, Tipo de Dano, Alcance e Reserva. A leitura natural é "garras, mordidas e afins, tratados como uma arma da criatura", e uma frase resolve.
3. **Não há ficha de criatura no núcleo (observação maior).** Além do Ataque natural, o núcleo não diz como se definem a Vida, a Vontade e a Absorção base de uma criatura, nem se ela segue as fórmulas dos personagens. Na prática, o Narrador usa as fórmulas dos personagens. Resolver isso é escrever um guia de criação de criaturas, o que é trabalho novo e grande. Proponho abrir uma questão (Q-014) em vez de resolver nesta seção.
4. **Atributos acima de 5 (Q-007, decisão do autor).**
   - A Escala vai até 5, "Auge humano". Isso sugere que existe algo além do humano, mas nenhuma regra diz se uma criatura pode passar de 5.
   - Um dragão com Força 5 tem a força de um atleta humano no auge, o que não parece a intenção.
   - **Opção A:** criaturas podem ter Atributos acima de 5; personagens continuam limitados a 5.
   - **Opção B:** o teto é 5 para todos, e criaturas fortes se diferenciam por Tamanho, Dano e características.
5. **Reservas de resistência sem padrão (Q-007).**
   - Hoje: Venenosa usa Vigor + Determinação, Paralisante usa Vigor + Força, Atordoante e Aterrorizante usam Determinação + Astúcia, e a Infecciosa não tem Reserva padrão.
   - Há um padrão quase completo: **efeitos no corpo** usam Vigor + Determinação; **efeitos na mente** usam Determinação + Astúcia. A exceção é o Paralisante, com Força.
   - Ter esse padrão escrito ajuda o Narrador a criar características novas e dá à Infecciosa um ponto de partida. As características que já têm Reserva própria podem continuar com ela, porque os valores já são configuráveis.
6. **Aterrorizante e dano de Vontade (Q-011).** A Q-011 pergunta se o Aterrorizante deveria causar dano de Vontade. Pela D-026, a Vontade é um recurso, e dano externo só existe quando uma regra específica o define. O Aterrorizante já tem um efeito claro (Medo, -1 dado por acúmulo). Somar dano de Vontade faria a criatura gastar um recurso do jogador sem que ele escolhesse, o que vai contra a D-026. **Não proponho mudança.** A parte da Q-011 sobre Condições fica para a seção 48.
7. **A Regeneração funciona com a trilha de Vida (observação).** O personagem só fica Incapacitado quando toda a trilha está agravada. Como a Regeneração converte agravado em superficial a cada Turno, a criatura só cai quando a Regeneração é interrompida. É o comportamento esperado de um troll e combina com a regra de Interrupção.
8. **A Teia não tem Alcance (lacuna).** É um Ataque à distância, mas não diz até onde vai.
9. **Frenesi: "outro alvo adjacente" (ambiguidade pequena).** Uma criatura com Ataque natural de Alcance 2 (uma cauda, por exemplo) não poderia usar o Frenesi contra um alvo a 2 quadrados. Se a intenção é "outro alvo que ela consiga atacar", o texto deveria dizer Alcance.
10. **Sopro sem valor padrão (observação).** É a única característica com valores no título sem número padrão. Funciona, porque o Dano é definido na criatura, mas foge do padrão da página. Não proponho mudança: um número padrão de Dano depende da ficha de criatura (Q-014).

### Texto e estrutura

11. **Aterrorizante repete a mesma regra duas vezes.** "Quem vê a criatura pela primeira vez na cena" e "Acontece uma vez por cena para cada personagem" dizem a mesma coisa.
12. **"Token" no Enxame.** É um anglicismo de mesa virtual. O Tamanho usa "o espaço que ocupa".

## Propostas

### P-30.1 · Ataque natural (lacuna) e Q-014

- Na introdução, depois do primeiro parágrafo, acrescentar:

> Um **Ataque natural** é um Ataque feito com o corpo da criatura, como garras, mordidas, chifres ou ferrões. A ficha da criatura define seu Dano, Tipo de Dano e Alcance, como os de uma [arma](../Equipamentos/Armas.md), e ele usa **Agilidade + Lutar**, salvo quando a ficha indicar outra Reserva.

- Abrir a **Q-014 · Ficha de criatura**: como definir Vida, Vontade, Absorção base e Ataques naturais de NPCs. Gatilho: seção 53 (ou um futuro guia de criaturas).

### P-30.2 · Atributos acima de 5 (Q-007, decisão do autor)

- **(a)** Na Escala de [Atributos](../Personagens/Atributos.md#escala), acrescentar: "Criaturas que não são humanas podem ter Atributos acima de 5; personagens ficam limitados a 5."
- **(b)** Teto 5 para todos, escrito na mesma Escala.

**Recomendo (a).** A própria Escala trata o 5 como limite humano, e um dragão deve poder superá-lo.

### P-30.3 · Reservas padrão de resistência (Q-007)

- **(a)** Em "Valores configuráveis", acrescentar: "Quando uma característica não indicar a Reserva para resistir, use **Vigor + Determinação** contra efeitos no corpo e **Determinação + Astúcia** contra efeitos na mente." As características atuais ficam como estão, inclusive o Paralisante com Força.
- **(b)** O mesmo de (a), e o Paralisante passa a usar Vigor + Determinação, para seguir o padrão.
- **(c)** Manter caso a caso, sem padrão.

**Recomendo (a).** Dá um ponto de partida sem mudar nenhuma característica que já existe. Com isso, a Q-007 fica resolvida.

### P-30.4 · Aterrorizante sem dano de Vontade (Q-011)

Manter como está. A parte da Q-011 sobre características de NPC fica fechada; a parte sobre Condições segue para a seção 48.

### P-30.5 · Texto

- **Frenesi:** "contra outro alvo adjacente" vira "contra outro alvo ao seu Alcance".
- **Teia:** acrescentar Alcance ao título, com valor padrão **6**: "Teia (Potência 2; Alcance 6; Ataque: Agilidade + Atirar; escapar: Força + Atletismo)", e na descrição, "um Ataque à distância, até o Alcance, com **Agilidade + Atirar**".
- **Aterrorizante:** tirar "Acontece uma vez por cena para cada personagem."
- **Enxame:** "dentro do token ou adjacentes" vira "no espaço que ela ocupa ou adjacentes".

## Decisões do autor (2026-11-02)

- **Reestruturação proposta pelo autor:** uma lista única de Capacidades, sem Nível nem restrição, usada pelas Competências (progressões fixas) e pelos NPCs (Capacidades soltas). Discutimos trocar as Competências por feats e decidimos **manter as Competências** para os jogadores. O tema virou a Q-015 e será desenhado à parte.
- **P-30.1:** aprovada. "Ataque natural" definido; a ficha de criatura virou a Q-014 (D-056).
- **P-30.2:** opção (a). Criaturas não humanas podem passar de 5; personagens ficam em 5 (D-056).
- **P-30.3:** opção (a). Reservas padrão para resistir, sem mudar as características atuais (D-056). A Q-007 está resolvida.
- **P-30.4:** o Aterrorizante não causa dano de Vontade (D-056). A parte de NPCs da Q-011 está fechada.
- **P-30.5:** aprovada (D-056).
