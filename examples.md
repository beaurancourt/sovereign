---
layout: default
title: Home
---

# Examples

This document is designed to provide examples of play. The examples are crafted to demonstrate edge cases, as well as to convey some play culture.

Dialog is between the **GM** and **Alice** (a representative for the party).

> In-line commentary will be in quote blocks.

## Table of Contents

- [Character Creation](#character-creation)
- [The Big Picture](#the-big-picture)
- [Core Gameplay Loop](#core-gameplay-loop)
- [Skills](#skills)
- [Combat](#combat)

## Character Creation

After reading through [Character Creation](/character-creation), following the various links and having a look at the classes, equipment, and spells, I start from the top.

> Character Creation asks you to make decisions. In order for these decisions to be *informed*, it's worth skimming through the document to get a handle on how the game works. Usually someone (like your GM) has read the game in more detail, and can help answer questions.

**Generate Attributes.** I roll [`3d6`](https://anydice.com/program/1) 5 times in order and get Strength 14, Dexterity 7, Constitution 11, Intelligence 8, Wisdom 10. I pencil all of these scores in.

**Choose a Character Concept.** One friend wants to play a big two-handed Conan the barbarian type, my partner is obsessed with necromancy ever since watching "The Mummy" as a child, and the other buddy really wants to be a "Bilbo Baggins". I figure the best way I could round out the team would be to play someone that can keep the team alive. I'm thinking it would be really cool to play some sort of support archer, throwing out heals from range if needed, but otherwise being a decent shot with a bow.

> We choose a character concept after everyone rolls stats because some stat lines are better suited for some concepts than others.

**Raise an Attribute to 14.** Since I want to be a good shot, I raise my Dexterity to 14. I write them all down.

![small](/assets/images/sheet-1.png)

**Starting Improvements.** I write down all of the skills at level -1

![small](/assets/images/sheet-2.png)

Then I get to make 4 improvements. My Strength and Dexterity are already 14, which is the threshold for +1, and the rest of my Attributes are at +0 and quite far away from 14 so I'll stick to improving my skills for now.

I decide to be a great healer, handy with a bow, and be knowledgeable, so I improve [Heal](/rules#heal) twice (to +1), [Shoot](/rules#shoot) once (to +0), and [Know](/rules#know) once (to +0).

> Looking forward at [Advancement](/character-creation#advancement-benefits), we get better value out of raising attributes at character creation than advancement. Raising an attribute 4 times would cost 10 points. Raising 4 skills to level 0 costs 4 points. Raising 2 skills to level 1 costs 6 points. That said, raising 4 skills will create an overall stronger character at first level, so trade-offs. It's also worth looking to see if you can get to a better mod *cheaply*. For instance, if your Strength is 13, it only takes 1 improvement to get a +1 STR.

![small](/assets/images/sheet-3.png)

**Choose a Class.** I know that I want to be a [Healer](/arcane-traditions#healer), but since it only comes as a [Partial Mage](/classes#partial-mage), I need to pick another partial class. [Partial Warrior](/classes#partial-warrior) would give me more HP and accuracy, but [Partial Expert](/classes#partial-expert) is still good with a bow and makes me *even better* at healing (as well as helping me with everything else). I decide on [Partial Expert](/classes#partial-expert), making me an [Expert/Healer](/classes#partial-expertpartial-mage).

Healer gives me [Heal](/rules#heal) as a [Bonus Skill](/rules#bonus-skill). Since I already have [Heal](/rules#heal):1, I'll take [Sneak](/rules#sneak):0 so that I don't hinder my team while trying to sneak around with [group checks](/rules#group-checks).

![small](/assets/images/sheet-4.png)

**Choose Feats.** The "Feats" column for level 1 Partial Expert/Partial Mage says I get "1 Non-combat + 1 Any", which means I can select any feat that doesn't have (C) in its name, and then any feat I want.

First, I'll pick up [Gifted Chirurgeon](/feats#gifted-chirurgeon) at rank 1 to be *even better* at healing. This gives me [Heal](/rules#heal) as a [Bonus Skill](/rules#bonus-skill), and since I already have [Heal](/rules#heal) at +1, I can make a free improvement. I'll improve my [Shoot](/rules#shoot) to +1.

For my other feat, I'll pick up [Deadeye](/feats#deadeye-c) at rank 1 to do more damage with my bow. This gives me [Shoot](/rules#shoot) as a [Bonus Skill](/rules#bonus-skill), and since I already have [Shoot](/rules#shoot) at +1, I can make a free improvement. I'll improve my [Know](/rules#know) to 1.

> Casters don't have *any* Feats that directly improve spellcasting. The closest is [Spirit Familiar](/feats#spirit-familiar) which provides a little bit of effort economy. This is intentional. Instead, casters should look to become more useful at other areas of the game. They get few spells per day, and so being more handy with a bow (like by grabbing [Deadeye](/feats#deadeye-c)) is a great option.

![small](/assets/images/sheet-5.png)

**Record Attribute Modifiers.** I record my modifiers next to my attributes. My STR and DEX are +1 and the others are +0.

![small](/assets/images/sheet-6.png)

**Generate Maximum Hit Points.** My class of [Expert/Mage(Healer)](/classes#partial-expertpartial-mage) tells me that I start with `1d6` HP (plus my 0 CON). I roll a 3. Mildly unlucky, but we'll take what we can get.

![small](/assets/images/sheet-7.png)

**Record Attack Bonus.** My class tells me that I start with a +0 attack bonus.

![small](/assets/images/sheet-8.png)

**Record Saving Throws**. My [Physical](/rules#physical) save is 15 minus the highest of STR or CON, so 14. My [Evasion](/rules#evasion) save is 15 minus the highest of DEX or INT, so 14. My [Mental](/rules#mental) save is 15 minus the highest of INT or WIS, so 15.

![small](/assets/images/sheet-9.png)

**Choose Starting Gear**. I roll `3d6•10` and get 130g starting gold; lucky! Based on my Strength I can carry 7 [Readied](/rules#readied) enc and 14 [Stowed](/rules#stowed) enc.

I'll grab Plate armor (60g, 3 enc), a Large Bow (7g, 2 enc), a Quiver (10g, 1 enc, comes with infinite arrows), and a Healer's Kit (10g, 1 enc) for my [Readied](/rules#readied) items.

I'll save my other 43g to add to the party slush fund and wait to buy the rest of my adventuring equipment to fill in missing gaps.

> Each weapon and armor should have *some* sort of niche. Plate provides a lot of AC but the -3 penalty to Exert means that they're more vulnerable to [Shoving](/combat#shoving) and [Grappling](/combat#grappling), especially if enemies gang up via [Swarm Attacks](/combat#make-a-swarm-attack-main). A Short Sword does the same damage as a Mace, but is more versatile (can be used with both STR and DEX vs just STR), and does more base Shock (2 vs 1), but isn't able to shock heavily armored targets (AC 15 vs AC 18). A Great Sword does more damage than a Polearm (1d12 vs 1d10), but has lower reach (5ft vs 10ft).
>
> We record equipment on card stock because equipment tends to get passed around, sold, discarded, stored, etc. I find that it's easier (and much less error-prone) to pass the paper around than to erase from one sheet and write on another in a game of [telephone](https://www.wikihow.com/Play-the-Telephone-Game) (especially when folks are intoxicated).

![small](/assets/images/sheet-10.png)

**Record Weapon Statistics.** I can shoot my bow at 100 ft for close range, 600 for long range. I add +2 to hit (+1 from DEX, +1 from [Shoot](/rules#shoot)), and I do `1d8+2` damage on a hit (+1 from DEX, +1 from [Deadeye](/feats#deadeye-c)). I haven't picked up a melee weapon yet, but I figure with [Deadeye](/feats#deadeye-c) I probably won't need one.

I write `• Bow(100/600): +2 -> 1d8+2` in my preferred short hand for weapon stats for basically any d20 game.

> One of the big differences here from BX is that all weapons include their mod for doing damage. Ranged still does less damage than melee because it generally doesn't do [Shock](/combat#shock).

![small](/assets/images/sheet-11.png)

**Record Armor Class.** Plate armor gives me 16 AC and my DEX bumps that to 17.

> AC is a funny stat; the more you have, the better each point is. Say you have 16 AC and 1 HP and you're fighting an opponent that attacks with +0 to hit, so hits 25% of the time. They need to attack you ~4 times on average to hit you. If you raise your AC to 17, then now they hit you 20% of the time, and they'll need to attack you ~5 times on average to hit you, which is a 25% increase to your life expectancy. If you raise your AC to 18, then now they hit you 15% of the time, which means they need to attack you ~6.67 times to hit you, which is a further 34% increase to your life expectancy.
>
> If you're going to go for AC, go for *a lot* of AC.

![small](/assets/images/sheet-12.png)

**Mages Choose Starting Spells.** Healers are technically mages, but don't get any starting spells, so we skip this.

**Mages Record Effort.** Healers get [Heal](/rules#heal)+INT [Effort](/arcane-traditions#effort), so 1 for now.

![small](/assets/images/sheet-13.png)

**Mages Choose Starting Arts.** I get [Healing Touch](/arcane-traditions#healing-touch) and an art of my choice. In order to make the healing-at-range thing work, I'll pick up [Far Healer](/arcane-traditions#far-healer). I'm limited to 10ft right now, but that should be fine. It'll get better as I level up. There's a decent argument to be made for taking a different Art that's more useful at lower levels, and then picking up Far Healer at level 2 or 4, but I think this is fine.

> There's a concept in Magic: The Gathering deckbuilding theory called [Win More](https://hobbylark.com/card-games/best-winmore-cards-mtg). Lots of cards (in our case, options like spells, feats, and arts) make winning positions even-more-winning. Those tend to *look* powerful, but in practice are much weaker than they appear (you would have already won). Instead, *good* options tend to be ones that convert losing or uncertain positions into winning positions.

![small](/assets/images/sheet-14.png)

**Record Level and XP.** We start at Level 1 with 0 / 1500 XP.

![small](/assets/images/sheet-15.png)

**Create Descriptive Details.** I'm imagining a character a lot like [Lucie](https://battlerite.fandom.com/wiki/Lucie) from Battlerite. I decide she's a chipper, slightly unhinged failed alchemist and flavor healing touch as chucking alchemical healing bombs at people. I think it will be fun to juxtapose her relentless optimism with the brutality and horror of dungeoneering. I'll name her Sunny.

> In Sovereign, your character's backstory *is not assumed to be relevant*. We play pre-written adventures, and these can't assume anything about your character. The GM *might* alter NPCs or hooks a bit to tie them in, but that's them going above and beyond. I don't, and it works just fine. Since that's the case, focus on the history that helps you make decisions in adventures *now*. Do the ends justify the means? Are you altruistic? Why do you want all of this gold and power so dang bad?

![small](/assets/images/sheet-16.png)

That's a character!

## The Big Picture

The players just defeated the [Black Wyrm of Brandonsford](https://rancourt.substack.com/p/review-the-black-wyrm-of-brandonsford) and hauled its hoard back to town, everyone reaching level 3.

**GM**: The citizens of Brandonsford are ecstatic that you've slain the beast, and the revelry continues well into the week. Many of the folks you've met or helped offer gratitude: Bently of the clumsy fox, Warwick, hand in hand with Ingrid, Father William, and even George the hunter seems to be in better spirits. As the celebrations are winding down, the town reeve, Eric, announces that they'll be memorializing you alongside Brandon as the second saviors of Brandonsford. You'll have your own statues! Is there anything else you want to do here before we wrap up?

**Alice**: I'd like to have my character, Huxley, stick around in Brandonsford for a few years. Settle in. Help Rebuild.

**GM**: No problem, we can make another character between sessions. Speaking of, here's what I'm thinking: We could play [the forest of Gornate](https://www.drivethrurpg.com/en/product/426926/The-Forest-of-Gornate?1892600=) which is a forest adventure with fallen civilizations, strange denizens, natural wonders, mysterious villas, and reclusive bandit leaders - there's a lot going on. Another option is [cavern of the creeping terror](https://www.drivethrurpg.com/en/product/418780/Cavern-of-the-Creeping-Terror?1892600=) which is a dungeon crawl with undead pirates, imprisoned fae, and huge slugs. Finally, we have [peril in the olden wood](https://www.drivethrurpg.com/en/product/397008/Peril-in-Olden-Wood?1892600=) which is a small hexcrawl with a bunch of interconnected problems happening; bigger in scope than the other two.

**Alice**: I'm leaning toward the creeping terror one, but I don't know yet.

**GM**: No need to decide right now. I'll drop the options in the group chat, but please vote by end-of-day tomorrow so I have time to prep!

> We focus on playing adventures because that's where the [high quality](https://udan-adan.blogspot.com/2016/11/conceptual-density-or-what-are-rpg.html) content is. The GM proposes only adventures that *they'd like to run*. That means that regardless of the player's choice, they're happy. Having the players talk and choose out-of-game means that they're making choices as players (who are playing to have fun) rather than characters (who are choosing based on in-game goals like wealth and power). It can be a whole lot of fun to put your PC through horrible situations!

## Core Gameplay Loop

Say that we're playing [Winter's Daughter](https://www.drivethrurpg.com/en/product/270795/Winters-Daughter). The players at at the Tomb Entrance:

![small](/assets/images/winters-daughter-stone.png)

**GM**: You see a mound sealed by a huge, granite slab. The whole thing is overgrown with lichen and sweet-smelling roses. What do you do?

> describe the situation, ask "what do you do?"

**Alice**: Does it look like we can move that slab?

> the players ask for clarification

**GM**: Hmm - hard to say. It's huge and granite is **heavy**. You also don't know how thick it is and can't tell just by looking. Are you willing to try to budge it?

> describe the situation, ask "what do you do?"

**Alice**: Sure - I'll use my crowbar and see if I can nudge it.

> the players describe their action and intent

**GM**: It moves, but barely; not something you could lift off like that. What do you do?

> inform the players about their chances

**Alice**: What if everyone helps shove?

> come up with a better plan

**GM**: Sure - how about a group STR/[Exert](/rules#exert) [check](/rules#group-checks)? And if it fails, everyone takes a point of [System Strain](/rules#system-strain) as you have to give it your all?

> inform the players about their chances

**Alice**: Yuck, that's a lot of strain. We're pretty flush - do you think some of the burly townsfolk would be willing to help us out for coin?

> come up with a better plan

**GM**: Sure - how about it takes a day and 20g to rustle everyone up, and then they'll be able to push it no problem?

> inform the players about their chances

**Alice**: Works for me.

> if the players find the ruling reasonable...

**GM**: Alrighty - ya'll head back to town, rustle folks up, pay them their dues, and then in the morning head back to the barrow and get the stone pushed off. The townsfolk shudder, clearly nervous, and quickly head back. Underneath the huge are dusty stone stairs descending down into the darkness. It's deathly silent and it smells moist and mouldy.

> honor the stakes and fast forward to the next meaningful decision

---

I can't stress enough how important this is, "getting" it. This loop and [The Big Picture](/rules#the-big-picture) are the whole thing - all the rest is commentary.

We have stuff like attributes and skills to make it easier for the GM to come up with consistent rulings for common situations, and for the players to be on the same page as the GM. We have subsystems like combat because it tends to be high stakes as well as *fun* to game out, but ultimately it serves the same purpose.

The [Core Gameplay Loop](/rules#core-gameplay-loop) has a lot of hidden complexity in it. For instance, take "players describe their actions and the *intent* behind their actions". Say that there's a 20ft pit that a player wants to cross. There's a big difference between an intent of "I want to clear the pit" and "I want to have a shot of grabbing the far ledge". In the first one, they're asking to just totally succeed. In the second one, they're asking for a *chance* to catch the ledge - even if they succeed at their *jump*, they still might not *catch*, and that uncertainty puts us back at the beginning of the loop, and allows us to build more complex mechanics. An excellent post on the subject is [Advantage and Impact - Dreaming Dragonslayer](https://dreamingdragonslayer.wordpress.com/2020/03/28/advantage-and-impact/).

These are the levers for negotiation. If the players are unhappy with their chances, they can negotiate with less desirable intents or more grievous consequences and so on. Similarly, this is the GM's space to port in more complex subsystems where they think they're needed, to handwave it all with a roll, or to say it *just happens*.

Finally, this is what allows for [tactical infinity](https://rolltop-indigo.blogspot.com/2018/05/the-invisible-rulebooks.html). [Notice](/rules#notice) how the phrase is "players describe their actions and the intent behind their actions" and **not** "players pick an action or skill to use". The players can try *anything*, and it's the GM's job to figure out what happens. *Sometimes* that results in a dice roll (which is *sometimes* a skill check), but usually what they want to do just happens.

This isn't to say that players don't need to learn the rules; *they do*. If a game is about making [informed, impactful choices](https://www.bastionland.com/2018/09/the-ici-doctrine-information-choice.html) then the rules themselves are doing a lot of the heavy lifting of making the choices *informed*. A player who has read the rules is much more informed about how "I want to distract the Bear with my staff to give Huxley an opening" will *actually work* if they know how [Swarm Attack](/combat#make-a-swarm-attack-main) works and so on. Playing Sovereign without knowing how the rules work would be a *lot* like playing chess without knowing the rules. You *can do it*, but it'll be much less interesting and can potentially feel unfair.

## Skills

Say we are playing through [Stonehell](https://www.lulu.com/shop/michael-curtis/stonehell-dungeon-down-night-haunted-halls/paperback/product-1v8vy2zz.html). Alice's PC has just fallen down the pit trap in area 1B, arriving at 2B21. Here's the original text:

> **21)** Landing Pad: Fearsome faces carved in walls; bloodstains; broken weapons & equipment. Victims of the pit trap on Level 1B arrive here, taking `1d6` points of damage from the slide and tumble. The chute may be climbed by a thief with a Climb Walls check or by any other character aided by ropes & spikes and making a STR check.

**GM**: The floor drops out from under you, and you slide down a narrow chute to the west. The walls around you are carved with fearsome faces. Broken weapons and equipment are strewn over old bloodstains. What do you do?

**Alice**: Can I climb back up?

**GM**: Yeah - how about a DEX/[Exert](/rules#exert) check? It'll take a turn, and on failure you'll tumble back down but only suffer `1d3` damage since you won't be surprised.

**Alice**: Hmm, I don't love my chances there.

**Bob**: How far down is it? Can we communicate?

**GM**: Do you call out? I'll roll an extra [Wandering Encounter](#wandering-encounters) for the noise.

**Alice**: Crap, yeah, let's do it.

**GM**: Yeah - you can hear each other; doesn't seem that far away, just out of line of sight. Maybe 40ft total. (Rolls a 2 on the d6 for the wandering encounter; they're safe).

**Bob**: Okay, what if we lower the rope down? Can she get up?

**GM**: Yeah, no problem. It'll still takes a turn, but no risk.

**Alice**: Good enough for me. Carol has a +2, Bob has a +1, and I have a -1, so we're at +2 total. My 2d6 came up 5, so with the +2 I'm up.

---

A check is `2d6 + attribute mod + skill >= 10`, and the GM is in charge of determining each factor. As a player, you *do not* want to request skill checks - skill checks are how things go *wrong*. Instead, stick to stating your actions and intents, and *hope* that a skill check isn't called for!

The attribute mod represents that some people are naturally smarter, more coordinated, or are stronger than others, and that for those people, the same task should be easier. Skill represents that some people can have more *training* in a thing than others, and it should be easier for those folks too. It's simpler and more abstract than reality, but [most things are](http://johnsalvatier.org/blog/2017/reality-has-a-surprising-amount-of-detail).

We use 10 as the target because it's low enough that success is still reasonable, but high enough to encourage players to work together, negotiate for softer intents, higher stakes, higher costs, or come up with other plans.

This graph gives the distribution of rolling at least a number on `2d6`:

![small](/assets/images/skill-check-stats.png)

A natural 10 has only a 17% chance of occuring. If they have +1 in the relevant mod and +1 in the relevant skill, then they'd only need to roll an 8, which jumps them all the way up to 42%. If a friend is able to help, that gets them to 58%. These are *huge* differences, and incentivize the style of play we're aiming for.

## Reaction Rolls

From [The Necropolis of Nuromen](https://www.drivethrurpg.com/en/product/110292):

![400](/assets/images/nuromen-19.png)

When in doubt, we use monster stats from [Osric](https://osricrpg.com/files/osric_core_rules.pdf). Osric tends to be better specified than OSE and has a larger bestiary.

The only bit we need for reaction rolls is that Troglodytes have 2 HD. This means that the group of 3 of them has a total of 6 HD. We'll say our Party of 4 level 1 PCs are washed ashore and to the cave, where the Trogs come to investigate.

**GM**: You're swept by the river, battered along the way taking... can everyone roll a [Physical](/rules#physical) save for me, and if you fail, d6 damage. You hear multiple two-legged footsteps from the south. What do you do?

**Alice**: Let's see if they're willing to parley; we can see if they're willing to let us pass in exchange for us solving problems for them.

**GM**: Okay, sounds like you want to Talk. *rolls `2d6: 6` on the [Reaction Roll](/rules#reaction-rolls) table and gets a result of [Parley](/rules#parley).*

**GM**: They're willing to Parley - what's your [Leverage](/rules#leverage)?

Had the Party chosen to Fight, the 6 would have resulted in the Trogs fighting back. Had they chosen to Run, the trogs would have let them run. Had they chosen to Wait, the trogs would have watched them for a bit and then left.

Note that if the players aren't aggressive, the reaction rolls only go straight to aggression ~3% of the time, or ~28% of the time if the adversaries have at least a 3x HD advantage.

Results of Ignore do not mean they *totally disregard* the Party. This is their *home*, they'll go get friends (safety in numbers) and bring force to bear in either combat or use the threat of violence as leverage in a Parley. In the case of these Troglodtyes, they're looking to have at least 7 Trogs (7 trogs • 2 HD is a 3x advantage over 4 PCs of 1st level).

## Combat

The Party

- **Annora**, Warrior. 6 HP, 17 AC (Plate + Shield)
  - Short Sword: +3 -> `1d6+3`; Sh 5/AC 15.
  - Hand Axe(10/30): +3 -> `1d6+3`; Sh 4/AC 15.
- **Bennett**, Warrior/Healer. 4 HP, 17 AC (Plate + Shield), Mace: +1 -> `1d6+1`; Sh 2/AC 18.
- **Colette**, Expert. 3 HP, 12 AC (Leather), Small Bow(50/300): +2 -> `1d6+2`.
- **Daegal**, High Mage. 2 HP, 10 AC (Unarmored), Small Bow(50/300): +1 -> `1d6+1`.

are fighting 3 Skeletal Warrior and 3 Skeletal Archers.

- **Skeletal Warrior** 1 HD, (5, 1) HP, 15 AC (Shield), Short Sword: +2 -> 1d6; Sh 2/AC 15, 30 MV.
- **Skeletal Archer** 1 HD, (2, 6, 3) HP, 13 AC, Bow(50/300): +2 -> 1d6, 30 MV.

Skeletons are immune to poison, mind-controlling magic (like sleep), never flee, and take minimum rolled damage from anything that isn't blunt (like a mace).

Here's the setup:

![tiny](/assets/images/combat-1.png)

The PCs are blue, denoted by the first letter of their names. The Skeletal Warriors are orange, denoted with a W (for Warrior) and an identifying number. The Skeletal Archers are red, denoted with an A (for Archer) and an identifying number.

Combat begins by rolling initiative. We'll say that the group's highest DEX is Colette's at +1. The Players roll `1d8+1: 8` and the Skeletons roll `1d8: 8`. [Ties go to the Players](/combat#combat-sequence)!

**Round 1**

The players discuss if they want to [Charge](/combat#charge-special) (which will let them attack with +2 to hit at the cost of -2 AC until their next turn) or move forward more cautiously. Seeing that the Skeletal Warriors are armed with Short Swords, and knowing that short swords do 2 [Shock](/combat#shock) to anything with 15 AC or less, they decide they don't want to put their AC below that threshold by charging.

Annora [Runs](/combat#run-move) forward 30 ft and hurls her Hand Axe at W2. W2 is within her Hand Axe's short range of 10ft (no penalty) and since W2 does not have any sort of cover (no penalty), Annora rolls `1d20+3: 8`. This misses, as W2's AC is 15. Annora, wanting to thin the enemy line as fast as possible, chooses to use her [Veteran's Luck](/classes#class-ability-veterans-luck) ability to turn the miss into a hit. She deals minimum damage `1d6+3: 4` damage (since her axe is not a blunt weapon). Since W2 has 1 HP, it is destroyed.

Bennett uses [Screen an Ally](/combat#screen-an-ally-move) to get beside Annora and protect her from the Skeletons. Bennett plans to use [Total Defense](/combat#total-defense-instant) to protect himself if he's attacked.

![tiny](/assets/images/combat-2.png)

Colette [Runs](/combat#run-move) forward (to be able to get behind cover next turn) and shoots at W1 with her bow. She'd love to take out an archer, but they all have half cover: A1 and A3 from the pillars, and A2 because of the elevation. Colette rolls `1d20+2: 20` and hits for the minimum of `1d6+2: 3` damage, since arrows are not blunt. W1's HP is reduced from 5 to 2.

Daegal has the same plan as Colette. He [Runs](/combat#run-move) forward and tries to finish off W1 with his bow. he rolls `1d20+1: 4` and misses.

![tiny](/assets/images/combat-3.png)

Now the Skeletons act. Many intelligent beings (like bandits) would flee at this point (to regroup with overwhelming numbers), but Skeletons mindlessly follow the simple commands of whatever animated them.

Thd GM determines (randomly, since Skeletons are not intelligent) that W1 [Runs](/combat#run-move) up to attack Benett. The Skeleton rolls `1d20+2: 17` and hits. Bennett uses [Total Defense](/combat#total-defense-instant) to boost his AC to 19 this turn, making him him immune to [Shock](/combat#shock), and making the attack miss.

The GM decides that the Archers all attack Benett as well, as a [Swarm](/combat#make-a-swarm-attack-main). A2 makes the attack, and gets +4 to hit and +2 damage from its two allies helping. A2 rolls `1d20+6: 20` and hits Benett for `1d6+2: 5` damage. This [Mortally Injures](/rules#mortal-injury-and-stabalization) Benett.

**Round 2**

![tiny](/assets/images/combat-4.png)

Annora could [pick up](/combat#pick-up-an-item-move) Benett's mace to try to do full damage, but doing so would give W1 a free attack against her. She [Runs](/combat#run-move) 10ft east behind cover from the archers which does *not* trigger a free attack from W1 because she never leaves its range. Annora attacks W1 with her sword, rolling `1d20+3: 16`, and hits, for her minimum 5 [Shock](/combat#shock) damage because her sword is not a blunt weapon. Since W1 only had 2 HP, it is destroyed.

Colette and Daegal [Run](/combat#run-move) behind cover.

![tiny](/assets/images/combat-5.png)

Then, they both shoot at A1, deciding to [Make a Swarm Attack](/combat#make-a-swarm-attack-main) with Colette rolling to hit. A1 has [half cover](/combat#half-cover), because they're both able to see at least one but not all of A1's corners. Colette rolls `1d20+2: 14` to hit (+2 from her regular bonus, +2 for swarm, -2 for half cover) and hits for `1d6+3` damage (+2 normally, +1 for swarm). Since arrows are not blunt weapons, it does the minimum of 4 damage. Since A1 only had 2 HP, it is destroyed.

![tiny](/assets/images/combat-6.png)

Now it is the Skeleton's turn to act.

A3 [Runs](/combat#run-move) forward to deny Colette cover and shoots at her. A3 rolls `1d20+2: 17` and hits for `1d6: 6` damage. Colette is [Mortally Injured](/rules#mortal-injury-and-stabalization).

![tiny](/assets/images/combat-7.png)

A2 shoots at Daegal behind [half cover](/combat#half-cover). A2 rolls `1d20: 3` and misses.

**Round 3**

Annora [Runs](/combat#run-move) and circles around A3 (to be closer and give herself cover from A2).

![tiny](/assets/images/combat-8.png)

Then, she attacks A3 with her sword. She rolls `1d20+3: 23` (natural 20s are not special) and hits for the minimum damage of 5, her [Shock](/combat#shock) value. A3 had 3 HP and is destroyed.

Daegel [Goes Prone](/combat#go-prone-free) to apply an [additional -2 penalty](/combat#attack-rolls) to ranged attacks against him. He [Holds His Action](/combat#hold-an-action-move) to be able to choose between using [Total Defense](/combat#total-defense-instant) if he's shot or [Ready or Stow an Item](/combat#ready-or-stow-an-item-main) to grab his Healing Potion from his backpack if he's not. Annora can take care of the last skeleton!

Now it's the Skeleton's turn. A2 moves 10ft east to put a little distance between it and Annora, and then shoots against [half cover](/combat#half-cover).

![tiny](/assets/images/combat-9.png)

It roll `1d20: 13` and misses.

Daegel pops his [Held Action](/combat#hold-an-action-move) now that the danger is passed to grab a potion for Benett.

**Round 4**

Annora [Runs](/combat#run-move) 30ft towards A2 (diagonal movement can't cut corners) and hurls her last Hand Axe. She rolls `1d20+3: 16` and hits for the minimum of `1d6+3`, which is `4`. Skeleton A2 is reduced from 6 HP to 2 HP.

![tiny](/assets/images/combat-10.png)

Daegel [crawls](/combat#run-move) 5ft west to Benett and [adminsters](/rules#use-a-skill-main) the potion. Benett gains `1d6+1: 6` HP which makes him prone, conscious, back to his max HP of 4, and [Frail](/rules#frail).

Benett stands up and [Commits Effort](/arcane-traditions#committing-effort) for the [Turn](/rules#turn) to [Healing Touch](/arcane-traditions#healing-touch) Colette, healing her for `2d6+1: 4` HP and inflicting 1 [System Strain](/rules#system-strain). Colette is prone, conscious, back to her max HP of 3, and [Frail](/rules#frail).

Colette stays prone and prepares to use [Total Defense](/combat#total-defense-instant) if she's attacked. If she hits 0 HP again while [Frail](/rules#frail), she's dead.

A2 [Runs](/combat#run-move) from Annora before taking a shot.

![tiny](/assets/images/combat-11.png)

Annora has [half cover](/combat#half-cover) from A2 because of the verticality, and so A2 rolls `1d20: 19` to hit for `1d6: 3` damage. Annora's HP is reduced from 6 to 3. If Annora hadn't already spent her [Veteran's Luck](/classes#class-ability-veterans-luck), she could use it to turn the hit into a miss, but she used it in Round 1.

**Round 5**

Annora [Runs](/combat#run-move) after A2. If there was a straight line, Annora could [Charge](/combat#charge-special), but there isn't. Annora could leap off the platform, but would suffer `1d6` [falling](/rules#falling-and-other-hazards) damage and isn't feeling too hot right now. She uses her [Main Action](/combat#main-action) for another [Move Action](/combat#move-action) to catch fully up with A2 and interpose herself between it and Benett. This is especially valuable because A2 is only equipped with a Bow, and cannot make ranged attacks while engaged in melee. If it moves away from Annora without [Disengaging](/combat#disengage-main), it will trigger a free attack and die to the [Shock](/combat#shock) damage. If it does [Disengage](/combat#disengage-main), it can't attack this turn.

![tiny](/assets/images/combat-12.png)

Benett, Colete, and Daegel move in position and [Make a Swarm Attack](/combat#make-a-swarm-attack-main), using Benett as the attacker. Benett rolls `1d20+5: 15` and hits for `1d6+3: 5`. Since A2 only had 2 HP remaining, A2 is destroyed!

---

After combat, Benett heals Annora's wound at the cost of 1 [System Strain](/rules#system-strain).

The PCs are all still at full HP, but now two of them are [Frail](/rules#frail) and they're out a Healing Potion (worth 1000g). That was a close call! Whether or not to press on, or to retreat back to town to get rid of their [Frail](/rules#frail) condition is up to them.
