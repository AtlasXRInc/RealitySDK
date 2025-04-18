# Test a mod

!!! note

    The build / run process will be improved in next versions

To test a mod, be sure you are using the dev channel of the game (see prerequisites)

## Cook

Select `Platform > Android > Cook content` to cook you mod content

For map mods, ensure that `List of maps to include in a packaged build` in `Platforms > packaging settings` contains your map, if not add it before cooking.

## Build

Build the plugin using `Reality > Build` button

## Transfer

From the Reality menu, select your device and click `Transfer mod`.  
You can check Unreal logs to see if it succeeded.

## Launch game

Launch Beyond and use the game creation UI to select your gamemode and your map  
then start the game.