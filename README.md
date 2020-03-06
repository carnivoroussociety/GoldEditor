# GoldenEye Setup Editor
Carnivorous' fork of the GoldenEye Setup Editor - originally created by SubDrag, Wreck And Zoinkity.  

Feedback can be [posted in the shootersforever thread](http://www.shootersforever.com/forums_message_boards/viewtopic.php?t=4284)

## Downloads
| Version 4 (Recommended) | Download |
| --------------------------- | ----------- |
| 4.3 | [Installer](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.3/gesetupeditorinstaller4.3.exe) / [Zip Archive](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.3/gesetupeditor4.3.0.7z) |
| 4.2 | [Installer](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.2/gesetupeditorinstaller4.2.exe) / [Zip Archive](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.2/gesetupeditor4.2.7z) |
| 4.1 | [Installer](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.1/gesetupeditorinstaller4.1.exe) / [Zip Archive](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.1/gesetupeditor4.1.7z) |
| 4.0 - Last x86 Build | [Installer](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.0/gesetupeditorinstaller4.exe) / [Zip Archive](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.0/gesetupeditor4.7z) |

| Version 3 (Legacy) | Download |
| --------------------------- | ----------- |
| 3.0 - Final | [Installer](https://github.com/carnivoroussociety/GoldEditor/releases/download/3.0/gesetupeditorinstaller3final.exe) / [Zip Archive](https://github.com/carnivoroussociety/GoldEditor/releases/download/3.0/gesetupeditor3final.7z) |
| 3.0 - SubDrag's Last Build | [Installer](https://github.com/carnivoroussociety/GoldEditor/releases/download/Legacy/gesetupeditorinstaller3.exe) |
| 3.0 - Last Win98 build | [Installer](https://github.com/carnivoroussociety/GoldEditor/releases/download/Legacy/gesetupeditorinstaller3win98.exe) |

## FBX Support
[For legal reasons](https://forums.autodesk.com/t5/fbx-forum/fbx-sdk-faq/td-p/4165297) the FBX SDK cannot be included with the editor. If you want FBX support you'll need to install the [FBX SDK](https://web.archive.org/web/20200101042427/https://damassets.autodesk.net/content/dam/autodesk/www/adn/fbx/2020-0-1/fbx202001_fbxsdk_vs2013_win.exe) and copy `C:\Program Files\Autodesk\FBX\FBX SDK\2020.0.1\lib\vs2013\x64\release\libfbxsdk.dll` to the editor directory. Then replace `GEEdit4\Obj2An8.exe` [with this version](https://github.com/carnivoroussociety/N64-Tools/raw/master/objtoan8/bin/x64/Releasev12/ObjToAn8.exe)

## Requirements
* Microsoft Visual C++ 2019 Redistributable - [x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [x86](https://aka.ms/vs/16/release/vc_redist.x86.exe)
* Microsoft Visual C++ 2013 Redistributable - [x64](https://www.microsoft.com/en-us/download/details.aspx?id=40784)
* DirectX 9.0c Redistributable June 2010 - [Download](https://www.microsoft.com/en-us/download/details.aspx?id=8109)
* Autodesk FBX SDK 2020.0.1 VS2013 (optional) - [Download](https://web.archive.org/web/20200101042427/https://damassets.autodesk.net/content/dam/autodesk/www/adn/fbx/2020-0-1/fbx202001_fbxsdk_vs2013_win.exe)

## Warranty
The GoldenEye Setup Editor comes with `ABSOLUTELY NO WARRANTY`.
This is free software, and you are welcome to redistribute it under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International license.

FFmpeg/LAME/mpg123/SoX/libdeflate/Xdelta are covered under __their own software licenses__ - check below for more details.

## Included Software
* FFmpeg - https://ffmpeg.org/
* LAME - http://lame.sourceforge.net/
* mpg123 - https://www.mpg123.de/
* SoX - http://sox.sourceforge.net/
* libdeflate - https://github.com/ebiggers/libdeflate
* Xdelta - https://github.com/jmacd/xdelta
* ObjToAn8 - https://github.com/carnivoroussociety/N64-Tools/tree/master/objtoan8
