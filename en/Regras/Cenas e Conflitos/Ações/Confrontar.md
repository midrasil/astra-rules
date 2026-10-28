<!-- source: ed582411ad75 -->
# Confront

A **Confront** happens when a character decides to attack another character during a Tactical Scene.

When starting a Confront, the attacker builds a **Dice Pool** according to the kind of Attack used.

| Kind of Attack | Default Pool |
| --- | --- |
| Melee | **Agility + Fighting** |
| Shooting weapon | **Agility + Shooting** |
| Thrown weapon | **Strength + Throwing** |

The weapon, a Capability or another rule can set a different Attribute or Pool. Capabilities always take precedence over other replacements.

The [Heavy](../../Equipamentos/Armas.md#use-optional) property replaces Agility with Strength without changing the Skill: a Heavy melee weapon uses **Strength + Fighting**, while a Heavy shooting weapon uses **Strength + Shooting**. It does not add Strength to the damage.

## Two-Weapon Fighting

Every character can use one weapon in each hand by default. This lets them keep two weapons with different types and properties at hand, but by itself it grants no extra dice, damage or Attacks.

On each Confront, whether attacking or responding, the character chooses which of the two weapons to use:

- the **main weapon** is the chosen weapon. It sets the Pool, the Damage, the Damage Type and the Special Properties of the Confront;
- the **off-hand weapon** is the one in the other hand. It has no effect on the Confront, unless a Capability, such as those of [Ambidextrous](../../Personagens/Compet%C3%AAncias/Ambidestro.md), says otherwise.

[Unarmed](../../Equipamentos/Armas.md#unarmed), Natural weapons and [Shields](../../Equipamentos/Escudos.md) do not count as an off-hand weapon.

## Responding to the Confront

After the attacker declares the Confront, the target character must choose how to respond.

They can:

- **Accept the Confront**
- **Defend**
- **Dodge**

The chosen response sets how the test is resolved and which consequences can follow.

## Accept the Confront

When they **Accept the Confront**, the character does not merely try to avoid the Attack. They respond by striking back.

Both characters build their Dice Pools and make an opposed roll.

Whoever gets more Successes wins the Confront.

If the **attacker** wins, they deal damage equal to:

> **Margin of Successes + weapon Damage**

If the one who **accepted** the Confront wins, the counterattack deals only:

> **Margin of Successes**, as **superficial damage**

The weapon's Damage does not apply to the counterattack.

The **Margin** is the difference between the number of Successes the two participants got.

If both get the same number of Successes, it is a tie and **the attacker wins**, but deals only the **weapon's Damage** as **superficial damage**.

To Accept the Confront, the responding character must be able to hit the attacker with the weapon used, observing the ranged weapon restriction (see [Reach and Confront Responses](#reach-and-confront-responses)).

In general, confronts between melee weapons require both to be within each other's reach, while ranged Attacks can only be answered this way when the character also has a valid way to hit the attacker.

## Defend

A character equipped with a **Shield** can choose to Defend.

In that case, they make a roll opposed to the Attack. The Dice Pool used is:

> **Strength + Fighting**

The [Shield](../../Equipamentos/Escudos.md)'s **Protection** is added to the Dice Pool.

If the defender gets more Successes than the attacker, the Attack is blocked and neither participant deals damage.

On a tie, the attacker wins, but deals only the **weapon's Damage** as **superficial damage**.

If the attacker gets more Successes, they deal damage the same way as when winning against a target who Accepts the Confront: **Margin of Successes + weapon Damage**.

Defending is not a counterattack. Even when they win the roll, the character only keeps the Attack from hitting them.

## Dodge

A character can choose to **Dodge** to try to avoid the Attack entirely.

The Dice Pool used is:

> **Agility + Acrobatics**

Capabilities and other rules can replace this Pool. Describing the Dodge differently does not allow freely using another Attribute or Skill.

If the character gets more Successes than the attacker, they avoid the damage entirely and can immediately move up to:

> **half their base Movement**

in a direction of their choice.

This move follows the usual [Movement](../../Movimento/Movimenta%C3%A7%C3%A3o.md) rules, such as Difficult Terrain and Special Movement, but does not trigger effects provoked by movement, such as abilities that punish or interfere with opponents' movement.

On a tie, the attacker wins, but deals only the **weapon's Damage** as **superficial damage**.

If the attacker gets more Successes, they deal damage the same way as when winning against a target who Accepts the Confront: **Margin of Successes + weapon Damage**.

A character who is unable to move cannot choose to Dodge.

## Target without a Response

When the target cannot respond to the Confront, whether because they are surprised, unconscious, have no valid response or have their Dice Pool reduced below 1 die, only the attacker rolls. The target's result always counts as **1 Success**.

The Confront is resolved as usual with that value, including the tie rule. If the attacker gets no Successes, the Attack fails and no one takes damage.

## Numerical Advantage

When several characters surround the same enemy, the numerical advantage opens gaps in their defense.

When **starting a Confront** against an enemy, the attacker gets **+1 die** for each ally they have beyond the enemy side in that fight:

> **Numerical Advantage Bonus** = allies adjacent to the target - (the target + the target's allies adjacent to them)

The attacker counts themselves among the allies adjacent to the target. The bonus is never negative.

| Situation | Bonus for each attacker |
| --- | --- |
| 1 × 1 | +0 |
| 2 × 1 | +1 |
| 3 × 1 | +2 |
| 3 × 2 | +1 |
| 2 × 2 | +0 |

To count the sides:

- **Adjacent** includes diagonals. A creature that takes up more than one square is adjacent to everything next to any square it occupies (see [Size](../../Personagens/Tamanho.md)).
- The **attacker** must also be adjacent to the target.
- **Defeated** characters do not count for either side.
- **Player characters** are always allies of each other. Each NPC belongs to a side, which can be hostile, neutral or allied with the group.

Numerical Advantage applies **only to melee Attacks**. When the surrounded enemy attacks, the characters who respond (Accepting the Confront, Defending or Dodging) do not get the bonus.

## Attacking Beyond Range

A weapon's **Range** is the maximum distance, in squares, at which it hits its targets without penalty.

Ranged Attacks, including [thrown weapons](../../Equipamentos/Armas.md#properties), can hit targets beyond the weapon's normal Range. For each band of squares the size of the weapon's Range beyond its normal Range, the attacker suffers **-2 dice** to their Dice Pool on the Attack.

A weapon with **Range 6** hits targets up to 6 squares away normally. A target between **7 and 12 squares** imposes **-2 dice** on the Attack; between **13 and 18 squares**, **-4 dice**; and so on.

For thrown weapons, use the **throwing Range** instead of the weapon's Range (see [Thrown](../../Equipamentos/Armas.md#properties)).

If the loss reduces the Dice Pool below 1 die, the Attack cannot be made.

## Reach and Confront Responses

The available response depends on the characters' positions and the equipment used.

**Accept the Confront** requires the character to be able to hit the attacker.

**Defend** requires a Shield, unless a Capability allows another way, such as [Parry](../../Personagens/Compet%C3%AAncias/Aparador.md#level-1--parry) or [Cover Ally](../../Personagens/Compet%C3%AAncias/Guardi%C3%A3o.md#level-1--cover-ally).

**Dodge** can be used whenever the character is able to move.

Melee weapons can start Confronts against characters using ranged weapons when they are within the necessary reach.

Likewise, characters using ranged weapons can start Confronts against melee characters, but those can only Accept the Confront if they have enough reach to hit the attacker.

**Ranged weapon restriction:** a character cannot Accept the Confront using a ranged weapon when the attacker uses a melee weapon, even if the attacker is within the weapon's Range. Against ranged Attacks, they can Accept as usual, as long as they can hit the attacker.

---

← [Back to Action](../A%C3%A7%C3%A3o.md)
