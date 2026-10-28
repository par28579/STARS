# Genre Dials

*Draft.* The core rules stay the same in every world. **Genre dials** are the settings a world builder turns to make those rules feel gritty, heroic or superhuman, without rewriting anything.

Each world sets its dials once, before play. Players and the GM (human or AI) should know them from the start.

## Presets

Most worlds can pick a preset and stop there:

| Dial | Gritty | Standard | Heroic | Superhuman |
| --- | --- | --- | --- | --- |
| **Power level** | Gritty | Standard | Heroic | Heroic |
| **HP bonus** | +0 | +5 | +10 | +20 |
| **Lethality** | Gritty | Standard | Heroic | Heroic |
| **Full rest** | A week | A night | A short break | A short break |
| **Hit locations** | Injuries only | Injuries only | Injuries only | Injuries only |
| **Powers** | Usually off | On or off | On or off | On |
| **Slot rate** | Scarce | Standard | Standard | Abundant |
| **Attribute ceiling** | 90 | 90 | 90 | 100 |
| **Attribute method** | Point-buy | Point-buy | Point-buy | Point-buy |

Mixing is encouraged. A brutal fantasy war story might use Heroic power level (skilled veterans) with Gritty lethality (anyone can die). A cozy slice-of-life world might be Standard everywhere, with Powers off and Heroic lethality, because nobody should die in a bakery.

## The dials

### Power level

How capable characters are at the start and how fast they grow.

| Setting | Attribute points (per attribute) | Skill points | Advancement points per milestone |
| --- | --- | --- | --- |
| Gritty | 15 | 150 | 10 |
| Standard | 25 | 200 | 15 |
| Heroic | 35 | 250 | 20 |

See [`10-character-creation.md`](10-character-creation.md) and [`11-advancement.md`](11-advancement.md).

### HP bonus

Added to Strength ÷ 5 for every character's max HP: **+0, +5, +10 or +20**. See [`05-health-and-injuries.md`](05-health-and-injuries.md#hit-points).

### Lethality

What happens at 0 HP. See [`05-health-and-injuries.md`](05-health-and-injuries.md#zero-hp).

| Setting | At 0 HP |
| --- | --- |
| Heroic | Unconscious; wakes after the scene with 1 HP |
| Standard | Dying; dies without a Medicine test within a few minutes |
| Gritty | Dying, and any further damage kills outright |

### Full rest

How long a full rest takes. This one dial sets how fast characters recover **power slots**, **HP** and **injuries**. See [`04-power-slots.md`](04-power-slots.md#recovering-slots) and [`08-healing.md`](08-healing.md).

| Setting | Full rest |
| --- | --- |
| Heroic | A short break (an hour or so) |
| Standard | A night's sleep |
| Gritty | A week of downtime |

### Hit locations

| Setting | Effect |
| --- | --- |
| Injuries only | One HP pool; criticals and big hits cause injuries to a location |
| Full hit locations | Each body part also has its own HP, and armor can cover single locations |

See [`05-health-and-injuries.md`](05-health-and-injuries.md#optional-dial-full-hit-locations).

### Powers

**On** or **off**. When off, the Powers attribute isn't bought or rolled, characters have four attributes, and there are no power slots. See [`02-attributes.md`](02-attributes.md#about-powers).

### Slot rate

How many power slots a character gets from their Powers attribute. See [`04-power-slots.md`](04-power-slots.md#how-many-slots).

| Setting | Slots | Powers 50 gives |
| --- | --- | --- |
| Scarce | Powers ÷ 20 | 2 slots |
| Standard | Powers ÷ 10 | 5 slots |
| Abundant | Powers ÷ 5 | 10 slots |

### Attribute ceiling

The highest an attribute can reach through advancement: **90** (peak human) or **100** (legendary or superhuman). Character creation caps attributes at 70 either way. See [`11-advancement.md`](11-advancement.md#major-milestones-attributes).

### Attribute method

**Point-buy** or **rolled**. See [`10-character-creation.md`](10-character-creation.md#2-attributes).

## World sheet

A world records its dials in a short block like this, so anyone running it knows the settings:

```
STARS dials
  Preset:            Standard
  Power level:       Standard
  HP bonus:          +5
  Lethality:         Standard
  Full rest:         A night
  Hit locations:     Injuries only
  Powers:            On (called "Weaves")
  Slot rate:         Standard
  Attribute ceiling: 90
  Attribute method:  Point-buy
```

The world can also rename things to fit its flavor, such as what Powers and power slots are called, or which skills exist.
