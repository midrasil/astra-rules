<!-- source: ba50d4a45c2b -->
# Dice Pool

The **Dice Pool** is the number of dice used to resolve an action whose outcome is uncertain. The larger the Pool, the better the character's chances of a good result.

## Dice Used

Astra uses **ten-sided dice**, written with the abbreviation **d10**. Each point of the Dice Pool is one d10 rolled: a Pool of **5 dice** means rolling **5d10**.

## Building a Dice Pool

When a character tries something that requires a test, the rule in use or the Narrator determines which **Skill** applies. The Pool is the Skill plus its **linked Attribute**, listed in [Skills](../Personagens/Per%C3%ADcias.md).

> **Attribute + Skill = Dice Pool**

For example, a character with **Agility 3** and **Stealth 2** trying to slip quietly through a guarded area rolls **Agility + Stealth**, a Pool of **5 dice**.

When no Skill applies to the action, the Pool is formed **by the Attribute alone**. For example, resisting a poison might use only **Vigor**.

Every Dice Pool has at least **one Attribute**. The second part, when there is one, is a **Skill** or **another Attribute**, never the same Attribute twice.

The linked Attribute only changes when a rule expressly says so (see [Attribute Replacements](#attribute-replacements)).

## Successes

Roll all the dice in the Pool. Each die showing **6 or more** is a **Success**.

| Result | Effect |
| --- | --- |
| 1 - 5 | No Success |
| 6 - 9 | 1 Success |
| 10 | 1 Success (a pair of 10s grants 1 extra Success) |

A result of **1** has no special effect: it simply does not count as a Success.

### Pairs of 10s

When two dice show **10** on the same roll, they form a **pair of 10s**. Each pair grants **1 extra Success**, on top of the 2 Successes the dice already produced.

> **10 + 10 = 3 Successes**

Each pair of 10s is counted separately. An unpaired 10 counts normally as **1 Success**. For example, the results **10, 10, 10, 7, 3** produce **5 Successes**: the pair of 10s produces 3, the third 10 produces 1 and the 7 produces 1 more.

## Difficulty

A test's **Difficulty** is the number of Successes needed for the action to succeed. The test succeeds when the number of Successes is **equal to or greater than the Difficulty**. Otherwise, the result is a **Failure**.

### Difficulty Scale

The table below is a **suggested** calibration, not a firm rule. The Narrator can adjust it to the situation.

| Difficulty | Description                                     |
| ---------- | ----------------------------------------------- |
| 1          | Routine: almost always works                    |
| 2          | Basic: standard for most tests                  |
| 3          | Challenging: takes a little effort              |
| 4          | Hard: needs a good Pool                         |
| 5          | Very hard: few even try                         |
| 6+         | Feat: reserved for extraordinary deeds          |

> An average character (Attribute 2 + Skill 2, a Pool of 4 dice) has good odds at Difficulty 2. Use it as a starting point.

### Extra Successes

Matching the Difficulty already guarantees success. Each Success **above** the Difficulty, however, deserves special treatment: the action can be finished faster, more elegantly or more discreetly, reveal extra information or open new opportunities. The bigger the surplus, the more impressive the result. It is up to the Narrator to reward the surplus narratively.

> **Example:** with a Pool of 5 dice, a character gets **2, 6, 10, 10, 4**. The 6 produces 1 Success and the pair of 10s produces 3, for a total of **4 Successes**. Against Difficulty 4 or less, the action succeeds; against Difficulty 5 or more, it is a Failure.

## Opposed Tests

In an **opposed test**, two characters roll their Dice Pools and whoever gets more Successes wins. For example, the Stealth of someone hiding against the Perception of someone searching.

On a tie, **the current situation stands**: whoever is trying to change something fails. Specific rules, such as [Confront](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md), can set a different result for a tie.

## Penalties

Dice penalties, such as those from [Prone](../Condi%C3%A7%C3%B5es/Ca%C3%ADdo.md), [Debilitated](../Condi%C3%A7%C3%B5es/Debilitado.md), [Grappled](../Condi%C3%A7%C3%B5es/Agarrado.md) and [Overload](../Equipamentos/Equipamentos.md#overload), **add up**. A character who is Prone and Debilitated, for example, suffers **-4 dice**.

Some penalties only affect rolls of one category, **Physical** or **Spiritual** (see [Attributes](../Personagens/Atributos.md)). A roll's category is determined by the Attribute actually used, including after a replacement. When the Pool combines two Attributes of different categories, the penalties of both categories apply, and they also add up.

### Minimum Pool

Penalties never reduce a Dice Pool below **1 die**. A heavily penalized character still rolls 1 die.

The exception is a rule stating that the action cannot be taken when the Pool falls below 1 die, such as an Attack beyond Range in [Confront](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md).

## Attribute Replacements

A Skill only uses another Attribute when an Action, equipment, Capability or other rule expressly says so. Describing the same action in a different way does not, by itself, change the linked Attribute.

When a Pool uses a Skill, determine its Attribute in this order:

1. the Skill sets its **linked Attribute**;
2. an Action, equipment or another rule can replace that Attribute;
3. a **Capability** can set another Attribute and always takes precedence over the previous steps.

For example, Fighting is linked to Agility. A melee Attack normally uses **Agility + Fighting**. If the weapon has a property that sets Strength, the Attack uses **Strength + Fighting**. If a Capability sets Cunning as the Attribute of that Attack, the final Pool is **Cunning + Fighting**.

A replacement follows these principles:

- it swaps one Attribute for another: only the final Attribute is added to the Skill;
- its effect is limited to the Skill, Action, Pool or formula it names;
- replacements do not chain to add several Attributes;
- when more than one optional replacement is available, the character picks only one.

The narrative approach can still change the applicable Skill, the Difficulty, the effects of a win or failure and any circumstantial bonuses or penalties. It just does not freely replace a Skill's Attribute.

## Help

Other characters can help whoever is making a test. Helpers do not roll dice. Help adds **+1 die** to the Dice Pool of whoever makes the test.

There is no limit on helpers, but the bonus **does not stack**: the test gets at most **+1 die** of help, no matter how many characters help.

In a Tactical Scene, a helper must be **adjacent** to whoever makes the test and uses their **Action**. Outside one, it is enough that the helper can actually take part in the task, at the Narrator's discretion.

> **Example:** a character with **Research 2** looks for information in a library with two allies helping. Their Pool gets **+1 die**.

---

← [Back to Basic Mechanics](Mec%C3%A2nica%20B%C3%A1sica.md)
