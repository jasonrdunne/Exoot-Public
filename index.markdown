# Game overview ----------------------------------------

### General Gameplay Loop
1. Prepare for adventure in town
2. Explore the wilderness, encountering structures/monsters/secrets.
3. Return to town to process the loot/experience accumulated from the adventure

### General Gameplay Loop Details
 - The town vs wilderness dichotomy: a system of tension and relief. In the wilderness, dangerous foes and creatures roam about. Players have limited ability to heal away from towns, which means a careless blunder can put them in a bad situation. I think this dichotomy is the secret sauce behind making exploration fun. A player who has no reason to return to town feels no thrill about being far away from it. In contrast, a player who is running low on health in the depths of a dungeon is grappling with two opposing forces: fear of running out of health versus the burning desire to discover what loot awaits at the end. Barely surviving a dangerous encounter by the skin of their teeth and then stumbling through the door of a warm inn is the sought-after scenario.
 - Character builds are comprised of stats, active skills, passive skills, and gear choices. The intention for these systems is to be easy to understand, yet the intricate relationship between them enables for a wide range of outputs, i.e. many *interesting* resultant playstyles
 - Enemy encounters aim to feel like a puzzle. The player's build is akin to their toolset, and they are expected to utilize each tool creatively & to its maximum potential to solve the encounter
 - Soft barriers allows for even craftier players to get ahead (refer to the mentalities section)
 - Exploration is valued. Players can be greatly rewarded for satisfying their curiosity, but risk must be considered. 


### Overworld Map Layout
The landscape is always based in the same fantasy world. I emphasize this because it's also true that the wilderness regenerates every time the player recovers at an inn, to keep exploration fresh.

Everything in the wilderness lies on the scale between predetermined and random:
- The wilderness is always composed of static named regions. For example, "The Shire" is a named region in LOTR. Static meaning the same regions will always exist in the same spots, like on a map.
- The terrain in a region is randomly generated to the context of the region. For example, The Shire will always randomize with rolling grassy hills. Likewise, Mordor's terrain would be a spiky, barren wasteland.
- The village where all the hobbits live is equivalent to a "city": a handcrafted point of interest which is guaranteed to spawn.
- Each region has an intrinsic level range. The region's level matches the level of the highest player in the game, staying clamped within the intrinsic range. For instance, a region might have a level range of 5-10. If the only player in the world is level 7, then the region is level 7. When the player levels to 8, the region will become level 8. Higher level enemies can drop better loot. The purpose of this system is because static levels are impossible to balance in an open world, but completely adaptive enemy levels are ridiculous and ruin any sense of progression.
- When exploring the wilderness, the player will encounter structures. Structures include anything "manmade" like dungeons, ruins, buildings, cities, or dilapidated shacks. There are two types of structures: randomly generated and handcrafted. Handcrafted structures fulfill specific lore-related purposes like containing quest locations/specific npcs, while randomly generated structures are solely for exploration and loot. Handcrafted structures *can* utilize randomness, though, like for their monster spawns.
- Regions are composed of biomes of varying rarity. For instance, a creek may commonly spawn in the shire, but sometimes, rarely, an ancient patch of trees with unique resources to harvest can occur. Biomes have their own attributes: monsters/structures/resources that spawn, events that occur, terrain generation parameters, etc. Biomes will be apparent to the player as they explore, that they've stumbled upon an area which prompts further investigation.
- Dungeons/structures inside a region often have a higher level range than the region itself, especially if they're difficult to reach (it'd be bad game design to let the player stumble into a difficult dungeon without cueing it).


### Atmosphere Objectives
 - Overall, the world is dangerous place. The player needs to watch their back, because a multitude of factors (monsters, environmental hazards, untrustworthy npcs/online players) can work against the player.
 - A sense of "strandedness" while in the wilderness. The player has to manage limited (in the context of a single journey) resources (health/mana/consumables) carefully to make it back alive.
 - Towns & Cities: a generally safe hub where the player can recover, sell their loot, trade, take quests, and many more activities to build out their character. Some towns might feel sketchy though - players should rely on their intuition in general.
 - Despite the dangerous and unforgiving nature of the wilderness, players will find beauty in the places they explore. This contrast makes the beauty stand out more.
 - Civilizations feel culturally different from one another, and this is reflected through gameplay elements.
 


### Progression
Progression is the core of RPGs. Exoot's progression is founded on the principle of contrast: each stage of the game should feel distinct from one another to highlight the player's growth in power.

- At the very beginning of the game, players should feel disadvantaged, and they will need to use every wit at their disposal to scrape by. This may include spending a few days gathering herbs to sell, begging, stealing, or hunting small wildlife. Players are barely strong enough to fend off a boar, let alone another person.
- As they enter early game, they can revel in the satisfaction of no longer being "at the bottom of the food chain." Players will now have accrued various abilities (albeit not impressive ones), and they will begin setting the trajectory of their builds. Players are still exploring conceptually "normal" areas, like caves, small bandit encampments, forests, etc. They currently have little reason to suspect that anything in this game is fantastical.
- In midgame, players will get their first rush of power. They think of themselves like seasoned adventurers, but have begun encountering situations out of the ordinary: dueling rogue mages, hunting magical beasts, and witnessing a few supernatural sights that give the player a taste that they're delving into a world beyond their scope.
- As players approach endgame, they start seeing crazy shit. Entering zones like an underworld full of nightmarish undead, elusive mythical beasts, illusionary & non euclidean environments. When players encounter such areas, it will be startling because it contrasts the "normal" world they were in before. At this point, they've internalized the fact that visual appearance in exoot is not a meaningless detail, so they will expect a ramp up in difficulty, rightfully so. This will manifest as anxiety about limited healing: they won't know how much they should try to conserve their health. But this extra caution is driven by an excitement to find sweet loot (which, in these kinds of areas, will certainly not disappoint).
- Throughout this progression, the quantity and complexity of tools available to the player increases, and so does the relative difficulty of monsters. Therefore, the game expects increasing mechanical mastery from the player.

### Online "Ladder"
In online multiplayer, ladder is like a season: an optional, recurring game mode that allows players the opportunity to start fresh characters without previously earned items. Ladder lasts for ~6 months. After the ladder ends, all characters are rolled over to non-ladder. This system is exciting because players race to endgame, it refreshes the economy, and comes with new balance changes to keep the meta fresh.


### Framework
The ultimate purpose of this game is for players to have fun. Unfortunately, that's an awfully vague task, and humans are complicated. 

On one hand, I think most games are boring because they're too restrictive. Consider the lack of creativity and player choice in a game like flappy bird.

However, having completely open ended creativity is not particularly satisfying because there’s no resistance. Giving someone a blank canvas is not interesting. A game attempting to hold onto the fabric of its reality while you poke it in the wrong ways is what’s rewarding.

In other words, when the game has limitations, the player needs to learn how to finesse things in just the right way to reach their goal. It’s more fun to push the boundaries of the system than to set them.

So it’s up to me to decide what the boundaries of the system are, culminating as the framework.

### Exoot's Framework
Exoot's framework is based on the reciprocal nature between the desire to improve one's player character, and how an improved player character lets players have a larger influence on the game world.

This brings us to the concept of "activities": activities are any interaction between the player character and the game world.  Activities take many shapes and forms: PVE, PVP, and socializing to name a few (view a more extensive list below). In other words, activities serve as the high-level classifications of the fabric of the game.

By participating in and pushing the boundaries of these activities, players are rewarded in various ways which allows them to improve their character. By improving their character, players can gain advantages in these activities, or participate in new ones. 

The purpose of these activities is to engage different parts of players' brains: reaction time, skill-based mechanics, socializing, strategizing, discovery, creativity, anticipation, excitement, fear. Together, these fullfill exoot's ultimate goal: creating a fun experience.

A wide scope of activities is beneficial for the following reasons:
- Players can enjoy the option of both casual and competitive activities, depending on their mood
- Players do not want to be doing the same thing over and over
- Every player has different taste. I want to avoid forcing players to engage in activities they wouldn't enjoy.

### Activities
For the following list of activities, note that:
- The individual execution of activities determines whether they're actually fun or not. A lot of care must go into their design. 
- The following list is not yet comprehensive

**Competitive/Skill based/Boundary pushing activities**
- Exploration Gameplay Loop: around or above player's level
- Competitive PVP
- Buildcrafting (deciding on skills, gear, etc)
- Uncovering new information about game lore
- Theory-crafting new strategies to speedrun/optimize aspects the game
- Theory-crafting to breach ultra endgame zones and foes
- Race to level up at the start of a season (placing on the global leaderboard)

**Social activities**
- Hanging out at hubs
- Trading
- PVP
- Minigames against against other players (betting games at the inn, as well as other random minigames that exist throughout the game world) (these could become competitive)
- Doing any other activity in this list as a party

**Leisure activities**
- Exploration Gameplay Loop: below the player's level, or for pure exploration
- Crafting (not overemphasized in this game)
- Gathering resources: foraging, fishing, mining, farming lower level mobs
- Innkeeper betting games against CPU (unique board game type games of various depth, like chess, you can play in town) 
- Exploring the world for secrets
- Selling loot and upgrading gear in town

**General Activities**
- Questing
- Inventory management


# Aspects of Gameplay -----------------------------------

### Voxels
The world is voxel-based. Voxel stands for "volumetric pixels," but it's a fancy word for cubes: think minecraft, except the cubes are much smaller. Voxels enable the world to be randomly generated, including the structures and dungeons that are placed within. This also means that everything is destructible. Randomly generated worlds are necessary, because in my opinion, the foundation of an rpg is exploration.

### Inventory
The inventory is a grid of squares, where items take up different sizes.

### Economy
The player primarily accrues gold by selling loot found on expeditions. This loot may come from enemy drops, harvesting natural resources, in chests, \<continue listing\>, etc. Players can use gold to purchase goods or services from various NPCs, and during trading with other players.
Potions are strikingly expensive. Players should be reluctant to use them. 

### "Recursive Lootboxes"
A key strategy to make exploration interesting is a concept I call "recursive lootboxes". It basically hijacks the brain's urge to gamble... recursively (joking but not really). Essentially, the hunt for loot can be broken into multiple tiers:
- 1st Tier: what structures players find while exploring. "Difficult" structures for the area are rarer but contain better loot, better chance for a boss/rare mob spawn, etc, so players looking for a challenge will be hoping for these. It doesn't mean other structures are bad by any means, but stumbling across an opportunity like this will ideally spike the adrenaline. Let's say the player has found a challenging dungeon.
- 2nd Tier: what spawns in the dungeon. Dungeons may or may not spawn with particular rooms, like hidden stashes or vaults guarded by especially difficult foes, or mini-bosses. Again, players looking for a challenge will hope to find these. 
- 3rd Tier: what loot drops from these enemies/chests? (Greatsword, if you're a berserker? Rare or Unique quality?)
- 4th Tier: how do the items roll? Does it have the right mods, with high rolls?

Notice that chance for interesting loot correlates with difficulty. I want to emphasize a point I made earlier: enemy encounters aim to feel like a puzzle. Players will see a situation and strategize how to tackle the room of foes that would probably win in a straight-up fight. And of course, harder puzzles give greater rewards.

Also notice that no tier is completely decisive:
- you can still find good loot in easier dungeons, it's just less common.
- you can still find good loot from normal enemy kills (not from a vault or a mini-boss), it's just less common.
- you can still find good items of a lower "quality" (magic {blue} items can actually outperform uniques under rare circumstances), it's just less common.
- you can still find good items with subpar rolls, it's just less common.

This exploration+loot system is dynamic and exciting.

### Dying and Respawning
Dying respawns you in the last town you visited. Death penalties include (not finalized):
 - Loss of xp and gold
 - Loss of all unidentified items in your inventory (ie the loot you've collected on the current expedition). Additionally, unidentified loot outside of towns despawns after a period of time with no living players nearby. This system means players have to actually return from their journey alive. It makes them consider whether they should turn back or not.
 - Reduction of proficiency skill levels
 - Note: a fraction of everything lost (25%?) would be dropped in a grave where the player dies, so they can reclaim some losses if they make their way back.

### World Mechanics
- The world is saved realtime. If you quit and log back in, you will be exactly where you left off.
- Characters only exist in one world at once. You can only transfer worlds via "hubs" found in towns. If you’re stuck in a dungeon, too bad, you will have to get rescued or die to respawn at a town.

### Inns
- When players sleep at an inn, the wilderness rerolls new terrain and structures.
- During multiplayer, all players must be at an inn to sleep. Players can summon other players to an inn (assuming they've visited the city already), although this effectively counts as dying without xp drop. Sleeping at an inn regenerates "supplies" (full restores that can be used outside of combat) and it regenerates the world. This is a further reason why it's so painful to abandon a rare structure - it won't be there after healing.

### Pvp-Aware Endgame
PVP is a completely optional aspect of exoot. A PVP arena system will be implemented, where players can wager loot and duke it out.
The best build in PVE is not necessarily the best build in PVP. A lot of interesting and crazy builds, which need highly specific gear (not necessarily endgame gear; it'd include elusive items from midgame/early game. View \<itemization\>), will mean that even after one has cleared PVE content, there is a new realm of complexity for them to interact with. Some player's real goal during PVE may be to get the gear they have in mind for PVP.

### Socialization
Players will be able to join larger hubs that enables them to socialize with other players, show off their gear, etc. This makes the character an extension of the self; more than just a vehicle for slaying monsters (as described by the framework).

### Survival
This game does not have hunger or thirst; survival mechanics refer to debuffs that occur from being in a particular location. Such mechanics will only be incorporated in a few small area, eg blizzard in a mountain pass to get to a new region. They're used as a soft barrier. If there is a survival mechanic present, it must be represented visually. Cold? The landscape is shrouded by a foggy blizzard. Hot? Heat waves radiate on the horizon. The player must be convinced that the conditions are real.


# Main Mentalities ----------------

### Contrast 
I think contrast is a hugely important concept to keep in mind while designing. To emphasize something, it must contrast its surroundings.

### Soft Barriers
Often times in games, progression is locked behind hard barriers. For example, players can't enter a new zone until they've beaten the last zone. However, this game will mostly utilize soft barriers. A soft barrier implies there's resistance to achieving something, but there's not an outright restriction. If players have the ingenuity, they can overcome these obstacles (soft does not mean easy). Hard barriers are dumb because there's no reason to restrict player freedom if they're dedicated.

### Meaningful Appearances and Symbols
A common occurrence in games is when enemy appearance does not match their strength. For example, an early game boss might be 15 feet tall, but have less health than a regular human during midgame. I aim to avoid this: appearance will generally scale with strength (if you see a big enemy, you should damn well be scared). This is one example of the meaningful symbols mentality: players should be able to rely on their instincts to gauge situations. Another example: if a door has scratch marks and blood stains, they actually need to be wary of what might be behind it. As players get more accustomed to the game, they will eventually form an intuition: symbols actually have meaning; the game must be respected. Of course, building this intuition just to violate it in the right places is also key.

### Everything has a Pattern
One of the best parts about playing RPGs is building a general intuition that players can use to their advantage. Everything in the world should have a learnable, exploitable pattern. An obvious instance of this would be that abandoned hospitals have a higher likelihood of medical loot compared to other structures. Going a bit deeper, hospital structures would be more likely to spawn on the border between two hostile factions. I would like this intuition-based mentality to apply to all entity spawn locations (monsters, traps, roaming merchants, secret areas, etc), since it's these subtle patterns that, consciously or not, create a players' intuition. A world that's perfectly random feels dull and meaningless.

### Info Scarcity Theory / Utilizing Player Imagination
Knowing when to omit information is also an important tool. This serves two benefits: firstly, it's often less work, lol. More importantly, though, it allows me to harness the player's imagination. Examples include:
- In world building, I provide small clues which allude to a deep, complex history, but players can only get bits at a time.
- Create situations where players can hear an enemy, but not see it. Like tracking an enemy's movement in darkness, and trying to figure out how big of a threat it is. This will light up their brain. Or make a really mysterious creature that the player can only get glimpses of if they’re observant.
- I think this relates to the fundamental appeal of retro graphics: players' brains makes extra assumptions based on limited visual information.
In essence: scarcity of information makes things wayyy more interesting/tantalizing.

### Interfering with the Meta
Once most players have figured out how to min/max, the game becomes stale. IMO it's the game designer's job to obfuscate the meta as much as possible & use balance changes to keep the meta fresh.

### The Purpose of Character Building
Ultimately, the reason why building out a character is fun is because it's a simple problem to comprehend (what gear and skills should I use) with a clear measure of success (am I killing stuff better), yet also a super complex sandbox where players can exercise their creativity. Everything about character building should come down to tough choices that change the way the character plays. What passive skills complement which active skills, gameplay or synergy-system wise? Having to balancing defense with offense. Sacrificing some aspect of your build to gain another. Every single choice has rippling effects on the character that need to be considered.

### Utilizing Probability Distributions to Keep Things Fresh
You know what's boring? When things are the same every time in a game. And I don't just mean combat: nothing in real life is the same every time. Why not have every game parameter lie on a complex distribution?

Like take weather in minecraft. Rain is a binary state, on or off. I want to have unique, rare, random weather patterns just for the sake of a vibe change! Not everything exists for consequence. Just to make players go “oh that’s cool ive never seen that mountain have fog before” and then sit and appreciate nature... that's nice. 

### Putting the Excitement Back into Exploration
Basically all of the mentalities above serve the main goal I hope to achieve with this game: putting the excitement back into exploration. It's so rare I find myself excited to explore anything anymore, in games or in life. By generating a fresh world with awesome shit to discover (loot/locations/nature) all on various complex, changing distributions, I want to create something worth exploring.


# Theories ----------------
Extra "game theory" stuff

### Allocation Theory
Briefly introduce concepts (areas, imporant characters, etc) that will become important later. When concepts are pre-established in the player's mind, it becomes easier to explain subsequent more complex details to them: the callback to a "foundation" justifies a cognitive exertion.

### Commitment Theory
As players spend more time in a game, they are more willing to exert effort to learn difficult systems. Therefore, I would like to keep early game skill cap relatively low to let players figure things out. To clarify: the game itself will not be easy at first, but the players will have less tools at their disposal to have to keep track of. As they progress, more systems (eg skills with more nuance) will be introduced: that's how the skill ceiling is raised.

### Scope Theory
If you limit a player’s vision, the area will feel larger. For example: underground passage in pokemon, removing the fog from silent hill, or even cupping your hand into a hole and looking through it. This is because it forces player to focus on local details instead of the big picture.

### Expectation Theory
Before any event occurs, set up the player with the correct expectations, otherwise they will be left confused and frustrated. If players expect to succeed but fail, it sucks. But if players expect to fail and then succeed, it feels fcking amazing. 
Building on this: if you allow players to discover tools let them think they've used the tools to “game the system”.... it's straight dopamine.

Example plot utilizing expectation theory: you’re a street rat who was just beaten. You wake up with your heartbeat pounding in your ears, vision red, low health. You were scammed by some noble bozo, then beaten by said noble bozo, who laughs in your face and mocks you for how weak you are, then disappears. This sets the stage of zero expectations, justifying any future hardship to the player. After all, you were set up for failure. Also when the player #owns the rich guy in the future, it’d be satisfying af. I’m thinking there’s an arena quest, where once you’ve accrued fame, you can challenge him to combat.

### Complexity Theory
Complex > Complicated. Systems should be easy to understand, but hard to master.


# Levelling, Stats, and Skills------------------

### Experience and Levelling System
By gaining experience, players can level from 1-99. Every level grants one "Active Skill Point," and every 10 levels grants players one "Passive Skill Point."

### Active Skill System
As players explore the world, they will naturally find and learn active skills. Active skills have a base requisite level before points can be allocated towards it, and each active skill can receive a max of 20 skill points. **Active skills fall under the category of a single subclass (eg "berserker skill"), but are often usable by the other class' subclasses, at reduced effectiveness.** Active skills are benefitted by synergies, so players can continue to scale their primary skill while flushing out their build:
- Players can equip 7(?) skills at a time, and are toggled with hotkeys (1-7 by default).
- When the skill's hotkey is pressed, the skill will either activate, or be equipped to LMB or RMB (i.e. if players would like to replace their basic attack with a low cooldown skill). These options are configurable by the player
- Each skill has broad synergetic classifications: lightning, physical, melee, cold, etc. Each point into these classifications will improve other the skills in the same synergy class, but *synergies only count while the spell is equipped*
- Skills may have specific synergies for other skills. Synergies may experience diminishing returns, for balancing reasons
- Level synergy: the skill scales with player level
- Attribute synergy: the skill scales with the base count of an attribute
- Proficiency synergy: the skill scales with a particular proficiency level
- Some skills are upgrades to previous skills. When equipping a skill, the player can choose which version of the skill they'd rather use. Some upgrades are strictly more powerful, while others act like alternate versions of the skill. This is how early game skills can scale into the late game, and it improves build diversity

Misc:
- not all active skills consume mana; many are stamina based
- it's easier to respec active skill points than passive ones

### Passive Skill System
Each class has a passive skill tree, composed of 8 tiers. Players can only allocate 1 point per tier, and they start with one passive skill point. The first passive tier is offered at level 1 and is how the player picks their subclass. Picking a subclass gives a slew of inherent benefits and changes; for example, by picking the berserker subclass, the player's mana bar is replaced with rage. The subclass skill also marks the starting point in the passive tree in which the player must branch out from.
- Passive skills ideally alter gameplay more than just increase stats, as their purpose is to diversify builds.
- The last tier is the "Ultimate" skill (I dislike that word because it's not supposed to be a raw power boost). Ultimates are toggleable abilities that give you a great strength but at a great penalty. They are meant to diversify gameplay, and are ideally situational.
- Some passive skills, including ultimates, may change based on the subclass chosen.

### "Ultimate" Skills (WIP)
Ultimates are build-shaping abilities that give the player a great strength that comes at a great penalty. As mentioned, they are meant to diversify gameplay.
- Illusionist: shadow form that increases stealth, crit chance, adds blink (short range teleport) ability, but cripples defenses. Encourages high risk high reward gameplay.
- Another thing I can do is modify each ultimate skill based on the subclass chosen. Haven't fully considered this yet; ultimates are very subject to change

### Player Stats
- Health: when health reaches 0, the player dies.
- Mana: used to cast active abilities
- Stamina: used for physical actions and skills
- Block meter: When it reaches zero, the hit partially goes through, the player is staggered, and they lose stamina.
- Crit chance: base chance is on weapon
- Crit damage: base damage is on weapon
- % fire, cold, lightning damage
- \<etc\>

### Attribute System
The four attributes are Strength, Dexterity, Energy, and Vitality. 
- Strength: increase physical damage (2h>1h>>bows), small stamina bonus, small-to-medium health bonus, small block meter bonus. Adds a small multiplier to block damage.
- Dexterity: increase physical damage (bows&daggers>1h>2h), small crit chance bonus, small stamina bonus, small sneaking bonus, even smaller block meter bonus
- Energy: increase nonphysical damage, mana bonus
- Vitality: health/stamina/block meter bonus

### Proficiency System
As players complete certain actions (such as attacking, sneaking, or defending), they will gain proficiency experience. 
- This experience is gained is based off the monster's level relative to proficiency level; players cannot cheese it by farming weaker enemies.
- Only a certain amount of proficiency XP can be gained per monster, so players can't trap a monster in a hole to farm off them.
Proficiency levels give players bonuses in their respective domain. When players die, they lose proficiency XP - however, the XP penalty gets softer the farther away the current XP is from its "ceiling". The ceiling value is a strictly increasing number, which represents the base proficiency of the player. When the player reaches a new proficiency level, this becomes the new ceiling. However, even if the player dips from this max, the max value will slowly rise whenever the player gains experience. This follows the intuition that players get rusty at the skill, but still make permanent progress. 
For example (numbers are arbitrary):
- If a player's proficiency ceiling is 70/100, then their proficiency could never realistically dip below 50/100
- If the player's proficiency then reaches 75/100, then this would be the new ceiling
- If the player's proficiency then drops to 60/100, and back up to 74/100, the ceiling will have risen to 76/100, despite the player never having reached 76/100 proficency.
I believe a proficiency system is necessary because it represents how people naturally get better at actions with practice. For instance, balancing sneaking would be unnatural if the player did not improve at sneaking while doing so. Additionally, this system aids noobs by guaranteeing forward progress as they grind.
I can use proficiency as a requirement for some items and skills if necessary for balancing.

### Passive skill trees
In progress. Imagine a tree-like structure, with 3 starting nodes at the bottom, and the players work their way upwards ('tiers' being on the same horizontal level). Each class' tree structure looks a bit different. Notice how with 3 starting nodes at the bottom, one will be in the middle with one on each side: this is intentional. Subclasses can be conceptualized as a scale: if you're on the left subclass, you have to work your way through the middle before you can reach the right subclass. Therefore it is unnatural for opposite subclasses to interact, but still possible. For instance, the warrior subclasses are Berserkers, Collossi, and Paladin. It follows that Berserkers are the conceptual opposite of Paladin, and Collossi acts as a middle ground.



# Classes----------------

## Classes
Warrior, Rogue, Elementalist, Druid, Necromancer

### Warrior
The Warrior class is built to delve into the fray. Warriors have the best physical traits: best innate movement speed, health, blocking, stamina, and strength & vitality bonuses. On the other hand, warriors generally have the least capacity for magic. 
- Berserkers sacrifice their mana for rage: an alternate resource which grows when taking and dishing damage. They are highly maneuverable.
- Colossi use mana to enhance their physicality, whether that be for generating force or defensive purposes.
- Paladins harness their mana toward holy, fire, healing, and to buff their allies.  
[[Warrior Skills (WIP)]]

### Rogue
Rogues excel in the art of subtlety. Utilizing sneaking, backstabbing, illusion, sniping, and various concoctions to their advantage, rogues certainly aim to be a high skill-cap class. Rogues have high innate movement speed, but have lower health, blocking, and strength/vitality bonuses compared to warriors. However, rogues have the best dexterity and sneaking bonuses, with respectable mana conserves. 
- Illusionists use shadow magic to turn invisible and warp the minds of their foes
- Assassins rely on physical prowess to maneuver and strike with devastating blows
- Saboteurs come prepared, employing a variety of concoctions, traps, and techniques to apply bleed
[[Rogue Skills (WIP)]]

### Elementalist
Elementalists use their mastery of magic to sew destruction. They have the best mana conserves, but have to be cautious as they're the least defensive class.
- Fire magi are aggressive, using explosions to maneuver and deal AOE damage. Their spells can catch opponents on fire.
- Stormborn spells travel fast and can stun, but are short ranged. Stormborn can also use lightning to enhance their physical movements, and are keen on being spellswords.
- Frostweaver is a tactical class. Their projectiles are often part physical which allows them to hit critical strikes, and many spells apply slow. Frostweaver does not have strong movement abilities, and move especially slow while casting.
[[Elementalist Skills (WIP)]]

### Druid
Druids harness nature magic in creative ways - they have markedly different playstyles based on their subclass. 
- Wardens prefer the bow and are slippery like rogues
- Shamans are casters who harness nature magic
- Shapeshifters transform between various creatures mid-combat to maneuver or maul their opponents
[[Druid Skills (WIP)]]

### Necromancer
By harnessing death magic, Necromancers wield unnatural power. It's amazing what you can do when you sacrifice your morals.
- Corruptors harness poison, curses, and resurrect the unliving
- Bonewalkers cast spells of bone and flesh
- Death Lords wear heavy plate armor and fight in melee.



# Combat---------------

### Skill cap determines progression system:
- Low skill/tight progression example: clicker heroes. Your power is entirely gear based.
- High skill system (infinite skillbased progression): dark souls. You can do a naked no hit run in dark souls. This would not be possible in games like diablo.
- Exiled kingdoms and diablo 2 are good mid-based examples. There's certainly a finite ceiling to how much skill improves the player, which enables a tighter and more satisfying progression. There still needs enough skill, so players try to optimize what they have, and can reap the satisfaction of "getting ahead". I need to figure out what approximate % effectiveness player skill should contribute for. Maybe like 50%, i don't know. (Aka high skill players should be 50% stronger than average skill players). I also need to articulate how this skill manifests: positioning, active skill execution, build choices, ...
- "forced exchange of blows" is a good way to describe how I want monster encounters to boil down to. Good players might have a 3:2 ratio with good dodging and the like, while average players have a 1:1 ratio. Players should NEVER achieve a 1:0 ratio.
- I can prevent mages from infinitely kiting by slowing them while casting and by making monsters fast enough to catch up (potentially via movement or ranged abilities).


### Number scaling and itemization -- NUMBER STUFF IS CONJECTURE
This video summarizes why i think rapid power scaling is bad: https://www.youtube.com/watch?v=x6UV2gXwFPw&ab_channel=Shadiversity

**Incoming conjecture that is basically meaningless until playtesting:**

I’m thinking max endgame dps would be around 500. I'd prefer it not getting much higher considering early enemies have <10 hp. The lower the better.

Current estimations (highly subject to change): 2.5x from active skill points, 2.5x from passive tree, 2x from stat, \<X\> weapon dps = 12.5\<X\> dps. 
Calculating max potential weapon dps:
Adamantite sword = 17 * (50% ed) * (30% attack speed) * (20% other mods) = 39.8 MAX wep dps. This gives us a max dps of 497.25, which is alright. Hasn’t yet accounted for charms, buffs, or armor mods.

The more I think about it though, I think I'm gonna have to make the DPS range much larger. It's completely dependent on how I craft the skill ceiling. 


### Avoiding linear DPS
Problem: how do I provide a sense of damage progression without inflating DPS? In other words, how do you make later enemies hard while keeping earlier enemies un-trivial? Base case: only DPS matters; linear scaling.

One solution: resistance pierce

Noob: 50 dps, 0 pierce.

Chad: 50 dps, 50 pierce.

EasyMob: 100 hp, 0 resistance.

HardMob: 100hp, 75 resistance.

It takes noob player 2 seconds to kill easy mob and 8 seconds to kill hardmob.

It takes chad player 1.33 seconds to kill easy mob and 2.66 seconds to kill hard mob. Notice how the easy mob became 1.5x easier while the hard mob became 3x easier. Thus pierce resistance is a way to “gatekeep” harder mobs without completely invalidating earlier mobs.(i need to figure out a bunch of formulas that describe this kind of relationship)


### Endgame
How to make endgame really interesting: have a few optional areas that are REALLY hard (like you have to min-max to clear). The types of items dropped there are rare and marginally better at best, and possibly a few charms/socketables/whatever that are desirable for completionists. Therefore most players won’t feel super obligated to farm these areas, since the loot isn't that much better, but it keeps the endgame fresh.


### Stealth System
The stealth system is complex. There are 3 types of detection: visual, auditory, and olfactory. It requires an adequate visual to continually lock on to the player. However, enemies may try swing at you even if they don't see you (watch out illusionists)
- Alertness: there are 3 stages of alertness: unalerted, alerted, and spotted. If enemies are unalerted, then they will have the lowest detection capabilities. Once alerted, they will be more sensitive to stimuli. Once spotted, players have to drastically lower visual detection to go back to the alerted stage.
- Visual detection: enemies see in a frustum toward the direction they're facing that allows them to detect the player. The player's visual detectability is determined by movement speed, visual stealth level (determined by skills/gear), distance from the monster, and light level the player is in. Different monsters have different capacities for visual detection.
- Auditory detection: enemies can hear in any direction. The player's auditory detectability (AD) is determined by movement speed, type of ground being walked on, auditory stealth level (determined by skills/gear), distance from the monster, and wind direction + speed (since wind affects how sound propagates). However, this only makes up half of the equation: in addition, each point in the world has an ambient sound level (AMB). The player's true audio detectability is the difference between their raw audio detectability minus ambient sound (AD - AMB). This implies that players can only be detected if they make noise significantly above the ambient noise level. Ambient noise may be impacted by: certain events (eg right when a goblin blacksmith hammers a piece of metal), indoor vs outdoor, which biome, etc. The player can always see the wind direction and ambient sound level in the UI.
- Olfactory detection: not a factor in a large majority of encounters, but can play an important role for certain creatures like dogs. Players have a scent level which refreshes at inns, when the player jumps in water, or by certain consumables. Players leave a trail scent wherever they go based on their current scent level (applied statically to the ground, and can move dynamically in the air). I know it sounds overkill but it's important.
- Sneak un-detection: once an enemy spots the player, the player’s visual detectability (VD) score receives a large penalty in reference to that specific enemy. For example, if the monster is able to detect a VD of 10, and the player just reached a VD of 10.1, then the player would receive a penalty of say 5 and have a new VD of 15.1 (only for that enemy). Now, for the player to escape detection, they’d have to lower their VD by >5.1, in which case they will become undetected and have a new VD of <5.0. (it may be necessary to give enemies pseudo wallhacks for a period of time to let them chase players around corners). Enemies who can see the player well also boost the VD of other nearby enemies to represent communication.
- Sneak attack resistance: certain monsters may have a sneak attack resistance based on their anatomy. It's possible for skills to aid in bypassing these resistances, but some monsters, like a rock golem, would be completely immune.

## Damage calculations

#### Damage Types
Physical (pierce/slash/blunt), fire, cold, lightning, poison, magic, holy, death.

#### Gear Modifiers

#### Defensive Modifiers (can be negative)
Health, Stamina, Mana, Str, Dex, Vit, Ene, Armor, Block meter, Block regen, Stamina regen, % resist, Flat resist, Max health/stamina/mana % (UNIQUE), Max resist % (UNIQUE), Crit resist (UNIQUE), Attacker takes damage (phys or ele), Blind resistance %, Gold find, Frw, Magic find, Skill charges, % experience gained, +stat/clvl (clvl * rate), +active skill (requires points in the skill), +oskill (does not require points in the skill), +active skill type (eg +fire skills), +all skills, Socket, Cannot be frozen/thawing??, Drain life (UNIQUE), Requirements -%, Poison length reduced %, Bleed Resistance, 

#### Offensive Modifiers
Attack speed
Cast rate
Dmg, flat or min/max
Ele, poison, holy, magic, death dmg
Crit chance %
Crit damage %
Anything that adds life: life/mana after kill, Life/mana steal, would have to come at the cost of life/mana drain while in inventory (UNIQUE)
Socket
Piercing attack %
Ignore target defense (UNIQUE) (GHOSTLY WEAPON) (LOW DMG)
Freezes target ?
Slows target? (UNIQUE/weapon type)
Bleed (UNIQUE/weapon type)
Blind (UNIQUE)
-enemy resistance (UNIQUE)
% damage against monster type (only for physical)
Enhanced damage
Knockback???? Questionable
Dmg type % bonus


#### Physical Damage and Armor
Players have minimum and maximum armor values. On each hit, their effective armor rolls as a random number in this range.

For example, say a player's armor values are 2 and 10. This means they will negate between 2-10 damage.

How max armor is calculated:
1 point of any armor type contributes 1 point of armor to the maximum

How min armor is calculated:
1 point of light armor contributes 20% to the minimum,
1 point of light armor contributes 25% to the minimum,
1 point of heavy armor contributes 30% to the minimum,
1 point of shield contributes 40% to the minimum

Pierce/slash damage compound in every attack together to “combat” flat armor. Pierce is negated first, but ignores 10% of the armor. Slash still has to get through this 10% left by pierce, but then receives a 15% damage bonus after getting through (numbers obviously subject to change).

Blunt bypasses flat armor but gear innately provides % blunt damage reduction. (enemy stats mimic this)

There is additional nuance to this which is not covered in the GDD. Though these systems may seem overly complex, it's an attempt to analog to how stuff really works (+adds nuance). Also, these calculations will be invisible to the players, so they don't have to think about it unless they want to.

For much more detailed notes: [[Blunt Slash Pierce Discussion]]

#### Crits
Crits do 50% more damage. Certain monsters like undead may be immune. Innate crit chance is on the weapon. Blunt rolls separately from slash/pierce. Blunt has a reduced crit rate, but isn't completely affected by crit immunity.

#### Resistances
Unsure between EK (diminishing return) and D2 (subtraction). Many kinds of math functions could work - I want one that keeps earlier mobs semi relevant.

(Experimental) Burst resistance: all enemies have innate "burst resistance" which reduces damage if taken too quickly (eg resistance kicks while they've lost more than 40% of their max health in the last second). It would be bypassed during sneak attacks. This seems like the best solution to keeping earlier mobs relevant - it wouldn't affect difficult mobs whatsoever.
The downside to this is it punishes single target damage over aoe...

# Enemy Archetypes and Mechanics---------

### Enemy Spawning
- Case 1: General Spawns
Individual and small groups of enemies are randomly distributed throughout areas.
- Case 2: Enemy Pack
A few large groups of monsters will also randomly spawn in areas. Some may be boss groups with special modifiers & better loot/xp.
- Case 3: Guaranteed Spawns
In some locations, monsters will be guaranteed to spawn.

### Misc Mechanics
- When a player's crosshair pans over a monster, it will display their nametag and health at the top of the screen.
- Monsters visually change (eg blood splattered or becoming more grey) when at low health as an indication for players to cue in on.
- Monster size will proportionally scale with difficulty. For example, early bosses will be humanoid-sized creatures. There will never be a large enemy who doesn't hit like a truck: physically, think about how much more muscle & inertia they have. I also want to demonstrate that monsters don't have to be huge to be scary.
- Combat: monsters should have 2 kinds of moves: normal and telegraphed attacks. Normal attacks are quick, and the player is not expected to dodge them. However, BIG attacks should do a lot more damage & be telegraphed. This creates a good middle ground between skill and forced exchange of blows.

### Enemy Archetypes
The following are physical archetypes based on the fact the the player can deal 3 types of physical damage, as well as many low damage hits VS a few high damage hits:
1. Lots of flat armor. This would be something like a plated foe. Weaknesses: blunt, pierce (at least compared to slash). Strength: slash dmg
2. High physical resistance, ie “hard” enemies like a stone golem or treant. Weakness: blunt. Strengths: slashing, pierce
3. Not much armor, but high health pool. Order of effectivenes (high to low): slash, pierce, blunt
4. “Squishy” enemies, like slimes. Weaknesses: foremostly slash, then pierce. Strength: blunt
5. "Tough skin" enemies are weak to pierce (implies some slash and blunt resistance)
6. Ethereal mobs: high resistance to physical. Especially blunt tho.
7. Undead made of flesh, like zombies, are held together by negative energy. They do not need organs to function, making them immune to crits. They're vulnerable to blunt and slash, and resistant to pierce: they dont value organs but have to expend a lot of energy to counteract structural damage. These undead are the only enemies to have flat blunt dmg negation, individually determined by how meaty they are, cuz blunt will do 0 dmg until it begins damaging bone. Since they use their physical body, they can be blinded, unlike skeletons. They're immune to bleed. Such creatures are usually not dextrous because their reanimation isn't nuanced - that requires a powerful necromancer. Undead without bones, though, would be very resistant to blunt, since it would not cause meaningful structural damage.
8. Undead made of bones: are held together with negative energy. They have a “necromatic flow” throughout their structure, and they are only killed if this flow is disrupted. Due to their brittleness, they are weak to blunt (slash is OK, but they're especially resistant to pierce). Immune to bleed.

As for non-physical damage, enemies will often be resistant to certain elements and weak to others. I don’t think that an entire area should be strong to one element and weak to another... this would promote builds who specialize farming a specific area, which I think is boring. Therefore I think that areas could generally favor one element, like a hot area generally has fire resists/cold weaknesses, but in the area should exist enemies which defy the norm, akin to a small biological niche. Also, immunities generally don't exist, but monsters may be highly resistant. It's possible for damage types to heal a mob, though.

Note that these categories have individual exceptions: vampies fall into category 7, but are crit-able because they need their hearts, and can bleed, since a lot of their negative energy is in their blood. Since the heart is the only organ they need, they receive a crit chance reduction %, which can be ignored by the Advanced Anatomical Lore assassin perk.

### Enemy Personalities
Enemies will generate with a “personality,” which defines their likelihood to:
- Call for backup when they see the player (passive personality)
- Or confidently attack the player (aggressive personality)
This chance is also influenced by if the enemy has detected the player or not. If an enemy cannot sense the player and takes damage, it will be more likely to flee. However, if the player damages the player and reveals themself, an aggressive enemy might choose to engage.

How to tell them apart: aggressives and passives look visually distinct. Additionally, the spell "Intuit" reveals the personality of an enemy. Knowing the personality of an enemy is strategic information: it may be easier to lure aggressives away, so you don’t engage a passive and then get mobbed by all the foes. Passives also have worse stats, while aggressives have increased stats.



# Areas-------------------

Areas in this game should all have distinct vibes to them. Loosely speaking, easier areas will be close to the spawn point while far away lands will be harder. Harder areas will have soft barriers to prevent noobs from blindly stumbling into them. However, players should have gathered clues about what they're getting into via intentional design (eg bones on the ground+spooky area+townsfolk talk about how people never return from there = dangerous).

### Main Vibe Parameters to be Considered for Areas
- Magic Level (applies to all other parameters)
- Civilization level (sub parameter)
- Hospitableness / Climate (sub parameter)
- Creature level (sub parameter)
- Beauty level
- Topology (flat or bumpy)
- Geological features
- Recreation level (stuff you can do here)
- Susceptibility to natural disasters
- Stuff to find

Sub-Parameter: Civilization
- Technology level
- Architecture
- Entertainment
- Transportation available
- Goods available
- Economic level
- Demographic of inhabitants
- Cultural and historical factors (eg city with rich history of art vs economic trading hub). Culture is very important to me; I want to dive into how cultures are shaped by their geography.
- Political state

Sub-Parameter: Hospitableness / Climate
- Wetness (arid vs foggy), 
- Temperature: affecting light hues, species (eg tropical vs tundra), dirt, etc
- Light level: darkness vs sunlight


### Area discussion
Here I ponder potentially cool areas (villages, cities, caves, deserts, whatever) and fill out their lore and descriptions. As of now, these areas are not yet spatially defined relative to one another - i can worry about placing them on a map later. For now, describe why they're cool and at what point in their journey the player should encounter them. This will eventually be an organized list.
- Inside of a volcano
- (Abandoned?) Tower of illusions, has a lot of trippy effects, non euclidean fuckery, forest temple twisty hallway stuff
- Crypt of the dictator (skeleton army inside?)
- Howling mines
- Sanctum of dreams (idek it just sounds sick, maybe you can only go there once)
- Shadowed keep (lots of stealthy mobs?)
- Area of oppressive darkness, where you can easily get lost in the dark
- Village in the treetops, maybe you won’t even notice it until you look up
- cliff goes off to a floating castle.
- lots of stuff in "random notes" not yet added here




# Art-----------------
I very much enjoy the dark retro art of diablo 2, which inspired the atmosphere of this game. Pixelation lets the mind fill in the gaps.

Weapons should often have unique art. This adds a lot to the immersion in a loot based game.

## Build planning / Foreseen builds-----------------------
I want to plan out what niche each build occupies in terms of skill. Some builds will be lower skill+lower potential, and vice versa. I would like to outline what actions each build can do and how that contributes to the skill cap and overall playstyle.

#### Warrior

#### Ranger

#### Sorcerer



# General Lore---------
Too early to go on the GDD

### Death Magic
Death magic stems from some evil god/deity, and one must make a pact with him to harness some of his power... maybe
