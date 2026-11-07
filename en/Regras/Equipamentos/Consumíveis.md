<!-- source: 681aaff4825a -->
# Consumables

A **Consumable** is a piece of equipment that is used up when used, such as remedies, Drugs, poisons, bombs and supplies. The core Consumables are in the [Consumable Catalog](Cat%C3%A1logo%20de%20Consum%C3%ADveis.md).

Each Consumable has **Uses** (how many times it can be used before it runs out; 1 when the catalog gives no other number), **Use** (what using it costs), **Effect**, [Load and Value](Equipamentos.md).

## Using a Consumable

- **Drawing** a Consumable follows the rules of [Switching Equipment](Trocar%20Equipamento.md).
- **Using** a Consumable on yourself or on an adjacent creature takes an [Action](../Cenas%20e%20Conflitos/A%C3%A7%C3%A3o.md), unless the catalog gives another cost. A creature that does not want the effect must be the target of a [Confront](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md).
- A **throwable** Consumable is used with Confront, like a weapon with **Thrown** (see [Weapons](Armas.md)) and the range given. The item is spent even if the Attack fails.
- **Applying to a weapon** takes an Action. The effect applies to the next Attack that deals damage with it, until the end of the Scene.

The same Consumable does not stack on the same creature: using it again only renews the duration.

**No Consumable recovers damage** to [Health](../Personagens/Vida.md) or [Willpower](../Personagens/Vontade.md). The [Healing Kit](Cat%C3%A1logo%20de%20Consum%C3%ADveis.md#other-consumables) provides the supplies for Treatment, but Treatment is what recovers the damage.

## Drugs

**Drugs** are Consumables that strengthen the body or the mind at a price. A Drug lasts until the end of the Scene or, outside a [Tactical Scene](../Cenas%20e%20Conflitos/Cenas%20T%C3%A1ticas.md), for 1 hour. It has three parts:

- **Effect:** what the Drug grants while it lasts.
- **Cost:** the penalty the character suffers while the Drug lasts.
- **Crash:** when the Drug ends, the character pays the rest of the bill, equal to the Grade:
  - **body** Drugs give stacks of [Impaired](../Condi%C3%A7%C3%B5es/Prejudicado.md);
  - **mind** Drugs deal superficial [Willpower](../Personagens/Vontade.md) damage.

A creature can be under **only one Drug at a time**. Using another ends the first, and its Crash happens at once.

### Grades

Every Drug comes in five **Grades**. The Grade sets the strength of the Effect, the Costs, the Crash and the Value.

| Grade | Name | Costs | Value |
|---:|---|---|---:|
| 1 | Diluted | the Cost | 25 |
| 2 | Common | the Cost | 50 |
| 3 | Concentrated | the Cost and the extra Cost | 150 |
| 4 | Strong | the Cost and the extra Cost | 400 |
| 5 | Pure | the doubled Cost and the extra Cost | 1000 |

### Effects

Each effect has an **Intensity**. The sum of a Drug's Intensities equals its Grade.

| Effect | Intensity |
|---|---:|
| **+1 to an Attribute.** The Attribute can go above 5, with no limit. The bonus applies to rolls and requirements, but does not change Health, Willpower, Load or Initiative | 1 per point |
| **[Resistance](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia.md) 1** to a Damage Type | 1 per point |
| **+2 base [Movement](../Movimento/Movimenta%C3%A7%C3%A3o.md)** | 1 per +2 |
| **Ignore a Condition:** [Fear](../Condi%C3%A7%C3%B5es/Medo.md), [Stunned](../Condi%C3%A7%C3%B5es/Atordoado.md), [Poisoned](../Condi%C3%A7%C3%B5es/Envenenado.md), [Slowed](../Condi%C3%A7%C3%B5es/Lento.md), [Shaken](../Condi%C3%A7%C3%B5es/Abalado.md) or [Challenged](../Condi%C3%A7%C3%B5es/Desafiado.md) has no effect while the Drug lasts | 1 each |
| **[Darkvision](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md#darkvision)** up to 6 squares | 1 |
| **Numb:** ignores the dice penalties of [Debilitated](../Condi%C3%A7%C3%B5es/Debilitado.md), Impaired and Poisoned | 2 |
| **Clarity:** the first use of Willpower in the Scene costs no Willpower damage | 2 |
| **Still Standing:** a full Health track does not leave the character [Incapacitated](../Condi%C3%A7%C3%B5es/Incapacitado.md) while the Drug lasts. If the track is full when it ends, they become Incapacitated | 3 |

### Costs

| Cost | Effect | Doubled |
|---|---|---|
| **Attribute** | -1 to an Attribute the Drug does not strengthen | -2 |
| **Vulnerability** | [Vulnerability](../Resist%C3%AAncia%20e%20Vulnerabilidade/Vulnerabilidade.md) 1 to a Damage Type | Vulnerability 2 |
| **Heavy** | -2 base Movement | -4 |
| **Dazzled** | Bright counts as Dim for the character | — |
| **Unsteady** | at the end of each Turn, roll 1 die; with no Success, the character loses their Movement next Turn | — |

Dazzled and Unsteady cannot be doubled, so they only appear as the extra Cost.

---

← [Back to Equipment](Equipamentos.md)
