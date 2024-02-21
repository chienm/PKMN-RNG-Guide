# Pokemon Generation 6 Fishing RNG for Pokemon XY and ORAS

### Tools needed
* [3DS RNG Tool](https://ci.appveyor.com/project/Bambo-Rambo/3dsrngtool/build/artifacts) (Latest Version)
* [Tiny Finder](https://ci.appveyor.com/project/Bambo-Rambo/tinyfinder/build/artifacts) (Latest Version)
* [Pcalc G6](https://gbatemp.net/threads/pokecalcntr-for-gen-6-the-rng-tool-suite-for-the-3ds.473221/) (Old and New 3DS, 3DS XL, 2DS, and 2DS) or [CitraRNG](https://github.com/Admiral-Fish/CitraRNG/releases) (3DS Emulator)

### Quick Note

Even though it is possible to RNG fishing in generation 6 Pokemon games, I would highly recommend using the DexNav if you are planning to hunt in Pokemon ORAS if the Pokemon can be obtained using surf first. This does not apply to Pokemon that can only be fished. For information on how to RNG DexNav in Pokemon ORAS, I would recommend reading Bambo-Rambo's DexNav RNG guide [here](https://github.com/Bambo-Rambo/RNG-Guides/blob/main/DexNavRNG.md#dexnav-rng-abuse-guide). Alternatively, I would also suggest doing Egg RNG.

In generation 6, along with the seed of a given frame, a secondary set of seeds, called TinyMT, is used to determine some parts of a Pokemon when encountering a Pokemon, including the species, level, and held item. This guide is for those who understand how to RNG in Pokemon XY and ORAS, and have a basic understanding of TinyMT, how to advance TinyMT frames, and how to use Tiny Finder and 3DS RNG Tool. For a more in-depth explanation, I would recommend reading Bambo-Rambo's RNG guide that goes more into depth [here](https://github.com/Bambo-Rambo/RNG-Guides/blob/main/NormalWild-FS-RNG.md).  For a quick run-through, the following is a reminder of the different ways of advancing TinyMT frames.

Within the bag...
* Turning on/off the EXP Share = 3 * [Number of Pokemon in Party] TinyMT index advancements (E.g. 6 Pokemon = 18 TinyMT index advancements, 5 Pokemon = 15 TinyMT index advancements).
* Reject teaching a TM to a Pokemon by immediately pressing `B` on the move selection screen = 1 TinyMT index advancement.
* Exiting the bag to the `X` menu and entering the bag again immediately = 16 TinyMT index advancements (ORAS Outside of Caves), 28 TinyMT index advancements (XY Outside of Caves), **OR** 4 TinyMT index advancement (Caves)

To advance hundreds or thousands of TinyMT indexes...
* Use Pokemon-Amie to advance hundreds of indexes quickly (Be sure to have 0 people in your PSS).

### Introduction

This guide will teach you how to RNG fishing in Pokemon XY and ORAS. For this guide, I will be explaining the steps that were taken to make this guide using Pokemon Alpha Saphire on an old 3DS XL as an example. The same steps can be taken for Omega Ruby and XY.

### Things to Keep In Mind

Before you start fishing, here are some tips that should be considered to make your hunt easier.
* For those shiny hunting, having a Shiny Charm will help getting more shiny frames.
* To increase the possible TinyMT index when finding the index of the Pokemon you are looking for, have a Pokemon with the ability Suction Cups or Sticky Hold in the front of your party. This is not possible if you are planning to Synchronize the Pokemon's nature.
# Steps
### Step 1: Setting Up.

Choose a Pokemon that you will be hunting for in Pokemon XY or ORAS. Go to the location where the Pokemon can be fished at and stand in the location where you will be fishing, either on land or on your surfing Pokemon. Once you are at your fishing location, go into your bag. If the Pcalc GUI is not present, press `Select` + `D-pad Up` to bring up the Pcalc GUI.

![](https://github.com/chienm/PKMN-RNG-Guide/blob/main/Images/Images/4a.jpg)

It is wise to have a chain of 2 or 3 by fishing and KO Pokemon to prevent delay issues if you are going for shiny Pokemon.

### Step 2: Choosing Your Target TinyMT Index in Tiny Finder.

After connecting your 3DS to 3DS RNG Tool first, connect your 3DS to Tiny Finder. Select your game in the Game dropdown and select `Fishing` in the Method dropdown. Select the location you are hunting in the Location dropdown and the rod that will be used in the dropdown next to the Location dropdown. If you are using Citra emulator, check the Citra box. If you are looking for a specific Pokemon, select the Pokemon in the Species dropdown. If you are using Suction Cups, change the number in the Ratio box to `98`. If you are using Synchronize to synchronize the Pokemon's nature, check the Sync button. In the number box for Party, type in the number of Pokemon currently in your party. Once your desired preferences have been set, press the `Update` button.

Once you have selected the Index you are after, carefully advance your target index forward until your target index reaches 0. Be sure to press `Update` to update Tiny Finder after each index advancement.

![](https://github.com/chienm/PKMN-RNG-Guide/blob/main/Images/Images/1.png)

### Step 3: Finding Your Shiny Frame in 3DS RNG Tool.

In your game, press `A` to select the rod you will be using and pause the game by pressing `Start` and `Select` once you have selected a rod.

![](https://github.com/chienm/PKMN-RNG-Guide/blob/main/Images/Images/4.jpg)

When you have paused your game, open up 3DS RNG tool. In 3DS RNG Tool, select the Wild RNG tab and change the Category dropdown to `Fishing` in the Wild Encounter Setting section. Select the rod you are using in the Pokemon dropdown. If you are using Synchronize, select the nature you are synchronizing in the Sync Nature dropdown and select the Assume Synced button. If you are using Suction Cups, select `Suction Cups | Sticky Hold` in the Lead dropdown. If the Pokemon you are having has a gender ratio other than 1:1, select the correct ratio in the Gender Ratio dropdown. For redundancy, select the location where you are hunting and your target Pokemon in the Location and Slots dropdowns. If you have a shiny charm, check the Shiny Charm box on the top right of the window.

In the Filters section, if you are looking for Pokemon with specific IV's, input the IV's values in each of the stats. If you are looking for a shiny Pokemon, check the Shiny Only box.

In the RNG Info section, input your current frame that you paused on in the box under "Frame Range". Next to Consider Delay, type in the delay of your index from Tiny Finder to into the box. If you do not type in the correct delay, you will not land on the frame that you are targeting.

![](https://github.com/chienm/PKMN-RNG-Guide/blob/main/Images/Images/2.png)
![](https://github.com/chienm/PKMN-RNG-Guide/blob/main/Images/Images/3.png)

Once you have filled in all of the information into 3DS RNG Tool, press Calculate and pick out a frame that you are going to target.

### Step 4: Advancing to Your Target Frame.

In your game, press `Start` or **TAP** the `A` button to resume the game. Once you are close to your target frame, pause the game again by pressing `Start` + `Select`. Press `Select` to go frame by frame until you reach your target frame. Be sure you have the rod you are using selected and the cursor selecting the `USE` button.

![](https://github.com/chienm/PKMN-RNG-Guide/blob/main/Images/Images/5.png)
![](https://github.com/chienm/PKMN-RNG-Guide/blob/main/Images/Images/4b.jpg)

### Step 5: Encounter.

Once you have reached your target frame, **PRESS AND HOLD** the `A` button to resume the game **AND** use the rod. Taping the `A` button will only resume the game in generation 6 Pcalc. Wait until you get a bite.

Press the `A` button when your fishing line gets a bite to reel in the line.

![](https://github.com/chienm/PKMN-RNG-Guide/blob/main/Images/Images/6.png)

### Step 6: Profit.

If everything is done right, you will have hit your target frame.

![](https://github.com/chienm/PKMN-RNG-Guide/blob/main/Images/Images/7.png)

# Bambo-Rambo Tips
* "DexNav fishing is only possible with the Search function which, currently is not supported by public tools. Pure fishing is the way to go here"
* "Building a small chain beforehand (2-3 KOs) solves the delay issue if going for shinies"

# Personal Experiences

* You are most likely not going to get your target on the first try. From my many tests, I was able to get my target first try twice, twice on the third or fourth attempt, and the rest on the second attempt. It took 2 attempts to get the shiny Gyarados at Sootopolis City for the pictures for this guide. During my test at Sootopolis City, however, it only took 1 attempt to get a shiny. So don't worry if you don't get a shiny on your first try. Following Bambo-Rambo's tip of building a chain of 2-3 should solve this issue.
* This might just be me, but I had an easier time RNG fishing in Pokemon Y than in Alpha Saphire.
* In my attempts while testing for this guide, I have tested RNG fishing at every location listed in the Locations dropdown in Tiny Finder in Pokemon Alpha Saphire. Out of all of the locations, I was able to get a shiny Pokemon in every location except Lilycove City, Meteor Falls, Route 119, and Route 123. I don't know if I was just unlucky, but I attempted to shiny hunt at those four locations at least twice on separate occasions but was unable to get a shiny Pokemon. Lilycove City was impossible for me after 2 separate failed Staryu RNG fishing hunts on top of the attempts for this guide. Following Bambo-Rambo's tip of building a chain of 2-3 should solve this issue.
* Don't forget to input the correct delay from Tiny Finder to 3DS RNG Tool. I had multiple attempts where I failed because I forgot to type in the delay for the TinyMT index I was going for.
