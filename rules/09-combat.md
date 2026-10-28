# Combat

*Draft.* Combat happens in **rounds** of about 5 seconds. In each round, every character takes one **turn**, in initiative order.

## Initiative

At the start of combat, everyone makes a **Dexterity test**. Turn order is:

1. **Criticals**, highest roll first
2. **Successes**, highest roll first
3. **Failures**, highest Dexterity first

Ties go to the character with higher Dexterity. Initiative is rolled once and kept for the whole fight.

> **Example:** Rafael (DEX 60) rolls 52, a success. Marina (DEX 70) rolls 31, also a success. The guard (DEX 40) rolls 77, a failure. Order: Rafael, Marina, guard.

### Surprise

Characters caught by surprise act **after everyone else** in the first round, and can't take reactions until their first turn.

## Your turn

On your turn you get:

- **Movement**
- **One major action**
- **One minor action**
- **Any number of free actions**

You can do them in any order, and you can split your movement around your actions. You can also **trade down**: give up your major action for a second minor action or a second movement.

Outside your turn, you also get **one reaction** per round.

### Movement

**Movement = (Strength + Dexterity) ÷ 4 feet**, rounded to the nearest 5, with halves rounding up (minimum 5 feet). In other words, half the average of the two attributes.

| Strength + Dexterity | Movement |
| --- | --- |
| Under 30 | 5 ft |
| 30–49 | 10 ft |
| 50–69 | 15 ft |
| 70–89 | 20 ft |
| 90–109 | 25 ft |
| 110–129 | 30 ft |
| 130–149 | 35 ft |
| 150–169 | 40 ft |
| 170–189 | 45 ft |
| 190–200 | 50 ft |

> **Example:** Rafael has Strength 45 and Dexterity 60, a total of 105, so he moves 25 feet (5 squares on a 5-foot grid).

A leg injury halves movement. Standing up from prone costs half your movement. Powers like Flight or Super-Speed can exceed these numbers.

### Major actions

| Action | What it does |
| --- | --- |
| **Attack** | Make one melee or ranged attack |
| **Use a power** | Use a Moderate, Major or Extreme effect |
| **Dash** | Move again (a second full movement) |
| **Full defense** | +20 to every defense until your next turn |
| **First aid** | Make a Medicine test on someone (see [`08-healing.md`](08-healing.md#first-aid)) |
| **Help** | Give an ally +20 on their next test, if you can plausibly help |
| **Ready** | Choose a major action and a trigger ("I shoot whoever comes through the door"). It happens as your reaction when the trigger occurs |
| **Other test** | Anything else that needs a test: pick a lock, hack a console, intimidate a foe |

### Minor actions

| Action | What it does |
| --- | --- |
| **Aim** | +10 to your next attack this turn |
| **Use a Minor power** | A free (0-slot) effect |
| **Ready or stow an item** | Draw a weapon, put one away, pull something from a pack |
| **Reload** | Reload a weapon |
| **Quick use** | Drink a potion, flip a switch, open a door |

### Free actions

Things that take no real time: say a few words, drop an item, let go of a ledge. The GM can limit these if they get out of hand.

### Ranged attacks

Ranged attacks take a penalty based on how far away the target is:

| Range band | Distance | Modifier |
| --- | --- | --- |
| **Close** | Up to 30 ft | ±0 |
| **Medium** | Up to 100 ft | −10 |
| **Long** | Up to 300 ft | −20 |
| **Extreme** | Up to 1,000 ft | −40 |

Every ranged weapon has a **range class**, the farthest band it can reach:

| Range class | Farthest band | Fantasy | Modern | Sci-fi |
| --- | --- | --- | --- | --- |
| **Thrown** | Close | Throwing axe, javelin | Grenade, knife | Grenade |
| **Short** | Medium | Sling, shortbow | Pistol, shotgun | Holdout blaster |
| **Long** | Long | Longbow, crossbow | Rifle | Blaster rifle |
| **Extreme** | Extreme | Siege engine | Sniper rifle | Railgun |

Range class is separate from damage class (see [`06-damage.md`](06-damage.md#weapon-classes)): a pistol and a shortbow both deal Medium damage, but a longbow out-ranges both.

- **Scopes and sights:** when you Aim with a scoped weapon, treat the target as one band closer.
- **Powers:** damaging powers reach Medium range unless the world or discipline says otherwise.
- **Shooting in melee:** making a ranged attack while an enemy is in your engagement range is at −20, and you can't Aim.

### Cover

A target behind cover is harder to hit:

| Cover | Example | Modifier |
| --- | --- | --- |
| **Light** | Brush, a fence, a crouching ally | −10 |
| **Partial** | A low wall, a car door, an overturned table | −20 |
| **Heavy** | An arrow slit, a doorframe, peeking around a corner | −40 |
| **Full** | Completely hidden behind something solid | Can't be targeted directly |

- Cover mainly affects **ranged** attacks. It applies in melee only when something is actually in the way, such as fighting across a table.
- **Area effects** ignore cover unless it's full cover between the target and the center of the blast.
- **Darkness, smoke and fog** use the same modifiers: dim light is Light, thick smoke is Heavy, and total darkness is Full unless the attacker can see in it.

## Engagement

A character is **engaged** with every enemy within their **engagement range**: 5 feet for most weapons, or 10 feet for reach weapons like spears and polearms.

## Reaction

You get **one reaction** per round, outside your turn. Use it for one of these:

- **A defense** (dodge, parry or block, see [`07-defense-and-armor.md`](07-defense-and-armor.md#defense))
- **A readied action**
- **An opportunity attack**

Your first defense each round uses your reaction. You can still defend again after that, at a cumulative −20 per extra defense, but you can't make a readied action or an opportunity attack once your reaction is spent.

### Opportunity attacks

An opportunity attack is a melee attack at **−20**, made as your reaction, when either of these happens:

- **An enemy's melee attack against you misses.** You strike back through the opening.
- **An enemy leaves your engagement range.** You strike at them as they pull away.

The target can defend against an opportunity attack as normal.

Because it uses your reaction, you can't dodge an attack *and* counter it in the same round. A counter only comes when the enemy misses on their own, so you can either play it safe and defend, or gamble on a miss and strike back.

> **Example:** A guard attacks Marina and rolls 68 against his Melee of 50, a miss. Marina hasn't used her reaction yet, so she makes an opportunity attack with her Melee of 60 at −20, for a target of 40.
