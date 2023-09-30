    ____  __ ___________      ______      __                           
   / __ \/ //_/ ____/__ \    / ____/___  / /__________ _____  ________ 
  / / / / ,< / /    __/ /   / __/ / __ \/ __/ ___/ __ `/ __ \/ ___/ _ \
 / /_/ / /| / /___ / __/   / /___/ / / / /_/ /  / /_/ / / / / /__/  __/
/_____/_____\____//____/  /_____/_/ /_/\__/_/  _\__,_/_/ /_/\___/\___/ 
      / __ \____ _____  ____/ /___  ____ ___  (_)___  ___  _____       
     / /_/ / __ `/ __ \/ __  / __ \/ __ `__ \/ /_  / / _ \/ ___/       
    / _, _/ /_/ / / / / /_/ / /_/ / / / / / / / / /_/  __/ /           
   /_/ |_|\__,_/_/ /_/\__,_/\____/_/ /_/ /_/_/ /___/\___/_/            
                                                                       

   ____        _      __      _____ __             __ 
  / __ \__  __(_)____/ /__   / ___// /_____ ______/ /_
 / / / / / / / / ___/ //_/   \__ \/ __/ __ `/ ___/ __/
/ /_/ / /_/ / / /__/ ,<     ___/ / /_/ /_/ / /  / /_  
\___\_\__,_/_/\___/_/|_|   /____/\__/\__,_/_/   \__/  


https://www.romhacking.net/utilities/1487/

"Randomize All" generates a seed completely at random for you. This does not take into consideration any options you pick. To use your chosen options, choose the "Randomize" button. All of the options are mostly self-explanatory. If you would like more elaboration, please continue reading. 

You need a U 1.0 version of DKC2 for this.

Gameplay:
There are a couple of gameplay changes. One big one is the inclusion of auto-saves. You can reset at anytime and the bosses you beat are remembered. Most coins can be collected once. Most notably, is the ability to go to Funky or Cranky at any time. To do this, while paused press L to go to Cranky and R to go to Funky. Leaving either will take you back to your last checkpoint. Funky has the option to bring you back to 1-1 for a small price. The big difference to resetting is this keeps your checkpoint. Cranky can offer paid hints. Careful! Cranky still wants this game to be about him so the 'Free' hints may not always portray what they seem.
The goal is still to beat enough bosses and then beat K Rool. To help you keep track of which bosses you beat and which world you are in, there are trackers built in to the HUD.

   ________                                          ____
  / ____/ /___  ______________ ________  __   ____  / __/
 / / __/ / __ \/ ___/ ___/ __ `/ ___/ / / /  / __ \/ /_  
/ /_/ / / /_/ (__  |__  ) /_/ / /  / /_/ /  / /_/ / __/  
\_______\____/____/____/\__,_/_/   \__, /   \____/_/     
 /_  __/__  _________ ___  _____  /____/                 
  / / / _ \/ ___/ __ `__ \/ ___/                         
 / / /  __/ /  / / / / / (__  )                          
/_/  \___/_/  /_/ /_/ /_/____/                           
                                                         
	- ROM: Read Only Memory (the format all games are in)
	- Seed: A number that represents the result of randomization. If two ROMs have the same seed, the results will be identical.
	   A technical definition is "A random seed (or seed state, or just seed) is a number used to initialize a pseudorandom number generator."
	- Logic: Another randomizer term. Logic ensures the seed is completable.
	- Exit: A way to exit the current stage you are in. NOTE: This is not an exit randomizer! Exit examples: 1-1 exit, 1-1 bonus 1, 1-1 bonus 2, 1-1 warp, 1-1 K Rool's cabin
	- Entrance: Any entrance to a stage. A bonus exit leads to a stage entrance. Entrance examples: 1-1 start, 1-1 from bonus 1, 1-1 from bonus 2, 1-1 from warp, 1-1 from K Rool's cabin
	
This is an entrance randomizer. What this means, is the entrances from each exit are randomized. There are a few types of exit. Bonus exits, level exits, game intended warps, etc. This game ends up being a puzzle, now. As is mentioned, the goal is to beat the number of bosses you decide and K Rool.

	
This program takes a DKC2 ROM, randomizes it, and creates a new ROM for you. This program accepts only a U 1.0 version of this game. An error will be thrown if you provide anything else. Also, you may wonder about the extention of your ROM. You could have either an sfc or smc. sfc is the standard/official (Super FamiCom) ROM, and shouldn't have a 512-byte header at the beginning of the file. smc is an unofficial but popular extension (Super MagiCom, a copier), and will probably have a 512-byte header at the beginning of the file. In this case, this program accepts both sfc and smc, ie. Header vs headerless is not important.


   __  __     _                ________    _     
  / / / /____(_)___  ____ _   /_  __/ /_  (_)____
 / / / / ___/ / __ \/ __ `/    / / / __ \/ / ___/
/ /_/ (__  ) / / / / /_/ /    / / / / / / (__  ) 
\____/____/_/_/ /_/\__, /    /_/ /_/ /_/_/____/  
                  /____/                         
BEFORE USE
It is recommended that you place the DKC2 ROM in its own folder (example: https://imgur.com/a/gqbVqD6), as the program will generate many extra files alongside it.

You can hover over each option to get a quick description.

Logic: Ensures that the seed (the unique result of randomization) allows the game to be completed.
Easy Logic avoids any necessary backtracking within levels. You can still go backwards to find other exits, but it will not be required.
Hard Logic does not consider direction Backtracking may be necessary.
No Logic has zero restrictions, so the game may not be possible to finish.

Enemy Randomizer:
Default keeps enemies the same as in the regular game.
"Randomized" changes the enemies that appear in each stage. Enemy location is the same, but the type of enemy is random.
Walking off-screen and returning will cause enemies to change again. Enemy randomization does not affect the seed.

Music can also be randomized. This causes buggy sound effects in some levels.

Color select allows you to change the color of the Kongs' clothing, as well as Dixie's hair. Custom allows you to choose from a color wheel.

Bosses: Determines the amount of bosses that must be defeated before K. Rool appears. Increasing the amount also increases the cost of hints from Cranky.

Checkpoint Style:
Barrels (Standard) does not create any checkpoints other than at checkpoint barrels.
Entrance + Barrels creates a new checkpoint whenever you go enter a new area.

Kong Number:
"Force 2" gives you both Kongs whenever you enter a new area.

Enter Custom Seed: this allows you to choose a specific seed, so that you may coordinate randomizer results with others.
The Customize button modifies the ROM with the chosen seed number. Randomize modifies the ROM with a random seed.
Finally, we have the 'Randomize All' button. This randomizes both the seed and the options.

Click the 'Customize', 'Randomize', or 'Randomize All' button sets up the folder you set up before like this: (https://imgur.com/a/y2B47l3)



    __  ___       __      
   / / / (_)___  / /______
  / /_/ / / __ \/ __/ ___/
 / __  / / / / / /_(__  ) 
/_/ /_/_/_/ /_/\__/____/  
                          
There are 3 main 'types' of hints. There's free hints, paid hints, and a big K Rool hint. 
Free hints could be helpful, but have a possibility of not being helpful. Anything goes with these hints. If your hint is of the style 
	"I once heard from {name} that {stage} was important.";
this means that that stage is in the spoiler log somewhere.
Next we have paid hints. These are always helpful, to a degree. There are two styles. positive hints and negative hints. All the hints mean what they seem.
Finally, there is the super specific expensive hint. This hint tells you which stage K Rool is in.

   _____ __        __          ____                 
  / ___// /_____ _/ /______   / __ \____ _____ ____ 
  \__ \/ __/ __ `/ __/ ___/  / /_/ / __ `/ __ `/ _ \
 ___/ / /_/ /_/ / /_(__  )  / ____/ /_/ / /_/ /  __/
/____/\__/\__,_/\__/____/  /_/    \__,_/\__, /\___/ 
                                       /____/       
After finishing, a stat page is displayed. first thing displayed is your total time. This time includes all time spent sitting in Cranky, Funky, or on the title (after you start the game). This time does not include the time between stages, so this is more like how DKC does in game time. The next 2 are fairly self-explanatory. There is 137 unique entrances in the game. This tracks how many of them you found. The next one designates how many you found total. Last 2 fairly obvious.


    __ __                              __                    
   / //_/____  ____ _      ______     / /_  __  ______ ______
  / ,<  / __ \/ __ \ | /| / / __ \   / __ \/ / / / __ `/ ___/
 / /| |/ / / / /_/ / |/ |/ / / / /  / /_/ / /_/ / /_/ (__  ) 
/_/ |_/_/ /_/\____/|__/|__/_/ /_/  /_.___/\__,_/\__, /____/  
                                               /____/        
	- There is a serious problem with lag. This is due to SNES hardware limitations. There is nothing I could do about this, short of severely limiting enemy sprite pools as well as moving assets. There is something YOU can do to combat this though. Kill as many enemies as possible.
	- Exit won't spawn (sprite overload). Due to limitations, there is a limited amount of sprites available. Exits are sprites themselves. Because of this, all slots may still be filled with other sprites, not allowing the goal (or other exits) to spawn. Once again, kill as many enemies as possible to avoid this.
	- In your travels, other things may not appear for you. Squitter may also refuse to spit more platform webs for you, or Squawks may gag instead of shoot. While this is funny, only killing enemies will fix this.
	- There is a nasty bug where if you have a different song than the original in Rambi Rumble or Screech's Sprint, the game could crash on you. For now, I just ensured the proper tracks play there.
	- Similarly, the end of level fanfare is part of the track. Bosses don't have this, so you just crash. I forced you never to have boss music in places other than bosses.
	- A random tile glitch Dna found. This is not game breaking and not repeatable, therefore, there is nothing I could do about this. Just do a quick start select to repeat.
	- A game crash found by Otakuroi. This has nothing to do with my code. Rather, this is a DKC2 glitch that rarely occurs when multiple things are happening that shouldn't. You should kill things to avoid this, but should this happen, you will lose no progress.

   ______              ___ __      
  / ____/_______  ____/ (_) /______
 / /   / ___/ _ \/ __  / / __/ ___/
/ /___/ /  /  __/ /_/ / / /_(__  ) 
\____/_/   \___/\__,_/_/\__/____/  
                                   

This is in no particular order.
Thank you:

Pichi - For playtesting this and consult.

Fathlo - For playtesting this and consult.

Sch1ey - For playtesting this and creating a tracker for this and just general tips.
https://docs.google.com/spreadsheets/d/1ozKksgyz4QKIhEqFHJShy7zaGCSGl1Kr6IBtIOKNmIA/edit?usp=sharing

V0oid - For being one of the main influences on this and providing me a list of every enemy to be in the randomizer pool.

Lumophile - For ideas and consult.

DustPan - For playtesting and being patient with bugs.

Emptysys - For teaching me colors and consult.

Jermro - For being the first ever to complete a run of this.

Tompa - For being Tompa (a positive, nice, patient person who always supports me and is great to be around).

Zera - For letting me use their name for Cranky hints.

DLB - For letting me use their name for Cranky hints.

SilentWolf - For letting me use their name for Cranky hints.

Otakuroi - For playtesting.

SuperStarNuggets - For playtesting.

OronJoker - For inspiring me to add 2p team to this.

DNA - For playtesting this.

Bluebeary - For playtesting this.

The DKC Science discord - For helping me with ram.

The DKC_Hacks discord - For playtesting this.



   _____                 _       __   ________                __       
  / ___/____  ___  _____(_)___ _/ /  /_  __/ /_  ____ _____  / /_______
  \__ \/ __ \/ _ \/ ___/ / __ `/ /    / / / __ \/ __ `/ __ \/ //_/ ___/
 ___/ / /_/ /  __/ /__/ / /_/ / /    / / / / / / /_/ / / / / ,< (__  ) 
/____/ .___/\___/\___/_/\__,_/_/    /_/ /_/ /_/\__,_/_/ /_/_/|_/____/  
    /_/                                                                

Snakpak
Seriously helped me with editing how Kongs look in the longrun. Put in a serious amount of work. Also very serious.
Has been a great support through it all.

P4plus2
Extremely knowledgeable about DKC2. I couldn't have done this without him! 

Myself086
I don't know where to start. None of this would be possible without him, the use of his assembler, emu, and C# skills he passed on along the way. Honestly, his name should be on this, not mine.
