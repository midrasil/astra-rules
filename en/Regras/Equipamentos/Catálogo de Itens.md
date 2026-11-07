<!-- source: ee143546c8ac -->
# Item Catalog

This is the Astra core's catalog of common items. Drugs are in the [Consumable Catalog](Cat%C3%A1logo%20de%20Consum%C3%ADveis.md). The Load and Value rules are in [Equipment](Equipamentos.md).

**Value** is abstract, has no currency name and may have decimals.

| Item | Load | Value | Use |
|---|---:|---:|---|
| Healing Kit | 1 | 5 | healing supplies for [Treatment](../Personagens/Vida.md#treatment) and [Patch Up](../Compet%C3%AAncias/Socorrista.md#level-1--patch-up); 5 uses, each Treatment or Patch Up spends 1 |
| Candle | 0 | 0.01 | [light source](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md#light-sources) (Bright 1 + Dim 1); lasts 1 hour |
| Torch | 1 | 0.01 | [light source](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md#light-sources) (Bright 4 + Dim 4); lasts 1 hour; can be used as an Improvised Weapon |
| Lantern | 1 | 5 | [light source](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md#light-sources) (Bright 6 + Dim 6); lasts 6 hours per flask of oil |
| Flask of oil | 0 | 0.1 | lantern fuel |
| Rope (15 m) | 1 | 1 | for climbing, descending, tying or pulling |
| Backpack | 1 | 2 | **+2 [Maximum Load](Equipamentos.md#maximum-load)**; only one Backpack counts |
| Bedroll | 1 | 1 | for sleeping outdoors with some comfort |
| Ration (1 day) | 0 | 0.5 | dry food for one day of travel |
| Waterskin | 0 | 0.2 | holds water for one day |
| Crowbar | 1 | 2 | a lever for forcing doors, chests and bars; can be used as an Improvised Weapon |
| Thieves' tools | 1 | 25 | picks and fine tools for opening locks and disarming traps |
| Arrows (20) | 1 | 1 | [ammunition](Armas.md#use-optional) for bows; Common metal |
| Bolts (20) | 1 | 1 | [ammunition](Armas.md#use-optional) for crossbows; Common metal |
| Sling bullets (20) | 1 | 0.04 | [ammunition](Armas.md#use-optional) for slings; Stone |
| Antidote | 0 | 50 | Action: ends [Poisoned](../Condi%C3%A7%C3%B5es/Envenenado.md) |
| Smelling Salts | 0 | 1 | Action, adjacent creature: ends [Stunned](../Condi%C3%A7%C3%B5es/Atordoado.md) or [Fear](../Condi%C3%A7%C3%B5es/Medo.md) |
| Flask of Acid | 0 | 25 | Confront, Thrown (4): Damage 2, Acid |
| Alchemist's Fire | 0 | 50 | Confront, Thrown (4): Damage 1, Fire; the fire spreads into a persistent Burst 1 [Zone](../Cenas%20e%20Conflitos/Zonas.md) around the target, until the end of the thrower's next Turn, dealing Damage 1 Fire to anyone who enters it or starts their Turn in it |
| Smoke Bomb | 0 | 10 | Action, up to 4 squares: a Burst 2 with Dark [lighting](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md), until the end of the thrower's next Turn |
| Basic Poison | 0 | 100 | Action, apply to a weapon: the next Attack that deals damage leaves the target Poisoned for 2 Turns |
| Weapon Oil | 0 | 25 | Action, apply to a weapon: until the end of the Scene, the weapon's Attacks also count as Fire, Ice or Electric (chosen when bought) for [Resistances and Vulnerabilities](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md) |

**Load 0** items are very small. For every 10 Load 0 items, count **1** Load.

## Using Items

- Using an item on yourself or on an adjacent creature, such as an Antidote, takes an [Action](../Cenas%20e%20Conflitos/A%C3%A7%C3%A3o.md). A creature that does not want the effect must be the target of a [Confront](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md).
- An item with **Thrown** is used with Confront, like a Thrown weapon (see [Weapons](Armas.md)). It is spent even if the Attack fails.
- **Applying to a weapon** takes an Action. The effect applies to the next Attack that deals damage with it, until the end of the Scene.
- The same item does not stack on the same creature: using it again only renews the duration.

---

← [Back to Equipment](Equipamentos.md)
