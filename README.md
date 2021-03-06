DayZ Scripts Collection
====================================
###### note: I am NOT the original author of all of these scripts. The reason I have these scripts here is that I have heavily modified a lot of these scripts and created others myself. It's my intent to give credit where it's due so I've tried to credit the original author where possible.

###All the files are packaged in one zip but you can add the scripts you want by following the instructions for each script.

-----

##FAST TRADING
#####credits: mudzereli -- inspired by Gr8boi
####This adds faster trading without an animation. Each trade takes one second and to cancel a trade you simply move just like normal. Since this is an overwrite and not an addon, it's very dependent on 1.0.5.1 files and will likely not work on other versions!
#####warning: doesn't work with config based traders
###Installation
 1. download the zip file
 2. create an **overwrites** folder in your mission file if you don't already have one
 3. copy the fast_trading folder from the **overwrites** folder in the zip file to the addons folder in your mission file
 4. add this line to the end of the bottom of your mission file init.sqf

```call compile preprocessFileLineNumbers "overwrites\fast_trading\player_traderMenuHive.sqf";```

-----

##PLOTBUFF
#####credits: mudzereli
####Plotbuff is an addon that is currently only used to remove zombies that are near plot poles
###Installation
 1. download the zip file
 2. create an addons folder in your mission file if you don't already have one
 3. copy the plotbuff folder from the addons folder in the zip file to the addons folder in your mission file
 4. edit the config.sqf file in the plotbuff folder of your mission file to your liking
 5. add this line to the end of your mission file init.sqf

```call compile preprocessFileLineNumbers "addons\plotbuff\init.sqf";```

-----

##BUILDINGS
#####credits: various -- see below
####This adds a ton of different buildings and better looking areas to the game
  * Ghost of Chernarus Map Pack (Charlatan)
  * NWAF Gas Station (Crankyfist)
  * Field Hospital (Crankyfist)
  * NEAF Barracks (mudzereli)
  * C130 Crash (Crankyfist)
  * Balota Overhaul (Ixxo)
  * NWAF Rework (oxygen220)

###Installation
 1. download the zip file
 2. create an addons folder in your mission file if you don't already have one
 3. copy the buildings folder from the addons folder in the zip file to the addons folder in your mission file
 4. optionally commment out any buildings you don't want loaded in init.sqf
 5. add this line to the end of your mission file init.sqf

```call compile preprocessFileLineNumbers "addons\buildings\init.sqf";```
 
-----

##CLICK ACTIONS
#####credits: mudzereli
####This is used to register right click actions on items. Required by other addons. Is an overwrite so only works with Epoch 1.0.5.1
###Installation
 1. download the zip file
 2. create an overwrites folder in your mission file if you don't already have one
 3. copy the click_actions folder from the overwrites folder in the zip file to the overwrites folder in your mission file
 4. add this line to the end of your mission file init.sqf **but before any addons that require it**
      
```call compile preprocessFileLineNumbers "overwrites\click_actions\init.sqf";```

-----

##TAKE CLOTHES
#####credits: Zabn
####This adds the option to take clothes from bodies. I have written in configuration options and some other things to Zabn's script.
###Installation
 1. download the zip file
 2. create an addons folder in your mission file if you don't already have one
 3. copy the takeclothes folder from the addons folder in the zip file to the addons folder in your mission file
 4. add this line to the end of your mission file init.sqf
      
```call compile preprocessFileLineNumbers "addons\takeclothes\init.sqf";```

-----

##SAFE ZONE
#####credits: Infistar
####This adds safe zones. I put this script here because the only other place I could find it is pastebin and I didn't want to lose it.
###Installation
 1. download the zip file
 2. create an addons folder in your mission file if you don't already have one
 3. copy the takeclothes folder from the addons folder in the zip file to the addons folder in your mission file
 4. add this line to the end of your mission file init.sqf
      
```call compile preprocessFileLineNumbers "addons\safezones\init.sqf";```