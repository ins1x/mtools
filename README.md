# MTOOLS for Texture Studio SA:MP

![logo](/img/logo_mtools.png)

**MTOOLS** is a filterscript that complements Texture Studio and provides a classic dialog interface.  
Mtools gives mappers more features to be more productive.

>The main menu is called by default on ALT (Can be changed in the settings)\
For the list of all server commands and features type /help

## Fast installation
* Download a ready snapshot with [Texture Studio 2.1 + mtools](https://drive.google.com/file/d/1y-4jfvl5EpzH5FeN2Hji62NBIB88rMkv/view?usp=sharing)
* Unpack archive and run samp-server.exe, connect to localhost in client
## Manual installation
* Install latest version *[Texture Studio](https://vk.com/tip_mapper?w=page-89889560_49251374)*
* Copy the mtools.amx file to the filterscripts folder
* Create /scriptfiles/mtools folder
* Open the [server.cfg](https://open.mp/docs/server/server.cfg) file in any editor and add mtools to filtescripts.
```
filterscripts tstudio mtools
plugins crashdetect sscanf streamer filemanager
```
> Note: mtools is connected after tstudio (server.cfg)  

## Requirements
* Use the [Zeex's improved compiler](https://github.com/pawn-lang/compiler) to compile this filterscript!
* [SA:MP 0.3.7 R2 server](https://www.sa-mp.com/download.php) or highter (DL not requred)
* [Incognito Streamer plugin v2.7 - 2.9.4](https://github.com/samp-incognito/samp-streamer-plugin/releases)
* **mtools** works correctly with  *[Texture Studio 2.0](https://vk.com/tip_mapper?w=page-89889560_49251374)* and above

## **[Wiki](https://github.com/ins1x/mtools/wiki)**
* :gb: [Mtools English wiki](https://github.com/ins1x/mtools/wiki)
* :ru: [Mtools Russian wiki](https://github.com/ins1x/mtools/wiki/Home-%5BRus%5D)  
* [Texture Studio wiki](https://github.com/Crayder/Texture-Studio/wiki/Using-Texture-Studio)  

## Disclaimer

**This script** does not claim to be original and is provided as is. The developer is not tasked with making another map editor, but supplementing the existing one for the convenience of work.  
