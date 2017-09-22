# Getting Started

To use Pokemon Unity, you must have [Unity 2017.1](http://www.unity3d.com) installed. After installing Unity, you can then clone the branch you'd like to use (master is for stable builds of the framework without any issues, develop is the WIP branch, which should only be used for testing or experimental purposes). You can also install Visual Studio Code rather than Visual Studio Community as the full VS package is not needed and can take upwards to 4gb of space.

# Working in Unity

While this documentation will not teach you how to use Unity, it will demonstrate how to work with the framework in Unity.
Open the 'Pokemon Unity' folder as a project (The one alongside 'TOOLS' and the readme) and then open 'startup.unity'. Going to the startup scene will bring you to the title screen. In the develop branch, this will also include the intro cutscene for starting a new game. Playable scenes are listed under the 'overworld' prefix. To edit anything code-wise, for example you'd like to change the name of the player when you start a new game, you would need to head into the script the gameobject uses. More information on how to use Unity and C# can be found elsewhere.

# Debug Mode (Develop)

**THIS FEATURE IS CURRENTLY UN-IMPLEMENTED, THIS SECTION IS A PLACEHOLDER AND MAY BE MOVED TO A NEW FILE SOON**

In the develop branch, you can enable debug mode in the settings menu by pressing "QPWOEI" and pressing the Delete key. Enabling debug mode will put a permanent marker on your screen alongside disabling the save feature, it will also grant you access to every Pokemon in the database using the Pokedex along with No-Clipping mode. 

In the Pokedex, you can add selected Pokemon to your current party by pressing numbers on the numpad (1-6). You can also use No-Clipping mode by toggling it with comma (,). The screen will say "Noclip Enabled" alongside your co-ordinates. Noclip is useful if you need to move to certain co-ordinates for events or to test out collision maps. In battles, you can instantly win any battle by pressing 'N' and selecting a move or using an item.
