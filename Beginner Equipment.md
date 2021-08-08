# Beginner PVE Equipment

#### Table of Contents
- [Basic Concepts](Beginner%20Equipment.md#basic-concepts)
- [Shops Guide](Beginner%20Equipment.md#shops)
- [Equipment and Farming Recommendations](Beginner%20Equipment.md#equipment-list--early-game-farming-locations)
  - [Core Blue Equipment](Beginner%20Equipment.md#core-blue-equipment)
  - [Farming Maps](Beginner%20Equipment.md#early-game-farming-maps)

## Basic Concepts
### Very Important, Please Read:
While an understanding of these concepts is not truly necessary to play or enjoy the game, they are important if you wish to understand why certain guns are superior to others, especially when a more surface-level examination would not imply such. If you wish to skip this section, at least read the first two sections that cover why equipment is more important than ship selection and tech level. More than anything else, an understanding of tech level will aid you in making informed decisions about what equipment is worth using.

### Why Equipment?
I've seen many newer players hit a wall and struggle with content, and they'll ask 'What ships should I replace?' Many times, they are using ships generally considered weak and they do have superior options that they could tag in. But what do you do when that player is already using strong ships; when that player replaces their ships but still struggles; when that player is so grossly overleveled they're gaining the maximum damage boost from level advantage?

Invariably, the problem is equipment. Especially for a player who might come from another game where equipment selection is a more secondary concern, or perhaps even non-existent, it's easy to not realise how incredibly impactful equipment selection is. What ultimately sets ships apart in the late-game is their skillset more than anything else per se, and a newer player is most likely running ships still at skill level 1. When stripped of their skills, all that sets ships apart is their equipment and their statline, which only serves to enhance the equipment you give them.

Another piece of advice I see frequently given to new players is just to overlevel your ships and rely on level advantage. While this will technically work, and work for quite awhile, it will stop working at some point. My goal as a guide creator is to grant players the knowledge necessary to make informed decisions on their own and rely on tactics that will always remain effective. If you learn how to fight at level parity early on, you will always be capable of fighting at level parity.

If you only take one piece of advice away from this guide it should be this: **always upgrade your damn equipment**.

### Tech Level
Perhaps one of the least obvious concepts for a newer player, tech level is also one of the most important when it comes to choosing what equipment to use. Tech level can be viewed in the upper right corner of an equipment's stat card. For most equipment in the game, tech level ranges from T1 to T3, with a higher tech level version of a piece of equipment being stronger in every aspect and one rarity higher. Tech level 0 also exists and is functionally identical to tech 3, except that tech 0 equipment is unique and has no lower-rarity variant.

Assuming all pieces of equipment are at the same upgrade level, tech 3 equipment of *all rarities* is comparable. This means that early game, tech 3 blue equipment will often be as strong as purple or gold equipment, while being easier to obtain and cheaper to upgrade. Blue equipment will fall off later in the game because it caps at an upgrade level of +6, while purple and gold equipment can be upgraded to +10.

Because of the tech level system, purple rarity equipment has the potential to be superior to gold equipment, which is something that happens in many cases. Similarly, with the relative ease of acquisition and upgrading of purple equipment, it's far more efficient for a newer player to focus on strong, but lower rarity equipment, rather than tunnel vision on acquiring shiny gold rarity equipment.

### [Damage Calculations](https://azurlane.koumakan.jp/Combat#Damage_Calculations)
Understanding the way damage is calculated is vital to understanding why certain pieces of equipment are stronger than others. While the full damage formula (available on the wiki) can seem daunting, a basic version of the damage formula that tells you most of what you need to know would be: <br/>
```base damage × armour modifier × stat modifier × slot efficiency```

- **Base Damage:** this is the base damage of the weapon, available on the equipment's stat card. The only exceptions are fighters and dive bombers, whose displayed damage stats are not indicative of the actual damage dealt by that piece of equipment.
- **Armour Modifier:** every type of ammo for every type of weapon has a unique set of damage multipliers for each type of armour in the game. Boss fights mandate specialisation; know your enemy's armour class and equip your ships accordingly. Armour mods for every type of weapon can be found on the wiki.
- **Stat Modifier:** one of two stats in the basic damage formula that's tied to the equipped ship rather than the weapon. A ship's corresponding damage stat translates into a +% damage at a 1:1 level. A ship's stat modifier can be found with <br/>
```1 + (stat / 100)``` <br/>
In other words, there's a base damage multiplier of 1.00x, and a firepower stat of 100 would be +100% or +1.00 to that for a stat modifier of 2.00x; a firepower stat of 500 would be a 6.00x stat mod, et cetera. Stat bonuses from equipment or skills should be added before translating the stat into the stat mod.
- **Slot Efficiency:** the other ship statistic. Efficiency for a given equipment slot can be viewed on the ship's equipment screen or the wiki. It's a very straightforward damage multiplier; e.g an efficiency of 135% translates directly into a 1.35x damage modifier.
- **[Level Advantage:](https://azurlane.koumakan.jp/Combat#Damage_Formula)** while left out of the earlier basic damage formula, ships deal increased damage and take reduced damage based on the level difference between them and their targets, stacking 2% per level up to a maximum bonus of 50% with a 25 level difference. Level advantage allows a newer player to brute-force earlier maps despite having mediocre or unupgraded equipment, just by having a significantly higher level than the enemies on the map. However, the high-level of later maps as well as the linear scaling of exp makes this less viable.
- **[Danger Level:](https://azurlane.koumakan.jp/Combat#Danger_Level)** by killing the boss of a given map after 100% it (not 3*), you can build up a stacking damage reduction buff that caps out depending on the chapter you are in. However the true benefit of the Danger Level mechanic is when you have reached Safe level where Danger Level acts as an artificial extra level added on your fleets on top of the damage reduction buff. These artificial Danger levels stacks additively with level advantage and shares the same 50% cap. This is the primary mechanic through which high-level maps are made easier for faster and more efficient grinding.

Base damage is the single-most important attribute of a given weapon and as such, upgrading your equipment is the most effective way to increase the performance of your ships. Low or no equipment upgrades are the leading cause of newer players running into a wall when progressing through maps.

### Ballistics
An often overlooked aspect of equipment performance, ballistics refers to the physical characteristics of a weapon in combat. While mathematics can provide a basis for comparison, it cannot account for certain ballistic characteristics. As such, it's important to back up maths with empirical evidence and vice versa. A short list of important ballistic characteristics would include:
- **[Ammo Type:](https://azurlane.koumakan.jp/Combat#Shell_Type)** aside from affecting damage in a more direct way, different shell types also have different velocities. High-explosive shells have the lowest velocity while armour-piercing shells have the highest velocity. This impacts the range of a gun, which is especially noticeable with low-caliber destroyer guns. A given HE gun might have a much higher listed range than a comparable normal or AP gun, but the effective range of the shells are identical because the low velocity of the HE shells reduces the amount of distance the shell can travel. Shell velocity is also why AP shells tend to have an advantage at interception when equipped as an aux gun on main fleet ships. In addition to impacting armour mods and shell velocity, AP shells can penetrate their initial target and potentially hit a second target.
- **Range:** mentioned briefly under ammo types, the displayed range stat of a given gun is its targeting/acquisition range. Higher caliber gun types also receive a small, innate bonus to their range, beyond what the range stat would imply. A gun will only fire when it detects a target within this range. However, each gun also has a hidden 'bullet range' which is the amount of time a shell will stay on screen. The implications of this, as stated under ammo types, is that HE guns tend to have shorter effective ranges when compared to the other shell types. The increased targeting range of HE guns paired with the short effective range means HE guns will tend to have a substantial deadzone where the gun will fire, but the physical shell will reach its maximum range and fizzle out without hitting anything. This is most obvious and impactful with lower-caliber guns, but can sometimes be seen with higher-caliber guns as well. While it is hard to visualize the range of a given gun, a good metric to compare would be the approx 90 distance between the left-most of the vanguard screen and the white line limiting vanguard acceleration.
- **Spread:** perhaps the most obvious stat that impacts practical performance, also sometimes referred to as dispersion or deviation. The spread of a gun is the angle at which shells can be launched. The longer the distance from the target, the more impactful spread will be on a gun's performance. There are also two different fundamental types of firing patterns, which alter the way spread affects a given gun: fixed pattern guns, whose shells will always occupy the same relative spots within the firing cone, meaning the shells will always be as spread out as the displayed spread stat of the gun; random pattern guns, whose first salvo is going to be zeroed into the target, but whose followup shells will randomly deviate from the zero within the spread of the gun. A preview of a gun spread can sometimes be seen on its respective equipment page on the wiki.
- **Targeting Angle:** similar to range, a ship will only fire its gun when that gun detects a target within its targeting angle. For the most part, angle is consistent for all guns within a given caliber, though some exceptions exist. Because of this, angle is not a terribly important statistic, but its existence impacts certain things, namely scattershot guns (see below) and vanguard barrages. All vanguard barrages fire directly forward, however, destroyer guns are capable of firing behind the ship, while light cruiser guns fire in a wide cone that includes enemies mostly to the side of the firing ship. The increased firing angles of these low caliber guns can often lead to a vanguard unit triggering her barrage without a target in front of her to actually hit.
- **Targeting Attribute:** there are three types of targeting attributes: lock-on, bracketing, and scattershot. Most vanguard caliber guns have lock-on targeting. This means that the targeting vector will always be zeroed in on the target's hitbox center (relatively, the back of a chibi's head and middle of a mook ship). Bracketing guns are guns that launch arcing shells and include every battleship gun and a handful of especially high-caliber vanguard guns. Bracketing guns can bypass shields, have targeting vectors fixed on a certain point with a radial spread, and can create small aoe explosions. Because their targeting vectors are fixed on a point, if they miss their intended target, they will splash harmlessly into the water, while a lock-on gun's linear shells can continue traveling and potentially hit another target within their effective range. Scattershot guns shoot linear shells, like lock-on guns, but lack targeting vectors entirely. This means they will always zero in on 0° on the horizontal axis, which is to say, they will fire directly in front of the ship regardless of whether there's a target there or not. Scattershot guns only exist in light cruiser calibers, and despite not aiming their shells at an actual target, they share the same wide targeting angle as other CL guns, meaning your gun can acquire a target to the side of your ship, fire, and hit absolutely nothing. Scattershot guns should be avoided even if their statline would imply that they're a higher damage option than whatever alternatives you have available.
- **Targeting Vectors:** once a target is acquired within a given gun's targeting range and angle relative to the equipped ship, the gun fires along a targeting vector. Targeting vectors are tracked on the hitbox of the targeted enemy once the gun begins firing. This means, for guns that shoot multiple salvoes per reload cycle, the followup salvoes will always be aimed at the same target (or where it was last seen) regardless of if the intended target dies or moves. If the targeting vector goes outside of the gun's angle or in the case of battleship guns, a lack of eligible targets, these weapons will go through their firing time all the same but fire nothing.

### Bomb Drops Mechanics
- This is a graphical representation of how plane bomb drops work, mechanically.
- In the center colored dark red is the intended target which is prioritized based on their priority stat (generally humanoid > production > fireboats).
- The black circles, which get larger as weight increases, indicate the circle in which the bomb can be dropped around the triggering target. The bomb is dropped on a point with 3d dimensions identical to that of a ship torpedo within that black circle. Each bomb for each plane is dropped independently and can be on the same point. This location is determined randomly. 
- Bombs simply splash into the water and do not explode if they do not directly hit a target.
- Assuming a target (any target, even if it is not the intended target) is hit, the bomb will explode and deal damage in the pink circle corresponding to its weight.
- The image below reflects a bomb which has hit its triggering target dead-center in its black circle and hence dealt damage to its intended target and the surrounding pink area.

![](/resources/Bombs%20Graph.png)

## Shops
There are five main shops of note in Azur Lane:
 - **[General Munitions](https://azurlane.koumakan.jp/Shops#General_Shop)** - Exchange gold for various supplies. While equipment boxes may seem tempting, they're practically never worth buying. Even on a deep discount, the price of equipment boxes is still too steep given their rng nature. More cost-efficient purchases from this shop are: *T3 Skill Books* and *T3 Upgrade Parts*.
 - **[Merit Supply](https://azurlane.koumakan.jp/Shops#Merit_Shop)** - Merits are acquired from PVP exercises. This shop contains two unique ships (Eldridge and South Dakota) and, for late-game players, is a popular source for Gold Bulins. Given the high cost of these items however, they represent a relatively low value prospect for newer players compared to instead purchasing: *Wisdom Cubes* and *T4 Equipment Packs*.
 - **[Core Data Exchange](https://azurlane.koumakan.jp/Shops#Core_Exchange)** - Core data is acquired through running daily hard mode maps. This is one of the most important shops in the game and, as such, *always remember to run your hard mode maps every day*. They're a piece of daily content that's relatively easy to overlook as a newer player, and the 'hard' designator might be something of a turn-off, but the map levels are only slightly increased over their normal difficulty versions, and the rewards more than justify running the maps. Similar to the general shop, equipment boxes are never worth buying, instead you should focus on directly purchasing the *unique, core data exclusive equipment*. More info on individual pieces can be found in the [Core Data Guide](Core%20Data%20Guide.md).
 - **[Medal Exchange](https://azurlane.koumakan.jp/Building#Exchange)** - Tucked away in the build interface rather than the shops interface alongside the other shops. Medals are acquired by scrapping any ship of R rarity or higher. The medal exchange has three main sides to it: general ship exchange, item exchange, and SSR exchange. Similar to the merit shop, the medal exchange can also sell *Gold and Purple Bulins*, making it a popular source of those for established players. Consult other guide content or the wiki to decide whether or not any given ship is worth purchasing from the medal exchange. From the item exchange, there are no truly worthless purchases, but your ability to purchase anything will be tied to the rate at which you can acquire and scrap undesired ships. Notable items include the *Retrofit and Development Blueprints, Auxiliary Plates and Gems-only Food*. While *Submarine Equipment Boxes* cannot be acquired from any other shop, the gears they give are only transitional for SOS maps so purschase with caution.
 - **[Event Exchange](https://azurlane.koumakan.jp/Shops#Event_Shop)** - Only available during ongoing events, event points are acquired through clearing event maps and completing event missions. While every event has a different shop, a generally recommended buying order from event shops that are worth buying as a newer player are: Gold/Oil (during event) > Exclusive Gears > Ships if you don't have > Aux and any needed Plates > (Optional Boxes if lack specific gears) > DR BPs >= PR BPs > SSR Cat >= Chips the rest

## Equipment List & Early-Game Farming Locations
### Core Blue Equipment
This is a list of easily accessible blue rarity equipment. In general, upgrading these to +6 is worthwhile, especially with how cheap it is to do so. Many will be replaced by higher rarity variants later, but some lack higher rarity alternatives and will continue to be useful.

Because blue equipment requires such a small number of blueprints to craft, farming for core blue equipment, where possible, is highly recommended.

#### [120mm Twin <br/> ![DD Gun](/resources/120mm%20twin.png)](https://azurlane.koumakan.jp/Twin_120mm_(QF_Mark_XII))
- **Source:** Royal Equipment Boxes
- **Relevant Ships:** Destroyers and Battleships
- Easily the strongest damage-focused blue-rarity destroyer gun. While the purple rarity 127mm guns can compete with the purple rarity 120mm twin, their blue rarity variants shoot normal shells, reducing their damage by even greater amount than the natural damage reduction of using a lower tech level version of a weapon. Unfortunately, this gun can only be acquired from boxes.

#### [152mm Single <br/> ![CL Gun](/resources/152mm%20single.png)](https://azurlane.koumakan.jp/Single_152mm_(6%22/53_caliber_gun))
- **Source:** 3-2
- **Relevant Ships:** Light Cruisers
- A Russian gun and as such not available in any equipment boxes. If you want this gun, you'll need to farm for it. While it has incredibly high damage output, it has equally high spread, and achieving your max damage potential is next to impossible. When compared to other readily accessible alternatives, however, its sheer damage makes up for its poor hitrate. When one shell already hits harder than just about any other gun you could be using, it doesn't matter that you're only going to hit with one shell.

#### [152mm Twin <br/> ![CL Gun](/resources/152mm%20twin.png)](https://azurlane.koumakan.jp/Twin_152mm_(6%22/53_caliber_gun))
- **Source:** Eagle Equipment Boxes, 3-4
- **Relevant Ships:** Light Cruisers and Battleships
- A surprisingly potent low-rarity gun, useful as both a main gun for light cruisers and an aux gun for battleships. While it is a shotgun, it has a relatively low spread compared to some of the alternatives, and decent damage per volley with a fast reload speed.

#### [150mm Twin TbtsK <br/> ![CL Gun](/resources/150mm%20twin%20tbtsk.png)](https://azurlane.koumakan.jp/Twin_150mm_(TbtsK_C/36))
- **Source:** Ironblood Equipment Boxes
- **Relevant Ships:** Light Cruisers and Battleships
- With its purple rarity T3 variant being the strongest readily-accessible CL gun, it should be no surprise that the T2 TbtsK is also one of the best blue guns for CLs. Unfortunately, it's limited to boxes while its T3 variant is farmable.

#### [203mm Mounted](https://azurlane.koumakan.jp/Twin_203mm_(3rd_Year_Type)) and [203mm Twin SKC](https://azurlane.koumakan.jp/Twin_203mm_(SK_C/34))
[![CA Gun](/resources/203mm%20mounted.png)](https://azurlane.koumakan.jp/Twin_203mm_(3rd_Year_Type)) [![CA Gun](/resources/203mm%20skc.png)](https://azurlane.koumakan.jp/Twin_203mm_(SK_C/34))
- **Source:** Sakura and Ironblood Equipment Boxes
- **Relevant Ships:** Heavy Cruisers
- With the relative lack of available heavy cruiser guns, ships will be reliant on the lower rarity variants of the readily available HE and AP guns respectively. While it makes little difference which you choose early game, HE heavy cruiser guns deal significantly more damage against light armour while AP guns deal significantly more damage against medium and heavy armour.

#### [203mm Triple <br/> ![CA Gun](/resources/203mm%20triple.png)](https://azurlane.koumakan.jp/Triple_203mm_(8%22/55_caliber_gun))
- **Source:** Eagle Equipment Boxes, 1-4
- **Relevant Ships:** Heavy Cruisers
- The farmable alternative to the 203mm mounted. Worse in nearly every respect, given that it's a shotgun, but stronger than any white equipment you could be using, and 1-4 is one of the best farming spots early game so it's likely you'll end up with a few of these if you choose to farm 1-4.

#### [356mm Twin <br/> ![BB Gun](/resources/356mm%20twin.png)](https://azurlane.koumakan.jp/Twin_356mm_(41st_Year_Type))
- **Source:** Sakura Equipment Boxes, 1-4
- **Relevant Ships:** Battleships
- The best early-game battleship gun in the game. While its damage output seems low (and it is), it still hits hard enough to deal with just about any early-game threat. More importantly is the reload. Reload functions on a curve, with 100 reload stat being the equivalent of the equipment's base reload speed which can be viewed on the equipment card or the wiki. Because of the way this curve works, reload values below 100 disproportionately slow down the reload speed of a gun compared to how values above 100 speed it up. This means guns with a fast base speed such as the 356mm twin suffer less from the low reload stat of early-game battleships

#### [406mm Mk6 <br/> ![BB Gun](/resources/406mm%20mk6.png)](https://azurlane.koumakan.jp/Triple_406mm_(16%22/45_caliber_Mark_6))
- **Source:** Eagle Equipment Boxes
- **Relevant Ships:** Battleships
- The blue rarity variant of the infamous 'strongest gun in the game'. While its relatively long base reload speed means it's more negatively impacted by low reload values than other, faster guns, its sheer damage output is higher than any other blue rarity battleship gun. Once again, this gun is unfortunately not farmable, but if you open one from a box, it's well worth using, especially for boss killing.

#### [533mm Triple Torpedoes <br/> ![Torpedo](/resources/533mm%20triple%20torpedoes.png)](https://azurlane.koumakan.jp/533mm_Triple_Torpedo_Mount)
- **Source:** Eagle and Royal Equipment Boxes, 2-4
- **Relevant Ships:** General Vanguard
- Torpedoes follow a logical progression where, in addition to the increase in rarity with tech level, there's also a lower rarity variant that launches one fewer torpedo. The universal series torpedoes have a gold quintuple launcher, purple quadruple launcher, and this, the blue triple launcher. However, each of these is tech level 3, and because base damage is tied to tech level, the blue triple launcher actually deals the same damage per torpedo as the gold quintuple launcher, which means they deal more damage than the blue (and therefore T2) quad launcher, and even more than that compared to the blue (T1) quint launcher. As explained with battleship guns above, their fast base reload speed means they're also less negatively impacted by low reload values on your ships compared to the alternatives. When all of these factors are combined, there's little reason to run any other blue rarity torpedoes.

#### [F4U Corsair <br/> ![Fighter](/resources/f4u%20corsair.png)](https://azurlane.koumakan.jp/F4U_Corsair)
- **Source:** Eagle Equipment Boxes
- **Relevant Ships:** Carriers and Light Carriers
- Planes and their mechanics are another can of worms. With fighters especially, you'll want to look out for planes that are equipped with bombs, which you can see in the loadout for the plane listed on the equipment card. While higher tech level bombs deal more damage, meaning you would ideally want a T3 fighter, there isn't a single T3 blue rarity fighter equipped with bombs, leaving the T2 Corsair as the next best option.

#### [SBD Dauntless <br/> ![Dive Bomber](/resources/sbd%20dauntless.png)](https://azurlane.koumakan.jp/SBD_Dauntless)
- **Source:** Eagle Equipment Boxes, 3-1
- **Relevant Ships:** Carriers and Light Carriers
- The strongest T3 blue rarity dive bomber. Relatively easy to farm, but often skipped due to other maps in chapter 3 having overall more appealing equipment and ship drops.

#### [SB2C Helldiver <br/> ![Dive Bomber](/resources/sb2c%20helldiver.png)](https://azurlane.koumakan.jp/SB2C_Helldiver)
- **Source:** Eagle Equipment Boxes
- **Relevant Ships:** Carriers and Light Carriers
- While higher tech level bombs deal more damage, the Helldiver's loadout is so much stronger than the Dauntless in the first place that it ends up pulling ahead even with the reduced damage. While the T2 variant is not farmable, the T3 variant is, and in chapter 3, one of many reasons the Dauntless is not a terribly appealing option.

#### [Ju-87c 'Stuka' <br/> ![Dive Bomber](/resources/ju-87c%20stuka.png)](https://azurlane.koumakan.jp/Junkers_Ju-87C)
- **Source:** Ironblood Equipment Boxes
- **Relevant Ships:** Carriers and Light Carriers
- Generally regarded as a weaker dive bomber than the Helldiver, the Stuka's damage output is not too far behind, putting its T2 variant in a similar position to the Helldiver's where it can pull ahead of the alternatives despite having a damage penalty.

#### [TBD Devastator](https://azurlane.koumakan.jp/TBD_Devastator) and [Nakajima B5N](https://azurlane.koumakan.jp/Nakajima_B5N)
[![Torpedo Bomber](/resources/tbd%20devastator.png)](https://azurlane.koumakan.jp/TBD_Devastator) [![Torpedo Bomber](/resources/nakajima%20b5n.png)](https://azurlane.koumakan.jp/Nakajima_B5N)
- **Source:** Eagle and Sakura Equipment Boxes, 2-4
- **Relevant Ships:** Carriers and Light Carriers
- The strongest farmable blue rarity torpedo bombers, conveniently both farmed in the same spot. Japanese torpedo bombers launch torpedoes that are aimed at their target while other nations' bombers launch a parallel spread of torpedoes. Other than that, the differences between these two planes is minimal

#### [Barracuda](https://azurlane.koumakan.jp/Fairey_Barracuda) and [Tenzan](https://azurlane.koumakan.jp/Nakajima_B6N_Tenzan)
[![Torpedo Bomber](/resources/barracuda.png)](https://azurlane.koumakan.jp/Fairey_Barracuda) [![Torpedo Bomber](/resources/tenzan.png)](https://azurlane.koumakan.jp/Nakajima_B6N_Tenzan)
- **Source:** Royal and Sakura Equipment Boxes
- **Relevant Ships:** Carriers and Light Carriers
- As with the recommended blue rarity dive bombers, the increased base damage of these torpedo bombers makes up for the damage penalty they suffer from being low tech level. Both are functionally upgrades over the Devastator and B5N respectively.

#### [Fire Extinguisher <br/> ![Auxiliary](/resources/fire%20extinguisher.png)](https://azurlane.koumakan.jp/Fire_Extinguisher)
- **Source:** All Equipment Boxes, 2-3
- **Relevant Ships:** All Ships
- The fire extinguisher reduces the chance of catching fire, reduces the duration of burns, and reduces the damage of burns. While its true usefulness isn't apparent until late-game, fire extinguishers still provide a substantial boost to hitpoints and as there is no higher rarity auxiliary equipment that does the same thing, it will continue to be useful indefinitely.

#### [Naval Camo](https://azurlane.koumakan.jp/Naval_Camouflage) and [Hydraulic Rudder](https://azurlane.koumakan.jp/Hydraulic_Steering_Gear)
[![Auxiliary](/resources/naval%20camo.png)](https://azurlane.koumakan.jp/Naval_Camouflage) [![Auxiliary](/resources/hydraulic%20rudder.png)](https://azurlane.koumakan.jp/Hydraulic_Steering_Gear)
- **Source:** All Equipment Boxes, 2-2 and 2-1
- **Relevant Ships:** All Ships
- The strongest readily available evasion-boosting auxiliary equips. While mostly used on cruisers, they can be useful on any ship early-game, when auxiliary equipment is rare. Similar to the fire extinguisher, there are no higher rarity versions, but there is an evasion boosting aux acquired through research that functionally obsoletes these. Other than sprite and farming location, these equips are identical.

#### [Octuple 40mm Pom-Pom  <br/> ![Norfolk AA Gun](/resources/Octuple%2040mm%20PomPom.png)](https://azurlane.koumakan.jp/Octuple_40mm_Pom-Pom#Type_1)
- **Source:** Stock Equipment on Norfolk and Royal Equipment Boxes
- **Relevant Ships:** All Ships
- One of the most easily obtainable blue AA gun in the game due to Norfolk. While AA isn't as big of a problem early on, having a couple copies of this +3 equipped will make your push through 3-4 massively easier. Do note that for AA guns, the highest rarity gun should be equipped on the highest efficiency ship in your fleet as a beginner rule of thumb, optimizing AA is in the [Equipment Guide](Equipment%20Guide.md#anti-air-aa-guns).

### Early-Game Farming Maps

#### Note on useful ships
- Only drop only or Elite/SR ships will be listed here, for more information on good ships for beginners, looking at a beginner ship guide like Kawaii Five 0's.

#### Any Event Map
- Did you join during an event? Consider yourself in luck. Farming event maps is one of the most efficient things you could do, regardless of what the event actually drops. Aside from potentially having useful blueprints or ship drops, clearing an event map will reward you with a chunk of event currency, which can be used to purchase a number of useful consumables from the event shop, which typically includes retrofit blueprints and equipment boxes. A list droppable equipment blueprints can be gleam before you start a sortie

#### 1-4
- **Useful Equipment:** 203mm Triple, 120mm Single, 356mm Twin
- **Useful Ships:** Renown
- The only true farming map in chapter 1, as no other map drops blueprints. The heavy cruiser and battleship guns are practically guaranteed to be stronger than anything else you might have available. Renown isn't an especially flashy ship, but she performs adequately early game and is worth using if you pick her up. The 120mm single whose blueprints drop in this map, while not useful as an early-game weapon, is a potent end-game weapon for certain ships due to its high rate of fire.

#### 2-2
- **Useful Equipment:** Naval Camo, Blue Anti-Air Guns
- **Useful Ships:** Laffey, Javelin, Ayanami (JP), Z23 (CN/EN), Shouhou, Arizona
- One of the absolute best grinding spots for newer players. Starting in chapter 2, the starter ships are available as map drops, with the starter ship collection providing both a gold rarity quintuple torpedo launcher and the fourth starter ship. Arizona and Shouhou are both healers, with Arizona in particular being the only healing battleship in the game. While most blue rarity map drop ships either aren't notable enough to warrant mention, or are readily accessible otherwise, Shouhou only drops in chapter 2 and is an incredibly potent ship for most content save the plane heavy conditions of Worlds 12 and 13. The blue anti-air guns that drop here, while not particular noteworthy, are still useful for the upcoming chapter 3, which has some of the first maps that test your ability to survive in high-aviation fights.

#### 2-3
- **Useful Equipment:** Anti-Air Radar, Fire Extinguisher
- **Useful Ships:** Starter Collection, Shouhou, Nelson, Norfolk
- Another great map to prepare yourself for chapter 3. If you manage to cobble one or two together, the anti-air radar will substantially increase your ability to deal with enemy carriers. Nelson, and her sister Rodney, aren't especially strong ships later in the game, but they're useful early game due to their ease of access, ability to equip CL aux guns, and barrage. Norfolk is noteworthy not for her efficacy as a ship, but because she comes stock with a relatively very powerful blue anti-air gun.

#### 2-4
- **Useful Equipment:** 150mm Single SKC, Anti-Air Radar, 533mm Triple Torpedoes, TBD Devastator, Nakajima B5N
- **Useful Ships:** Starter Collection, Shouhou, Rodney
- The 150mm single is the fastest CL gun worth using. Similar to the 120mm single from 1-4, it's not especially useful early game, but if you manage to build one, it's worth holding onto for when it does become useful. Rodney is functionally identical to Nelson. Kent and Suffolk, unfortunately, lack the stock blue aa gun of their sister.

#### 3-2
- **Useful Equipment:** Steam Catapult, 127mm Single, SB2C Helldiver, 152mm Single
- **Useful Ships:** Starter Collection, Charles Ausburne, Souryuu and Hiryuu (Dragons)
- Easily one of the best early-game farming maps. What 2-2 gives you in ship drops, 3-2 gives you in equipment drops. Every single piece of gear here is useful with the exception of the 102mm destroyer gun. while 3-1 and 3-3 give okay drops, any blueprint acquired from those maps is a blueprint not acquired from 3-2. For ship drops, Charles Ausburne is part of the Beaver collection, and the hardest to acquire, being a purple rarity ship and drop only. Dragons are often overlooked compared to the Foxes from 3-4, but are significantly easier to acquire, have comparable performance in PvE, and have remodels which make them substantially better for late-game PvE.

#### 3-4
- **Useful Equipment:** Toolbox, F4U Corsair, 152mm twin
- **Useful Ships:** Starter Collection, Akagi and Kaga (Foxes), Kagerou
- The most popular early-game farming maps. While the equipment can be useful, 3-2 is a more efficient map to farm if that's what you're after. The main reason 3-4 is a popular farming spot is the Foxes. Overall not as efficient a spot to farm as 3-2. While Foxes are strong, they're significantly harder to farm than Dragons, and can be acquired through chapter 3's SOS mission. Kagerou packs a monsterous punch with her torpedoes for rarity before conidering her refit and vanguard torpedo buff, more so since the other IJN buffers are event locked or late game drops, especially ones for heavy cruisers.

#### 4-2
- **Useful Equipment:** 152mm Triple, 120mm Twin, 40mm Quad Pom-Pom, 203mm Mounted, 150mm Twin TbtsK
- **Useful Ships:** Starter Collection, Shiranui, London, Shigure
- As with 3-2, every single equipment drop from here is useful. All five drops are T3 and only the pom-pom has a readily accessible replacement. Shiranui, similar to Shouhou, is a low-rarity ship that only drops in chapter 4. While she's not as universally useful as Shouhou, she's still an incredibly capable ship you should keep an eye out for while farming. London, meanwhile, while less generally useful without her remodel than some of the other early-game farmable ships like Shouhou and Shiranui, becomes incredibly strong with her remodel, and is worth keeping an eye out for and investing in. Shigure is roughly comparable with base Javelin but with better torps, and her refit makes her close to Yukikaze in general performance

#### Chapter 5 and why you should not farm here
While chapter 5 is the first map that drops gold equipment blueprints, and that can seem tempting at first, chapter 5 is a terribly inefficient spot to farm. Gold blueprints require more copies to craft their respective piece of gear than purple equipment, while only dropping from the boss node, unlike purple blueprints which drop from all nodes. Additionally, T3 upgrade plates, which are required to upgrade equipment past +6, only start to drop starting in chapter 6. It will take an exceptionally long amount of time to actually acquire enough blueprints from a chapter 5 map to craft a piece of equipment, all the while you're not receiving T3 upgrade plates. If your fleets are capable of clearing the chapter 5 maps, your fleets are capable of starting to farm in chapter 6. If you're struggling in chapter 5, you'd be better off dropping back down to 4-2 to farm strong purple equipment instead.
