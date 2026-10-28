# Healing

*Draft.* Characters recover HP in three ways: **resting**, **first aid**, and **healing powers**. Injuries need treatment before they heal.

## Natural healing

After each **full rest**, a character regains **Strength ÷ 10 HP** (rounded down, minimum 1).

The length of a full rest is set by the world (see [`04-power-slots.md`](04-power-slots.md#recovering-slots)), so healing speed scales with it automatically:

| World | Full rest | Strength 45 character (14 HP) |
| --- | --- | --- |
| Heroic | A short break | Back to full in an afternoon |
| Standard | A night's sleep | Back to full in about four nights |
| Gritty | A week of downtime | Back to full in about a month |

### Extended care

If someone looks after the character during a full rest and succeeds at a **Medicine** test, natural healing is **doubled** for that rest.

## First aid

A **Medicine** test patches up fresh wounds during or right after a fight.

| Result | Effect |
| --- | --- |
| **Critical** | Restores 4 HP |
| **Success** | Restores d4 HP |
| **Failure** | No effect |
| **Fumble** | The patient loses 1 HP |

- Each character can receive first aid **once per scene**.
- Without medical supplies (bandages, a medkit, a healer's kit), the test is at **−20**.
- First aid also **stabilizes** a dying character at 0 HP (see [`05-health-and-injuries.md`](05-health-and-injuries.md#zero-hp)). A stabilized character wakes at 1 HP after the scene.

## Healing powers

A healing discipline uses the effect tiers from [`04-power-slots.md`](04-power-slots.md#effect-tiers), mirroring power damage:

| Tier | Cost | Healing |
| --- | --- | --- |
| **Minor** | Free | 1 HP to one target, or stabilize a dying character |
| **Moderate** | 1 slot | d8 HP to one target |
| **Major** | 2 slots | 2d6 HP to everyone in a small area, **or** heal one injury |
| **Extreme** | 3 slots | 4d8 HP to everyone in a large area, **or** heal every injury on one target |

Healing powers aren't limited to once per scene, but each use costs slots as normal.

## Treating injuries

An injury (see [`05-health-and-injuries.md`](05-health-and-injuries.md#injuries)) doesn't heal on its own until it's **treated**.

1. **Treat it:** a successful **Medicine** test sets the bone, closes the wound, or bandages the burn. This is separate from first aid, and each injury can be attempted once per scene.
2. **Let it heal:** a treated injury goes away after **3 full rests**.

An untreated injury heals only after **6 full rests**, and the GM can have it worsen in Gritty worlds.

### Serious injuries

A serious injury (a second injury to the same location, such as a broken bone or a lost eye) needs a **Hard (−20)** Medicine test to treat. It takes **6 full rests** to heal once treated, and the GM may rule some are permanent without a healing power.
