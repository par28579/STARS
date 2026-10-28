# Open Questions

Design decisions still being worked out.

## Powers

**Decided:**

- Powers is its own attribute, and the power system is the skills (disciplines) under it. Powers can be switched off for mundane settings.
- Powers are limited by **one shared pool of slots**, with Minor/Moderate/Major/Extreme effects costing 0/1/2/3 slots (see [`rules/04-power-slots.md`](../rules/04-power-slots.md)).

Still open:

- **Slot count.** Is one slot per 10 Powers the right rate? Should it be a genre dial?
- **Backlash.** Leave it to the GM, or write a table?
- **Effect scale.** How do worlds define what each tier of a discipline can do?

## Willpower

Resolve moves out of Powers. Proposed home: **Charisma** (force of personality). Alternative: Intellect (mental discipline).

## Endurance

Nothing explicitly covers stamina or physical endurance yet. Fold it into Strength, or handle it elsewhere?

## Damage and health

**Decided:**

- One HP pool (Strength ÷ 5 + world bonus), plus injuries to a hit location on criticals and big hits. Full per-location HP is an optional dial (see [`rules/05-health-and-injuries.md`](../rules/05-health-and-injuries.md)).
- Classic damage dice by weapon class, d3 to 2d8 (see [`rules/06-damage.md`](../rules/06-damage.md)).
- Defense (dodge, parry, block) avoids hits with an opposed test; armor reduces damage by a static value (see [`rules/07-defense-and-armor.md`](../rules/07-defense-and-armor.md)).
- Healing via rest (Strength ÷ 10 per full rest), first aid (Medicine, once per scene) and healing powers; injuries need treatment, then 3 full rests (see [`rules/08-healing.md`](../rules/08-healing.md)).

Still open:

- **Healing rates.** Are the draft numbers right in play? Gritty worlds heal very slowly by design.- **Scale.** How do vehicles, starships and giant monsters fit the d3–2d8 range?
- **Power damage.** Are the draft tier values (d3 / d8 / 2d6 / 4d8) balanced against weapons?

## Combat structure

**Decided:**

- Initiative is a Dexterity test. Each turn has movement, a major action, a minor action and free actions, plus one reaction per round (see [`rules/09-combat.md`](../rules/09-combat.md)).
- Movement is the average of Strength and Dexterity in feet, rounded to the nearest 5 (about 35 feet for an average person).
- Four range bands (Close ±0, Medium −10, Long −20, Extreme −40); each ranged weapon has a range class setting its farthest band.
- Opportunity attacks at −20, as a reaction, when an enemy's melee attack misses you or an enemy leaves your engagement range.
- Cover as an attack modifier (Light −10, Partial −20, Heavy −40, Full can't be targeted).
- A Withdraw major action lets a character leave engagement without provoking.
- Multiple attacks: 1 + skill bonus (+1 at 75, +2 at 100) + weapon bonus (Rapid +1, Automatic +2).
- Ammunition is tracked per magazine: weapons have a capacity in attacks, every attack uses 1, and reloading is a minor action.

## Character creation

**Decided (draft):** Point-buy attributes from a base of 20, or an optional rolled method; skill points for training, capped at +40 per skill and 60 total at creation (see [`rules/10-character-creation.md`](../rules/10-character-creation.md)).

Still open:

- **Point totals.** Do the Gritty / Standard / Heroic amounts feel right in play?
- **Starting equipment.** A more concrete default kit, or leave it to each world?

## Advancement

**Decided (draft):** Milestone-based. Each milestone gives 10 / 15 / 20 advancement points by power level; skills cost 1, 2 or 3 points per +1 as they rise, up to +5 per milestone. Every fourth milestone adds +5 to an attribute (see [`rules/11-advancement.md`](../rules/11-advancement.md)).

Still open:

- **Pacing in play.** Does skill 75 around milestone 3 and skill 100 around milestone 8 feel right?
- **Attribute cap.** Is 90 the right ceiling for non-legendary characters?

## Genre dials

Settings a world builder can turn without changing the core rules. Candidates:

- Lethality (heroic / standard / gritty)
- HP bonus (+0 / +5 / +10 / +20)
- Hit locations (injuries only / full per-location HP)
- Powers on/off
- Rarity and potency of powers (including slot count)
- Length of a full rest (heroic / standard / gritty)
- Power level for character creation (gritty / standard / heroic)
- Heroic resources (Luck, Grit, and so on)
