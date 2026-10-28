# Health and Injuries

*Draft.* Characters have one pool of **hit points (HP)**. Serious hits also cause **injuries** to a specific body part.

## Hit points

**Max HP = Strength ÷ 5** (rounded down, minimum 1) **+ the world's HP bonus.**

| World type | HP bonus |
| --- | --- |
| Gritty | +0 |
| Standard | +5 |
| Heroic | +10 |
| Superhuman | +20 |

> **Example:** In a Standard world, a character with Strength 45 has 9 + 5 = **14 HP**.

Damage reduces current HP. Healing restores it, up to the maximum.

## Injuries

A hit causes an **injury** when either of these is true:

- The attack was a **critical**.
- A single hit dealt **more than half the target's max HP**.

### Hit location

Find the location by **reversing the digits of the attack roll**. No extra roll is needed.

> **Example:** An attack roll of 37 hits location **73**, the left leg. A roll of 05 hits location 50, the torso.

| Reversed roll | Location |
| --- | --- |
| 01–10 | Head |
| 11–25 | Left arm |
| 26–40 | Right arm |
| 41–70 | Torso |
| 71–85 | Left leg |
| 86–100 | Right leg |

Worlds with non-human creatures, vehicles or starships can define their own location tables.

### Injury effects

| Location | Effect |
| --- | --- |
| **Head** | −20 to Intellect tests; dazed for a moment |
| **Arm** | −20 to tests using that arm; may drop what it holds |
| **Torso** | −10 to all physical tests |
| **Leg** | Movement halved; −20 to Athletics and Dodge |

An injury lasts until it's treated and heals (see [`08-healing.md`](08-healing.md#treating-injuries)). Injuries to the same location don't stack, but the GM can make a second one more serious (a broken bone, a lost eye).

## Zero HP

At 0 HP, a character is **out of action**. What happens next depends on the world's lethality dial:

| Lethality | At 0 HP |
| --- | --- |
| **Heroic** | Unconscious; wakes after the scene with 1 HP |
| **Standard** | Unconscious and dying; dies unless an ally succeeds at a Medicine test within a few minutes |
| **Gritty** | As Standard, and any further damage kills outright |

## Optional dial: full hit locations

For crunchier worlds, each location has its own HP instead of using injuries alone:

| Location | Share of max HP |
| --- | --- |
| Head | 1/3 |
| Each arm | 1/4 |
| Torso | 1/2 |
| Each leg | 1/3 |

Damage applies both to the location (rolled as above, on every hit) and to the main pool. A location at 0 HP is disabled, and the character suffers its injury effect until healed.
