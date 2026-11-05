<!-- source: bd28a935cc5a -->
# Weapons

**Weapons** are equipment used to attack, usually in a [Confront](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md).

Each weapon is described by the following fields:

| Field | Description |
|---|---|
| **Name** | the weapon's name |
| **Damage** | a fixed modifier (1, 2, 3…) added to the damage in a Confront |
| **Damage Type** | the type of damage the weapon deals — Slashing, Piercing, Bludgeoning, Fire, etc. (see [Damage Types](#damage-types)) |
| **Grip** | how the weapon is held (see [Grip](#grip-optional)) |
| **Reach** | the reach, in squares, at which the weapon can hit its targets |
| **Other Properties** | the weapon's Use Properties (see [Use](#use-optional)) |
| **Mastery** | the effect only those who have mastered the weapon can use (see [Mastery](#mastery-optional-at-most-one-per-weapon)) |
| **Material** | the category of the weapon's material (see [Material](#material-required-one-per-weapon)) |
| **Load** | how much of the Maximum Load it takes |
| **Value** | the weapon's cost |

A weapon's **Damage** is the **weapon bonus** applied in a Confront, added to the Margin of Successes (see [Confront](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md)).

The weapons available in the core are in the [Weapon Catalog](Cat%C3%A1logo%20de%20Armas.md).

## Unarmed

Every character has a natural weapon, **Unarmed**: punches, kicks, elbows and the body itself.

| Field | Value |
|---|---|
| **Damage** | +0 |
| **Damage Type** | Bludgeoning |
| **Reach** | 1 |
| **Load** | 0 |

Unarmed has the **Natural** Origin and the **Organic** Material: it is **always available**, does not need to be equipped and does not take up the hands. It also cannot be removed, sold or lost. When the character attacks with no weapon in hand, they use Unarmed.

By default, Unarmed damage is **superficial** (see [Damage Severity](../Personagens/Vida.md#damage-severity)). Since its Damage is +0, a tie in an unarmed Confront deals no damage. Capabilities can change these traits when their effect expressly says so.

## Properties

A weapon's **Properties** are organized into five categories. Every weapon has exactly one **Origin** and one **Material**; the **Grip**, **Use** and **Mastery** properties are optional and can be combined as the weapon's entry says.

### Origin (required, one per weapon)

- **Crafted** — a weapon made to be used as a weapon. This is the default origin.
- **Improvised** — an ordinary object used as a weapon.
- **Natural** — a weapon that is part of the body, such as fists, claws, fangs or tails. It is always available: it does not need to be equipped, does not take up the hands and cannot be the target of the [Disarm](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#disarm) Maneuver. [Unarmed](#unarmed) is Natural.

### Material (required, one per weapon)

Material represents a category that matters for defenses, rather than telling apart every common raw material.

| Material | Covers |
|---|---|
| **Organic** | Body, flesh, claws, fangs, bones and shells |
| **Wood** | Common wood and other plant materials used in weapons |
| **Stone** | Rock, flint, obsidian and common minerals |
| **Common metal** | Iron, steel, bronze, copper and other common alloys |
| **Silver** | Special material, with its own interaction with defenses |
| **Meteorite** | Special material, with its own interaction with defenses |

**Special materials** is an organizing category, not a selectable option. Each special material has its own entry. Every weapon still has exactly one Material: Silver and Meteorite do not also count as Common metal.

Material is considered together with the Damage Type when applying [Resistances, Vulnerabilities and Immunities](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md). Resistances and Vulnerabilities to the Type and the Material are added together when calculating Effective Absorption; Immunity to either one ignores all the damage. For now, these Material values are set directly on characters and creatures.

### Grip (optional)

- **Light** — a nimble, balanced weapon. It has no effect of its own; some Capabilities require Light weapons, such as [Ambidextrous](../Compet%C3%AAncias/Ambidestro.md).
- **Two-handed** — a weapon that must be held in both hands to be used.
- **Flexible** — a weapon that can be used in one hand or both. Held in both hands, it gets **+1 Damage**.
- **Attached** — a weapon fixed to the body or the armor, which does not take up the hand and cannot be the target of the [Disarm](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#disarm) Maneuver. It only attacks when the hand it is attached to holds nothing. Each hand has at most one Attached weapon.

### Use (optional)

- **Heavy** — Attacks made with this weapon use **Strength instead of Agility**, keeping the Skill set by the kind of Attack. A Heavy melee weapon uses **Strength + Fighting**; a Heavy shooting weapon uses **Strength + Shooting**. This replacement is mandatory, adds no dice or Damage. Heavy changes only Attacks: it does not change the Pools of Maneuvers made with the weapon. A Capability that expressly sets the Attack's Attribute always takes precedence over Heavy.

- **Thrown (value)** — a weapon that can be thrown as a ranged Attack. The Property always comes with a value, which gives the weapon's **throwing Range** in squares — for example, **Thrown (6)** means the weapon can be thrown up to 6 squares. Thrown Attacks use **Strength + Throwing**, unless explicitly replaced. The weapon's **Reach** field still applies to its melee use. In a [Confront](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md), the weapon can be used to **Accept the Confront** against a ranged attacker, as long as they are within the throwing Range.

- **Versatile (damage type)** — a weapon with a second Damage Type, given in the Property. The attacker chooses which one to use on each Attack. For example, a Piercing weapon with **Versatile (Slashing)**.
- **Nonlethal** — the weapon's damage is always **superficial** (see [Damage Severity](../Personagens/Vida.md#damage-severity)). To deal aggravated damage with it, the attacker suffers **-2 dice** on the Attack.
- **Maneuver (Reposition, Trip or Disarm)** — the weapon can be used to perform the given [Maneuver](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md) up to the weapon's **Reach**, instead of requiring physical contact. The Maneuver gets no bonus from the weapon and keeps its own Pool; the Heavy property does not change that Pool either.
- **Ammunition (type)** — a shooting weapon that fires the given ammunition, such as **Ammunition (arrows)** (see [Item Catalog](Cat%C3%A1logo%20de%20Itens.md)). Each shot spends **1 ammunition**, whether starting a Confront or Accepting the Confront; without ammunition, the weapon cannot fire. Drawing the ammunition is part of the Attack. On the Attack, the **ammunition's Material** applies, not the weapon's. At the end of the Scene, if there is time to search, the character recovers **half the ammunition spent**, rounded down.
- **Loading** — the weapon fires at most **once per Round**.
- **Charge** — if the character moved at least **3 squares in a straight line** to the target this Turn, right before the Attack, the Attack gets **+1 Damage**.
- **Guard** — while wielding the weapon, the character gets **+1 die** when they [Dodge](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md#dodge). Two weapons with Guard do not add up.

### Mastery (optional, at most one per weapon)

**Mastery** is an effect characteristic of the weapon's model, which only shows itself in the hands of someone who has mastered it. It belongs to the weapon, but can only be used by a character who has **mastered** that weapon (see [Mastering a Weapon](#mastering-a-weapon)). Anyone who has not mastered it uses the weapon normally, without the Mastery.

Each weapon has at most **one Mastery**. A Mastery can create effects on winning an Attack, change a specific interaction or represent an advantage that does not fit the structural categories above.

Techniques the character has learned still belong to **Capabilities**. The Mastery describes what the weapon does in the hands of someone who has mastered it; a Capability describes what the character knows how to do.

A Mastery that says **on winning an Attack** does not trigger on a tie. When the effect requires giving up part of the damage, the attacker decides after winning and before calculating it.

- **Lethal** — on winning an Attack, each pair of dice showing **10** on the attacker's roll adds the **weapon's Damage** once more to the damage dealt.
- **Sweep** — on winning a melee Attack, the attacker can give up the Margin. The original target takes only the weapon's Damage, and a second target of the attacker's choice takes the same Damage as superficial damage. The second target must be within the weapon's reach and adjacent to the original target; they do not make another roll to respond.
- **Debilitating (Shaken)** — on winning an Attack, the attacker can give up the weapon's Damage. The target takes only the Margin and becomes [Shaken](../Condi%C3%A7%C3%B5es/Abalado.md).
- **Debilitating (Slowed)** — on winning an Attack, the attacker can give up the weapon's Damage. The target takes only the Margin and becomes [Slowed](../Condi%C3%A7%C3%B5es/Lento.md).
- **Momentum** — on winning an Attack, the attacker's next Attack against the same target, until the end of their next Turn, gets **+1 die**. Momentum bonuses do not stack.
- **Graze** — when the target wins the Attack, they still take **half the weapon's Damage**, rounded up, as superficial damage. It does not apply if the attacker got no Successes.
- **Displace** — on winning an Attack, the attacker can move the target **1 square** in any direction, with no other roll, following the limits of [Reposition](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#reposition).
- **Puncture** — on winning an Attack, the target's [Absorption](Armaduras.md#absorption) converts **1 point less** of aggravated damage.

Modules and settings can add new properties, origins, materials and weapons to the core catalog.

## Mastering a Weapon

Mastering a weapon means knowing it well enough to draw out its **Mastery**.

- When an **Attack Skill** (Fighting, Shooting or Throwing) reaches **5**, the character masters **one specific weapon** of their choice that uses that Skill.
- Each additional weapon costs **3 XP** (see [Advancement](../Personagens/Progress%C3%A3o.md#experience-costs)) and requires **5** in one of the Skills the weapon uses.
- Mastery is of the **weapon**, not of the effect: mastering the Battle Axe does not grant the Mastery of another weapon with the same effect.
- A character who masters a weapon uses its Mastery on **any Attack** made with it, whatever the Attack's Skill.
- **Unarmed** Attacks have no Mastery.
- Narrator characters master the weapons the Narrator chooses.

## Damage Types

The **Damage Type** tells the nature of the wound — a piece of information separate from the damage's **severity** (see [Damage Severity](../Personagens/Vida.md#damage-severity)).

The starting list of damage types is:

- **Physical:** Slashing, Bludgeoning, Piercing
- **Elemental:** Fire, Ice, Electric, Acid, Poison
- **Magic:** Magic

Each damage source defines its Damage Type — for example, a sword deals Slashing, a mace deals Bludgeoning and a fire spell deals Fire. Catalogs and modules can add new damage types.

---

← [Back to Equipment](Equipamentos.md)
