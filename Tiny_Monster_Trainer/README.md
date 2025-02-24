# Tiny_Monster_Trainer 
A game for the Thumby  
Move around, fight monsters, collect monsters, train monsters.  
(Version update information is at the bottom)  




############ **Game Info** ##############

**Player Info**  
To start you can only have up to two Monsters with you.    
Each Monster starts with 7 training points.
If you get an additional Monster, you will be asked you to select one & let it go.  
Every 10 Trainer Levels you can have an additional Monster with you, up to a maximum of 5.  
Your Trainer Level also influences how well your Active Monster can fight.  
The higher your Trainer Level, you'll seek out stronger Roaming Monsters to fight.  

**Monster Stats**  
**Health**: Amount of Health the Monster can have.  
**Agility**: Used to determine who attacks first and chance to dodge an attack.  
**Strength**: Used to determine damage for physical attacks.  
**Endurance**: Used to determine defense for physical attacks.  
**Mysticism**: Used to determine damage for magical attacks.   
**Tinfoil**: Used to determine defense for magical attacks.  
**Types**: The Type that the Monster is and what pool of moves it can learn from.  

**Battles**  
**Swap**: shows you your Active Monster and you can select another one of your Monsters to be the Active one.  
**Info**: Shows the opposing Monster's Stats/Types & the Active Monster's Stats/Types.  
**Attack**: Lets you pick a move to use against the opposing Monster.  
**Run**: Lets you escape the battle.  
**Tame**: Lets you try to tame the opposing Monster, at the cost of one Crystal.   

**If a fight is won**, Your active monster will gain 1 Training Point, you will gain an Experience Point towards your Trainer Level, & you might get an Item.  
**If a fight is lost**, one of your Monsters will have its HP & Stamina restored, but it will also be disheartened and lose a Training Point.  


############ **Training** #############  

Train is used to increase a stat by 1 point, up to a maximum amount.  
Learning a new attack cost 3 Training Points, a Monster can know up to 6 attacks.  
A monster can Mutate to increase a procedurally determined stat's maximum training amount.  
A monster can mutate up to 5 times, if you have duplicates of a monster they will mutate in the same ways.  
Mutating can potentially Change the look of a monster.  
Mutating can potentially add a new type to the monster, if a type is added the monster will also learn an attack from the new type.  

**Training Point (TP) Costs**  

Training:     1 TP  
Learn Attack: 3 TP  
Mutate:       5 TP  


############# **Items** ##############  
Items are not usable during combat.  
  
**For items that increase the a stat's maximum trainable amount:**  
  You can only do this 30 times per monster. If you give a monster more than 30 items that do this the maximum number will not go up anymore, but the monster will still recover any HP that the item is set to restore.

#######  
**Item List**  
#######  
  
**Bandaids** - Heals 8 HP  
**PushPops** - Heals 20 HP  
  
**Stickers** - Raises max trainable HP by 1 and heals for 10  
**Vitamins** - Raises max trainable Strength by 1 and heals for 9  
**Helium** - Raises max trainable Agility by 1 and heals for 8  
**Pillows** - Raises max trainable Endurance by 1 and heals for 7  
**Stardust** - Raises max trainable Mysticism by 1 and heals for 6  
**Tinfoil** - Raises max trainable Tinfoil by 1 and heals for 5  

**Crystals** - Will restore all stamina for all moves that the active Monster knows.  **Crystals are also needed for Taming Monsters.** They are consumed by the opposing monster while attempting to Tame  
  
############# **Types: Strengths and Weakness** ##############  

Bonus damage/defense is based on the Attack's Element Type vs Defending Monster Type  

Type | is Strong against | is Weak against
------- | ------|----------
**Earth**       |Wind      | Fire  
**Wind**        |Water     | Earth  
**Water**       |Fire      | Wind  
**Fire**        |Earth     | Water  
------- | ------|----------
**Light**       |Darkness  | Mind  
**Darkness**    |Cute      |Light  
**Cute**        |Mind      |Darkness  
**Mind**        |Light     |Cute  
------- | ------|----------
**Physical**    |Mystical  |Ethereal  
**Mystical**    |Ethereal  |Physical  
**Ethereal**    |Physical  |Mystical  


  
  
#######**Attacks**#######  

If the monster doesn't have the stamina for an attack: They will lose a % of their HP rounded up, then proceed with the attack.  


########  
**Attack List**  
########  
  
(Basic isn't a Monster Type, Basic attacks can't be learned, They are just default starting moves that a Monster can have)  


Monster Type | Attack Name | Element Type | Damage based on Strength/Mysticism
:------- | :-------: | :-------: | :-------:
**Basic** | | | 
------- |"Poke"       |No Element Type      | Strength  
------- |"Hit"        |No Element Type      | Strength  
------- |MagicHit"    |No Element Type      | Mysticism   
**Earth** |   |   |  
------- |"RockToss"        |Earth       | Strength  
------- |"Quake"           |Earth       | Mysticism  
------- |"Pressure"        |Water       | Mysticism     
------- |"Entomb"          |Darkness    | Strength    
**Wind**| |   |   |  
------- |"Gust"        | Wind        | Strength  
------- |"Cyclone"     | Wind        | Mysticism  
------- |"Lightning"   | Light       | Strength  
------- |"Divine Wind" | Ethereal    | Mysticism  
**Water**|   |   |  
------- |"Geyser"      | Water       | Physical  
------- |"Ice Shards"  | Water       | Mysticism  
------- |"Freeze"      | Mind        | Mysticism  
------- |"Wave"        | Physical    | Strength  
**Fire**|   |   |                                  
------- |"Torch"       | Fire        | Strength  
------- |"Blaze"       | Fire        | Mysticism  
------- |"Flare"       | Light       | Mysticism  
------- |"Inferno"     | Wind        | Strength  
**Light**|   |   |                                
------- |"Dazzle"      | Light       | Strength  
------- |"Razzle"      | Light       | Mysticism  
------- |"Radiance"    | Fire        | Strength  
------- |"Gleam"       | Mystical    | Mysticism  
**Darkness**|   |   |
------- |"Murk"        | Darkness    | Strength  
------- |"Shadow"      | Darkness    | Mysticism  
------- |'Unholy Poke" | Mystical    | Strength  
------- |"Dire Ruin"   | Ethereal    | Mysticism  
**Cute**|   |   |
------- |"Sing Song"   | Cute        | Strength  
------- |"Adorbes"     | Cute        | Mysticism  
------- |"Bubbles"     | Water       | Strength  
------- |"Fluff Ball"  | Physical    | Mysticism  
**Mind**|   |   |
------- |"Headbutt"     | Mind       | Strength  
------- |"Psychic"      | Mind       | Mysticism  
------- |"Telekinesis" | Earth      | Strength  
------- |"Good Vibes"   | Cute       | Mysticism  
**Physical**|   |   |
------- |"Body Slam"    | Physical   | Strength  
------- |"Super Hit"    | Physical   | Mysticism  
------- |"Boulder Toss" | Earth      | Strength  
------- |"Love Tap"     | Cute       | Strength  
**Mystical**|   |   |
------- |"Magic Missile" | Mystical   | Strength  
------- |"Ritual"       | Mystical   | Mysticism  
------- |"Rune Toss"    | Wind       | Strength  
------- |"Immolate"     | Fire       | Mysticism  
**Ethereal**|   |   |
------- |"Spooky Hit"    | Ethereal   | Strength   
------- |"Superlunary"   | Ethereal   | Mysticism   
------- |"Obscurity"     | Darkness   | Mysticism  
------- |"Rue"           | Mind       | Mysticism  
  
  
Updates as of 11/30/22:    
Fixed some bugs. Moved some code around to be better? probably added new bugs.
Changed the odds of getting specific items.
Changed the player info screen to show how many monsters you have out of how many you can have.
Added a way for the game to keep track of how many bonus items have been used. (A monster can only receive bonuses from items up to 30 times)
Players can now inspire their active monster every time their trainer level goes up. The option for this is found in "My Monsters" under "Inspire". If you do not have any inspiration points the option will not show up. Once you inspire your monster, depending on what you do, one of their stat's maximum values will go up, their max potential HP will go up, and they will get 2 training points. A player can only inspire a monster up to 40 times)
  
  
Updates as of 11/19/22:    
Added the chance for monsters to receive extra training points, if they fought or not. Added an option to play again while doing versus, added titles for ghost assigned based on thier worldseed.   
  
Updates as of 11/18/22:    
"Various bug fixes and adjustments have been made to make your gameplay experience more enjoyable" ... Changed some screens to look better, to hopefully show information better. Lowered number of attack moves a monster can have from 6 to 5. (Five makes my life easier and is easier on memory.)  Added new items that can increase how high you can train your stats. (you can give a monster 30 different items before this stops working) all new items increase HP by a set amount. Monsters need to have unique names so that multiplayer won't bug out (I think this issue would have been really rare, but it's better to just make all monsters have different given names)    
    

Updates as of 11/06/22:  
Versus modes have been added. You can fight other players via the link cable though the Link Battle mode. After you've fought someone over a link cable their data is saved so you can fight them offline via the Ghost Battle mode.
  
Updates as of 04/18/22:  
Fixed Folder Name from Curtian to Curtain. I'm a dork :D
Restructured things, now using methods and stuff. The game will now make a list of monsters to load from for when you encounter a roaming monster. Player now roams the wilderness. (Which is just the map from the previous version, that is based on the player seed.)  
Things are setup so that new modes can be added, multiplayer is coming "soon(TM)" (Planning on adding live multiplayer via Link Cable & Ghost Multiplayer, to load someone else's trainer you have saved to fight them that way too), A storage mode to save monsters & be able to trade them via Link Cable. We'll see how far I can get with those things.  
  
Updates as of 4/11/22:   
Fixed issue where items were not being loaded correctly, it only loaded the first item that was saved.  
Added numbers to item screen, to help show how many items the player has.   
Added text to tell the player they used an item.   
   
Updates as of 4/10/22:  
Rewrote the battle animation screen.    
Attacks will pick a bolt that goes across the screen based on the element type for the attack that was selected.  
Fixed maxFriends, so that you can't go above the max amount anymore.    
Had to lower monster count to 22 due to memory issues that comes up when loading a game with 5 monsters on your team, from the title screen.  
  
Updates as of 4/9/22:  
Changed up the combat math, trying to make it less swingy.  
  
Updates as of 4/8/22:  
Fixed - now the game will let you know that active monster doesn't have enough HP to fight, if in a fight it will tell you that it switched to another monster that has HP  
Added mutate animation ( That takes up too many lines :D )  

Updates as of 4/6/22:  
Added the ability to cycle up through select first monster/monster info/swap active screens.   
Changed the way the options menu checks for the correct selection.  

Updates as of 3/26/22:  
Fixed issue where the worldseed wasn't assigned to the player block and the game would always load the default 0 world  
If the world seed equals the default of '0' then the game will give you a new world seed.
Fixed scroller speed on opening screen  

Updates as of 1/19/22:  
Fixed issue where you could go above the max amount for some skills

Updates as of 1/14/22:  
Issue where there was not enough memory to load TMT from the thumby launcher on physical thumby. Moved images and attacks to their own ujson files in an attempt to fix this.
Fixed issue where there where two images named legs7. Changed name of Mind move to telekinesis from project rock. Added tmt.ujson save for ease of testing.

Updates as of 1/5/22:  
Changed some combat math s'more. I like it better now, but I still haven't been able to play it long enough to see what it might be like at higher trainer levels. I also added some visuals and more monster parts. I fixed some more things that I found that weren’t working as intended.

Updates as of 1/3/22:  
Changed combat math so that the potential for high agility monsters avoiding all damage, all the time, was hopefully removed. Added a couple of monster parts. Added some visuals to help with navigating the game. Rewrote some functions to be the same, they just take up less lines. Removed some errors that caused the game to break. Fixed some things that weren't working as intended.
