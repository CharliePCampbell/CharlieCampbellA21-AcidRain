<!-- *** INTRODUCTION *** -->
<!-- *** QUICK START GUIDE *** -->
<!-- *** DETAILED START GUIDE *** -->
<!-- *** BASIC GAMEPLAY TIPS *** -->
<!-- *** WINNING STRATEGIES *** -->
<!-- *** PHILOSOPHY BEHIND THE MOD *** -->
<!-- *** APOLOGIES *** -->
<!-- *** CREDITS *** -->


<!-- ************* -->
- IMPORTANT: Only install this mod at the beginning of a new playthrough. 
- If you install it for a game you've already started, you'll get some weird behaviour, and it will likely ruin that playthrough.
<!-- ************* -->



<!-- *** INTRODUCTION *** -->
- As if the zombiepocalyse wasn’t bad enough, now you have to deal with acid rain. 
- Worse still, you have a condition that makes you feel the acid burn more than most folks, and your condition is getting worse every night. 
- Your only chance is to get the cure before it's too late. The Duke has it, but it will come at a cost.
- Goal: Complete up to five unique traders' missions to the tier level you agreed with the Duke (i.e. quest tiers 1, 2, 3, 4 or 5). Then, and only then, will he cure your pain.
- Collect clothing items along the way that offer some waterproofness. 
- When you complete each trader's quest tier, you'll receive an acid balm (which offers temporary acid rain invulnerability). 
- When you complete a quest tier up to the level agreed with the Duke, you'll also receive a hazmat item (which offers the best waterproofness).
- After a set number of days, the cure will be useless. Can you get it in time?


<!-- ************* -->


<!-- *** QUICK START GUIDE ***-->
- If you want to jump right in: 
--- Ensure the "CharlieCampbellA21-AcidRain" folder is in your 7dtd Mods folder. (Ensure that it's the folder that, when opened, you see the "Config" folder, etc inside).
--- Create a new playthrough, perhaps in Navezgane. 
--- If you prefer a new map, make it 6k (strongly recommended, but not essential). 
--- Note that for this mod to work, you'll need at least one hour of nighttime. 
--- Your goal is to do all five unique traders’ T1 quests in 18 days (this is the default challenge). 
--- Key tip: If you're burning, find cover from the rain and equip a torch, which allows you to dry off three times faster than without.
--- Key tip: If you're under cover and you want to know how hard it's raining before you step out, you can press F1 to access the console, then type "weather" and press enter. If the "rain" percentage is higher than your waterproofness, you'll burn in the rain. 
--- Key tip: Don't get discouraged if you're a bit behind schedule during the early game, because your character starts weaker, and you'll find yourself completing missions faster in the mid/late game.
--- Once you’ve completed your first playthrough (whether you win or lose), come back to reading this file in detail to learn about how to set new challenges within the mod, and customise it to your liking. 


<!-- ************* -->


<!-- *** DETAILED START GUIDE *** -->
<!-- HOW TO CHANGE THE BASIC CHALLENGE -->
- You can set the basic challenge by changing:
--- Unique Traders: The number of unique traders you'll be doing missions for (see the first section of the 'buffs' file). 
--- Cure Countdown: The number of days you'll have to complete the challenge ('buffs' file too).
--- Required Trader Quest Tiers: The level of quest tiers that must be completed for your specified number of traders, i.e. T1, T2, T3, T4 or T5 (see 'quests' file). 
--- For example, maybe you want the challenge to be completing all T2 quests for all five unique traders within 28 days.

<!-- GETTING THE LEVEL OF CHALLENGE RIGHT IS CRITICAL -->
- If you set the challenge too easy, the mod won't feel like it adds much value to your gameplay experience. 
- If you set it too hard, it might be frustrating. Yet if I had to choose, I'd prefer too hard over too easy. (I've found that even when I don't get the cure in time, it's still fun trying to survive with the challenge of being vulnerable to the rain). 
- I've gameplay tested this mod for 250+ hours, and I've noticed the following factors make for a challenging (and therefore fun) playthrough. 
--- An unfamiliar map: (Use the Random Gen Previewer to create a new map every time, so you never know where the traders are from the outset. The time taken to find them adds to the tension). 
--- The map's size: (6k is best, because you'll have fewer tradies, and thus will be less likely to complete most of your quest tiers in the easier biomes like the pine forest and the desert).
--- The Random Gen Previewer should have the number of towns set to 'default'. (More towns might mean more tradies, making the playthrough too easy). 
--- The map's biome percentages: (Ideally no more than 40% should be pine forest and desert combined, leaving 60% for the harder biomes. This way, you should ideally only get two traders in the easy biomes, and thus the other three will be in harder biomes).
    (Before you start your playthrough, you can check the Random Gen Previewer map to ensure there's at least one town in the pine and desert biomes, and ideally no more, as this is more likely to mean one tradie only for each of these easier biomes).
	(If you want to alter where the biomes are placed, see the "INCLUDING THE BURNT FOREST BIOME" section below).
--- Rainfall frequency: (I've upped most of the biomes' rainfall frequencies relative to vanilla. Try it on these default settings on your first playthrough, then tweak to your liking). 
--- Waterproofness of items: (I've tweaked the values to their current default settings based on plenty of playthroughs. It's designed to be challenging but fair).
- Signs that you've set the difficulty to a good level:
--- Ideally, you should have to do your last trader's missions in the wasteland, or at least in the snow biome. (If your map is such that you're finding most/all your traders in the pine/desert, then your playthrough won't be challenging/fun). 
--- Ideally, going into the final trader's quests, you shouldn't have been able to stockpile too many acid balms from your previous tradie quests. (e.g. If you have say eight acid balms going into that final trader's quests, the playthrough has been too easy. Perhaps you've been able to spend too much time in the easier biomes?).
--- Ideally, you should only have a day or two left when you finish all the required quest tiers and get the cure. If you had more days left, then on your next playthrough drop the number of days for more challenge and a tenser final few days. 

<!-- RECOMMENDED SETTINGS FOR EACH QUEST TIER CHALLENGE -->
- The following assumes you've selected all 5 unique traders:
--- T1 Quest Challenge: Cure Countdown of 18 days. Acid balm value of 1.00. Acid balm cost of $24k.
--- T2 Quest Challenge: Cure Countdown of 28 days. Acid balm value of 1.00. Acid balm cost of $24k.
--- T3 Quest Challenge: Cure Countdown of 42 days. Acid balm value of 0.80. Acid balm cost of $36k.
--- T4 Quest Challenge: Cure Countdown of 60 days. Acid balm value of 0.75. Acid balm cost of $48k.
--- T5 Quest Challenge: Cure Countdown of 100? days. Acid balm value of 1.00? Acid balm cost of $60k. (I haven't done playthrough tests on this particular challenge, so this line is just an educated guess). 
- How to find the above variables quickly: 
--- Quest challenge: 'quests' file. See first line of active code, and change the quest_tier number to 1, 2, 3, 4 or 5. 
--- Cure Countdown: 'buff' file. Search for "varCPCCureCountdown", and change the "value". 
--- Acid balm value: 'buff' file. Search for "varCPCAcidBalmSAReducer", and change the "value". (This is the amount of skin acidity you reduce each time you take an acid balm. The recommendations factor in how quickly you'll be completing quests relative to how many days you'll have been playing, and how long it takes to do each quest tier).
--- Acid balm cost: 'items' file. Search for "Acid balm cost variable", and change the "value" of the "EconomicValue" line. (This setting is perhaps less necessary, but will contribute to game balance if you're keen). 

<!-- INCLUDING THE BURNT FOREST BIOME -->
- If you want the fifth biome in your map, here's how:
--- Generate a map in the 7dtd Random Gen Previewer with max 20% pine forest, 20% desert, 20% wasteland, and 40% snow. Note the map's name. Keep the Random Gen Previewer available (don't select 'Back' yet). 
--- Using Windows Explorer, find the folder with the map (for me it's .../(my windows account name)/AppData/Roaming/7DaysToDie/GeneratedWorlds/(the name of the map))
--- Copy/paste the 'biomes' file so you have 'biomes - Copy' as a backup. 
--- Open 'biomes' (not 'biomes - Copy') in an image editor (I use GIMP), and colour half the snow biome in the burnt forest colour code (ba00ff). (Use the Pencil, not the Brush, to draw an outline, then the Bucket to fill in the middle with ba00ff colour code).
--- Pine forest (004000). Desert (ffe477). Burnt forest (ba00ff). Snow (ffffff). Wasteland (ffa800).
--- Use the colour picker to ensure that there are only these five colours on the map, and not a blend of two colours, for instance where you painted the burnt forest over the snow biome (otherwise I've found the entire map is drawn as wasteland!).
--- Refer to the Random Gen Previewer to get a sense of where the towns are relative to the burnt forest biome you're creating, and aim to have at least one town in the biome. 
--- For extra difficulty, ensure that the snow biome is between the pine and desert biomes, which will force you to traverse this harder biome early on when your waterproofness is low. 
--- If you're using the GIMP image editor, when you're happy with your map, select ‘Export As’, ‘Export’, ‘Replace’, and then ‘Export’ and to keep it as a png file. You can then close GIMP and select ‘Discard changes’ (because the file has already been exported).
--- On the Random Gen Previewer, select 'Back', and the start a new game, and select the map name you've created. 

<!-- CUSTOMISATION -->
- This mod is designed to be very customisable for the sake of replayability. 
- Explore the variables in the opening sections of the 'buff' and 'quests' files (and to a lesser extent the 'biome' and 'trader' files) to see what you can customise. 
- The 'buffs' file gives thorough details on how to customise your playthrough, so start there first. 
- I've provided plenty of comments in case that's handy when you're wanting to customise. 


<!-- ************* -->


<!-- *** BASIC GAMEPLAY TIPS *** -->
<!-- Staying dry -->
- If your wetness exceeds your waterproofness, you will feel the acid burn, and you'll take damage. 
- So be wary of the rain, and also puddles/lakes/rivers, etc. 
- Even when you're inside a POI, be aware that some blocks allow water through the ceiling (hatches, horizontal windows, etc). 
- Also, sometimes water will come through solid blocks if you have your head too close. So avoid attic spaces when it's raining too heavily outside. 
- Beware: Exiting the game removes any applied acid balm buff (i.e. invulnerability to the rain). 
--- So if it's raining heavily and you're relying on acid balm protection, find cover and ensure your wetness percentage is below your waterproofness before exiting the game, otherwise you'll be burning when you rejoin.

<!-- Getting dry -->
- If you're wet and are feeling the acid burn, either: 
--- Apply acid balm (this gives you 15mins of invulnerability).
--- Find cover and equip a torch (this allows you to dry off three times faster than without).

<!-- Weather report: Using the console command "weather" -->
- Sometimes you'll be sheltering from the rain under cover, and you'll want to know how rainy it is vs your waterproofness, and thus whether you can step outside without fear of being burned. 
- Use the console command by pressing F1, then type weather, highlight it and type Ctrl+C so you've got it copied. 
- From now on you'll be able to get a quick weather report by selecting F1 then Ctrl+V and Enter. 
- Avoid stepping out from cover until "rain" or "snowfall" drops below your waterproofness. (NB: The "wet" and "snow" numbers aren't a factor).


<!-- ************* -->


<!-- *** WINNING STRATEGIES *** -->
<!-- Before you read this section -->
- IMPORTANT: Half the fun is in the learning, right? 
- It's recommended that you only read this section if you've done a few playthroughs and you're struggling to win.

<!-- Staying dry -->
- Learn how to spot when it might rain. If the wind picks up, or the clouds get dense and the day's light drops, best head for some cover until you can give the all clear. 
- When the light dims, use the console command "weather" to check the cloud percentage. Heavier clouds are sometimes the precursor to heavy rain. 

<!-- Getting dry -->
- Do you really need to take that acid balm? 
--- Acid balms are rare, and can get you out of a tight spot (i.e. a hoard shows up and you need to leave your cover asap, or you need to travel between towns (i.e. away from quick cover) and the rains start).
--- A better option might be to take a first aid kit or two, and then run through the rain to safer cover.
--- Apply the first aid kit as soon as you start to burn, as time can be a real factor. 
--- Keep an eye on your health meter. Take painkillers if needed for an instant health boost. 
- Stockpile your acid balms if possible during your early game in the pine and desert biomes, as you'll be using them more in the late game in the snow and wasteland biomes. 

<!-- Staying not dead -->
- Over time, your skin acidity value will rise (this is the damage you take per 2.5 seconds).
- Once your skin acidity reaches 8+, you might find your damage taken outpaces your first aid. 
- Spec heavily into "Physician", up to level 3, i.e. "Surgeon", if you can. This increases the rate of healing, which keeps up with your skin acidity damage rate (which can get pretty high after a while and in some biomes). 
- Keep beers, blood bags and sewing kits, which are the key ingredients for making first aid kits. 
- Always have a first aid kit handy! 
- At some point, perhaps at around 12+ skin acidity or so, even being spec'd into Surgeon might not be enough to keep up with the damage rate, but at least the above approach will have preserved some of your acid balms when you reach this point. 

<!-- Increasing your waterproofness -->
- Prioritise finding the right clothing items: When in the game, read the Waterproofness buff description, which shows which items have waterproofness values. Learn where best to find each type of clothing (laundries, Savage Country stores, etc). 
- Hazmat gear: 
--- The likelihood of finding hazmat gear in loot has been strongly nerfed (though not impossible, particularly from Day 40 onwards), and the cost of buying it at the traders has been made expensive (particularly for the higher tier items). 
--- This makes the reward of completing a unique traders' required quest tier all the more satisfying and important (yet it also leaves room for the 'yay!' moments when you sometimes find them elsewhere). 
--- There is a chance that at the end of a trader's total required quest tiers, they will reward you with the same hazmat gear that you already have. This risk is intentional. It adds anticipation when going to the trader to hand in your final mission for that tier. 
--- This is also intended to add to the challenge and the variability/playability long term. 

<!-- Finding all the unique traders in time -->
- Ideally, you'll be given the exact location of the next new trader when you complete their tier quests (via "Opening Trade Routes"). 
- But sometimes you'll just need to go looking, which is very time consuming given you're racing against the clock. 
- Spec heavily into Grease Monkey to get the minibike as quickly as possible so you can get around the map a little easier. 
- If you're searching for the next tradie, stick to the main roads, as they're almost always to be found in towns, which are linked by main roads. 


<!-- ************* -->


<!-- *** PHILOSOPHY BEHIND THE MOD *** -->
<!-- A broader goal -->
- 7dtd is easily my favourite game. Yet while it's fun at say Day 70, nothing beats the compelling first week or two. 
- In the early game, your focus is on survival "must-haves" for your character, which is intense (i.e. "heaps of fun"). 
- But by the mid game, your focus shifts to "nice-to-haves", which further increase the survivability of your character, but these improvements feel less critical. 
- So while the mid and late games are still fun (the sense of power of a T6 M60 is good times), you don't feel as threatened anymore, so the game loses some of its compulsion.

- This Acid Rain mod is designed to extend that sense of compusion into the mid/late game.
- If you don't complete the quest tiers in time, the Duke's cure will be useless. So it's effectively a race against time. 
- The vanilla version is great for its openness, in that the player can do whatever they want. 
- This mod sacrifices a bit of that openness in exchange for maintaining the sense of tension beyond the early game. 
- Yet despite the mod's restrictions, the player still has plenty of freedom of choice in how to achieve the ultimate goal of getting that cure in time. 

<!-- Tension through conflicting priorities -->
- "Should I stay or should I go now?" 
--- On the one hand, it's a race against time to complete the quest tiers.
--- Yet it's now dangerous to stray too far from buildings (i.e. convenient cover) without any acid balm. 
--- You might want to ration your use of acid balm, which can mean waiting under cover a few in-game hours for the rain to pass before you venture out again to pursue those quests. 
--- But watching the clock tick when you know you've got only so much time to complete the quest tiers gets tense, and can make for tricky decisions (which is fun!). 

- I recommend installing Khaine's Wandering Horde Patch. (See: https://community.7daystodie.com/topic/32007-khaines-a21-modlets-bigger-backpacks-lockable-slots-behemoths-random-wandering-hordes-etc/)
--- I like to crank up the frequency of wandering hordes, and their size. 
--- Normally in vanilla, if a massive horde shows up when you're raiding a POI, you've always got the option of bravely running away! 
--- Yet with this Acid Rain mod, if it's raining heaps outside and you don't have any acid balm handly, you might feel compelled to hold the fort!
--- It gets pretty intense when you're on the ground floor, and you can hear too many zombies beating on all the doors and windows around you while you desperately try to fight them off. 


<!-- ************* -->


<!-- *** APOLOGIES *** -->
- Note to players with localization in languages other than English: Some waterproof items might not display their description correctly, and if so, I’m unsure how to fix this sorry. 


<!-- ************* -->


<!-- *** CREDITS *** -->
- Khaine: I was inspired to create this mod after playing Khaine's DeadlySun mod, which was showcased by the irrepressible Jawoodle in his Inferno series. This is my first mod, and I've learned lots by seeing how Khaine wrote DeadlySun and other mods. 
- Dough: I checked out Dough's PunishingWeather mod for a sense of how to tweak the rainfall/snowfall. 
- Max Fox: Before diving into writing this mod, I first checked out Max's excellent YouTube tutorial series for beginners in XML modding for 7dtd. (See: https://www.youtube.com/playlist?list=PLfY-5aBkL7v_AAtm1TWEyKhAYb5RI828p).
