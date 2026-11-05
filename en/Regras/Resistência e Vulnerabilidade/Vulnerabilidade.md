<!-- source: 93067469d1e6 -->
# Vulnerability

A **Vulnerability** is a value tied to a specific [Damage Type](../Equipamentos/Armas.md#damage-types) or [Material](../Equipamentos/Armas.md#material-required-one-per-weapon) that makes the character more susceptible to the matching damage. It always comes with a value — for example, **Ice Vulnerability 2** or **Silver Vulnerability 3**.

When calculating [Effective Absorption](Resist%C3%AAncia%20e%20Vulnerabilidade.md#effective-absorption), Vulnerabilities to the weapon's Damage Type and Material are added together and **subtracted** from the absorption. That is why a Vulnerability eats into the [armor's Absorption](../Equipamentos/Armaduras.md#absorption) before it becomes extra damage.

For now, Vulnerabilities to Materials are set directly on characters and creatures.

When Effective Absorption is **negative** and the character takes at least 1 point of damage from that source:

- the negative value is added to the damage taken (as an absolute value);
- all the damage then becomes **aggravated** — no conversion is possible, even if the damage taken would originally have been superficial.

For example, a character with **Absorption 2** and **Fire Vulnerability 3** has Effective Absorption -1 against Fire; **1 Fire** damage becomes **2 aggravated damage**.

---

← [Back to Resistance and Vulnerability](Resist%C3%AAncia%20e%20Vulnerabilidade.md)
