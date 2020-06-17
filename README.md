This is the extended armory for FusionGEN.

Installation:
 1. Extract the contents of the archive usually on the desktop.

 2. Copy the contents of the folder Content into the root folder of your copy of FusionGEN, merge and replace all.
 
 3. Open the folder SQL from the extracted files from the module archive,
    in this folder you will find the data required for deferrent versions of wow, 
    choose the ones your realms run on and import them into the Fusion Database.
    Note: You can import all of them if you're not sure which ones you need.

 4. Clear your template cache.
 
 5. Clear your browsers cache.

 6. You are done.
 
 For V3 RC1:
 - You need to set this to false to use wowhead tooltip in fusion.php in your config folder.
 
 /*
|--------------------------------------------------------------------------
| Use FusionCMS tooltip system instead of WoWHead tooltips
|--------------------------------------------------------------------------
|
| Put to false if you mainly have "blizzlike" items.
|
*/
$config['use_fcms_tooltip'] = false;
