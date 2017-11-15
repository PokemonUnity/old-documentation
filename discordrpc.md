# Discord RPC Support (NOT FINISHED)
Pokémon Unity supports integration with Discord Rich Presence, which displays your current map, follower, player name, and gender (using an icon).

While PkUnity uses a premade application for this support, this guide will show you how to set up your own.

## Setting up an application
Firstly, sign up for [Discord](http://www.discordapp.com) and head to your [developer applications page](https://discordapp.com/developers/applications/me).
If you're signed in, there should be a button that says "New App," click it. You should see a page to name your app and setup a description.

Once you give it a name and an icon, click on "Create App" and "Enable Rich Presence" once you're in the app config.
You should now be able to upload a cover image as well as assets. Upload your cover image, copy your "Client ID" (not the secret or token!),
and head back to PkUnity. View the components for the Global prefab and you should see a string box named "Application ID," usually this box
already has an ID, just replace it with yours. 

## Assets
After you have set the Application ID, head back to the website. Upload some assets to get started with, in "Assets/Resources/DiscordRPC" there
are some example assets you could use. The main menu uses the key "main_menu" and the players use the keys "m_(outfitname)" and "f_(outfitname)", usually the outfits are set to "hgss"

<img alt="Application properly set up" src="/img/application.png"/>

Now it's time to upload maps.
Try to get your best screenshot of the overworld town, no indoors areas such as caves or houses!
Once you have your screenshot, format it to 512x512 and upload it as an asset. Keep note of the key you used for later.
After uploading everything, go to your map settings and add the token to "Discord Image Key" and do not set the state.
Repeat the tokens for every indoors area in the map as well, however set the state box to say something like "Inside a Pokemon Center," "Inside a house (House Name)," or "Exploring a cave (Cave Name)."


Once all of the tokens are set, head in-game and walk around a bit. Make sure the editor window is set as your game on Discord.
Check your presence, if it says something along the lines of this (Should display follower info and current state in-game), you've added everything correctly!

<img alt="Presence showing up on Popplio's profile" src="/img/presenceexample.png"/>

# Disabling Discord RPC

TBD
