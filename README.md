- - - - Delmod A17 Modlet Collection - - - - 

This is currently a set of modlets that I have thrown together to provide some sensible quality improvements, and add a few more items to the game. The usual disclaimers and rules apply. 

I created this for my own personal use among my tribe. These Modlets are very much "works in progress" and will be updated and/or improved and added to as my time allows and as I am able. Of course, additions. corrections, and suggestions are ALWAYS welcome. 

The following individuals I would like to credit right now: sphereii , Guppycur , stedman420 , KhaineGB , stallionsden , and others for code examples, tutorials, etc. If you are not credited here it is because I can not remember what I used of yours. However, I am sure I will credit more people here as time goes on and as I borrow more of other people's code.  

Delmod Kitchen - Working Sinks and Stoves that can be crafted

	Working Granite Sink
	Working Sink
	Working Oven
	Working Stove

	All can be crafted at Level 1 of Advanced Engineering
	The Stove and Oven operate like the Campfire but they do not require fuel.
	The Sinks fill empty bottles with murky water by right mouse clicking on the sink with the bottle in your hand.

Delmod Pack & Store - Larger Backpack (60) and Larger Storage Containers

	Increases Backpack to 60
	Increases Gun Safe, Refrigerator, Cabinets to 72
	Increases Desks, nightstands, Lockers to 48
	Increase Bookcase, Medical Cabinets, Pill Case to 36


Delmod Recipes Fix - Changed some of the recipes.

	Dropped the meat requirements on most recipes to 1 instead of 10.
	Added quantity 5 stews using less ingredients
	Modified the Medical Kit recipe to require antibiotics instead of a blood bag and added an additional Medical Kit recipe
	Added a Bottle of Acid recipe
	Added a Hardened Chest recipe
	Added Beaker recipe
	Added Solar Cell and Solar Bank recipe
	Added Log Spikes recipe

	More recipes will be forthcoming as I am able,...

Delmod Stack Sizes - Changes several item item stack sizes

	Doubles the ammunition stack size
	Changes stack size for several resources, food items, drink items, drugs and medical items.

	Click on the Github download link to see a detailed list of all stack size changes.

Delmod Startup Packs - New Startup Packs

	Adds bug out bags to your new character at the beginning of the game. These packs contain randomly generated clothes, weapons, and other survival type gear you might commonly find in a bug out bag.
	Set the bags on the ground and punch them to open them.
	
Delmod Combiner

	Adds combiner function back to the game.  
	This provides the ability to combine two like objects into a single better quality object.  
	The combiner is accessable via the Workbench and Vehicle Storage

Delmod Archetypes - Added one new Del Stryker archetype

	This is just an example of how to create additional archetypes to use within the game.


Installation

These are all xpath Modlets. Therefore, the modlet folder needs to reside within your "7 Days To Die\Mods" folder. 
This is typically located here: "C:\Program Files (x86)\Steam\steamapps\common\7 Days to Die\Mods"

If the "Mods" folder does not exist within your "7 Days to Die" folder, simply create the "Mods" folder. 

Extract/Copy the modlet folder into your "7 Days To Die\Mods" folder. 

Example: "C:\Program Files (x86)\Steam\steamapps\common\7 Days to Die\Mods\Delmod_Kitchen"


Localization.txt File

The localization.txt file is not processed as an XML file, of course. Therefore, if a localization.txt file is included in the modlet you want to use, you will need to please append this file to the end of your current localization.txt file. 

First, please make a backup copy of your current localization.txt file to something like localization.txt.bak. This file is located in your "7 Days To Die\Data\Config" folder. 

Then copy the contents of the new localization.txt file into the end of your current localization.txt file in your "7 Days To Die\Data\Config" folder.

Easy Method Using Localization Appender

This can more easily be done with the included "Localization Appender" which I first saw posted by Jereth_Khan 

It is a batch file named "Localization.bat" that you can launch from within the Modlets "Config" folder. 

Follow the onscreen directions and it will create a backup of your existing localization.txt file and then append the modlets data for you.

These all currently work in Single Player and MultiPlayer mode. 
For MP they are only required on the Server side and not required on the client side.
