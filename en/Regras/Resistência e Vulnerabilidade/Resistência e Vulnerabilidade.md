<!-- source: b0208352d075 -->
# Resistance and Vulnerability

This section gathers the rules that define how characters and creatures react to damage from specific [Damage Types](../Equipamentos/Armas.md#damage-types) and [Materials](../Equipamentos/Armas.md#material-required-one-per-weapon), through **Resistances**, **Vulnerabilities** and **Immunities**.

They can be granted by equipment, Conditions, origins, creatures, spells or effects.

## Concepts

- [Resistance](Resist%C3%AAncia.md) — a value that helps convert aggravated damage into superficial damage.
- [Vulnerability](Vulnerabilidade.md) — a value that reduces absorption and increases the damage taken.
- [Immunity](Imunidade.md) — no value; damage of the Type or Material simply does not apply.

Resistances, Vulnerabilities and Immunities to Materials are, for now, set directly on characters and creatures. Armor still grants Resistances only to Damage Types.

## Effective Absorption

When taking damage, the **Effective Absorption** is calculated considering the [Damage Type](../Equipamentos/Armas.md#damage-types) taken and the Material of the weapon that caused it, if any:

> **Effective Absorption** = [total Absorption](../Equipamentos/Armaduras.md#absorption) (base Absorption + armor Absorption) + Σ [Resistances](Resist%C3%AAncia.md) to the Type and the Material - Σ [Vulnerabilities](Vulnerabilidade.md) to the Type and the Material

The values for the Type and the Material are added together. When the damage source has no Material, only the Damage Type is considered.

- **Effective Absorption greater than or equal to the aggravated damage:** all the damage is converted into superficial damage.
- **Effective Absorption between 0 and the damage:** only the part covered by the absorption is converted; the rest stays aggravated (see [Armor](../Equipamentos/Armaduras.md)).
- **Negative Effective Absorption:** the negative value is added to the damage taken (as an absolute value) and all the damage is aggravated — no conversion is possible (see [Vulnerability](Vulnerabilidade.md)).
- Damage that is already **superficial** is not affected by positive absorption.
- [Immunity](Imunidade.md) to the Type or the Material takes precedence over everything: the damage is ignored before Effective Absorption is even calculated, even if there is Vulnerability to the other.

## Examples

- A character with **Absorption 1** and **Fire Resistance 3** takes **4 Fire damage**: the Effective Absorption is 4, and the 4 points are converted into superficial damage.
- A character with **Fire Vulnerability 3** and **Absorption 0** takes **1 Fire damage**: the Effective Absorption is -3, and they take **4 aggravated Fire damage**.
- A character with **Fire Immunity** takes **4 Fire damage**: the damage does not apply, and no damage is taken.
- A character with **Absorption 2** and **Fire Vulnerability 3** takes **1 Fire damage**: the Effective Absorption is -1, and they take **2 aggravated Fire damage**.
- A creature with **Absorption 0**, **Slashing Resistance 3** and **Silver Vulnerability 3** takes Slashing damage from a Silver weapon: the Effective Absorption is 0, since the values cancel out.
- A creature with **Common metal Immunity** takes damage from an iron or steel weapon: no damage is taken, whatever the weapon's Damage Type. This Immunity does not apply to Silver or Meteorite weapons.

## Relations

Damage Types and Materials are defined in [Weapons](../Equipamentos/Armas.md). The severity of damage and its recovery are described in [Health](../Personagens/Vida.md).

Damage dealt by [Zones](../Cenas%20e%20Conflitos/Zonas.md) does not use Effective Absorption. In that case, Resistances and Vulnerabilities are added together as in Effective Absorption: a positive total converts that many points of the Zone's aggravated damage into superficial before applying the test's Successes, a negative total increases the Zone's Damage, and Immunities prevent the damage entirely.

---

← [Back to Astra](../../Readme.md)
