# Debug Mode

Pokémon Unity's Expansion features a "Debug Mode" which lets you access various options while developing your project on the  
framework. To enable access to this mode, change the boolean "allowDebug" in GlobalVariables.cs to a true value.

## Enabling the Debug Menu

To open the Debug Menu, press Right Shift while on the overworld. The first time you open this menu, it will  
ask you if you'd like to enable the Debug Menu and disable saving:

![Enabling debug mode](/img/enabledebugmode.png)

After enabling the mode, saving will be disabled and your Discord Player image key will be set to "debugging".  
You can press right shift again to see the Debug Menu:

![Debug menu](/img/debugmenu.png)

* Reset Cam
  * Resets the Player's camera to it's default position.
* Toggle UI
  * Toggles the build information and debug logging in the corner.
* Toggle Time
  * Toggles the dynamic time of day system, resets to 12:00 when disabling.
* Jump On A
  * Allows the Player to jump at any time using the Select button \(usually space\).
    This allows for map exploits to be taken advantage of.
* High-Res
  * Changes the current resolution of the game to 1062x597.
    \(Highest resolution when game is maximized on a 768p display in the editor\)
    ![High-Res](/img/highres.png)
    Make sure not to enter any new areas with this mode active as it will blind you.
    You can unblind yourself by using Right Shift+Down x4+Select.
* Low-Res
  * Resets the current resolution to the default 392x192.
* Reload Map
  * Resets the current scene as well as resetting the Player's position.
* Exit Debug
  * Exits the Debug Menu and returns control to the Player.

## Other Debug features

You can win any battle you're in by pressing the Mega Evolution button with a Pokémon that cannot Mega Evolve.  
This will cause your Pokémon to use Struggle and by the time all moves have finished and you have not blacked out, you will  
automatically win regardless of what progress you've made during the battle.

You can manipulate the camera while you're not busy. T moves forward, G moves backward, F moves left, H moves right, V moves up, and B moves down. To reset the camera's position, head into the Debug Menu and select "Reset Cam".

