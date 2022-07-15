WTP Familiars v2.7
==================

**Authors: Rabain & [Salk](mailto:crimes73@gmail.com)  
EE Port: flamewing & [artyfox](https://github.com/artyfox/WTPFamiliars)**

(originally intended to be part of the now discontinued World Transition Project)

Overview
--------

This mod introduces an alternative version of the Find Familiar spell, opting for a more PnP faithful representation of it.  The player will also be able to choose from a pool of three or four creatures (exception: True Neutral mages are restricted to the True Neutral Familiar).

When the spell is cast you will be able to select the Familiar matching your own alignment or one of the Familiars whose alignment is within one step from your own. For example, if your alignment is Lawful Evil you would have a choice between the Imp (LE), the Dust Mephit (NE) and the Ferret (LN).

The Familiars have now extended dialogue and new icon colors. They will make themselves heard when they feel they've spent too much time in the backpack and their death has now different consequences for the player: failing the constitution based system shock check (see table below) will render the mage temporarily vulnerable to enemy attacks. Afterwards, a three-day period of mourning will prevent the summon of a new Familiar. During this period, the mage suffers a -1 penalty to their constitution. When the mourning is over, the mage will regain the lost constitution point and will be able to summon a new Familiar.

The mod also introduces a new Familiar (spider) in order to have each alignment represented by a different creature.  The spider has been placed in the True Neutral slot and as such minimum bumping has occurred with regard to which Familiar is assigned to which alignment.

The new breakdown is as follows:

|Familiar|Spell File|Alignment|Change|Summonable by|
|:--- |:--- |:--- |:--- |:--- |
|Rabbit|WTPFLGRA|Lawful Good|- was True Neutral|Lawful Good, Neutral Good and Lawful Neutral|
|Pseudodragon|WTPFNGPD|Neutral Good|- no change|Lawful Good, Neutral Good and Chaotic Good|
|Faerie Dragon|WTPFCGFD|Chaotic Good|- no change|Neutral Good, Chaotic Good and Chaotic Neutral|
|Ferret|WTPFLNFE|Lawful Neutral|- no change|Lawful Good, Lawful Neutral and Lawful Evil|
|Spider|WTPFTNSP|True Neutral|- no change|Neutral Good, True Neutral and Neutral Evil|
|Cat|WTPFCNCT|Chaotic Neutral|- no change|Chaotic Good, Chaotic Neutral and Chaotic Evil|
|Imp|WTPFLEIM|Lawful Evil|- no change|Lawful Evil, Neutral Evil and Lawful Neutral|
|Dust Mephit|WTPFNEME|Neutral Evil|- no change|Lawful Evil, Neutral Evil and Chaotic Evil|
|Quasit|WTPFCEQU|Chaotic Evil|- no change|Neutral Evil, Chaotic Evil and Chaotic Neutral|

The Familiar also levels up with the mage, acquiring betters statistics and abilities at different stages

*   Hit points will increase
*   Saving Throws will improve
*   Armor Class will improve
*   Special abilities will be gained
*   ...and more

Detailed information about the Familiar is provided in the Inventory page, by right clicking on the Familiar icon.  All Familiars have now a portrait and also a soundset assigned to them.  The individual sounds vary for each Familiar.  The following sounds are installed:

*   BORED
*   BATTLE\_CRY1
*   BATTLE\_CRY2
*   BATTLE\_CRY3
*   BATTLE\_CRY4
*   BATTLE\_CRY5
*   DAMAGE
*   DYING
*   HURT
*   SELECT\_COMMON1
*   SELECT\_COMMON2
*   SELECT\_ACTION1
*   SELECT\_ACTION2
*   SELECT\_RARE1
*   SELECT\_RARE2

The Familiar behaves in the same fashion as the standard BG2 Familiars and will follow you from area to area. Each Familiar has a reference class (warrior, thief, mage or druid/mage) that serves as generic guideline for THAC0, skills and saving throws advancement. Familiars have a sense of self preservation and are therefore scripted to jump into the backpack when their health is critically compromised and an ongoing battle is threatening their life.  Providing you rest before taking them out again they will heal and memorise their known spells. 

The system shock table:

|CON|System Shock|
|:---:|:---:|
|1|25%|
|2|30%|
|3|35%|
|4|40%|
|5|45%|
|6|50%|
|7|55%|
|8|60%|
|9|65%|
|10|70%|
|11|75%|
|12|80%|
|13|85%|
|14|88%|
|15|90%|
|16|95%|
|17|97%|
|18+|99%|


Familiar Statistics
-------------------

Each familiars now has an assortment of special abilities and grow in power with the summoner. Talk to your familiar after leveling up to see the changes. 

Many familars will also grant a unique bonus when they are within 15 feet proximity to the master. Take note of your familiars tooltip while in combat.

  

## Rabbit (LG) \[WTPRABBI.CRE / WTPFRAB.BAF\]
------------------------------------------
    
    Armor Class: 6
    
    Hit Points:  4
    
    Attacks per Round: 1
    
    Backstab multiplier: x2
    
    Special abilities: Wary (immunity to backstab), Lucky (+1 luck bonus)
    
    Burrow once per day (hides from enemies)
    
    Empowerment: the familiar receives a level-based, affinity-modified bonus to Saving Throws and Armor Class if in proximity to the master
    
      
    
    Level Up (Thief Class):
    
    HPs: +4 (Lv 2-9), +2 (Lv 10-19), +1 (Lv 20-50)
    
    Thieving skills: +4 to Open Lock, Move Silently, Hide in Shadow, Detect Illusion, Find Traps, Pick Pocket (Lv 2-7, 9-14, 16-21, 23-28, 30-35, 37-42, 44-49), +5 (Lv 8, 15, 22, 29, 36, 43, 50)
    
    Armor Class: +2 (Lv 4, 11, 19, 32)
    
    THAC0: +1 (Lv 3, 5, 7, 9, 11, 13, 15, 17, 19, 21)
    
    Weapon enchantment: +1 (Lv 5, 12, 20)
    
    Saving Throws improvements at level 5, 9, 13, 17, 21
    
    Backstab multiplier: +1 (Lv 5, 9, 13)
    
    Special: Burrow (Lv 6, 12, 20, 30)

## Pseudodragon (NG) \[WTPSEUDO.CRE / WTPFPSE.BAF\]
------------------------------------------------

    Armor Class: 2
    
    Hit Points: 4
    
    Attacks per Round: 1
    
    Magic Resistance: 35%
    
    Special abilities: Attacks with a +4 bonus (may render those scratched by it unconscious)
    
    Grants 2% magic resistance to the master if within 15 feet
    
    Can cast Camouflage once per day
    
    Spell bounce: the familiar has an affinity-modified chance of mirroring the effects of personal protective spells cast by the master
    
      
    
    Level Up (Mage Class):
    
    HPs: +4 (Lv 2-9), +2 (Lv 10-19), +1 (Lv 20-50)
    
    Armor Class: +1 (Lv 4, 11, 19, 32)
    
    THAC0: +1 (Lv 7, 10, 13, 16, 19, 22)
    
    Weapon enchantment: +1 (Lv 5, 12, 20)
    
    Saving Throws improvements at level 6, 11, 16, 21
    
    Special: Camouflage (Lv 1, 6)
    
    Detect Invisibility (Lv 3, 9)
    
    Improved Camouflage (Lv 12, 15)

## Faerie Dragon (CG) \[WTPFAIRY.CRE / WTPFFAE.BAF\]
-------------------------------------------------

    Armor Class: 5
    
    Hit Points: 4
    
    Attacks per Round: 1
    
    Magic Resistance: 10%
    
    Special abilities:  Attacks with a 2-foot-diameter cloud of euphoria gas (failing a saving throw vs. breath weapon, the victim will wander around aimlessly, unable to attack and with Armor Class decreased by 2)
    
    Can cast Invisibility once per day
    
    Spell bounce: the familiar has an affinity-modified chance of mirroring the effects of personal protective spells cast by the master
    
      
    
    Level Up (Mage/Druid Class):
    
    HPs: +4 (Lv 2-9), +2 (Lv 10-19), +1 (Lv 20-50)
    
    Armor Class: +1 (Lv 4, 11, 19, 32)
    
    THAC0: +1 (Lv 7, 10, 13, 16, 19, 22)
    
    Weapon enchantment: +1 (Lv 5, 12, 20)
    
    Saving Throws improvements at level 4, 6, 7, 10, 11, 13, 16, 19, 21
    
    Magic Resistance: +6% (Lv 2) +8% (Lv 3-12)
    
    Special: Suggestion (Lv 3, 9)
    
    Invisibility (Lv 6)
    
    Limited Wish (Faerie Dragon) (Lv 15)

## Ferret (LN) \[WTPFERRE.CRE / WTPFFER.BAF\]
------------------------------------------

    Armor Class: 6
    
    Hit Points: 4
    
    Attacks per Round: 1
    
    Backstab multiplier: x2
    
    Special abilities: Rapid motions (always hasted)
    
    Can cast War Dance once per day (taunts one enemy)
    
    Empowerment: the familiar receives a level-based, affinity-modified bonus to Saving Throws and Armor Class if in proximity of the master
    
      
    
    Level Up (Thief Class):
    
    HPs: +4 (Lv 2-9), +2 (Lv 10-19), +1 (Lv 20-50)
    
    Thieving skills: +4 to Open Lock, Move Silently, Hide in Shadow, Detect Illusion, Find Traps, Pick Pocket (Lv 2-7, 9-14, 16-21, 23-28, 30-35, 37-42, 44-49), +5 (Lv 8, 15, 22, 29, 36, 43, 50)
    
    Armor Class: +2 (Lv 4, 11, 19, 32)
    
    THAC0: +1 (Lv 3, 5, 7, 9, 11, 13, 15, 17, 19, 21)
    
    Weapon enchantment: +1 (Lv 5, 12, 20)
    
    Saving Throws improvements at level 5, 9, 13, 17, 21
    
    Backstab multiplier: +1 (Lv 5, 9, 13)
    
    Special: War Dance (Lv 6, 12, 20, 30)

## Spider (TN) \[WTPSPIDE.CRE / WTPFSPI.BAF\]
------------------------------------------

    Armor Class: 6
    
    Hit Points: 4
    
    Attacks per Round: 1
    
    Special abilities: Attacks with venom (onset time of 1-2 rounds and causes paralysis for 2d4 turns, unless the victim makes a successful saving throw vs. poison with a +1 bonus)
    
    Immunity to critical hits, Has 50% resistance to poison
    
    Can cast Web once per day
    
    Empowerment: the familiar receives a level-based, affinity-modified bonus to Hit Points, THAC0 and Armor Class if in proximity of the master
    
      
    
    Level Up (Warrior Class):
    
    HPs: +4 (Lv 2-9), +2 (Lv 10-19), +1 (Lv 20-50)
    
    Armor Class: +1 (Lv 4, 11, 19, 32)
    
    THAC0: +1 (Lv 3-21)
    
    Weapon enchantment: +1 (Lv 5, 12, 20)
    
    Saving Throws improvements at level 3, 5, 7, 9, 11, 13, 15, 17
    
    Attacks per Round: + 0,5 (Lv 4, 7, 10, 13)
    
    Poison Resistance: +5 (Lv 2-8)
    
    Special: Web (Lv 6, 12, 20, 30)
    
    Wraith Form (Lv 9)
    
    Phasing (Lv 12)
    
    Improved Phasing (Lv 15)

## Cat (CN) \[WTPCAT.CRE / WTPFCAT.BAF\]
-------------------------------------

    Armor Class: 6
    
    Hit Points: 4
    
    Attacks per Round: 2
    
    Backstab multiplier: x2
    
    Special abilities: Keen Vision (dispels normal invisibility), Nine Lives (+4 bonus to Save vs Death)
    
    Empowerment: the familiar receives a level-based, affinity-modified bonus to Saving Throws and Armor Class if in proximity of the master
    
      
    
    Level Up (Thief Class):
    
    HPs: +4 (Lv 2-9), +2 (Lv 10-19), +1 (Lv 20-50) 
    
    Thieving skills: +4 to Open Lock, Move Silently, Hide in Shadow, Detect Illusion, Find Traps, Pick Pocket (Lv 2-7, 9-14, 16-21, 23-28, 30-35, 37-42, 44-49), +5 (Lv 8, 15, 22, 29, 36, 43, 50)
    
    Armor Class: +2 (Lv 4, 11, 19, 32)
    
    THAC0: +1 (Lv 3, 5, 7, 9, 11, 13, 15, 17, 19, 21)
    
    Weapon enchantment: +1 (Lv 5, 12, 20)
    
    Saving Throws improvements at level 5, 9, 13, 17, 21
    
    Backstab multiplier: +1 (Lv 5, 9, 13)
    
    Special: Keen Sense (Lv 12) (dispels non-detection)

## Imp (LE) \[WTPIMP.CRE / WTPFIMP.BAF\]
-------------------------------------

    Armor Class: 2
    
    Hit Points: 4
    
    Attacks per Round: 1
    
    Magic Resistance: 25%
    
    Special abilities: Attacks with the wicked stinger on its tail (1-4 points of damage and injects a powerful poison)
    
    Regenerates 1 HP / round, 50% resistance to fire, cold, and electricity
    
    Can cast Detect Good once per day
    
    Grants 2% magic resistance to the wizard provided no distance greater than 15 feet separates them
    
    Spell bounce: the familiar has an affinity-modified chance of mirroring the effects of personal protective spells cast by the master
    
      
    
    Level Up (Mage Class):
    
    HPs: +4 (Lv 2-9), +2 (Lv 10-19), +1 (Lv 20-50)
    
    Armor Class: +1 (Lv 4, 11, 19, 32)
    
    THAC0: +1 (Lv 7, 10, 13, 16, 19, 22)
    
    Weapon enchantment: +1 (Lv 5, 12, 20)
    
    Saving Throws improvements at level 6, 11, 16, 21
    
    Fire, Cold and Electric Resistance: +5 (Lv 2-11)
    
    Special: Horror (Lv 3)
    
    Invisibility (Lv 6)
    
    Spider Form (Lv 9)
    
    Immunity to Normal Weapon (Lv 9)
    
    Detect Magic (Lv 12)~

## Dust Mephit (NE) \[WTPDMEPH.CRE / WTPFDME.BAF\]
-----------------------------------------------

    Armor Class: 6
    
    Hit Points: 4
    
    Attacks per Round: 2
    
    Special abilities: Regenerates 1 HP / turn, Immunity to critical hits
    
    Has 50% resistance to fire and 50% resistance to slashing, piercing, and missile damage
    
    Can use Glass Dust once per day (-4 AC and -2 THAC0 for 3 rounds to humanoids in a 15' radius)
    
    Empowerment: the familiar receives a level-based, affinity-modified bonus to Hit Points, THAC0 and Armor Class if in proximity of the master
    
      
    
    Level Up (Warrior Class):
    
    HPs: +4 (Lv 2-9), +2 (Lv 10-19), +1 (Lv 20-50)
    
    Armor Class: +1 (Lv 4, 11, 19, 32)
    
    THAC0: +1 (Lv 5-21)
    
    Weapon enchantment: +1 (Lv 5, 12, 20)
    
    Saving Throws improvements at level 3, 5, 7, 9, 11, 13, 15, 17
    
    Attacks per Round: + 0,5 (Lv 10, 13)
    
    Fire Resistance: +5 (Lv 2-11)
    
    Special: Glass Dust (Lv 3, 6)
    
    Gate Dust Mephit (Lv 12)

## Quasit (CE) \[WTPQUASI.CRE / WTPFQUA.BAF\]
------------------------------------------

    Armor Class: 2
    
    Hit Points: 4
    
    Attacks per Round: 3
    
    Magic Resistance: 25%
    
    Special abilities: Claws are coated in a toxin (save versus poison or lose one point of dexterity for 6 rounds, cumulative)
    
    Regenerates 1 HP / round, Immunity to critical hits, Has 50% resistance to fire, cold, and electricity
    
    Can cast Detect Good once per day
    
    Empowerment: the familiar receives a level-based, affinity-modified bonus to Hit Points, THAC0 and Armor Class if in proximity of the master
    
      
    
    Level Up (Warrior Class):
    
    HPs: +4 (Lv 2-9), +2 (Lv 10-19), +1 (Lv 20-50)
    
    Armor Class: +1 (Lv 4, 11, 19, 32)
    
    THAC0: +1 (Lv 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21)
    
    Weapon enchantment: +1 (Lv 5, 12, 20)
    
    Saving Throws improvements at level 3, 5, 7, 9, 11, 13, 15, 17
    
    Fire, Cold and Electric Resistance: +5 (Lv 2-11)
    
    Special: Horror (Lv 3)
    
    Invisibility (Lv 6)
    
    Wolf Form (Lv 9)
    
    Immunity to Normal Weapon (Lv 9)
    
    Detect Magic (Lv 12)

Compatibility
-------------

This mod is designed to work with Baldur's Gate II: Shadows of Amn with the Throne of Bhaal expansion pack and has been completely overhauled with full Baldur's Gate Trilogy compatibility in mind.

It also supports Baldur's Gate I: Enhanced Edition (incl. Siege of Dragonspear w/DLC Merger), Baldur's Gate II: Enhanced Edition, Enhanced Edition Trilogy,  and has experimental support for Icewind Dale: Enhanced Edition.

It is recommended to install this modification after Spell Revisions or any other modification that changes the Find Familiar spell in any way.  

Modder's notes:

Replaces the default Find Familiar spells (SPCL342, SPWI123) and scroll item (SCRL6D).

Does not use opcode #192 (Spell Effect: Find Familiar) and does not overwrite the default familiar creatures.

All new resources in the override folder start with the prefix, WTP\*.

Known Bugs
----------

There are a few minor visual glitches (unpolished level up process, spider's green circle's being a bit off, spells' visual effects showing for a brief moment when the familiar leaves the backpack).

Player1/Protagonist must be the summoner for the familiar in all games. In Icewinde Dale: Enhanced Edition, that means only the character in the first position will work.

Some scripts may interrupt the familiar's actions (eg. it may stop attacking, when you move into aura radius)

Installation
------------

WTPFamiliars is packaged and installed with WeiDU and distributed as a zip archive. To install, simply double-click the archive and extract the contents to your BG2 game folder.

You should then have a WTPFamiliar  folder and Setup-WTPFamiliar.exe in your BG2 folder. To install, simply double-click Setup-WTPFamiliar.exe and follow the instructions on screen.

Please run Setup-WTPFamiliar.exe in your BG2 folder to reinstall or uninstall this modification.

If you are on Linux, you need to have oggenc installed on your system at a place WeiDU can find it. Installing it through your package manager should suffice.

Contact Information
-------------------

Rabain created this mod.

[Salk](mailto:crimes73@gmail.com) expanded and bugfixed it (hopefully).

[flamewing](https://github.com/flamewing/WTPFamiliars) updated it for Enhanced Edition and put it on GitHub.

**[artyfox](https://github.com/artyfox/WTPFamiliars)** forked and maintains the mod.

Thanks and Acknowledgements
---------------------------

*   Thanks go to Sir-Kill and Dragonlord for accepting me into the WTP and to Sir-Kill for the new bams/portraits in use in this mod.
*   igi for pointing me in the right direction with spells and some tp2 user friendliness!
*   Blackwyrmlair Staff and Members for their support and patience.
*   The various mod site members and regulars who provide invaluable expertise to everyone who asks.
*   (Salk) My wife for her invaluable contribution in creating new portraits,bams and additional dialogue.
*   (Salk) Everyone at Gibberlings3, Pocketplane and SHS that helped me try putting all this together.

**Tools used in creation:**

[ConTEXT](http://www.context.cx/)  
[DLTCEP](http://www.dragonlancetc.com/forums/?board=9) by Avenger  
[IESDP](http://iesdp.gibberlings3.net/) maintained by igi  
[Near Infinity](http://www.idi.ntnu.no/~joh/ni/) by Jon Olav Hauglid  
[Shadowkeeper](http://www.mud-master.com/shadowkeeper/) by Mud-Master  
[GIMP](http://www.gimp.org/)  
[WeiDU](http://www.weidu.org/) by Wes Weimer / The Bigg

Credits and Copyright Information
---------------------------------

**The original WTPFamiliars is ©2007 Rabain. Version 1.0 and later are released and made public under the Creative Commons BY-NC-SA 3.0 licence.**

**Images used courtesy of:**

**[Monstrous Manual 1993](http://www.amazon.com/Monstrous-Manual-Fantasy-Roleplaying-Accessory/dp/1560766190/ref=sr_1_1?s=books&ie=UTF8&qid=1418470655&sr=1-1&keywords=monstrous+manual)  
[Monstrous Compendium Appendix (Planescape)](http://www.amazon.com/Monstrous-Compendium-Appendix-Planescape-Accessory/dp/1560768622/ref=sr_1_4?s=books&ie=UTF8&qid=1418470688&sr=1-4&keywords=Monstrous+Compendium+Appendix)  
[colvillevalleyanimalsanctuary](https://colvillevalleyanimalsanctuary.wordpress.com/2012/03/05/top-10-reasons-to-adopt-a-black-cat/)  
[VegasMike](http://vegasmike.deviantart.com/art/Imp-129907124)  
[Bruce Pearson](http://www.brucepearson.net/artist%20profile.html)  
[grouchywolfpup](http://grouchywolfpup.deviantart.com/art/Rabbit-Realism-148816910)  
[Alex Wild](http://www.myrmecos.net/about-alex-wild-2/)  
**

**Partial inclusion of material from:**

**[aTweaks](http://www.spellholdstudios.net/ie/atweaks)  
[Kit Revision](http://www.gibberlings3.net/kit_rev/)  
**

**Version History**
-------------------

****Beta Version 0.5****

*   Initial Beta release (Rabain)

**Version 1.0 Beta 1**

*   Complete overhaul of the original modification by Rabain
*   Fixed a number of bugs present in the 0.5 version
*   Expanded dialogue, script and level up dynamic

**Version 1.1 Beta 2**

*   Fixed CTD occurance (thanks MadMate)
*   Fixed a dialogue error

**Version 1.2 Beta 1**

*   Fixed a bug that would cause a dead familiar to return to the backpack

**Version 1.3**

*   First non Beta version
*   The familiar levels up now via dialogue (except when summoned)
*   Fixed a bug that would cause a script to fire more than once (thanks Jarno)
*   Changed the familiars' allegiance from "CONTROLLED" to "FAMILIAR" (thanks Argent77)
*   Added dialogue option to have the familiar follow automatically
*   Additional special ability for ferret, cat and rabbit (thanks Galactycon)
*   The familiars will no longer accept to go into the backpack too soon
*   The familiars' nagging will not knock the player out of a store or inn screen (thanks AstroBryGuy)
*   Corrected a few typos
*   Numerous adjustments of various kind
*   Minor script changes

**Version 1.4**

*   Fixed a bug with the wrong use of chapter globals

**Version 1.5**

*   Fixed a bug with equipping weapon for a number of familiars
*   Now the familiar leaving after friendly fire will no longer prevent the summoning of a new familiar
*   Attempt to avoid disruption of the familiar's levelling up process
*   Corrected a few typos

**Version 1.55**

*   Corrected a typo that'd reset the wrong variable
*   Fixed spell description for the Find Familiar scroll

**Version 1.6**

*   Fixed incompatibility with BGT transition script
*   Fixed incompatibility with Game Over Only on Party Dead modification
*   Improved familiars' discontent mechanic
*   Minor tweaks to dialogue and scripts

**Version 1.65**

*   Corrected a typo breaking level up dialogue option at level 12

**Version 1.7**

*   The familiars will no longer stubbornly refuse to return to the backpack when their or the mage's health is seriously compromised in battle
*   Attempt to avoid having the familiar's nagging ever interrupt the player during combat
*   Fixed minor bug with evil familiars' TOB dialogue
*   Additional dialogue for reputation shift (good aligned familiars will not stay with a villain!)
*   Fixed minor bug with the ferret's and the rabbit's Burrow ability

**Version 1.8**

*   All familiars use now their innate abilities instantaneously
*   Introduced new Special Ability for Thief/Warrior class familiars: Empowerment
*   Introduced new Special Ability for Mage class familiars: Spell bounce
*   Wraith Form and Phasing abilities added to Spider
*   Warrior class familiars are now immune to Critical Hits
*   Fixed a bug with the Spider's poison resistance
*   Fixed minor incompatibility with Sword Coast Stratagems

**Version 2.0**

*   Included missing Bard, Beast Master and Thief with UAI ability classes
*   Fixed minor issue with party members using the Find Familiar scroll in the quick slot
*   Fixed issue with Empowerment not switching on the fly when Reputation changes would affect it
*   Fixed issue with Empowerment not correctingly updating the hit points gain/loss
*   Fixed issue with Empowerment not removing old bonus before applying new ones
*   Changed Empowerment's visual cue to something less intrusive
*   Alleviated stuttering when Empowerment is being applied to or removed from Thief/Warrior class familiars
*   Raised base thieving skills for cat, ferret and rabbit
*   Changed Burrow ability: the familiar stays hidden until the master recalls him
*   Paralyzed or Intoxicated should now no longer appear on Undead
*   Mage class familiars now cast mirrored spells at the right level (thanks kjeron)
*   Fixed bug with some thieving skill and poison resistance bonuses being erased when the familair moves to the backpack (thanks magus)
*   Small cosmetic changes to the summoning/level up of the familiars
*   The spider's poisonous/paralyzing attack now scales with the enchantement of the weapon
*   The familiars no longer initiate any dialogue
*   Fixed compatibility problems with Game Over only on Party Dead (requires version 1.7 or higher)
*   Updated WeiDU to version 241

**Version 2.1**

*   The Burrow ability is now exclusive to the rabbit
*   The Burrow ability is now restricted to Outdoor and Dungeon areas rather than just Outdoor
*   The ferret gains more instances of its War Dance ability to compensate the loss of the Burrow ability
*   A couple of text changes to provide basic information about the Dust Mephit's Glass Dust ability
*   Fixed a typo in the WTFAMPx.d files
*   Minor code changes

**Version 2.5**

*   Fixed critical bug with Rabbit crashing the game when asked to return to backpack (thanks Chitown Willie)
*   Fixed critical bug with familiars not levelling up more than once (thanks enkku)
*   Fixed minor bug with empowered familiar not showing the correct name at the end of the dialogue-based level up process
*   The level up process now shows the amount of XP the familiar has gained
*   Updated WeiDU to version 246

**Version 2.6**

*   Added support for Linux and OSX by lowercasing all file names and using WeiDU's HANDLE\_AUDIO for ogg conversion
*   Enabling experimental IWDEE support
*   A few script improvements

**Version 2.7**

*   Fixed missing and incorrent string references in BGEE/IWDEE
*   Fixed summoning inconsistency on first cast in BG(2)EE
*   Enabled proper installation of global scripts in BGEE/SOD campaign/IWDEE
*   Incorporated Salk's 2.55 dialogue refinements
*   Updated to WeiDU 249