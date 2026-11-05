<!-- source: fc2787e47011 -->
# NPC Traits

**NPC Traits** are abilities belonging to NPCs, creatures and enemies. They are set directly on the creature's sheet and are not part of the characters' Competency system.

A **Natural Attack** is an Attack made with the creature's body, such as claws, bites, horns or stingers. The creature's sheet sets its Damage, Damage Type and Reach, like those of a [weapon](../Equipamentos/Armas.md), and it uses **Agility + Fighting**, unless the sheet sets another Pool.

## Configurable values

Each trait comes with **default values** in parentheses, such as **Potency**, the Pool used to resist, the duration or the number of stacks. These values are **configurable on each creature**: two creatures with the same trait can have different values.

**Potency** is the [Difficulty](../Mec%C3%A2nica%20B%C3%A1sica/Reserva%20de%20Dados.md#difficulty-scale) of the test the target makes to resist, when the trait calls for one.

When a Trait mentions a Skill without spelling out the full Pool, it uses the Skill's linked Attribute. Pools expressly made of two Attributes, such as Vigor + Determination, stay unchanged.

When a trait does not set the Pool to resist, use **Vigor + Determination** against effects on the body and **Determination + Cunning** against effects on the mind.

## Special movement

Swimming and climbing are [Special Movement](../Movimento/Movimenta%C3%A7%C3%A3o.md#special-movement) and cost 2 Movement points per square. With one of these traits, the creature uses that movement at the **normal cost**, 1 point per square, and chooses on its Turn whether to spend its Movement on normal or special movement.

**Aquatic** and **Flying** can come with a value in parentheses, such as **Aquatic (5)**: it is the creature's Movement in that medium, also at the normal cost. With no value, it uses its default Movement. A creature that only moves in water, such as a shark, has Movement 0 on land.

### Aquatic

- **Description:** swims at the normal cost and breathes underwater. With a value, swims with that Movement.

### Flying

- **Description:** flies at the normal cost (see [Flight](../Movimento/Movimenta%C3%A7%C3%A3o.md#flight)), with the value's Movement when there is one, and ignores Difficult Terrain on the ground. If it becomes [Prone](../Condi%C3%A7%C3%B5es/Ca%C3%ADdo.md), [Grappled](../Condi%C3%A7%C3%B5es/Agarrado.md) or [Paralyzed](../Condi%C3%A7%C3%B5es/Paralisado.md) in the air, it falls.

### Burrowing

- **Description:** digs and moves through the earth at the normal cost. While buried, it cannot be the target of Attacks.

### Climbing

- **Description:** climbs walls and ceilings at the normal cost, without needing a test.

## On-hit effects

When the creature **wins an Attack with a melee natural Attack**, the target makes a test to resist, with Difficulty equal to the Potency. On a failure, they suffer the effect.

### Venomous (Potency 2; Vigor + Determination)

- **Description:** a target who fails becomes [Poisoned](../Condi%C3%A7%C3%B5es/Envenenado.md) for a number of Turns equal to the Potency.

### Paralyzing (Potency 2; Vigor + Strength)

- **Description:** a target who fails becomes [Paralyzed](../Condi%C3%A7%C3%B5es/Paralisado.md) for 1 Turn.

### Stunning (Potency 2; Determination + Cunning)

- **Description:** a target who fails becomes [Stunned](../Condi%C3%A7%C3%B5es/Atordoado.md) for 1 Turn.

### Infectious

- **Description:** the disease or curse transmitted, the Pool to resist, the Potency and the duration are set on each creature (for example, lycanthropy).

## Special attacks

### Frenzy

- **Description:** once per Turn, on winning an Attack, the creature makes another Attack against another target within its Reach, with **-2 dice**.

### Improved Frenzy

- **Requirement:** Frenzy
- **Description:** Frenzy's extra Attack does not suffer the penalty.

### Breath (Damage; Damage Type)

- **Description:** with its Action, the creature creates an instant [Zone](../Cenas%20e%20Conflitos/Zonas.md) in a [Blast 3](../Cenas%20e%20Conflitos/Zonas.md#blast-n). The Zone has the Damage and Damage Type set on the creature. Breath cannot be used on consecutive Turns.

### Charge (+2 Damage; 4 squares)

- **Description:** if the creature moves at least 4 squares in a straight line before attacking, it adds **+2 to the Damage** of the Attack. It is the same rule as the weapon Property [Charge](../Equipamentos/Armas.md#use-optional), with its own values.

### Go for the Throat (Margin 3)

- **Description:** on winning an Attack with a Margin of 3 or more, the damage ignores the Absorption of the target's **armor**. Base Absorption and the armor's Resistances and Vulnerabilities still apply.

### Constrictor (Margin 2)

- **Description:** on winning an Attack with a Margin of 2 or more, the target also becomes [Grappled](../Condi%C3%A7%C3%B5es/Agarrado.md). At the start of each of the creature's Turns, whoever it is grappling takes the Damage of its natural Attack.

### Terrifying (Potency 2; Determination + Cunning; stacks equal to Potency)

- **Description:** whoever sees the creature for the first time in the scene makes the test to resist. Whoever fails receives stacks of [Fear](../Condi%C3%A7%C3%B5es/Medo.md).

### Web (Potency 2; Range 6; Attack: Agility + Shooting; escape: Strength + Athletics)

- **Description:** the creature makes a ranged Attack, up to the Range, with **Agility + Shooting**. A sheet can expressly set another Attack Attribute for its Web. On a win, it leaves the target [Grappled](../Condi%C3%A7%C3%B5es/Agarrado.md) by the web. To break free, the target uses their Action and tests **Strength + Athletics** against the Potency.

### Burrowing Ambush

- **Requirement:** Burrowing
- **Description:** when coming out of the ground to attack, the creature tests **Agility + Stealth** against the target's **Cunning + Perception**. If it wins, it gets **+2 dice** on the Attack.

### Swarm (damage by Size)

- **Description:** the creature is a swarm of small critters, treated as a single one. At the **start of each of its Turns**, every creature **in the space it occupies or adjacent to it** takes **superficial damage**, with no Attack roll. The base damage comes from Size (**Medium 2, Large 4, Huge 6**) and drops by **1 for each creature hit beyond the first**, to a minimum of 1. The creature's on-hit effects, such as [Venomous](#venomous-potency-2-vigor--determination), apply to each creature hit. The base damage can change on each creature. It is usually **Immune to Slashing and Piercing**.

## Recovery

### Regeneration (2; interrupted by the Damage Type or Material set on the creature)

- **Description:** at the **end of each of its Turns**, the creature converts a number of points of aggravated damage to superficial equal to its Regeneration value, without needing treatment. The value is configurable on each creature.
- **Interruption:** each creature lists the Damage Types or Materials that interrupt its Regeneration. If it took damage from one of them since the end of its last Turn, it **does not regenerate on that Turn**. The interruption lasts only that Turn: on the next Turn, with no new damage of that type, Regeneration comes back.

## Senses

### Darkvision (12 squares)

- **Description:** up to its range, the creature treats **Dim** as **Bright** and **Dark** as **Dim**, but sees without telling colors apart. Beyond its range, [Lighting](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md) applies as usual. [Supernatural darkness](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md#supernatural-darkness) blocks Darkvision.

---

← [Back to Creatures](Criaturas.md)
