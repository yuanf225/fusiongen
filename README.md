Compatibility:

Extended_Armory_v2 till Extended_Armory_v2.2 - WOTLK,CATA and MOP(limited support)

Extended_Armory_v3_RC1 - MOP,WOD,LEGION,BFA


Installation:

**** FROM Extended_Armory_v2 till Extended_Armory_v2.2! ****

 1. Extract the contents of the archive usually on the desktop.

 2. Copy the contents of the folder Content into the root folder of your copy of FusionGEN, merge and replace all.
 
 3. Open the folder SQL from the extracted files from the module archive,
    in this folder you will find the data required for deferrent versions of wow, 
    choose the ones your realms run on and import them into the Fusion Database.
    Note: You can import all of them if you're not sure which ones you need.

 4. Clear your template cache.
 
 5. Clear your browsers cache.

 6. You are done.

**** FROM Extended_Armory_v3_RC1 and up! ****

 1. Extract the contents of the archive usually on the desktop.

 2. Copy the contents of the folder Content into the root folder of your copy of FusionGEN, merge and replace all.
 
 3. Open the folder SQL from the extracted files from the module archive,
    in this folder you will find the data required for the armory and import them into the Fusion Database.
    Note: You must import all of them in order to allow the armory to work properly!

 4. You must disable the FusionGen tooltip in order to the WoWHead tooltip to work properly.

	You can find it in the config/fusion.php
	--------------------------------------------------------------------------
	 Use FusionCMS tooltip system instead of WoWHead tooltips
	--------------------------------------------------------------------------
	
	 Put to false if you mainly have "blizzlike" items.

	$config['use_fcms_tooltip'] = false;

 5. Clear your template cache.
 
 6. Clear your browsers cache.

 7. You are done.

Changelog:

Extended_Armory_v3_RC1 changes

- Fetching all of the images from wowhead.
- Fetching tooltip from wowhead.
- Fetching item data from wowhead.
- Disabled fetching item_template for the items.
- Enabled caching for the mayor part.