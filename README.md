# GTA-V Public Solo/Friend Session
An additional file that needs to be installed in order to make a public friend only session in GTA V. This **DOES NOT** modify any game files or tried to modify anything! Although I **DO NOT** guarantee you'll not get banned from using it. Its only my opinion that it would not let you get banned as due to the nature of this file not giving any player some advantage nor modifying any configurations/values within the game.

## How-to

- Download the startup.meta in this repository
- Modify the startup.meta file accordingly
```xml
<?xml version="1.0" encoding="UTF-8"?>
<!--YourUniqueID-->
<CDataFileMgr__ContentsOfDataFileXml>
	...
</CDataFileMgr__ContentsOfDataFileXml>                     
<!--YourUniqueID-->
```
- Change "YourUniqueID" to any random values and make sure your friend also have the same "YourUniqueID" so he could join your session else don't share the modified startup.meta file that you made so you would only have a permanent public solo session

## Installation

- Go to GTA V directory 
- Go to x64/data
- Paste startup.meta file

Credits: RDO Community (That's where the original idea came from. I just made one for GTA-V cause I can't find anything for it so I made one)
