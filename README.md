# MTOOLS for Texture Studio SA:MP

![logo](https://i.imgur.com/Cq7GYf9.png)

**MTOOLS** is a filterscript that complements Texture Studio and provides a classic dialog interface.  
Mtools gives mappers more features to be more productive. Visit the [Mtools wiki](https://github.com/ins1x/mtools/wiki) to learn more.  

> The main menu is called by default on ALT (Can be changed in the settings)  
For the list of all server commands and features type /help    

## Installation
* Download and install [Texture Studio 1.9 ENG](https://github.com/Pottus/Texture-Studio) or [Texture Studio 2.0 RUS](https://vk.com/@tip_mapper-texture-studio-20-rus) 
* Download [latest release mtools](https://github.com/ins1x/mtools/releases/tag/Release), unpack it into any folder
* Copy files from this folder, pre-selecting the desired version TextureStudio
* Copy the mtools.amx file to the filterscripts folder
* Open the [server.cfg](https://open.mp/docs/server/server.cfg) file in any editor and add mtools to filtescripts.

```
filterscripts tstudio mtools
plugins crashdetect sscanf streamer filemanager
```
> Note: mtools is connected after tstudio (server.cfg)  

## How to use
* Run **Texture Studio** via samp-server.exe
* In samp client add server [localhost:7777](samp://localhost:7777)
* Connect to localhost the server
* After loading, press **ALT** or type **/mtools** to open the main menu
* At the first start, recommended open settings section, and configure mtools for yourself

## Requirements
* Use the [Zeex's improved compiler](https://github.com/pawn-lang/compiler) to compile this filterscript!
* [SA:MP 0.3.7 server](https://www.sa-mp.com/download.php) (DL not requred)
* [Incognito Streamer plugin v2.7 - 2.9.4](https://github.com/samp-incognito/samp-streamer-plugin/releases)