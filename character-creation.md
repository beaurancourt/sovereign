---
layout: default
title: Home
---

# Character Creation

This section will guide you through creating your own character step by step. There are a number of decisions that you'll be asked to make, and some choices will be mechanically better than others. As you gain familiarity with the rules, you'll be able to create more powerful characters with more synergy. This is intended, and deliberately rewards system mastery. Another choice is to pick options based on archetypical tropes, this is also fine! The game tries to make sure that the archetypes are *viable* (but maybe not optimal).

If creating your own character isn't your thing or you want inspiration, check out the [pre-built characters](#pre-built-characters). I've also included a [worked demonstration](/examples#character-creation).

## Table Of Contents

{% include chapter-toc.html items=site.data.character-creation %}

## Character Creation Steps

Adventuring is a profession, and all Characters have undergone extensive training to become 1st level. They can clean and sharpen weapons, set up camp, cook meals, ride mounts, perform first aid, know the value of coins, trade goods, treasure, and identify common magical effects and monsters.

1. **Generate Attributes**. For each of the five [Attributes](/rules#attributes) (Strength, Dexterity, Constitution, Intelligence, Wisdom), assign them a score of `3d6` **in order**. So your first `3d6` is your Strength, your second is your Dexterity, and so on.

1. **Choose a character concept**. Discuss what your role will be in the team. A well-rounded party needs a way to deal with melee enemies, a way to deal with ranged or flying enemies, a way to deal with mundane security measures (guards, locked doors, traps), a way to deal with magical security measures, and a way to keep everyone healthy when things go south. A team of a melee-focused [Warrior](/classes#warrior), [Sneak](/rules#sneak)-focused [Expert](/classes#expert), utility-focused [High Mage](/arcane-traditions#high-mage), and [Partial Warrior](/classes#partial-warrior)/[Healer](/arcane-traditions#healer) is well-rounded, but part of the fun is trying out other compositions.

1. **Raise an Attribute to 14**. With your role on the team in mind, choose an [Attribute](/rules#attributes) to raise to 14.

1. **Record Skills**. There are 9 [Skills](/rules#skills): [Exert](/rules#exert), [Heal](/rules#heal), [Know](/rules#know), [Magic](/rules#magic), [Notice](/rules#notice), [Sneak](/rules#sneak), [Brawl](/rules#brawl), [Shoot](/rules#shoot), and [Stab](/rules#stab). Record the name of each skill and write `-1` next to it, to represent an initial lack of training.

1. **Starting Improvements**. Make a total of 4 <span id="improvement">Improvements<span> to your [Skills](/rules#skills) or [Attributes](/rules#attributes). To improve an [Attribute](/rules#attributes), raise it by 1 to a max of 18. To improve a [Skill](/rules#skills), raise its level by 1 to a max of 1. All skills start at level -1. A single [Attribute](/rules#attributes) or [Skill](/rules#skills) can be improved multiple times. [Brawl](/rules#brawl), [Shoot](/rules#shoot), and [Stab](/rules#stab) are primarily used for making [Attack Rolls](/combat#attack-rolls). All skills are used for making [Skill Checks](/rules#skill-checks).

1. **Choose a Class**. Pick either a full [Class](/classes) or combine two Partial Classes. [Warriors](/classes#warrior) are great at [combat](/combat), [Experts](/classes#expert) are great at [Skill Checks](/rules#skill-checks), and [Mages](/classes#mage) have specialized [powers](/arcane-traditions) or [spells](/spells).

1. **Choose Feats**. Each [Class](/classes) gets a different starting amount of [Feats](/feats) at first level, detailed in the class' "Feats" column. Some [Feats](/feats), like [Alert](/feats#alert-c) grant a [Bonus Skill](/rules#bonus-skill). Raise that skill by one level to a maximum of level 1. If that skill is *already* level 1, make a free [Improvement](#improvement).

1. **Record Attribute Modifiers**. Each [Attribute](/rules#attributes) has a [Modifier](/rules#attribute-modifiers), ranging from -2 to +2 based on its score. This modifier is added to [Skill Checks](/rules#skill-checks), [Attack Rolls](/combat#attack-rolls), [Damage](/combat#damage) rolls, [Shock](/combat#shock) damage, and [Saving Throws](/rules#saving-throws).

1. **Generate Maximum Hit Points**. Each [Class](/classes) gets different amount of [Hit Points](/rules#hit-points) (HP) at first level according to their [HP Progression](/rules#hp-progression). Roll based on your class, add your CON, and +2 if you chose the [Die Hard](/feats#die-hard-c) Feat.

1. **Record Attack Bonus**. Your character has a certain degree of basic combat competence based on their class. This bonus increases as you advance in character levels and is added to your attack roll. A new character’s attack bonus is usually +0, though [Warriors](/classes#warrior) start with a +1 attack bonus.

1. **Record Derived Statistics**. Record your [Physical](/rules#physical) (exhaustion, poison, etc), [Evasion](/rules#evasion) (explosions, traps, etc), and [Mental](/rules#mental) (mind control, tests of will, etc) [Saving Throws](/rules#saving-throws).
  - Your [Physical](/rules#physical) score is 15 minus the greater between your STR and CON.
  - Your [Evasion](/rules#evasion) score is 15 minus the greater between your INT and DEX.
  - Your [Mental](/rules#mental) score is 15 minus the gerater between your INT and WIS.
  - Record your maximum [System Strain](/rules#system-strain), which is equal to your Constitution.

1. **Choose Starting Gear**. Gain `3d6 x 10` gold to spend on [gear](/equipment) (ignoring [Equipment Availability](/equipment#equipment-availability)), noting their [Encumbrance](/rules#encumbrance) and whether they are [Readied](/rules#readied) or [Stowed](/rules#stowed). You may carry [Readied](/rules#readied) equipment equal to half your Strength rounded down. You may carry [Stowed](/rules#stowed) equipment equal to your Strength. Other party members may be willing to Stow gear for you.

1. **Record Weapon Statistics**. For each weapon (or special Art) you attack with, record its properties.
  - Write it's name. *For example* `Sword:`.
  - Record the total attack bonus for that weapon. This is equal to your attack bonus plus your relevant [Stab](/rules#stab), [Shoot](/rules#shoot), or [Brawl](/rules#brawl) skill, and the relevant [Attribute Modifier](/rules#attribute-modifiers) for the weapon given on the weapon table. If two attributes are listed for a weapon, use whichever is better for you. *For example*, a [Warrior](/classes#warrior) (attack bonus of +1) with a STR of +1 and a [Stab](/rules#stab) of +1 has a total attack bonus of +3. They record `Sword: +3`.
  - Record the weapon's damage from the [Weapon Table](/equipment#weapons), adding your relevant [Attribute Modifier](/rules#attribute-modifiers) (like STR or DEX). Abilities like the Warrior's [Killing Blow](/classes#class-ability-killing-blow) and Feats like [Armsmaster](/feats#armsmaster-c) also increase damage. *For example*, A [Warrior](/classes#warrior) (+1 from [Killing Blow](/classes#class-ability-killing-blow)) with a STR of +1, the [Armsmaster](/feats#armsmaster-c) Feat, and a [Stab](/rules#stab) of +1 wielding a [sword](/equipment#sword) (1d8) records `Sword: +3 -> 1d8+3`.
  - Record the weapon's [Shock](/combat#shock) from the [Weapon Table](/equipment#weapons), adding the relevant [Attribute Modifier](/rules#attribute-modifiers). Abilities like the [Warrior's](/classes#warrior) [Killing Blow](/classes#class-ability-killing-blow) and Feats like [Armsmaster](/feats#armsmaster-c) also increase [Shock](/combat#shock). *For example*, A [Warrior](/classes#warrior) (+1 from [Killing Blow](/classes#class-ability-killing-blow)) with a STR of +1, the [Armsmaster](/feats#armsmaster-c) Feat, and a [Stab](/rules#stab) of +1 wielding a [sword](/equipment#sword) (2/AC 13) records `Sword: +3 -> 1d8+3, Sh 5/AC 13`.

1. **Record Armor Class**. Record the [Armor Class](/equipment#armor-class) (AC) of the armor you normally wear. AC is modified by DEX. For example, a character wearing [plate armor](/equipment#plate) with a DEX of +2 has 18 AC.

1. **Mages Choose Starting Spells**. [High Mages](/arcane-traditions#high-mage), [Elementalists](/arcane-traditions#elementalist), and [Necromancers](/arcane-traditions#necromancer) begin play knowing [Spells](/spells) based on their [Arcane Tradition](/arcane-traditions). These spells are chosen from any spell list available to them. Full [Mages](/classes#mage) choose 4 starting spells, and [Partial Mages](/classes#partial-mage) choose 2. A new full [High Mage](/arcane-traditions#high-mage), for example, would pick four first-level spells from the [High Magic spell list](/spells#high-magic-spells), while a new partial [Elementalist](/arcane-traditions#elementalist) could pick two spells total from either the [High Magic](/spells#high-magic-spells) or [Elementalist spell list](/spells#elementalist-spells).

1. **Mages Record Effort**. All Mages start with a pool of [Effort](/classes#effort) specific to their class. Refer to your chosen [Arcane Tradition](/arcane-traditions) section for how to calculate it. For example, an [Elementalist](/arcane-traditions#elementalist) refers to [Elementalist Arts](/arcane-traditions#elementalist-arts).

1. **Mages Choose Starting Arts**. All [Mages](/classes#mage) select Arts based on their [Arcane Tradition](/arcane-traditions). Refer to your chosen tradition for specific details. For example, a [Duelist](/arcane-traditions#duelist) refers to [Duelist Arts](/arcane-traditions#duelist-arts).

1. **Record Level and XP.** Characters start at Level 1 with 0 XP, and need 1500 XP to [advance](/rules#xp-thresholds).

1. **Create Descriptive Details**. Imagine the appearance, brief history, personality, mannerisms, motivations, and [Alignment](#alignment) for your character. Bear in mind that your character *will be* going on adventures and *will be* part of a team. Endeavor to create a character that *wants* to go on adventures, and *wants* to be part of a team.

## Alignment

Alignment interacts with various magic items. Creatures in [bestiaries](https://oldschoolessentials.necroticgnome.com/srd/index.php/Goblin) often have an alignment, which helps interpret their moral outlook. Characters don’t *choose* an alignment; they *live* it. If a magic item functions only for Lawful characters, then the character must act Lawfully for it to work (subject to GM discretion).

### Law vs Chaos

**Lawful**: [Lawfulness](https://en.wikipedia.org/wiki/Deontology) emphasizes adherence to moral rules or duties, regardless of the consequences. Lawful individuals believe that certain actions are inherently right or wrong based on the nature of the action itself, not its outcomes. They prioritize principles like honesty, promise-keeping, and respect for autonomy, even if following these rules leads to undesirable results in specific situations.

**Neutral**: [Neutrality](https://en.wikipedia.org/wiki/Virtue_ethics) focuses on cultivating virtuous character traits like wisdom, courage, justice, and temperance. Neutral individuals aim to develop good character and make decisions based on what a virtuous person would do. Their goal is to become morally exemplary, consistently acting in line with virtues to lead a fulfilling life and contribute to society's well-being.

**Chaotic**: [Chaotic](https://en.wikipedia.org/wiki/Consequentialism) individuals argue that the moral value of an action depends on its actual outcomes rather than the intentions behind it or adherence to moral rules.

### Good vs Evil

**Good**: [Good](https://en.wikipedia.org/wiki/Altruism) individuals believe in acting selflessly to benefit others without expecting anything in return, often at personal cost.

**Neutral**: [Neutral](https://en.wikipedia.org/wiki/Ethical_egoism) individuals believe an action is morally right if it maximizes their self-interest. According to this view, the only moral obligation is to promote one’s own well-being, considering the interests of others only when it benefits oneself.

**Evil**: Evil individuals actively seek to harm and exploit others for personal gain or pleasure. They lack empathy, disregard others' rights and well-being, and may even derive satisfaction from causing suffering.

## Advancement

Characters accumulate <strong id="experience-points">Experience Points</strong> (XP) by defeating monsters, gathering coins and treasure from dungeons, and making it back to a settlement. The *party* collects XP during an adventure, and all surviving members receive a share of the total XP upon returning to town. Each Character gets a full share, while [Henchmen](/equipment#henchmen) receive half of a share.

Coins and treasure award 1 XP per 1g worth of value, regardless of whether the treasure is sold or the coin is spent. The treasure simply needs to reach town.

For example, if a party of 4 PCs and 3 [Henchmen](/equipment#henchmen) defeats monsters worth 300 XP and returns with 1500g of treasure, the total XP is 1800. With `4 + 3/2 = 5.5` shares, each PC gets `1800 / 5.5 = 327` XP, and each [Henchmen](/equipment#henchmen) receives half that, or 164 XP.

### XP for Monsters

| Monster HD  | Base XP     | Bonus XP / Ability |
| ----------- | ----------- | ------------------ |
| Less than 1 | 5           | 1                  |
| 1           | 10          | 3                  |
| 2           | 20          | 5                  |
| 3           | 35          | 15                 |
| 4           | 75          | 50                 |
| 5           | 175         | 125                |
| 6           | 275         | 225                |
| 7           | 450         | 400                |
| 8           | 650         | 550                |
| 9–10        | 900         | 700                |
| 11–12       | 1,100       | 800                |
| 13–16       | 1,350       | 950                |
| 17–20       | 2,000       | 1,150              |
| 21          | 2,500       | 2,000              |
| 21+N        | 2,500+250•N | 2,000+250•N        |

### XP Thresholds

Once a character has enough XP to level up **and** is in a settlement, they may level up.

| Level | XP    | Level | XP     |
| ----- | ----- | ----- | ------ |
| 1     | 0     | 6     | 24000  |
| 2     | 1500  | 7     | 48000  |
| 3     | 3000  | 8     | 100000 |
| 4     | 6000  | 9     | 200000 |
| 5     | 12000 | 10    | 300000 |

### Advancement Benefits

**More HP.** To determine their new maximum, characters roll their <strong id="hp-progression">HP Progression</strong> for each level they possess, adding their CON to each die. No individual die can be reduced below 1 point, even with a negative CON. If the total roll exceeds their current maximum HP, they take the new total. Otherwise, their maximum HP increases by one.

**Better Saves.** Their saving throw scores decrease by one, making it easier to succeed on saving throws. For example, a first-level character has saving throw scores of 15, but reaching second level lowers them to 14, modified by their appropriate attributes.

**Improved Attack Bonus.** Their attack bonus improves according to their level and chosen [class](/classes).

**Gain Advancement Points.** Characters gain three <strong id="advancement-point">Advancement Points</strong>, which can be spent on improving [Skills](/rules#skills) or [attributes](/rules#attributes). [Experts](/classes#expert) and [Partial Experts](/classes#partial-expert) gain an additional Advancement Point (via [Quick Learner](/classes#class-ability-quick-learner)), giving them four points per advancement.

The cost for improving a skill is listed below. Every skill level must be purchased sequentially. For instance, to reach level 1 in a skill, they must first pay one point for level 0, then two points for level 1. Certain skill levels require minimum character levels:

| Skill Level | Point Cost | Min Character Level |
| ----------- | ---------- | ------------------- |
| 0           | 1          | 1                   |
| 1           | 2          | 1                   |
| 2           | 3          | 3                   |
| 3           | 4          | 6                   |
| 4           | 5          | 9                   |

Characters may also spend Advancement Points to improve their [Attribute](/rules#attributes) scores by 1, recalculating their [Attribute Modifier](/rules#attribute-modifiers) as needed:

| Advancement | Point Cost | Min Character Level |
| ----------- | ---------- | ------------------- |
| 1st         | 1          | 1                   |
| 2nd         | 2          | 1                   |
| 3rd         | 3          | 3                   |
| 4th         | 4          | 6                   |
| 5th         | 5          | 9                   |

**Gain a new Feat.** At levels 2, 5, 7, and 10, characters may add a level to an existing [Feat](/feats) or choose the first level of a new [Feat](/feats).

If this is their first level in the [Feat](/feats), they may receive a <strong id="bonus-skill">Bonus Skill</strong>. During character creation, this functions like a standard skill [Improvement](#improvement). However, when acquired through advancement, it counts as three Advancement Points spent toward a skill.

This bonus can increase a level -1 skill to level 1, or raise a level 1 skill to level 2, even if they do not meet the minimum level requirement.

If the Advancement Points aren't enough to raise the skill, they remain as credit for future advances. If applied to a skill already at level 4, the points can be spent on any other skill.

**More Spells and Arts.** Mages gain new arts, increase their ability to cast and prepare spells, and automatically learn new spells as they advance, based on their [Arcane Tradition](/arcane-traditions).

## Pre-Built Characters

### Cleric

- Class: [Warrior](/classes#partial-warriorpartial-mage)/[Healer](/arcane-traditions#healer)
- Requirements: 10+ Strength, 8+ Dexterity, 8+ Intelligence
- Feats: [Gifted Chirurgeon](/feats#gifted-chirurgeon), [Die Hard](/feats#die-hard-c)
- Improvements: We want to get [Heal](/rules#heal) to 1, and [Stab](/rules#stab) to 1. Any remaining points can be used to get to the 14 or 18 attribute breakpoints for any attribute.
- Readied: Plate Armor (60g, 3 enc), Shield (10g, 1 enc), Mace (5g, 1 enc)
- Stowed: 3 Bottles (3g, 3 enc), Ration (2s, 1 enc), Lamp Oil (3s, 1 enc), Lantern (10g, 1 enc), Scroll Case (1g, 1 enc), Sling (1g, 1 enc)

We want to make sure we have enough DEX to not decrease our AC, and plan on wearing heavy armor. We're able melee combatants, so we want to have good Strength for bonuses to hit and damage.

We take [Gifted Chirurgeon](/feats#gifted-chirurgeon) mostly for the improved odds at fixing [Fraility](/rules#frail). We take [Die Hard](/feats#die-hard-c) because we're frequently the only ones invested into healing others and if we die there's no one to help us. Die Hard makes sure that we live so long as the fight is won.

As we level up, we can look at picking up [Close Combatant](/feats#close-combatant-c) so that we can leave the fray to pick up wounded comrades.

### Defensive Fighter

- Class: [Warrior](/classes#warrior)
- Requirements: 14+ Dexterity, 10+ Strength, 8+ Constitution
- Feats: [Close Combatant](/feats#close-combatant-c), [Whirlwind Assault](/feats#whirlwind-assault-c)
- Improvements: Hit the above attribute breakpoints, then spend your remaining improvements on either getting 18 Dexterity, 14 or 18 Strength, and 14 or 18 Constition. Dexterity is more important than Strength, which is more important than Constitution, but if the next breakpoint is 1 or 2 points away, prioritize that. Our Feat combo gives us a guarenteed [Stab](/rules#stab) of 1, so we can spend any remaining improvements on filling in gaps for our group.
- Readied: Plate Armor (60g, 3 enc), Shield (10g, 1 enc), Mace (5g, 1 enc)
- Stowed: 4 Torches (2s, 2 enc), 2 points of Military Oil (4g, 2 enc), Crowbar (1g, 1 enc), Pickaxe (4g, 2 enc), Ration (2s, 1 enc), Rope (1g, 2 enc)

We prioritize DEX over STR because each point of AC is more valuable than the last. [Close Combatant](/feats#close-combatant-c) makes us immune to [Shock](/rules#shock) (otherwise we need to be scared of maces), and lets us feel comfortable surrounded by hoards of enemies, which is exactly where we'll want to be to maximize the benefit of [Whirlwind Assault](/feats#whirlwind-assault-c).

Our equipment is set up for traversal. We have rope to get up and down, a crowbar and pickaxe to get us through stuff, and torches to light the way.

As we level up, we keep doing more and more shock damage due to [Killing Blow](/classes#class-ability-killing-blow). We'll want to pick up [Armsmaster](/feats#armsmaster-c), the second level of [Whirlwind Assault](/feats#whirlwind-assault-c), and [Valiant Defender](/feats#valiant-defender-c).

### Offensive Fighter

- Class: [Warrior](/classes#warrior)
- Requirements: 14+ Strength
- Feats: [Whirlwind Assault](/feats#whirlwind-assault-c) level 2.
- Improvements: Raise [Stab](/rules#stab) to 1. If you're 1 or two points away from a breakpoint (either 14 or 18) for Strength, Dexterity, or Constitution, spend Improvements on reaching it. Spend any remaining points on filling on [Exert](/rules#exert).
- Readied: Plate Armor (60g, 3 enc), War Axe (10g, 2 enc), 10 Daggers (30g, 2 enc)
- Stowed: 4 Torches (2s, 2 enc), 2 points of Military Oil (4g, 2 enc), Crowbar (1g, 1 enc), Pickaxe (4g, 2 enc), Ration (2s, 1 enc), Rope (1g, 2 enc)

We prioritize STR over DEX because our aim is to kill stuff before we get hit back. We have enough [Shock](/rules#shock) damage to kill most 1 HD creatures on a miss, and get to attack twice a turn if we do.

As we level up, we'll want to pick up [Armsmaster](/feats#armsmaster) for the additional damage, [Alert](/feats#alert) if no one else has it, and [Shocking Assault](/feats#shocking-assault) for even more damage.

### Magic User

- Class [High Mage](/arcane-traditions#high-mage)
- Requirements: 14+ Intelligence
- Feats [Impervious Defense](/feats#impervious-defense-c)
- Improvements: Raise [Magic](/rules#magic) to 1. Raise [Shoot](/rules#shoot) to 0. If you're 1 or two points away from a breakpoint in Dexterity, Constitution, or Intelligence, spend Improvements on reaching it. Spend any remaining points on [Know](/rules#know).
- Readied: Small Bow (3g, 1 enc), Polearm (7g, 2 enc), Quiver (10g, 1 enc) Scroll Case (1g, 1 enc)
- Stowed: 3 Bottles (3g, 3 enc), Ration (2s, 1 enc), Soap (1s), Spellbook (20g, 1 enc), 3 Military Oil (6g, 3 enc), 100ft String (2s, 1 enc), 6 Iron Spikes (1g, 1 enc)

We grab [Impervious Defense](/feats#impervious-defense-c) to give us some *much needed* AC, and look at taking it again at level 2 to negate a hit and give us time to flee.

We want to have decent [Shoot](/rules#shoot) because we're *definitely* not on the front lines, and can cast a very limited number of spells per adventure, so we want to make the other 95% of our turns better. In this vein, we can look at picking up [Deadeye](/feats#deadeye-c).

### Thief

- Class [Expert](/classes#expert)
- Requirements: 14+ Dex, 8+ Wis
- Feats [Deadeye](/feats#deadeye-c), [Specialist](/feats#specialist) (Sneak)
- Improvements: Raise [Shoot](/rules#shoot) and [Sneak](/rules#sneak) to 1. Raise [Notice](/rules#notice) to 0.
- Readied: Small Bow (3g, 1 enc), Quiver (10g, 1 enc), 2 Military Oil (4g, 2 enc)
- Stowed: 100ft String (2s, 1 enc), Lodestone (10g), 6 Iron Spikes (1g, 1 enc), Hand Drill (10g, 1 enc), Fish Hook (1s), 50ft Rope (1g, 2 enc), Grappling Hook (25g, 1 enc), 10ft Pole (1c, 2 enc), Rations (2s, 1 enc), Mirror (5g, 1 enc), Hammer (1g, 1 enc).

We want to be able to [Notice](/rules#notice) hidden stuff, and use [Sneak](/rules#sneak) to it's fullest (disabling traps, stealing things, picking locks). We pick up [Deadeye](/feats#deadeye-c) to make us effective in a fight, and it synergizes well with the additional Improvements we get as we level up.

Our kit is chosen to be able to interact with objects from a distance. Fish hooks and string to tug on stuff from afar, string+lodestone to reel in distant metal things (like keys), 10ft pole for prodding, mirrors to look in places you couldn't otherwise.

We throw in some iron spikes because they tend to be *very* useful for disabling traps - hammering a spike into a trap's mechanism tends to work *a lot*.
