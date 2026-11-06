<!-- source: add1d8dc3e87 -->
# Zones

A **Zone** represents an effect that occupies an area and affects the creatures inside it.

The rule or Capability that creates a Zone sets its shape, size, range, position, duration, effects and, when applicable, its Damage and Damage Type.

By default, a Zone affects every creature inside it, including the allies of whoever created it. A creature whose space takes up more than one square is affected only once by the same Zone.

## Shapes

Zone shapes use the grid as Movement does: a diagonal counts as 1 square. In the diagrams, the circle is whoever creates the Zone, the highlighted squares are affected and the diamond marks the point of origin, which is also affected.

### Burst N

Every square within N squares of a point of origin, chosen within the source's range. A Burst N forms a square with sides of 2N + 1. If the origin is the square of whoever creates the Zone, they are affected too.

```grade
Burst 1, at a distance
· · · · · · ·
· · · · ■ ■ ■
· · · · ■ ◆ ■
· · · · ■ ■ ■
· · · · · · ·
· · · · · · ·
C · · · · · ·

Burst 2
· · · · · · ·
· ■ ■ ■ ■ ■ ·
· ■ ■ ■ ■ ■ ·
· ■ ■ ◆ ■ ■ ·
· ■ ■ ■ ■ ■ ·
· ■ ■ ■ ■ ■ ·
· · · · · · ·

Burst 1 on whoever creates it
· · · · ·
· ■ ■ ■ ·
· ■ Ⓒ ■ ·
· ■ ■ ■ ·
· · · · ·
```

### Blast N

A square of N × N squares adjacent to whoever creates the Zone, in any direction, including diagonally. Whoever creates the Blast is not affected by it.

```grade
Blast 3 forward
· · · · ·
· ■ ■ ■ ·
· ■ ■ ■ ·
· ■ ■ ■ ·
· · C · ·
· · · · ·

Blast 3 diagonally
· · · · · ·
· ■ ■ ■ · ·
· ■ ■ ■ · ·
· ■ ■ ■ · ·
· · · · C ·
· · · · · ·
```

### Line N

N squares in a straight line, horizontal, vertical or diagonal, starting from a square adjacent to whoever creates the Zone. Whoever creates the Line is not affected by it.

```grade
Line 4 horizontally
· · · · · · ·
· C ■ ■ ■ ■ ·
· · · · · · ·

Line 3 diagonally
· · · · · ·
· · · · ■ ·
· · · ■ · ·
· · ■ · · ·
· C · · · ·
· · · · · ·
```

A creature that takes up more than one square measures the Blast and the Line from any square it occupies (see [Size](../Personagens/Tamanho.md)). The source can use another shape, as long as it describes it.

## Damage Zones

When a creature is hit by a damage Zone, it makes a test of:

> **Agility + Acrobatics**

The rule or Capability that created the Zone can set a different Dice Pool.

A creature that cannot resist follows the [Target without a Response](A%C3%A7%C3%B5es/Confrontar.md#target-without-a-response) rule: its result counts as **1 Success**.

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
- [Resistances](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia.md) and [Vulnerabilities](../Resist%C3%AAncia%20e%20Vulnerabilidade/Vulnerabilidade.md) to the Zone's Damage Type and Material are added together, as in [Effective Absorption](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md#effective-absorption). A positive total converts that many points of aggravated damage to superficial before the test's Successes are applied; a negative total increases the Zone's Damage.
- [Immunity](../Resist%C3%AAncia%20e%20Vulnerabilidade/Imunidade.md) to the Zone's Damage Type or Material prevents the damage entirely.

## Duration

A Zone can be instant or persistent.

- **Instant:** resolves its effect as soon as it is created and then disappears.
- **Persistent:** stays in place for the duration set by the rule or Capability that created it. That source also sets when the Zone affects a creature, such as on entering it or starting the Turn inside it. The same persistent Zone affects each creature at most once per Round.

---

← [Back to Scenes and Conflicts](Cenas%20e%20Conflitos.md)
