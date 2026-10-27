<!-- source: 6e3713fe0eec -->
# Derived Traits

Some of the character's values are not chosen directly: they are **calculated from the Attributes**.

| Trait | Default formula |
| --- | --- |
| **Health** | **3 + Vigor** boxes (see [Health](../Regras/Personagens/Vida.md)) |
| **Willpower** | **3 + Determination** boxes (see [Willpower](../Regras/Personagens/Vontade.md)) |
| **Initiative** | Pool of **Cunning + Determination**, rolled at the start of the Scene (see [Initiative](../Regras/Cenas%20e%20Conflitos/A%20Cena.md#initiative)) |
| **Maximum Load** | **5 + Strength** slots (see [Load](../Regras/Equipamentos/Equipamentos.md#load)) |

## Replacements in formulas

Capabilities and other rules can replace an Attribute used in a derived trait. The replacement affects only the given formula, does not add the two Attributes together and does not change their other roles.

For example, if a Capability says Health uses Cunning instead of Vigor, its formula becomes:

> **Health = 3 + Cunning**

This replacement does not make Cunning work as Vigor in tests, recovery or any other rule.

When the Attribute that currently makes up a derived trait increases, the value is recalculated immediately. Capabilities always take precedence over the default formulas and over other earlier rules that set their Attributes.

---

← [Back to Character Creation](0%20-%20Cria%C3%A7%C3%A3o%20de%20Personagem.md)
