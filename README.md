# L2jNetwork_aCis

Video: https://www.youtube.com/watch?v=vywZdnt_MPU&feature=emb_logo

Revision 2 [6/1/2017]

NEWBIES HELPER NPC [sTARTING SYSTEM] --> Watch Me
BAKING SYSTEM
FLAG ZONES ON RB [CONFIG]
ANNOUNCE RB SPAWN [CONFIG]
OLYMPIAD PERIOD [CONFIG WEEKS]
ANNOUNCE HOW MUCH DAYS LEFT FOR NEW HEROES
WELCOME PM
RAKING NPC
and some errors/mistakes..
 
Revision 3 [13/1/2017]
 

Missing Multisells.
Fixed < New players spawn > on the water.
Fixed Nurse now can heal QA Boss.
Fixed mistakes on Newbies Helper Manager.
Removed color name for new characters.
Special Effect in npcs.
Augments stats on passives skills.
New htmls on npcs. Thanks to [protoftw]
NPC Services. [Change password, get Nobless, Change your name, change your class and etc].
Added new config file. Options:
1. Party teleporter items/amount.
2. Services Npc items/amount.
3. Clan Manager items/amount.
Added Password Changer.
You can get Noble status by killing Barakiel without Quest.


Revision 4/5 [23/1/2017]

Bugs Fixes:

Multisell Bug Fixed
Trade Check in Combat(if player is in combat cant trade anyone now)
Adena visual double icon (Fixed)

Olympiad:
Added acumen buff
Ranks Update Every Day
reuse skills after match Skills over 15min timer
fixed messages when players is registered

Misc:
Sieges Now Is Configurable (Siege.properties)
Antibow/AntiHeavy Protection Added
Config to allow players to teleport into Boss Zones Without Quest
Community Board Repair (Clean up And Fixed Bypass)
Ranking Manager Clean Up
Added Custom Spawnlist In database_installer.sh
Height on special npcs.
Mistake on RB Spawn Manager.
Removed Auto Pots [CP/MP/HP].
 

Revision 6 [26/1/2017]
 

Newbies NPC - Level Up Button fixed. [Now works for any level but not for subclass].
Syntax configs fixed.
Added Starting system. [Zones preview]
Added Infinity SS/Arrow. [1 SS/BSS/ARROW]
Karma/Flag player can not use buffer. [With config].
Removed some useless lines/methods.
Starting Items Fixed.
Pvp reward items Fixed.
Added/Removed some things for TvT Event.
- Root & Root effect [until fight start]
- Players is sitting [until fight start]
- Fixed Syntax errors with Reward.
 

Revision [10 14/2/2017]


AIO System (+ time)
You can give them AIO status from admin command and from item.
VIP System (+ time)
You can give them AIO status from admin command and from item.
Starting system fixed
If players close the window and make restart/exit game, system will restore the previous checkpoint.
Pets attack fixed
Donate Multi Shop. [Watch]
What's inside?
Noblesse Status
Level up your clan
Add x Reputation score
Get full clan skills
Augment Skills Lv10. [Active/Passive]
Clean x Pk Kills
Change your sex
Change your password
Get full Recomments
Siege Register
Register your clan for sieges.
Change your name color.
Green, Blue, Purple, Yellow, Gold
Change your character name
Enchant your items to max
Party Teleport
Go to your party member.
Teleport Restrictions:
Sieges, Olympiad, Events, Party Rift, jail, Duel, ObserverMode(oly), Non-Party members.
Cleaned many methods/lines.
Pvp/pk player can not use Buffer/Teleport
Q386_StolenDignity & updated Q384_WarehouseKeepersPastime
Saga's Quests
Thanks to Scrapy for quests.
 

Revision 11 [19/2/2017]
 

Added forgotten HTML folder for bot prevedion.
Added Grady Penalty with config.
Removed some aggro and clan from monsters on MOS.
Removed Anti-Buff shield from characters. [Works with Enabled/Disabled on .menu]
Fixed Flagzone. Now flag stay after hit inside of zone. [it is not in diff file. Will be fixed by adding the new l2jserver.jar]
Added Primeval Island as pvp zone. [it is not in diff file. Just copy/paste our Flagzone.xml from data/xml/zones]
Added time for new players Fireworks.
Disarm the main armor after Subclass.
Added Max enchant for Weapon/Armor with Crystal Scrolls.
 

Revision 12/13/14/15 [23/2/2017]


Skipping_items works fine now.
You can add Item Ids to remove it from any mob droplist.
Removed heavy armors for archers/daggers in Startup System.
Archers/Daggers can not see anymore heavy armors in startup.
Removed the bug on Multi Shop. (If you got color, after restart player will lost again the price of Donate Coins).
From now olympiad period ends every 1st and 15th day of month.
Changed the Olympiad announce. Now you will get the info with other way onEnter.
Added a new style of info.
Added reminder message for votes.
Player will get Pm to remind him to vote.
Added new XML file with all GrandBosses inside.
All GrandBosses in this XML file are in they original spawn.
Added all GrandBosses to original they spawn location.
I removed the old GrandBosses.Now you can find all GrandBosses in original location.
Also, New GrandBosses are with type <L2RaidBoss> and now the players will get Announce for every respawn.
Respawn time of GrandBosses 72Hours+24Hours Random respawn.
You can change the time as you wish. [Navicat --> raidboss_spawnlist table]
Barakiel's noblesse status fixed.
Reworked sieges.
Now the doors in TvT Event are closed.
Reworked Boss Status Manager.
Removed GrandBoss List from npc.
Added new command [ .epic ] You can see the status of GrandBoss.
Players can see the status of grandbosses. If are alive or dead.
Fixed the problem with subclasses height problem.
Added Geodata link. Now you will run your server with ready Geodata files.
Cleaned our customs mods. (Better writing style).
Deleded/Added some info on Augmentions HTML.
Fixed some problems on moving around.
(Somehow if you make much clicks on moving, you will stuck).
Removed some useless multisell.
Fixed the "warning" about BadReuestBypassToServer when you add/change subclass.
Added Disarm weapons & main part of armor when you add/change subclass.
Boss Status NPC
GrandBoss Status [ .epic ] command

 
Revision 16 [2/3/2017]
 

Clean up configs.
Reworked Multi Shop
Removed D/C Grade check for Enchants on Multi Shop
Reworked Buffer.
Added hitTime on buff effects & message info for every buff
Reworked gameserver console.
Added Olympaid Info on Gameserver console.
Added forgotten lines on SiegeManager.
Added NPCs style like characters.
Added PvP Info in Die.
Show enemy's CP/HP.
Removed check for /unstuck & SOE on GrandBoss zone.
Fixed some problems with Augments on Multi Shop.
 

Revision 17 [5/3/2017]


Offlineshop problems with save.
Sieges forgotten lines about the date.
The freezing of Fake NPCs.
Now can move, make actions etc.
Added respawn location after death.
Please check the spawnlist.sql of Diff file to know what you have to do in if you do not install new database.
You can find it in config/customs/customs.proeprties
Added spawn location for /unstuck SOE/BSOE
You can find it in config/customs/customs.proeprties
Added some respawn delay for mobs.
Some problems with Duel. (added some checks etc)
Forgotten HTML for MultiShop.
Added teleport to Clan members in MultiShop.
 

Revision 18/19 [11/3/2017]
 

First of all, we update the project to aCis 360 cause after the fight on maxcheaters, they said lies like "we already had acis 360 rev inside".. So, these lies now are truths.
Enchants has been moved to xml part.
You will find the new enchants on folder < data/xml/enchants/Enchants.xml >
Startup fixes/add:
Fixed the mistake when players make restart, he can see again the heavy armors(for light classes).
From now, Archers/Daggers they can see only Dagger/Bow weapon. Tnx to Celestine for idea.
Some rework on preview mode. (Removed useless lines).
Multi Shop Manager:
Added chnage base class. Now you can change yoru main class. [More like test mod for any bugs].
Removed all the prices of donate coins and moved to configs. Now you can change the price from configs.
Removed the same check for Donate Coin. [Now there is only 1 item for all of actions]
Players cannot change/add subclass while is in flag mode.
New droplist view design for mobs.
Works with target on mob and type .drop
Fixed Day/Night spawn mobs after restart. Thanks to RuLLez
Changed some NPC to Fake Player style.
 
Revision 20 [2/4/2017]


Include aCis revision 362
TvT Event configs moved from event.properties to customs/configs/tvt.properties.
In case of your changes, just get your old lines of events.properties and paste it in tvt.properties
Startup changes:
Removed SpecialCamera from observer.
Dark Crystal Heavy removed from heavy armors list.
Players in combat cannot change/add subclass.
Disarm weapons on add/change subclass & on 3rd class on classmaster.
Now daggers/archers players can not equip heavy armor with second class because the weapon will be disarm in 3rd class. [it was a bug]
Fixed TvT Event errors in every restart/shutdown of server.
Reworked FlagZone.
Now players can not loose pvpflag inside of pvpzone when they use party/clan buffs/cp. Let me know if the problem Isn't fix.
Fixed Overpower of Frenzy skill.
Cleanup some methods with less lines.
Fixed the stuck on stairs when you move your player with fast clicks. [Not always a problem. But It was a problem].


Revision 21 [14/4/2017]

Fixed Bug trade.
Added Hero & Castle Lord announce.
Announce the player name for hero or Castle lord on login.
PvP/Pk Title Prefix.
Title with count of pvp/pk. Ex: [50] | [50]
Added Pin Code.
If the player choose to secure his character, then for every login the system will ask for the Pin code.
Auction Shop.
Players can sell Items with adena in NPC.
Olympiad Protection.
For players with same IP, every battle will be Tie.
PvP Change Zone.
A random pvp change zone with every x time.
Cleanup Anti Bow system.
 
Revision 22 [22/4/2017]

Frintezza.
Added Frintezza script.
VIP/AIO system
Reworked the vip/aio character and added some restrictions in the town.
Adena
Adena config for new characters moved to StartingItems on customs.properties.
StartingItems = 728,20;1539,20;736,20;57,50000000;
Buffer
added some missing skills.
Pin Code
Fixed some mistakes on player enter..
(I forgot to check the player actions).
Bug double shot on archers fixed.
Configs
Cleanup all custom configs. [better organization]
MultiManager
Cleanup some useless lines.
Bot Protection
Fixed the teleport back to town if the player miss the correct color.



Revision 32 [28/2/2018]

Phoenix Engine:

Phoenix events has deleted.

PvP Zone:

Fixed the problem with respawn button (bug for rev26)
Added .exit command. Gives you 3 sec to leave if you aren't in combat.
L2FlagZone renamed to FlagZone (as all the others zones). acis update.

Skills:

Chant of Victory/Magnus/ p.of wind/ p.of fire/ p.of water now you can change from one buff to the other without problem.
Fixed the heal with some hero weapons. (again rev 26 bug)
Many skills has been fixed/reworked with acis latest rev.

Other misc:

Fixed the problem with drop items on the ground.
Fixed the Observe mode in olympiad.
Double archer shot (by acis)
Added message when you add a subclass.
Removed the Menu panel from revision 28. We use another now.
The invul command for GM characters changed from //invul to //setinvul
Changed the style of the raidboss info npc.
Announce the clan name or player name on raidbosses kill.
ex. The raidboss Horus has been killed by blabla Clan. or by killer player. (Thanks Reborn for help)
Added announce on end siege when a clan win the castle.
ex. The clan Blabla has take the x castle.
Added a new way to recovery your MP with mana potion. (New Item Handler for mana potions).
With config you can set the value of MP recovery.
aI6mZpm.jpg
Added Infinity Mana Potion. Set it true and always you can use only 1 mana pot.
Added config for max value P.atk speed & M.atk speed.
ex. By default is 2000. So, the player will get max p.atk speed or m.atk speed 2000.
Vote System:
Removed the server link from announce.
Changed the info announce for votes.
Startup System:
Reworked the whole system.
Removed:
Preview zones/buffs button/all the icons.
Added new style for Startup system. Check the PHOTOS
Cleric class removed. It was mistake to have the first class in there.