# Defense and Armor

*Draft.* Defense and armor do two different jobs:

- **Defense** (dodging, parrying, blocking) lets a target **avoid** a hit. It's an opposed test.
- **Armor** **reduces** the damage of a hit that lands. It's a static value.

## Defense

When an attack succeeds, the target can try to defend. The defender picks one option:

| Defense | Skill | Works against |
| --- | --- | --- |
| **Dodge** | Dodge (DEX) | Melee; ranged at −20 (diving for cover) |
| **Parry** | Melee, or Brawl if unarmed | Melee only |
| **Block** | Melee, with a shield | Melee and ranged |

### Resolving a defense

The attack and the defense are an **opposed test** (see [`01-core-resolution.md`](01-core-resolution.md#opposed-tests)). The attacker has already succeeded, so:

| Defender's result | Outcome |
| --- | --- |
| **Fails** | The attack hits |
| **Succeeds, but rolls lower than the attacker** | The attack hits |
| **Succeeds, and rolls equal to or higher than the attacker** | The attack is avoided |
| **Critical** | The attack is avoided, and the defender gets **+20 on their next action** |
| **Fumble** | The attack hits, and the defender is thrown off balance (falls, drops a weapon, or similar) |

An attacker's **critical** beats any defense except a defender's critical. Two criticals: the higher roll wins, ties go to the defender.

> **Example:** A guard attacks Rafael with Melee 50 and rolls 41, a success. Rafael dodges with Dodge 55 and rolls 48. Both succeeded and Rafael rolled higher, so the blow misses.

### Multiple defenses

The first defense before a character's next turn is free. Each defense after that is at a cumulative **−20**.

### Area effects

Area attacks, such as a Major or Extreme power or an explosion, can't be parried or blocked. A successful Dodge **halves** the damage instead of avoiding it.

## Armor

Armor has an **armor value (AV)**. Subtract AV from the damage of every hit. If that reduces damage to 0 or less, the hit does no damage.

| Class | AV | Penalty | Fantasy | Modern | Sci-fi |
| --- | --- | --- | --- | --- | --- |
| **None** | 0 | None | Clothing | Clothing | Clothing |
| **Light** | 1 | None | Leather, padded cloth | Leather jacket | Flight suit |
| **Medium** | 2 | −10 | Chain mail | Kevlar vest | Combat armor |
| **Heavy** | 4 | −20 | Plate armor | Riot or bomb suit | Heavy assault armor |
| **Powered** | 6 | −10 | Enchanted plate | Military exosuit | Power armor |

The **penalty** applies to Dodge, Stealth and Athletics tests while wearing the armor.

### Armor and other rules

- **Criticals ignore armor.** The attacker found a gap.
- **Injuries** use damage **after** armor. A hit counts as "more than half max HP" only if what gets through is that big.
- **Powers:** armor reduces physical power damage (fire, lightning, force). Mental or spiritual attacks ignore it unless the world says otherwise.
- **Full hit locations dial:** each location can have its own AV, so a helmet protects only the head.
