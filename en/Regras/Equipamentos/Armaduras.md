<!-- source: 39a0404111e1 -->
# Armor

**Armor** is equipment used to protect the character.

The armor available in the core is in the [Armor Catalog](Cat%C3%A1logo%20de%20Armaduras.md).

Each armor is described by the following fields:

| Field                | Description                                                          |
| -------------------- | -------------------------------------------------------------------- |
| **Name**             | the armor's name                                                     |
| **Category**         | Light, Medium or Heavy (see [Categories](#categories))               |
| **Minimum Strength** | the Strength needed to wear the armor without losing Movement        |
| **Description**      | a short description of the armor                                     |
| **Absorption**       | how many points of aggravated damage are converted into superficial |
| **Properties**       | the armor's special traits                                           |
| **Load**             | how much of the Maximum Load it takes                                       |
| **Value**            | the armor's cost                                                     |

## Absorption

An armor's **Absorption** tells **how much aggravated damage taken is converted into superficial damage**.

When taking damage from an Attack, the character converts to superficial a number of points of aggravated damage equal to their Absorption — never more than the aggravated damage taken. Total Absorption is the sum of the character's **base Absorption** and the Absorption of the equipped armor. Base Absorption can be raised or lowered by effects, but never goes below 0.

For example: an armor with **Absorption 2** takes an Attack that deals **3 aggravated damage**. **2 points** are converted into superficial damage, and only **1 point** stays aggravated.

Damage that is already superficial is not affected: armor only reduces how much damage stays aggravated.

Resistances and Vulnerabilities to specific [Damage Types](Armas.md#damage-types) can raise or lower this absorption (see [Resistance and Vulnerability](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md)).

## Categories

Every armor has a **Category**, which organizes its Absorption, Dodge penalty, Minimum Strength and typical Load.

| Category   | Absorption | When Dodging  | Minimum Strength | Load   |
| ---------- | ---------- | ------------- | ---------------- | ------ |
| **Light**  | 1          | no penalty    | —                | 1      |
| **Medium** | 2 to 3     | -2 to -3 dice | 2                | 2      |
| **Heavy**  | 4 to 5     | -4 to -5 dice | 3                | 3 to 4 |

- **Dodge:** with Medium or Heavy armor, the Dodge Pool loses dice equal to the **armor's Absorption**. The character's base Absorption and Resistances do not count.
- **Minimum Strength:** with Strength below the Minimum Strength of the armor worn, the character has **-2 Movement**.

## Properties

**Properties** are an armor's special traits. The starting list of properties is:

- **[Type] Resistance (value)** — the armor grants [Resistance](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia.md) to the given [Damage Type](Armas.md#damage-types). The value is added to [Effective Absorption](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md#effective-absorption) against that Type — for example, an armor with **Absorption 2** and **Slashing Resistance 1** has Effective Absorption 3 against Slashing and 2 against the other Types.
- **[Type] Vulnerability (value)** — the armor leaves the wearer [vulnerable](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md) to the given Damage Type. The value is subtracted from [Effective Absorption](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md#effective-absorption) against that Type — for example, metal armors have **Electric Vulnerability 1**: a Chain Mail with Absorption 4 ends up with 3 against Electric.

Modules and settings can add new properties and armors to the core catalog.

---

← [Back to Equipment](Equipamentos.md)
