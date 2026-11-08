<!-- source: c09eab246433 -->
# NPC Sheet

The **NPC sheet** is the simplified character sheet. It is used for human NPCs, such as a guard or a rival, and for creatures.

## Fields

| Field | On the NPC sheet |
| --- | --- |
| **Name and Concept** | the Concept in one line |
| **[Creature Type](Tipos%20de%20Criatura.md) and [Size](../Personagens/Tamanho.md)** | as for characters |
| **[Attributes](../Personagens/Atributos.md)** | from 1 to 5; creatures that are not human can go above 5 |
| **[Skills](../Personagens/Per%C3%ADcias.md)** | only those that are not 0 |
| **Health** | 3 + Vigor (see [Health](#health)) |
| **Willpower** | 3 + Determination (see [Willpower](#willpower)) |
| **[Initiative](../Cenas%20e%20Conflitos/A%20Cena.md#initiative)** | Cunning + Determination |
| **[Movement](../Movimento/Movimenta%C3%A7%C3%A3o.md)** | 6, unless the sheet sets another value |
| **Absorption** | base Absorption and armor (see [Absorption](#absorption)) |
| **[Resistances, Vulnerabilities and Immunities](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md)** | as for characters |
| **Attacks** | weapons and [natural Attacks](#natural-attacks) |
| **Equipment** | chosen by the Narrator |
| **[Maximum Load](../Equipamentos/Equipamentos.md#maximum-load)** | 5 + Strength, as for characters |
| **Capabilities** | standalone Capabilities, with their values in parentheses |

Left off the sheet: Ambition, Desire, Convictions and Pillars, XP, Competencies and Competency Points.

Instead of Competencies, the NPC receives standalone [Capabilities](../Capacidades/Capacidades.md), chosen by the Narrator from the Competency Capabilities and the [NPC Capabilities](../Capacidades/Capacidades%20de%20NPC.md) (see [Use by NPCs](../Capacidades/Capacidades.md#use-by-npcs)).

The NPC has a Maximum Load like characters, **5 + Strength**. The Narrator chooses equipment that fits it, and carrying more than the Maximum Load leaves it [Overloaded](../Equipamentos/Equipamentos.md#overload).

## Health

The [Health](../Personagens/Vida.md) track follows the characters' rule: **3 + Vigor** spaces. A creature that withstands more damage gets more Health in two ways:

- **Vigor above 5**, for creatures that are not human. This also makes it more resistant to effects on the body, such as poisons.
- **[Robust Body](../Compet%C3%AAncias/Robusto.md#robust-body) (N)**, which adds N spaces and changes nothing else.

Size does not change Health.

## Willpower

Every NPC has a [Willpower](../Personagens/Vontade.md) track of **3 + Determination** spaces, as characters do, with all the Willpower rules, including the Capabilities that cost Willpower.

An NPC recovers superficial Willpower damage on a [Long Rest](../Personagens/Descanso%20Prolongado.md). Aggravated damage is recovered when the Narrator decides, because the NPC has no Ambition or Convictions.

When the whole track is filled with aggravated damage, the Narrator sets the consequence, as in the [Full Willpower](../Personagens/Vontade.md#full-willpower) rule. For NPCs, the most common one is to flee or surrender.

## Absorption

**Base Absorption** is 0 by default. Thick hide, scales or a shell give base Absorption, with the value set on the sheet. [Armor](../Equipamentos/Armaduras.md#absorption) adds to it as for characters.

The sheet shows the total and where it comes from, such as "Absorption 3 (base 0, Breastplate 3)". Because it is base Absorption, natural protection does not penalize Dodge and is not ignored by [Go for the Throat](../Capacidades/Capacidades%20de%20NPC.md#go-for-the-throat-margin-3).

## Natural Attacks

A **natural Attack** is an Attack made with the creature's body, such as claws, bites, horns or stingers. The sheet sets its Damage, Damage Type and Reach, like those of a [weapon](../Equipamentos/Armas.md), and it uses **Agility + Fighting**, unless the sheet sets another Pool.

- **Origin:** it has the [Natural](../Equipamentos/Armas.md#origin-required-one-per-weapon) Origin: it does not take up the hands and cannot be Disarmed.
- **Material:** it is **Organic**, unless the sheet sets another, such as the Common metal fists of an iron Construct.
- **Severity:** it deals **aggravated** damage, as the general rule says. Unlike [Unarmed](../Equipamentos/Armas.md#unarmed), it is not superficial.
- **Properties:** the sheet lists them as for a weapon. A Heavy natural Attack, for example, uses Strength + Fighting.
- **Grapple:** the sheet can name a body part, such as the mouth or the tail, that counts as a free hand to [Grapple](../Condi%C3%A7%C3%B5es/Agarrado.md). Without it, a creature without hands cannot Grapple.

Besides Capabilities, the sheet can define the creature's **own attacks**, such as a tail strike that creates a [Zone](../Cenas%20e%20Conflitos/Zonas.md). The sheet says what the attack does, with the same information a Capability would give: Action, shape, Damage and Damage Type.

## Progression

NPCs do not earn XP. An NPC who comes back stronger gets a new sheet, or one adjusted by the Narrator, within the [Creating NPCs](Cria%C3%A7%C3%A3o%20de%20NPCs.md) budget.

## Template

| Field | Value |
| --- | --- |
| **Name** | Concept in one line |
| **Type and Size** | |
| **Attributes** | Str · Agi · Vig · Cha · Cun · Det |
| **Skills** | only those that are not 0 |
| **Health · Willpower · Initiative · Movement · Absorption** | |
| **Resistances, Vulnerabilities and Immunities** | |
| **Attacks** | name, Damage, Damage Type, Reach and Properties |
| **Capabilities** | with their values in parentheses |
| **Equipment** | |

## Examples

### Wolf

| Field | Value |
| --- | --- |
| **Wolf** | pack hunter |
| **Type and Size** | Beast · Small |
| **Attributes** | Str 2 · Agi 3 · Vig 2 · Cha 1 · Cun 2 · Det 2 |
| **Skills** | Acrobatics 3, Fighting 2, Perception 4 |
| **Health · Willpower · Initiative · Movement · Absorption** | 5 · 5 · 4 · 8 · 0 |
| **Attacks** | Bite, Damage 1, Piercing, Reach 1; grapples with its mouth |
| **Capabilities** | [Go for the Throat](../Capacidades/Capacidades%20de%20NPC.md#go-for-the-throat-margin-3) (Margin 3) |

### Orc Tribal Leader

| Field | Value |
| --- | --- |
| **Orc Tribal Leader** | warrior chief who leads through fear |
| **Type and Size** | Humanoid · Medium |
| **Attributes** | Str 4 · Agi 3 · Vig 4 · Cha 2 · Cun 2 · Det 2 |
| **Skills** | Acrobatics 3, Throwing 3, Stealth 2, Intimidation 4, Fighting 5, Perception 2 |
| **Health · Willpower · Initiative · Movement · Absorption** | 7 · 5 · 4 · 6 · 3 (base 0, Breastplate 3) |
| **Vulnerabilities** | Electric 1 (Breastplate) |
| **Attacks** | Battle Axe, Damage 2 (3 with both hands), Slashing, Reach 1, Flexible, Heavy |
| **Capabilities** | [Fury](../Compet%C3%AAncias/Furioso.md#level-1--fury), [Darkvision](../Capacidades/Capacidades%20de%20NPC.md#darkvision-12-squares) (12 squares) |
| **Equipment** | Battle Axe, Breastplate |

---

← [Back to Creatures](Criaturas.md)
