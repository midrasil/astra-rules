<!-- source: 6025137ffda4 -->
# Zones

A **Zone** represents an effect that occupies an area and affects the creatures inside it.

The rule or Capability that creates a Zone sets its shape, size, range, position, duration, effects and, when applicable, its Damage and Damage Type.

By default, a Zone affects every creature inside it, including the allies of whoever created it. A creature whose space takes up more than one square is affected only once by the same Zone.

## Damage Zones

When a creature is hit by a damage Zone, it makes a test of:

> **Agility + Acrobatics**

The rule or Capability that created the Zone can set a different Dice Pool.

Each Success on the test is applied as follows:

1. while there is aggravated damage, the Success converts 1 point of that damage to superficial;
2. once all the damage has been converted, each remaining Success removes 1 point of superficial damage.

### Example

A creature is hit by a Damage 4 Zone.

| Successes | Damage taken |
| ---: | --- |
| 0 | 4 aggravated |
| 2 | 2 aggravated and 2 superficial |
| 4 | 4 superficial |
| 5 | 3 superficial |
| 8 or more | no damage |

## Interactions

- A Zone is neither an Attack nor a Confront. The Accept the Confront, Defend and Dodge Responses are not used.
- Resisting a Zone is not Dodging. Bonuses, penalties and replacements specific to Dodge do not apply, unless a rule says otherwise.
- Resisting a Zone does not move the creature.
- Base Absorption and the Absorption granted by armor do not apply to a Zone's damage.
- [Resistances](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia.md) to the Zone's Damage Type and Material, if any, convert aggravated damage to superficial as with any damage: each point of Resistance converts 1 point of the Zone's aggravated damage to superficial before the test's Successes are applied.
- [Vulnerabilities](../Resist%C3%AAncia%20e%20Vulnerabilidade/Vulnerabilidade.md) to the Zone's Damage Type and Material, if any, directly increase its Damage.
- [Immunity](../Resist%C3%AAncia%20e%20Vulnerabilidade/Imunidade.md) to the Zone's Damage Type or Material prevents the damage entirely.

## Duration

A Zone can be instant or persistent.

- **Instant:** resolves its effect as soon as it is created and then disappears.
- **Persistent:** stays in place for the duration set by the rule or Capability that created it. That source also sets when the Zone affects a creature, such as on entering it or starting the Turn inside it.

---

← [Back to Scenes and Conflicts](Cenas%20e%20Conflitos.md)
