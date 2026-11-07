<!-- source: 1c510ecfb681 -->
# Consumable Catalog

This is the Astra core's catalog of Consumables. The rules for using them, for Drugs and for alchemicals are in [Consumables](Consum%C3%ADveis.md).

## Drugs

Each row shows the Effect at each Grade. Every Drug has Load 0 and 1 Use, and its Value depends on the Grade.

| Drug | 1 | 2 | 3 | 4 | 5 | Cost | Extra Cost | Crash |
|---|---|---|---|---|---|---|---|---|
| Bull's Blood | Strength +1 | Strength +2 | Strength +3 | Strength +4 | Strength +5 | Cunning -1 | Heavy | Impaired |
| Lynx Dust | Agility +1 | Agility +2 | Agility +3 | Agility +4 | Agility +5 | Determination -1 | Unsteady | Impaired |
| Ironbark | Vigor +1 | Vigor +2 | Vigor +3 | Vigor +4 | Vigor +5 | Agility -1 | Heavy | Impaired |
| Clearleaf | Cunning +1 | Cunning +2 | Cunning +3 | Cunning +4 | Cunning +5 | Vigor -1 | Unsteady | Willpower |
| Honeytongue | Charisma +1 | Charisma +2 | Charisma +3 | Charisma +4 | Charisma +5 | Determination -1 | Unsteady | Willpower |
| Poppy Tear | ignores Fear | Determination +1, ignores Fear | Lucid, ignores Fear | Lucid, Determination +1, ignores Fear | Lucid, Determination +1, ignores Fear and Shaken | Agility -1 | Heavy | Willpower |
| Salamander Blood | Fire Resistance 1 | Fire Resistance 2 | Fire Resistance 3 | Fire Resistance 4 | Fire Resistance 5 | Ice Vulnerability 1 | Dazzled | Impaired |
| Leatherskin | Slashing Resistance 1 | Slashing and Piercing Resistance 1 | Slashing Resistance 2 and Piercing 1 | Slashing and Piercing Resistance 2 | Slashing Resistance 3 and Piercing 2 | Heavy | Agility -1 | Impaired |
| Wind Dust | Movement +2 | Movement +4 | Movement +4, ignores Slowed | Movement +6, ignores Slowed | Movement +8, ignores Slowed | Vigor -1 | Unsteady | Impaired |
| Owl's Eye | Darkvision | Darkvision, Cunning +1 | Darkvision, Cunning +2 | Darkvision, Cunning +3 | Darkvision, Cunning +4 | Vigor -1 | Dazzled | Impaired |
| Numbweed | ignores Poisoned | Numbed | Numbed, Vigor +1 | Numbed, Vigor +2 | Numbed, Vigor +3 | Agility -1 | Cunning -1 | Impaired |
| Black Fury | Strength +1 | Numbed | Relentless | Relentless, Strength +1 | Relentless, Strength +2 | Determination -1 | Unsteady | Impaired |

The Numbed, Lucid, Relentless, Dazzled and Unsteady Conditions are in [Conditions](../Condi%C3%A7%C3%B5es/Condi%C3%A7%C3%B5es.md) and last as long as the Drug.

A new Drug is built with the [Effects and Costs](Consum%C3%ADveis.md#effects) tables.

## Alchemicals

Every alchemical has 1 Use.

| Alchemical | Use | Effect | Load | Value |
|---|---|---|---:|---:|
| Antidote | Action | ends [Poisoned](../Condi%C3%A7%C3%B5es/Envenenado.md) | 0 | 50 |
| Smelling Salts | Action, adjacent creature | ends [Stunned](../Condi%C3%A7%C3%B5es/Atordoado.md) or [Fear](../Condi%C3%A7%C3%B5es/Medo.md) | 0 | 1 |
| Flask of Acid | Confront, Thrown (4) | Damage 2, Acid | 0 | 25 |
| Alchemist's Fire | Confront, Thrown (4) | Damage 1, Fire; the fire spreads into a persistent Burst 1 [Zone](../Cenas%20e%20Conflitos/Zonas.md) around the target, until the end of the thrower's next Turn, dealing Damage 1 Fire to anyone who enters it or starts their Turn in it | 0 | 50 |
| Smoke Bomb | Action, up to 4 squares | a Burst 2 with Dark [lighting](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md), until the end of the thrower's next Turn | 0 | 10 |
| Basic Poison | Action, apply to a weapon | the next Attack that deals damage leaves the target Poisoned for 2 Turns | 0 | 100 |
| Weapon Oil | Action, apply to a weapon | until the end of the Scene, the weapon's Attacks also count as Fire, Ice or Electric (chosen when bought) for [Resistances and Vulnerabilities](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md) | 0 | 25 |

---

← [Back to Equipment](Equipamentos.md)
