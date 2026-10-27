<!-- source: 1ceea79d958e -->
# Equipment

Equipment is the objects characters carry and use, whether to attack, protect themselves or carry out other tasks.

The Astra core currently organizes equipment into **four types**:

- [Weapons](Armas.md) — equipment used to attack.
- [Armor](Armaduras.md) — equipment used for protection.
- [Shields](Escudos.md) — equipment used for defense.
- **Common items** — everyday objects, such as backpacks, ropes and tools.

The equipment available in the core is gathered in:

- [Weapon Catalog](Cat%C3%A1logo%20de%20Armas.md);
- [Armor Catalog](Cat%C3%A1logo%20de%20Armaduras.md);
- [Shield Catalog](Cat%C3%A1logo%20de%20Escudos.md).

New equipment types may be added in the future, through specific modules or settings.

## Value

All equipment has a **Value**, used to compare prices and build budgets. Value is an abstract number and may have decimals; the setting decides the currency's name, its availability and the buying rules.

## Use during scenes

- [Switching Equipment](Trocar%20Equipamento.md) — the action used to replace an item that is already in use.
- [Scenes and Conflicts](../Cenas%20e%20Conflitos/Cenas%20e%20Conflitos.md) — rules for confrontations and other tactical decisions.

## Load

The weight of equipment is **not measured in kilograms**. In Astra, the space an item takes up is measured in **slots**.

Each piece of equipment has a **Load** value, which tells how many slots it takes. This applies equally to weapons, armor, shields and common items.

### Maximum Load

A character's **Maximum Load** is the total Load they can carry without penalties. Its standard formula is:

> **5 + Strength** slots

Strength is the **Load Attribute** by default. Capabilities and other rules can replace it in this formula. When that happens, Maximum Load is recalculated immediately from the new Attribute, without changing Strength tests or other rules.

### Overload

Carrying more than the **Maximum Load** leaves the character in **Overload**. While in Overload, they:

- have their **base Movement** cut in **half** (see [Movement](../Movimento/Movimenta%C3%A7%C3%A3o.md));
- suffer **-2 dice** on rolls that use a [Physical Attribute](../Personagens/Atributos.md#categories).

Overload ends as soon as the Load is back within the limit.

---

← [Back to Astra](../../Readme.md)
