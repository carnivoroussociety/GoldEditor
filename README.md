# GoldenEye Setup Editor
Carnivorous' fork of the GoldenEye Setup Editor, originally created by SubDrag. Feedback can be [posted in the shootersforever thread](http://www.shootersforever.com/forums_message_boards/viewtopic.php?t=4284)

## Downloads
| Version 4 | URL |
| --------------------------- | ----------- |
| 4.1 - Installer (recommended) | [gesetupeditorinstaller4.1.exe](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.1/gesetupeditorinstaller4.1.exe) |
| 4.1 - Zip Archive (recommended) | [gesetupeditor4.1.7z](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.1/gesetupeditor4.1.7z) |
| 4.0 - Installer (last x86 build) | [gesetupeditorinstaller4.exe](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.0/gesetupeditorinstaller4.exe) |
| 4.0 - Zip Archive (last x86 build) | [gesetupeditor4.7z](https://github.com/carnivoroussociety/GoldEditor/releases/download/4.0/gesetupeditor4.7z) |

| Version 3 | URL |
| --------------------------- | ----------- |
| Final - Installer | [gesetupeditorinstaller3final.exe](https://github.com/carnivoroussociety/GoldEditor/releases/download/3.0/gesetupeditorinstaller3final.exe) |
| Final - Zip Archive | [gesetupeditor3final.7z](https://github.com/carnivoroussociety/GoldEditor/releases/download/3.0/gesetupeditor3final.7z) |
| Legacy - Installer (SubDrag's last build) | [gesetupeditorinstaller3.exe](https://github.com/carnivoroussociety/GoldEditor/releases/download/Legacy/gesetupeditorinstaller3.exe) |
| Legacy - Installer (last Win98 build) | [gesetupeditorinstaller3win98.exe](https://github.com/carnivoroussociety/GoldEditor/releases/download/Legacy/gesetupeditorinstaller3win98.exe) |

## FBX Support
[For legal reasons](https://forums.autodesk.com/t5/fbx-forum/fbx-sdk-faq/td-p/4165297) the FBX SDK cannot be included with the editor. If you want FBX support you'll need to install the [FBX SDK](http://images.autodesk.com/adsk/files/fbx20141_fbxsdk_vs2008_win.exe) and copy `C:\Program Files\Autodesk\FBX\FBX SDK\2014.1\lib\vs2008\x64\libfbxsdk.dll` to the editor directory. Then replace `GEEdit4\Obj2An8.exe` [with this version](https://github.com/jombo23/N64-Tools/raw/master/objtoan8/bin/x64/Release/ObjToAn8.exe)

## Requirements
* Microsoft Visual C++ 2008 Redistributable - [x86](https://www.microsoft.com/en-us/download/details.aspx?id=29) & [x64](https://www.microsoft.com/en-us/download/details.aspx?id=15336)
* Microsoft Visual C++ 2013 Redistributable - [x86 & x64](https://www.microsoft.com/en-us/download/details.aspx?id=40784)
* DirectX 9.0c Redistributable June 2010 - [Download](https://www.microsoft.com/en-us/download/details.aspx?id=8109)
* Autodesk FBX SDK 2014.1 VS2008 (optional) - [Download](http://images.autodesk.com/adsk/files/fbx20141_fbxsdk_vs2008_win.exe)

## Warranty
The GoldenEye Setup Editor comes with `ABSOLUTELY NO WARRANTY`.
This is free software, and you are welcome to redistribute it under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International license.

FFmpeg/LAME/mpg123/SoX/Gzip/Xdelta are covered under __their own software licenses__ - check below for more details.

## Included software
* FFmpeg - https://ffmpeg.org/
* LAME - http://lame.sourceforge.net/
* mpg123 - https://www.mpg123.de/
* SoX - http://sox.sourceforge.net/
* Gzip - https://www.gzip.org/
* Xdelta - https://github.com/jmacd/xdelta
* ObjToAn8 - https://github.com/jombo23/N64-Tools/tree/master/objtoan8
