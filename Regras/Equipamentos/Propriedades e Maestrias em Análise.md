Rascunho de trabalho. Lista as versões brutas, ainda em inglês, de propriedades e maestrias de armas candidatas, para analisarmos uma a uma e decidir como cada uma entra em [[Armas]]: se vira **Propriedade**, **Maestria** ou se é descartada.

As entradas parecidas estão agrupadas para tratarmos juntas e, se fizer sentido, fundirmos em uma só. Slow e Nick vieram duplicados na lista original e aparecem uma vez cada.

Legenda do status: ⬜ não analisado · 🟨 em discussão · ✅ decidido · ❌ descartado

## Princípio das Propriedades

As Propriedades são **traços simples da arma**, no estilo do D&D: como ela é empunhada, que tipo de dano causa, como pode ser usada. Elas não dão capacidades especiais. O que é técnica ou capacidade especial vira Maestria.

## Decisões gerais sobre Maestria

- A Maestria vem do Trunfo **Maestria com Arma** (nome provisório): estágio Experiente, repetível, com Arma Predileta como requisito.
- Cada cópia vale para **uma arma Predileta específica** do personagem.
- Ao pegar o Trunfo, **o personagem escolhe a Maestria** que aplica àquela arma. A Maestria não é da arma, é do personagem com aquela arma.
- Qualquer Maestria pode ser aplicada a qualquer arma, sem requisitos. Vamos reavaliar nas sessões de teste.
- Isso muda o texto atual de [[Armas#Maestria]], em que a arma "sempre apresenta" a sua Maestria.

## Regras gerais da Maestria (rascunho para [[Armas#Maestria]])

> Uma **Maestria** é uma técnica que o personagem domina com uma arma específica. Ela não pertence à arma: é o personagem quem escolhe qual Maestria aplica à sua arma ao adquirir o Trunfo **Maestria com Arma**.
>
> Cada cópia do Trunfo vale para **uma** arma Predileta do personagem e lhe dá **uma** Maestria. Qualquer Maestria pode ser escolhida para qualquer arma.
>
> Uma Maestria é ativada ao **vencer um Ataque** com a arma; cada Maestria diz o que mais é preciso e se tem custo. Em empate ela não ativa.
>
> Se a arma Predileta for perdida, a Maestria passa para a substituta junto com a Predileta, seguindo o mesmo prazo de duas semanas de jogo.

### Trunfo Maestria com Arma (rascunho)

- **Estágio:** Experiente
- **Categoria:** Combate
- **Requisito:** Arma Predileta
- **Repetível:** sim, uma cópia por arma Predileta
- **Efeito:** escolha uma das suas armas Prediletas e uma Maestria. Você pode usar essa Maestria com essa arma.

## Plano de implementação

Implementar depois que todos os grupos forem analisados, porque a base serve para todas as Maestrias.

1. **Maestria do personagem, não da arma:** o campo Maestria sai da ficha da arma. Ele passa a ser escolhido no Trunfo Maestria com Arma, junto com a arma Predileta. Os dados antigos do campo da arma precisam de migração.
2. **Trunfo Maestria com Arma** no compêndio do núcleo, com requisito Arma Predileta e repetível.
3. **Lista de Maestrias** no sistema, preenchida conforme as decisões desta nota.
4. **Card do Ataque (Golpe Tático):** quando o Ataque vence com a arma que tem a Maestria, aparece a opção de abrir mão da Margem e escolher a Manobra; o dano cai para o Dano da arma e aparece o botão do efeito, reaproveitando os botões das Manobras.
5. **Condição Embalo**, acumulável, ganha ao vencer um Ataque com a arma; os acúmulos somam dados contra o mesmo alvo e somem ao perder.
6. **Varredura no card:** um segundo dano, superficial e igual ao Dano da arma, para um alvo adjacente ao primeiro.
7. **Propriedade "Manobra (X)":** entra na lista de Propriedades da arma, no grupo Uso. A Reserva da Manobra passa a oferecer as armas com essa Propriedade, e o Alcance vem da arma, sem bônus de dados.
8. Atualizar [[Armas#Maestria]] e [[Armas#Propriedades]] com o texto final.

## Grupo 1 — Manobras com a arma

**Direção decidida:** as duas coisas, cada uma de um lado.
- **Propriedade "Manobra (Reposicionar / Derrubar / Desarmar)"**, a partir de Shove, Trip e Disarm: a manobra indicada pode ser feita com a arma, usando o Alcance dela e um bônus da arma na Reserva.
- **Maestria única "Golpe Tático"** (nome provisório), a partir de Push e Topple: ao vencer um Ataque com a arma, o personagem pode abrir mão da Margem para aplicar o efeito de uma destas Manobras, à sua escolha: **Reposicionar, Derrubar ou Desarmar**. Agarrar não entra. O custo em dano é equilibrado pela versatilidade.
- Propriedade sem bônus na Reserva: só permite fazer a manobra com o Alcance da arma, seguindo o princípio das Propriedades.
- Golpe Tático: ao vencer o Ataque, o personagem escolhe entre o dano normal (Margem + Dano da arma) e abrir mão da Margem, causando só o Dano da arma e aplicando o efeito da Manobra escolhida (Reposicionar, Derrubar ou Desarmar). Em empate não ativa.

Ligam a arma às [[Manobras]] que já existem: [[Manobras#Reposicionar|Reposicionar]], [[Manobras#Derrubar|Derrubar]] e [[Manobras#Desarmar|Desarmar]]. Cada par tem uma versão "permite a manobra com a arma" e uma versão "a manobra acontece ao acertar".

### 1a. Empurrar — Shove + Push ✅

**Shove.** You can use this weapon to Shove with the Athletics skill even if you don't have a free hand. This uses the weapon's reach (if different from your own) and adds the weapon's item bonus to attack rolls as an item bonus to the Athletics check. If you critically fail a check to Shove using the weapon, you can drop the weapon to take the effects of a failure instead of a critical failure.

**Push.** If you hit a creature with this weapon, you can push the creature up to 10 feet straight away from yourself if it is Large or smaller.

- Tipo: Propriedade **Manobra (Reposicionar)** (Shove); Push entra no Golpe Tático.
- Adaptação da Propriedade: o personagem pode Reposicionar usando a arma, até o Alcance dela. Não há bônus na Reserva.
- Maestria: coberta pelo **Golpe Tático**, que aplica este efeito quando a Manobra escolhida é esta.
- Descartado do original: a mão livre (nossas Manobras não exigem), a falha crítica e o empurrão de 10 pés (vira 1 quadrado, como Reposicionar).

### 1b. Derrubar — Trip + Topple ✅

**Trip.** You can use this weapon to Trip with the Athletics skill even if you don't have a free hand. This uses the weapon's reach (if different from your own) and adds the weapon's item bonus to attack rolls as an item bonus to the Athletics check. If you critically fail a check to Trip using the weapon, you can drop the weapon to take the effects of a failure instead of a critical failure.

**Topple.** If you hit a creature with this weapon, you can force the creature to make a Constitution saving throw (DC 8 plus the ability modifier used to make the attack roll and your Proficiency Bonus). On a failed save, the creature has the Prone condition.

- Tipo: Propriedade **Manobra (Derrubar)** (Trip); Topple entra no Golpe Tático.
- Adaptação da Propriedade: o personagem pode Derrubar usando a arma, até o Alcance dela. Não há bônus na Reserva.
- Maestria: coberta pelo **Golpe Tático**, que aplica este efeito quando a Manobra escolhida é esta.
- Descartado do original: a mão livre, a falha crítica e o teste de Constituição.

### 1c. Desarmar — Disarm ✅

**Disarm.** You can use this weapon to Disarm with the Athletics skill even if you don't have a free hand. This uses the weapon's reach (if different from your own) and adds the weapon's item bonus to attack rolls (if any) as an item bonus to the Athletics check. If you critically fail a check to Disarm using the weapon, you can drop the weapon to take the effects of a failure instead of a critical failure. On a critical success, you still need a free hand if you want to take the item.

- Tipo: Propriedade **Manobra (Desarmar)** (Disarm); o efeito de Desarmar também entra no Golpe Tático.
- Adaptação da Propriedade: o personagem pode Desarmar usando a arma, até o Alcance dela. Não há bônus na Reserva.
- Maestria: coberta pelo **Golpe Tático**, que aplica este efeito quando a Manobra escolhida é esta.
- Descartado do original: a mão livre, a falha crítica e a regra de pegar o item no sucesso crítico. Pegar o item continua sendo Trocar Equipamento.

## Grupo 2 — Vários ataques e embalo

Bônus que dependem de já ter atacado no turno, de ter errado ou de ter acertado antes.

### 2a. Bônus no próximo ataque — Backswing + Vex ✅

**Backswing.** You can use the momentum from a missed attack with this weapon to lead into your next attack. After missing with this weapon on your turn, you gain a +1 circumstance bonus to your next attack with this weapon before the end of your turn.

**Vex.** If you hit a creature with this weapon and deal damage to the creature, you have Advantage on your next attack roll against that creature before the end of your next turn.

- Tipo: Maestria **Embalo**, fundindo Backswing e Vex.
- Adaptação: ao vencer um Ataque com a arma, o personagem ganha um acúmulo da Condição **Embalo**, ligada àquele alvo. Cada acúmulo dá +1 dado nos Ataques contra o mesmo alvo. Os acúmulos somam e só valem no Ataque, não ao Confrontar em resposta ou ao Defender. Perder um Ataque tira todos os acúmulos.
- Atacar outro alvo zera os acúmulos. Não há limite de acúmulos. O Embalo acaba no fim do combate.

### 2b. Ataques seguidos — Sweep + Forceful ✅

**Sweep.** This weapon makes wide sweeping or spinning attacks, making it easier to attack multiple enemies. When you attack with this weapon, you gain a +1 circumstance bonus to your attack roll if you already attempted to attack a different target this turn using this weapon.

**Forceful.** This weapon becomes more dangerous as you build momentum. When you attack with it more than once on your turn, the second attack gains a circumstance bonus to damage equal to the number of weapon damage dice, and each subsequent attack gains a circumstance bonus to damage equal to double the number of weapon damage dice.

- Tipo: Maestria **Varredura** (Sweep). **Forceful descartado**, porque depende de vários ataques no mesmo turno e no Astra há uma Ação por turno.
- Adaptação: ao vencer um Ataque com a arma, o personagem também pode causar o Dano da arma, como dano **superficial**, em um alvo adjacente ao primeiro alvo.

### 2c. Ataque extra da arma Leve — Nick ❌

**Nick.** When you make the extra attack of the Light property, you can make it as part of the Attack action instead of as a Bonus Action. You can make this extra attack only once per turn.

Relaciona-se com a Propriedade **Leve** e com o Trunfo Lutar com Duas Armas.

- Tipo: descartado. É o ataque extra da arma Leve, e no Astra o [[Trunfos|Trunfo]] Lutar com Duas Armas já soma o Dano da outra arma, sem ataque extra.

## Grupo 3 — Golpes fortes

Efeitos de acerto crítico. No Astra, o equivalente mais próximo é vencer o Confronto por uma Margem alta.

### 3a. Crítico — Deadly + Fatal ✅

**Deadly.** On a critical hit, the weapon adds a weapon damage die of the listed size. Roll this after doubling the weapon's damage. This increases to two dice if the weapon has a greater striking rune and three dice if the weapon has a major striking rune. For instance, a rapier with a greater striking rune deals 2d8 extra piercing damage on a critical hit. An ability that changes the size of the weapon's normal damage dice doesn't change the size of its deadly die.

**Fatal.** The fatal trait includes a die size. On a critical hit, the weapon's damage die increases to that die size instead of the normal die size, and the weapon adds one additional damage die of the listed size.

- Tipo: Maestria **Golpe Letal** (nome provisório), fundindo Deadly e Fatal.
- Adaptação: funciona como um acerto crítico. Ao vencer um Ataque com a arma, cada par de 10 da rolagem do atacante soma o **Dano da arma** mais uma vez ao dano.
- Descartado do original: os dados de dano, as runas e a troca do tamanho do dado, porque o nosso dano é um valor fixo.

## Grupo 4 — Penalidades no alvo ao acertar

Efeitos que atrapalham o alvo depois de um acerto.

### 4a. Atrasar e atrapalhar — Slow + Sap ✅

**Slow.** If you hit a creature with this weapon and deal damage to it, you can reduce its Speed by 10 feet until the start of your next turn. If the creature is hit more than once by weapons that have this property, the Speed reduction doesn't exceed 10 feet.

**Sap.** If you hit a creature with this weapon, that creature has Disadvantage on its next attack roll before the start of your next turn.

- Tipo: Maestria **Golpe Debilitante** (nome provisório), fundindo Slow e Sap.
- Adaptação: ao vencer um Ataque com a arma, sem custo de Margem, o atacante escolhe um efeito no alvo, que dura até o começo do próximo turno do atacante:
  - **Lento**: −2 de Movimentação (Slow; 10 pés viram 2 quadrados).
  - **Abalado**: −2 dados no próximo Ataque (Sap; Desvantagem vira −2 dados).
- Os efeitos não se acumulam: aplicar de novo só renova a duração.
- Pendência: criar as Condições **Lento** e **Abalado** em [[Condições]], que saem sozinhas no começo do próximo turno do atacante.

## Grupo 5 — Defesa

### 5a. Aparar — Parry ❌

**Parry.** This weapon can be used defensively to block attacks. While wielding this weapon, if your proficiency with it is trained or better, you can spend a single action to position your weapon defensively, gaining a +1 circumstance bonus to AC until the start of your next turn.

O sistema já tem a automação **Aparar**, que oferece a arma ao Defender.

- Tipo: descartado. O Trunfo **Aparar** já cobre a ideia de defender com a arma.

## Grupo 6 — Alcance

### 6a. Haste — Reach ❌

**Reach.** This weapon is long and can be used to attack creatures up to 10 feet away instead of only adjacent creatures. For creatures that already have reach with the limb or limbs that wield the weapon, the weapon increases their reach by 5 feet.

As armas já têm o campo **Alcance**.

- Tipo: descartado como Propriedade. O campo **Alcance** já cobre: armas longas são as de Alcance 2.

## Grupo 7 — Empunhadura e mãos

### 7a. Mão livre — Free-Hand ✅

**Free-Hand.** This weapon doesn't take up your hand, usually because it is built into your armor. A free-hand weapon can't be Disarmed. You can use the hand covered by your free hand weapon to wield other items, perform manipulate actions, and so on. You can't attack with a free hand weapon if you're wielding anything in that hand or otherwise using that hand. When you're not wielding anything and not otherwise using the hand, you can use abilities that require you to have a hand free as well as those that require you to be wielding a weapon in that hand. Each of your hands can have only one free-hand weapon on it.

Lembra a Origem **Natural**, que não ocupa as mãos e não pode ser desarmada.

- Tipo: Propriedade de Empunhadura **Acoplada**.
- Adaptação: a arma não ocupa a mão e não pode ser alvo de Desarmar. Ela só ataca quando a mão em que está acoplada não segura nada. Cada mão tem no máximo uma arma Acoplada.

### 7b. Montaria — Jousting ⏸️

**Jousting.** The weapon is suited for mounted combat with a harness or similar means. When mounted, if you moved at least 10 feet on the action before your attack, add a circumstance bonus to damage for that attack equal to the number of damage dice for the weapon. In addition, while mounted, you can wield the weapon in one hand, changing the damage die to the listed value.

Mistura investida (mover antes de atacar) e empunhadura (Duas mãos vira uma mão montado).

- Tipo: adiado até existirem regras de montaria.

## Grupo 8 — Tipo de dano

### 8a. Versátil — Versatile ✅

**Versatile.** A versatile weapon can be used to deal a different type of damage than that listed in the Damage entry. This trait indicates the alternate damage type. For instance, a piercing weapon that is versatile S can be used to deal piercing or slashing damage. You choose the damage type each time you make an attack.

- Tipo: Propriedade **Versátil (tipo de dano)**.
- Adaptação: a arma tem um segundo Tipo de Dano, indicado na Propriedade, e o atacante escolhe qual usar a cada Ataque. Por exemplo, uma arma Perfurante com Versátil (Corte).
- Nova, inspirada na Versatile do D&D: Propriedade de Empunhadura **Flexível**. A arma pode ser usada com uma mão, ou com as duas para **+1 de Dano**.

### 8b. Não letal — Nonlethal ✅

**Nonlethal.** An effect with this trait is nonlethal. Damage from a nonlethal effect knocks a creature out rather than killing it. Attacks with this weapon are nonlethal, and are used to knock creatures unconscious instead of kill them. You can use a nonlethal weapon to make a lethal attack with a –2 circumstance penalty.

Conversa com a gravidade do dano (superficial ou agravado) em [[Vida#Gravidade do Dano|Gravidade do Dano]].

- Tipo: Propriedade **Não letal**.
- Adaptação: o dano da arma é sempre superficial. Para causar dano agravado com ela, o atacante sofre −2 dados no Ataque.
