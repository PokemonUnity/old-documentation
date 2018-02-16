![](/img/tiled2pkunityhigh.png)

# Using Tiled2PkUnity

Tiled2PkUnity is meant to replace the 'Pokemon Essentials' part of creating a map in Pokemon Unity. It creates a collision map out of a tilemap made with Tiled, using a tileset with specific variables.

To use this tool, you must first install the [Tiled Map Editor](http://www.mapeditor.org) and the LTS version of [Node.js](http://www.nodejs.org).

The application itself is located in the 'TOOLS/Tiled2PkUnity/' directory.

# Tiled

In order to use this application, you need a tileset with specific values to specify what tiles do what. There are premade tileset JSONs in the 'TOOLS/Map Texture Tilesets' directory.

Simply create a tileset directing to your image source, and select all tiles, then click the plus icon in the bottom left corner and add an int property named "Type".

Now that you have set up the tileset, you can now select tiles and set the values accordingly. Here is a sheet of the values used for collision:

* 0
  * Floor/Non-collidable
* 1
  * Wall/Collidable
*  2
  * Water/Surfable
* 3
  * Environment 2 \(Used for having different environments during battles in the same map\)

Once you're completed, save the tileset as a 'JSON Tileset File \(_.json_\)'.

After you have set up your tileset, you can now proceed to creating your tilemap. Once created, head to 'Map&gt;Add External Tileset' and add the tileset you'd like to use, do not use more than one tileset! After the tileset is added, embed the tileset into the map:

![](/img/embedtileset.png)

Once the tilemap is complete, save the tilemap and proceed towards making the collision map.

# Launching the app

Once Node.js is confirmed to be installed, drag and drop your tilemap JSON onto the Launch.bat inside the Tiled2PkUnity directory.

Afterwards, your collision map should be in a text file with an '\_cmap' suffix, but only if you have the 'fs' module installed. If not, the collision map will instead be outputted into the command prompt.

Copy this collision map and paste it into the MapCollider on your Pokemon Unity map and test the game to make sure it works properly. If not, try setting some offsets and make sure your width and height are set correctly. Thanks for using Tiled2PkUnity!

Arguments:

`node tiled2pkunity.js ./Tilemap.json [Output.txt]`

