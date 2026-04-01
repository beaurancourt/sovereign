---
layout: default
title: Home
---

# Rules

This chapter introduces the core rules of *Sovereign*. It aims to familiarize you with key terms, the game’s goal, main procedures, and structure for common situations.

*Sovereign* is a [Table-Top Role-Playing Game](https://en.wikipedia.org/wiki/Tabletop_role-playing_game), where a group of friends imagines a shared fantasy adventure. One player (the Game Master) prepares the adventure, while the others [create characters](/character-creation) to participate. The Game Master describes situations, and the players describe how their characters react. This interaction creates new situations, and the cycle continues.

The players aim to defeat monsters and recover treasure, gaining Experience Points in the process. *Sovereign* doesn’t have a strict concept of *winning*, but playing skillfully means gathering as many Experience Points as possible while avoiding death. As players earn Experience Points, their characters [grow stronger](/character-creation#advancement), allowing them to face greater challenges that reward more Experience Points.

The Game Master’s role involves resolving situations **fairly**. The Game Master doesn’t *win* in the traditional sense, but success involves creating [meaningful, informed choices](https://www.bastionland.com/2018/09/the-ici-doctrine-information-choice.html) for players and fairly determining the outcomes.

## Table Of Contents

{% include chapter-toc.html items=site.data.rules %}

## Common Terms

- **Player**: All of the real-life humans sitting around the table, *except* for the Game Master. Each Player controls a Character.
- **Game Master**: The real-life human in charge of everything *except* the actions of the Player Characters (PC). They control the setting, the actions of Non-Player Characters (NPCs), and read/run the [adventures](/index#recommended-adventures).
- **Character**: A person within the game world, built using the rules in [Character Creation](/character-creation).
- **Player Character (PC)**: A Character controlled by a Player.
- **Non-Player Character (NPC)**: All entities controlled by the GM. Some NPCs are also Characters (if the GM finds this useful).
- **Party**: The group of PCs and [Henchmen](/equipment#henchmen) adventuring together.

## Dice Notation

*Sovereign* uses [dice](https://www.amazon.com/Chessex-001LBCHX-Pound-O-Dice/dp/B008C0KXYS) to generate randomness. The notation `NdX` represents a dice roll, where `N` stands for the number of dice to roll, and `X` indicates how many sides the dice have. You add the results together.

For example, `3d8` means rolling 3 eight-sided dice and summing the results.

Sometimes, additional operations occur. For example, `2d6•10` means rolling two six-sided dice, adding the results, and multiplying the total by 10. `1d20+3` means rolling a 20-sided die and adding 3.

![small](/assets/images/dice-sizes.png)

## The Big Picture

1. The Game Master (GM) creates a loosely defined fantasy setting where most adventures fit in somewhere.
2. The GM proposes a few adventures (describing them in vague terms) to the players between sessions. The players choose one to pursue, and the GM prepares that adventure, using [hard framing](https://thealexandrian.net/wordpress/31509/roleplaying-games/the-art-of-pacing) to place the Party directly at the adventure’s starting point with a strong hook.
3. After completing an adventure, the process repeats from step 2, usually with the same Party. Weeks or months pass in-game between adventures as appropriate.

This game focuses heavily on playing all the wonderful [adventures](/#recommended-adventures) offered by the [OSR community](https://campaignwiki.org/osr/). *Sovereign* intentionally strips out or de-emphasizes elements that might pull players away from the pre-written content within these adventures. Domain play, crafting, and similar features have been deliberately removed.

The episodic nature of the adventures makes it easy for players to join or leave, and facilitates the introduction of new PCs as old ones die, retire, or recover. We aim to keep the game running smoothly for everyone!

## Core Gameplay Loop

*Sovereign* involves one GM and up to 8 players controlling 4 to 8 PCs, exploring dark dungeons, derelict castles, and ancient tombs for fun and profit. While the game mostly takes the form of a conversation, that conversation follows a *structured* process:

1. The GM describes a situation to the players, avoiding assumptions about player actions and focusing on what the characters see, hear, and smell. Then, the GM asks, "What do you do?"
2. The players clarify their actions and the [*intent*](https://www.bastionland.com/2022/12/action-intent-duality.html) behind them. When acting as a group (such as choosing which room to explore), one player speaks for the group to reduce chaos.
3. The GM informs the players how likely their actions are to succeed, based on the situation, their [Attributes](#attributes), and [Skills](#skills), as well as the potential costs and consequences of failure. Actions that cannot fail, have no consequence, or cost little to attempt, *just happen*. [Skill Checks](#skill-checks) offer a guideline, but the GM may assign probabilities directly, like 1-in-6 or 45%.
4. If the players agree with the ruling, they roll the dice and respect the outcome. If they disagree, they negotiate or revise their plan. Common adjustments include trading higher chances of success for lesser results, or accepting greater costs or consequences for failure in exchange for a better shot at success.
5. This leads to a new situation. The GM [fast forwards](https://thealexandrian.net/wordpress/31509/roleplaying-games/the-art-of-pacing) to the next meaningful decision, narrates the transition, and repeats the process.

That’s the *entire* game. All other rules either enable interesting decisions for #2, assist the GM with #3, or ease negotiation in #4. If a rule isn’t contributing to these elements, change or remove it.

### Narrative Interaction

A key aspect of skilled play in *Sovereign* involves devising plans that *avoid* rolling dice. A plan that prompts a [Skill Check](#skill-checks) or roll can be *workable*, but also carries *risk*. Much of the fun lies in creating strategies that *cannot fail*.

Imagine encountering a deep, 15-foot wide spiked pit. A risky obstacle. If a player attempts to leap across, the GM might call for a STR/[Exert](#exert) [Check](#skill-checks), with failure leading to `3d6` [Damage](#damage) from the fall and spikes, plus becoming trapped at the bottom.

A clever player might avoid this risk by *filling the pit*. They could spend time dragging coffins or furniture into the pit, allowing themselves to descend safely, cross, and climb up the other side—without rolling.

The same principle applies to searching rooms. The GM describes the environment but avoids assuming the players touch anything, since it might carry danger. A player could simply declare, "I search the room," relying on WIS/[Notice](#notice) and risking trap activation.

A better approach involves specifying *what* and *how* they search. If their method (which usually involves a time cost measured in [Turns](#keeping-track-of-time)) reasonably uncovers a hidden trap, treasure, or clue, they *find it* automatically.

## Attributes

A PC has five attributes ranging from 3 to 18, reflecting a range from the minimum viable capacity for a playable character to the maximum normal human level.

Three of these attributes are physical.

**Strength**, reflecting physical prowess, melee combat, carrying gear, and brute force. Influences melee [attack rolls](/combat#attack-rolls), melee [damage](/combat#damage), [encumbrance](/rules#encumbrance), and [Physical](/rules#physical) [Saving Throws](#saving-throws).

**Dexterity**, reflecting speed, evasion, manual dexterity, reaction time, and combat initiative. Influences attack rolls with ranged weapons and some melee weapons, [AC](/equipment#armor-class), and [Evasion](#evasion) Saving Throws.

**Constitution**, reflecting hardiness, enduring injury, and tolerating large amounts of magical healing. Influences [HP](#hit-points) and [Physical](/rules#physical) Saving Throws.

Two are mental attributes.

**Intelligence**, reflecting memory, reasoning, technical skills, and general education. Influences [Effort](/arcane-traditions#effort) for most [Arcane Traditions](/arcane-traditions), [Evasion](/rules#evasion) and [Mental](#mental) Saving Throws, and the efficacy of some spells.

**Wisdom**, reflecting noticing things, making judgments, reading situations, and intuition. Influences [Mental](/rules#mental) Saving Throws.

### Attribute Modifiers

Each attribute has a modifier, ranging from -2 to +2 based on its score. This modifier adds to skill checks, attack rolls, [damage](#damage) rolls, [Shock](#shock) damage, and relevant [saving throw](#saving-throws) targets.

| Attribute | Modifier |
| --------- | -------- |
| 3         | -2       |
| 4-7       | -1       |
| 8-13      | 0        |
| 14-17     | +1       |
| 18        | +2       |

In this text, when referring to an attribute’s score, the full name appears (e.g., Strength). When referring to an attribute’s modifier, it will be abbreviated to three letters: STR, DEX, CON, INT, or WIS.

If an injury, character advancement, or magic item changes an attribute, immediately update the attribute’s modifier.

## Hit Points

A character’s hit points (HP) measure their distance from death. If a character reaches zero HP, they are [Mortally Injured](#mortal-injury-and-stabilization). Taking [Damage](/combat#damage) reduces a character's HP. For instance, if a character with 11 HP takes 5 damage, they would have 6 HP remaining.

A new character rolls the [HP Progression](/rules#hp-progression) for their [Class](/classes) to determine their maximum HP, adding their CON. If they have the [Die Hard](/feats#die-hard-c) Feat, they add +2 to the roll. The final value for a given die cannot be less than 1 HP.

Characters gain maximum HP as they advance in level, re-rolling their prior levels' HP and taking the new score if it’s higher, as outlined in [advancement](/character-creation#advancement-benefits).

NPCs roll a number of d8s for their HP equal to their Hit Dice (HD).

## Saving Throws

Saving throws resist unusual dangers or chance hazards. To make a saving throw, roll `1d20` and try to get a result equal to or higher than the saving throw target. Sometimes bonuses or penalties apply to the roll, but a natural 1 always fails, and a natural 20 always succeeds.

There are three types of saving throws. While the appropriate type usually feels obvious for a given threat, the GM makes the final call.

**Physical** saves resist exhaustion, poisons, diseases, or other bodily afflictions. A Character’s Physical saving throw target equals 16 minus their character level and the higher of their STR or CON.

**Evasion** saves apply when dodging explosions, avoiding traps, reacting to sudden peril, or other situations where speed matters. A Character’s Evasion saving throw target equals 16 minus their character level and the higher of their DEX or INT.

**Mental** saves apply when resisting mental attacks, insubstantial magic spells, psychological trauma, and other mental hazards. A Character’s Mental saving throw target equals 16 minus their character level and the higher of their INT or WIS.

NPCs use a single saving throw target, which equals 15 minus half their rounded-down Hit Dice (HD). For example, an NPC with 3 HD has a saving throw target of 14+ for any hazard.

## Skills

A PC's skills represent their training. A newly-created PC starts with a few trained skills and [gains more](/character-creation#advancement-benefits) as they [level up](/character-creation#advancement).

### Interpreting Skill Levels

Skills are rated on a scale from -1 to 4. Level -1 represents an absence of training. Level 0 indicates basic competence. Level 1 reflects professional-level skill. Level 2 likely makes a character the best in a village or city block. Level 3 represents mastery, making the character one of the best in a city. Level 4 reflects world-class expertise.

Skills are compactly referred to as {Skill}:{Level}. For example, [Exert](#exert):1 or [Heal](#heal):2.

All skills start at level -1.

### The Skill List

Skills may overlap in their application; the character may use either skill at their discretion.

- <strong id="exert">Exert</strong>: Run, swim, climb, jump, labor for long periods, throw things, or otherwise exert your physical strength, stamina, and coordination. Even a Character with poor physical attributes might have a good Exert skill, reflecting athletic training and expertise in maximizing their talents.
- <strong id="heal">Heal</strong>: Treat wounds, cure diseases, neutralize poisons, diagnose psychological health issues, and tend to the wounds of body and mind.
- <strong id="know">Know</strong>: Understand matters of history, geography, natural science, zoology, and other academic fields relevant to a sage or scholar. While some sages specialize in particular areas, most have broad knowledge and rarely fail to attempt answering questions tied to this skill.
- <strong id="magic">Magic</strong>: Cast or analyze magic, and know details about famous mages or magical events. Classes unable to cast spells benefit intellectually and scholastically from this skill.
- <strong id="notice">Notice</strong>: Detect small details, impending ambushes, hidden features, or concealed objects. Identify subtle smells, sounds, or other sensory cues.
- <strong id="sneak">Sneak</strong>: Move silently, hide in shadows, avoid detection, pick pockets, disguise yourself, pick locks, disable traps, and similar actions.

- <strong id="brawl">Brawl</strong>: Fight unarmed or with natural body weaponry. Punch, kick, grapple, or otherwise brawl without man-made tools. This form of combat proves inefficient without a Feat to enhance it, though it reliably avoids lethality.
- <strong id="shoot">Shoot</strong>: Fire a bow, crossbow, or hurl weapons. Maintain ranged weapons and fletch arrows.
- <strong id="stab">Stab</strong>: Engage in melee combat with weapons or throw hurling weapons. Maintain and identify weaponry.

### Skill Checks

Most Characters are skilled, competent individuals capable of performing the ordinary duties of their role. However, sometimes they encounter a challenge beyond the usual scope of their abilities, and the GM calls for a skill check.

To make a skill check, roll `2d6` and add the most relevant skill level and [attribute modifier](#attribute-modifiers) (denoted as {Attribute Modifier}/{Skill}, like STR/[Exert](#exert) or INT/[Magic](#magic)). If the total is equal to or higher than 10, the check succeeds. On a failure, the Character either cannot accomplish the feat, bad luck intervenes, or they succeed with additional complications. The GM decides the consequence of failure.

The GM always calls for a skill check at their discretion. The player describes what their Character is attempting, and the GM specifies which skill and attribute combination to roll.

### Group Checks

When a Party faces a situation together, one Character makes the roll. For each additional Character with a positive modifier, add 1 to the roll. For each Character with a negative modifier, subtract 1.

This method applies to tasks like forcing open a heavy door together, stealthing past a guard, or collectively climbing a cliff face.

### Opposed Skill Checks

When skills oppose each other, the side attempting to change the situation rolls a skill check and aims for a result of 8 plus the opposing side's modifier. For example, a Character trying to sneak past a guard might roll `2d6` plus their DEX/[Sneak](/rules#sneak) against 8 + the guard’s WIS/[Notice](#notice). This is written compactly as DEX/[Sneak](/rules#sneak) vs WIS/[Notice](#notice).

## Keeping Track of Time

A <strong id="turn">Turn</strong> is a time measurement used to determine how often certain abilities or actions can be taken. Some powers can only be triggered a certain number of times per Turn, while some special abilities function once per Turn.

A Turn represents a fight, event, activity, or effort that doesn’t last more than ten or fifteen minutes. A fight takes a Turn. A chase takes a Turn. A tense backroom negotiation takes a Turn. As long as the party remains focused on the same activity in the same location, it likely counts as one Turn.

Combat consists of <strong id="round">Rounds</strong>, with each round lasting about ten seconds. A single combat encounter may involve multiple Rounds, but it always consumes a Turn. A round begins with the actions of the side that wins initiative and ends after the actions of the side with the lowest initiative.

Between adventures or in safe places, time passes naturally, usually measured in hours, days, or weeks as needed.

## Injury, Healing, and System Strain

Injury is almost inevitable in an adventurer’s career, with some forms lasting longer than others.

### Mortal Injury and Stabilization

When a Character reaches zero HP due to [damage](#damage), they suffer a Mortal Injury. They will die at the end of the sixth [Round](#round) after their incapacitation unless an ally or special ability stabilizes them. A Mortally Injured character remains helpless, taking no actions or contributing in any meaningful way.

Stabilizing an ally requires a [Main Action](/combat#main-action) and involves a DEX/[Heal](#heal) or INT/[Heal](#heal) [skill check](#skill-checks). This check carries a penalty equal to the number of [Rounds](#round) since the target fell. A [healer’s kit](/equipment#healers-kit) is also required. Only one ally can attempt to stabilize a victim per round, though others may assist (via a [group check](#group-checks)). Attempts can be retried each round as long as hope remains.

Once stabilized, the victim stays incapacitated for one [Turn](#turn) before recovering with 1 HP and gaining the [Frail](#frail) condition.

NPCs without a name or particular importance die instantly when reduced to zero HP.

### Frail

Creatures who reach 0 HP and recover become Frail.

A Frail character can act normally, but if reduced to 0 HP again, they die instantly. Frail characters cannot recover HP through [Natural Healing](#natural-healing).

Frailty is removed after a continuous week of [Comfortable Sleep](#comfortable-sleep) and medical attention from someone with a [healer’s kit](/equipment#healers-kit) and at least [Heal](#heal)-0. Additionally, someone with at least [Heal](#heal):1 can attempt to remove Frailty with a healer's kit, an hour of labor, and a successful DEX/[Heal](#heal) or INT/[Heal](#heal) check.

Frail characters without this level of medical care must make a [Physical](#physical) save after a week; failure results in death `1d6` days later, while success means Frailty is removed after another month of [Comfortable Sleep](#comfortable-sleep).

### Natural Healing

A wounded creature recovers HP through [Comfortable Sleep](#comfortable-sleep) and adequate food. As long as they remain warm, well-fed, and comfortable, they regain HP each morning equal to their experience level, or their HD if they are NPCs.

Characters *do not* count as comfortable when sleeping in tents, outdoors, or similar conditions. They need a proper *bed*.

[Frail](#frail) creatures cannot recover HP through natural healing.

### First Aid

Healers can quickly patch up victims at a cost to their physical resilience. By spending one minute treating an ally with a [healer’s kit](/equipment#healers-kit), heal `1d6` + [Heal](#heal) points of damage. Each application of first aid adds one [System Strain](#system-strain) to the target. First aid can restore HP to a [Frail](#frail) target, but it does not remove Frailty.

One [Turn](#turn) provides enough time for a healer to apply as much first aid as needed to the party.

### System Strain

Magical healing (like [Healing Touch](/arcane-traditions#healing-touch)), the use of powerful augmenting magic (like [Haste](/spells#haste)), and [First Aid](#first-aid) put stress on a character’s body, tracked by their System Strain total.

A healthy character starts at zero System Strain, with their Constitution serving as their maximum limit.

Magical healing, certain spells, and abilities (like [Speed](/spells#speed)) add to a subject’s System Strain. If this addition would exceed their maximum, they cannot activate the spell, receive healing, or benefit from the ability. If forced beyond their maximum by an unavoidable effect, they fall unconscious for an hour.

Characters lose one point of accumulated System Strain after [Comfortable Sleep](#comfortable-sleep).

## Rest

Each Character needs at least 8 hours of sleep daily to avoid incurring [System Strain](#system-strain) from [Lack of Sleep](#lack-of-sleep). Magic items that recharge on a per-day basis do so at dawn.

For other mechanics to recover ([System Strain](#system-strain), [Effort committed for the day](#committing-effort), recovering [Spells](/spells#casting-prepared-spells)), the Character must experience **Comfortable Sleep**.

<strong id="comfortable-sleep">Comfortable Sleep</strong> must be:

- Totally uninterrupted
- In a safe place
- Comfortable

This means Characters *cannot* achieve Comfortable Sleep (and thus recover resources) while on an adventure. They need to return to a settlement where they can rest in comfort and peace. During this time, the dungeon may repopulate or change in response to their absence.

Some (mega) dungeons offer places for Comfortable Sleep, often as a reward for exploration or forming alliances with factions.

## Poisons and Diseases

Most toxins force a victim to make a [Physical](#physical) saving throw to resist their effects or reduce their impact. Weak poisons may grant up to a +4 bonus to the saving throw, while severe dangers might impose a -4 penalty.

If the save fails, the poison or disease takes hold. Most poisons act quickly, dealing damage, adding [System Strain](#system-strain), or inflicting long-lasting penalties. Diseases have a slower onset but often cause similar harm.

A medic can treat a poisoned victim within a minute using a [healer’s kit](/equipment#healers-kit), improving their chances to resist. The medic adds twice their [Heal](#heal) level to the saving throw roll, or +1 if they have [Heal](#heal):0.

Some poisons, like that of a [pit viper](https://basicfantasy.org/srd/monstersAll.html#snake-pit-viper), are save-or-die. If the poison takes hold, the victim has `1d4` [Turns](/rules#turn) to live unless specified otherwise.

Other poisons have varied effects. A [giant centipede](https://oldschoolessentials.necroticgnome.com/srd/index.php/Centipede,_Giant) causes lethargy, while a [Tarantella](https://oldschoolessentials.necroticgnome.com/srd/index.php/Spider,_Tarantella) induces `2d6` turns of painful jerking spasms.

## Chases and Pursuit

Play out pursuit as a normal combat, tracking distance and position.

If the PCs choose to flee, the monsters continue to pursue in a straight line as long as there is not more than 90 feet between the two. Turning a corner, passing through a door, or traversing stairs discourges pursuit; the monsters only follow on a 2-in-6.

Burning oil deters many (5-in-6) monsters from chasing.

Edible items distract intelligent monsters from pursuit on a 1-in-6. Semi-intelligent monsters are distracted on a 3-in-6. Non-intelligent monsters are distracted on a 5-in-6.

Treasure operates inversely as food; more likely to stop intelligent monsters.

## Encumbrance

Gear has encumbrance, measured in points and denoted as `enc`, as shown in the table below. The more awkward or bulky the object, the greater its encumbrance. The GM adjudicates ambiguous objects.

| Gear                                    | enc         |
| --------------------------------------- | ----------- |
| Portable in a small pocket              | 0           |
| Portable in one hand                    | 1           |
| Requires two hands to carry or use it   | 2           |
| Requires a whole-body effort to haul it | 5+          |
| Dragging an unconscious teammate        | 12          |

Gear is either Stowed or Readied.

<strong id="stowed">Stowed</strong> gear is packed away carefully in pockets, packs, and harnesses. It’s easier to carry but harder to quickly access. Using Stowed gear requires a [Main Action](/combat#main-action) to pull it out before using it. A character can carry a total number of Stowed encumbrance points equal to their Strength score.

<strong id="readied">Readied</strong> gear is carried in hands, holsters, quick-access pockets, or other easily-accessible places. It can be used as part of an action without any further preparation. A character can carry a number of Readied encumbrance points equal to half their Strength, rounded down.

### Bulk Weights

Sometimes Characters need to transport bulk amounts of goods measured in pounds. When it’s necessary to convert these weights into encumbrance points, assume that 50 lbs equals 10 enc.

Every 100 coins count as 1 enc.

### Pack Animals and Porters

To haul more equipment and loot than the Characters can carry, they need pack animals, porters, or vehicles.

| Type                      | Cost   | enc |
| ------------------------- | ------ | --- |
| Heavy pack horse          | 40g    | 30  |
| Mule or donkey            | 20g    | 15  |
| Porter                    | 2g/day | 12  |
| Cart (pulled by 2 beasts) | 25g    | 300 |

## Falling and Other Hazards

Some perils occur regularly for adventurers. A few common ones are detailed below.

**Falling**: Most creatures take `1d6` [damage](#damage) per 10 feet fallen, up to a maximum of `20d6`. Spikes or other hazardous terrain at the bottom add at least `1d6` to the total. A creature intentionally leaping or sliding down in a controlled way may attempt a DEX or STR/[Exert](#exert) [skill check](#skill-checks) with a difficulty of 7 + 1 for every 10 feet; on success, the effective distance fallen is halved.

**Suffocation**: Creatures can fight or act without air for one [Round](#round) per point of Constitution, or 10 [Rounds](/rules#round) for most NPCs. If they remain still, this time quadruples. Once they run out of air, they must make a [Physical](#physical) save each [Round](/rules#round) or take 1 HP per HD or level.

**Starvation**: Each day without sufficient food (1 Ration) causes 1 [System Strain](#system-strain). If you already have maximum system strain, you die.

**Dehydration**: Each day without enough water (a waterskin's worth) causes 3 [System Strain](#system-strain). If you already have maximum system strain, you die.

<strong id="lack-of-sleep">Lack of Sleep</strong>: Each day without sufficient sleep (8 hours every 24 hours) causes 2 [System Strain](#system-strain).

Starvation and Dehydration are ignored as long as the Characters aren’t trying to sleep in a dungeon or staying longer than [they paid for](#overland-travel).

## Overland Travel

Unless there is an *extremely* compelling reason to play it out, montage through the journey and arrive at the destination. For time-tracking purposes, Characters can travel about 18 miles per day.

The cost of hiring mercenaries, donkeys, purchasing rations, and other travel-related expenses is abstracted using the chart below, based on [Illusory Sensorium](https://illusorysensorium.com/tyranny-of-wagons/). The further the party travels, the more food is required, which adds weight, requiring donkeys. These donkeys also need food and protection, which in turn leads to more donkeys and guards, creating exponential costs:

| Weeks | Cost per Character | Weeks | Cost per Character |
| ----- | ------------------ | ----- | ------------------ |
| 1     | 10g                | 6     | 320g               |
| 2     | 20g                | 7     | 640g               |
| 3     | 40g                | 8     | 1,250g             |
| 4     | 80g                | 9     | 2,500g             |
| 5     | 160g               | 10    | 5,000g             |

## Dungeon Exploration

These rules track adventures in dangerous locations where perils may arise at any moment. Not all [Wandering Encounters](#wandering-encounters) are hostile (see [Reaction Rolls](#reaction-rolls)), but each encounter poses the risk of needless combat or sudden alarm.

At the start of each [Turn](#turn) after the party enters the site:

1. Roll a secret [Wandering Encounter](#wandering-encounters) check, with frequency depending on the adventure or site. On a 1, the encounter will occur at some appropriate moment during this [Turn](/rules#turn). Most adventures specify a frequency (e.g., every other [Turn](#turn)).
2. The Players decide their actions for the [Turn](/rules#turn): moving into a new room, carefully searching their current location, examining an object, or something else that takes about ten minutes.
3. The GM describes the outcome, whether it’s the initial description of a new room, the appearance of a hideous creature, or the unexpected detonation of a crystal they just prodded.
4. Repeat the process, assuming their actions have consumed a [Turn](/rules#turn), until they leave the site or the area becomes safe enough to stop counting [Turns](/rules#turn).

### Timekeeping in the Dungeon

Once the Characters enter a ruin, dungeon, or other dangerous site, the GM begins tracking time in [Turns](#turn). Each Character can take one significant action per [Turn](/rules#turn). Different Characters may perform different actions in the same [Turn](/rules#turn), and not every Character *has* to act.

Tracking [Turns](/rules#turn) provides a rough measure of activity. The longer the Characters remain and the more they do, the higher the chances of facing [Wandering Encounters](#wandering-encounters) or alerting the denizens of their presence. Eventually, the Characters must decide to retreat or clear the site of its dangers entirely.

| Activity                                       | Turns |
|------------------------------------------------|-------|
| Move from one room of interest to another      | 1     |
| Pick a lock or disarm a trap                   | 1     |
| Get in a fight with something                  | 1     |
| Perform first aid and looting after a fight    | 1     |
| Search a 10x10ft area                          | 1     |
| Time a torch lasts until burning out           | 6     |
| Time a filled lantern lasts before burning out | 24    |

### Hidden Things

When a Player suspects something might be hidden in a location, they describe how they search for it, and this follows the [Core Gameplay Loop](#core-gameplay-loop). For instance, if they think riches are stashed under a mattress, they might say they’re lifting it up to check.

Some hidden objects are harder to detect through simple actions. Classic examples include secret doors disguised as seamless walls or traps hidden in locks. In such cases, each Character within 10 feet of the hidden item gets a *secret* WIS/[Notice](#notice) check (rolled by the GM). A Player may choose to actively search a 10x10ft area, triggering additional secret WIS/[Notice](#notice) checks with a +2 bonus, each search taking 1 [Turn](#turn).

### Traps

Traps are often [Hidden](#hidden-things), though many have some sort of tell or clue to hint as its presence. Other traps are totally obvious, and figuring out how to disarm or bypass them is a puzzle.

All traps have some sort of trigger (what sets off the trap), and some sort of effect (like taking damage). By default, traps are unreliable - an action that satisfies its trigger only *does* 2/6th of the time, rolled for each triggering action. For example, a party of five PCs walking through a cooridor with an unseen tripwire rolls 2-in-6 five times (one for each PC).

Players bypass or disarm traps through the [Core Gameplay Loop](#core-gameplay-loop), describing ways to not trigger the trap (like wedging a pressure plate) or ways to mitigate the effect of a trap (like clogging the spout of a gas trap).

### Doors

Doors will be *by far* the most common obstacles the party faces. Doors often signal the beginning of new areas, making it important to understand how to handle them, as this scenario will occur *frequently*.

Doors can be **locked**, in which case a character with [Thieves Tools](/equipment#thieves-tools) can attempt to pick the lock, usually with a DEX/[Sneak](/rules#sneak) [check](#skill-checks). If they fail, they cannot try again until they gain a level of experience.

Locked doors can be **battered down**. It takes 6 turns minus STR and [Exert](#exert) bonuses for wooden doors, and three times that for metal-reinforced doors. Metal or stone doors cannot be battered down with mundane means. Roll an extra [Wandering Encounter](#wandering-encounters) check for each [Turn](#turn) spent battering the door.

Doors can be **stuck**, in which case a character may attempt to force them open within a [Round](#round) using a STR/[Exert](#exert) check. On failure, it takes `1d3` [Turns](/rules#turn) to open the door.

Doors can be **listened at** for a [Round](/rules#round) (but only once per [Turn](#turn)), revealing noises as loud as talking without a roll. Detecting quieter sounds requires a WIS/[Notice](#notice) check.

When passing through a door, choose either a **hard** or **soft** entry. If unspecified, a soft entry is assumed.

In a <strong id="hard-entry">hard</strong> entry, the party arranges around the entrance, bashes the door in, and charges into the room in a planned pattern. This triggers any traps over the threshold and makes them appear [hostile](#fight) to inhabitants but offers the chance to [surprise](#encounters-and-surprise) anyone watching the door.

In a **soft** entry, the party arranges to defend the door as a choke point, standing far enough away from traps. One Character quietly opens the door and observes. This method provides an opportunity to notice traps and avoids appearing hostile, but they cannot surprise anyone watching the door.

## Encounters

When the Party encounters a group of NPCs in a dungeon, either from a [Wandering Encounter](#wandering-encounters) or because the room contains NPCs, the following process occurs:

1. The GM describes what the Characters see, hear, smell, etc.
2. The Players decide whether to fight, talk, run, or wait.
3. The GM rolls for (or chooses) the NPCs’ [reaction](#reaction-rolls), which often leads to [parley](#parley) or [combat](/combat).

### Encounters and Surprise

Characters stay alert enough while exploring to avoid surprise, except in the case of a set ambush. However, if they suddenly burst into a room, the denizens might be too stunned to act for a round.

If the GM deems this possible, use an [opposed](#opposed-skill-checks) roll. Bursting into a room is represented by a [group](#group-checks) STR/[Exert](#exert) vs. WIS/[Notice](#notice) check. Ambushing a group is represented by a group DEX/[Sneak](/rules#sneak) vs. WIS/[Notice](#notice).

### Wandering Encounters

Every so many [Turns](/rules#turn), the GM should roll `1d6` to check for a Wandering Encounter. On a result of 1, the Characters will run into one during that [Turn](/rules#turn). The frequency of this check depends on how alert and organized the site’s inhabitants are.

The contents of the encounter are decided when the GM prepares the site. Not all encounters involve creatures—some may be events or situations fitting the environment. Similarly, not all encounters are necessarily hostile. [Reaction rolls](#reaction-rolls) should be made for all groups of creatures.

A wandering encounter begins when one side sees the other, based on the map and available light sources. Usually, both sides notice each other at the same time, but differences in vision or light may allow one side to see the other without being noticed. In these cases, the side with the advantage may achieve [surprise](#encounters-and-surprise).

#### When to Roll an Encounter Check

| Type of Location                           | Turns    |
| ------------------------------------------ | -------- |
| Alerted site with organized defenders      | Every 1  |
| Unalert site with organized defenders      | Every 2  |
| Site with no organized or active defense   | Every 3  |
| Site with very few mobile inhabitants      | Every 4  |
| Abandoned or disused nook in a site        | Every 6  |
| Chamber unknown to the natives of the site | No check |

### Reaction Rolls

Unintelligent monsters attack immediately.

When the party encounters intelligent creatures, the GM describes what they sense and asks the Players what they do. Broadly, the options are:

- Start a <strong id="fight">fight</strong>, leading to either [combat](/combat) or causing the creatures to flee.
- Try to <strong id="talk">talk</strong> (if the creatures are willing). Achieving anything useful requires [leverage](#leverage).
- <strong id="run-away">Run away</strong>, in which case the creatures might give [chase](#chases-and-pursuit).
- <strong id="wait">Wait</strong> to see how the creatures respond.

If the creatures' response is uncertain, the GM rolls for their reaction, comparing the result with the Players' actions:

| `2d6` / Action | Fight  | Talk                          | Run    | Wait                          |
| -------------- | ------ | ----------------------------- | ------ | ----------------------------- |
| 2-5            | Combat | Combat if could win, run otw. | Chase  | Combat if could win, run otw. |
| 6-8            | Combat if could win, run otw. | Parley | Ignore | Ignore                        |
| 9-12           | Run    | Parley                        | Ignore | Ignore                        |

- **Combat**: Head immediately into [combat](/combat).
- **Combat if could win, run otw**: They'll fight if they believe victory is *very* likely (typically with a 3:1 HD advantage or greater). Otherwise, they’ll run.
- **Parley**: They [parley](#parley) with the Characters. Meaningful parley requires [leverage](#leverage); otherwise, it’s just pleasantries or posturing.
- **Run**: They flee from the Characters, often seeking reinforcements. The Characters may [give chase](#chases-and-pursuit).
- **Chase**: They’ll [chase](#chases-and-pursuit) the fleeing Characters.
- **Ignore**: They continue with what they were doing before encountering the party.

Intelligent denizens immediately turning to combat should be *rare*. More often, they'll retreat to gather allies and create an overwhelming advantage, forcing the Characters to withdraw.

## Parley

Talk is cheap, especially in a dungeon. To get anything valuable (information, assistance, items), Characters need <strong id="leverage">Leverage</strong>.

Leverage includes (but is not limited to) anything the Characters...

- **have** that the NPCs want (an exchange).
- **can do** that the NPCs want them to do (a promise).
- **have done** that the NPCs appreciate (gratitude).
- **can do** that the NPCs *don't* want them to do (a threat).

The value an NPC offers should roughly match how much leverage the Characters possess.

- **Dragons** seek food, territory, treasure, and domination.
- **Humanoids** crave territory, treasure, domination, or higher-order concepts like fairness, kindness, loyalty, obedience, and sanctity.
- **Giants** obsess over their place in the hierarchy of Giants and value anything that advances them in it.
- **Fiends** aim to cause suffering.
- **Aberrations** possess alien and unintelligible motives.
- **Fey** have emotional motives, often driven by dream logic or the [seven deadly sins](https://en.wikipedia.org/wiki/Seven_deadly_sins) (gluttony, lust, greed, sorrow, wrath, sloth, pride).

Source: [The Monsters Know What They're Doing](https://www.themonstersknow.com/)

## Swimming

All Characters can swim. Under normal conditions, a Character can swim 15 feet per [Round](#round) for a number of hours equal to 1/4th of their Constitution (rounded down). Characters wearing Chain or Plate armor will sink. Characters can hold their breath for 3 [Rounds](#round), after which they must pass a Con/[Exert](#exert) check each round or suffer 1 [System Strain](#system-strain).

Fighting underwater poses additional challenges:

- Only thrusting melee weapons (like daggers, polearms, spears, and swords) deal full damage. Bludgeoning and slashing weapons deal half damage.
- All melee weapons attack with a -4 penalty.
- Bows don't work at all; crossbows have half their normal range.
- Fire-based spells have no effect underwater.
- Verbal spellcasting is impossible unless a spell (like [One With Water](/spells#one-with-water)) or another magical effect allows verbal communication.
- Sound, and sound-based magic, travels twice as far.
- Magical light has its range halved.

## Summary

That's it for the core rules! By now, the reader should have a clear understanding of the game's goal (get XP), the structure (the [Core Gameplay Loop](#core-gameplay-loop)), and should *know where to look* to resolve commonly occurring situations.

Key takeaways:

- Players should engage with the GM's description of the situation, think [laterally](https://en.wikipedia.org/wiki/Lateral_thinking), and devise plans to defeat monsters and recover treasure, often using their [equipment](/equipment) and environment. These plans should have a favorable cost-to-benefit ratio.
- The main scarce resources are:
  - [Encumbrance](#encumbrance): You can only carry so much.
  - Time: Every [Turn](#turn) increases the risk of a wandering encounter.
  - Spells: They only replenish back in town with [Comfortable Sleep](#comfortable-sleep).
  - [System Strain](#system-strain): It also only replenishes with [Comfortable Sleep](#comfortable-sleep) in town.
- Combat drains resources and isn't the only option.

Note that this chapter doesn't cover [Combat](/combat), which has its own dedicated section due to its complexity.

![small](/assets/images/game-flowchart.png)
