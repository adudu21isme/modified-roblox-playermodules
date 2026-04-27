# Modified Roblox PlayerModule
## This is my modified version of the roblox default PlayerModule (StarterPlayerScripts/PlayerModule, non-server authority one)

The modified PlayerModules in this are designed for games i develop for but decided to let anybody use it if they want instead of my modified PlayerModules being Private.

### Notes for each:
- InvisCamera is removed
- Click to move is removed
- Roblox FFlags/[such config live values](https://clientsettingscdn.roblox.com/v2/settings/application/PCDesktopClient) will mostly not affect the modules in this repo
- Original source is old but has been updated to most latest changes [of Roblox](https://github.com/MaximumADHD/Roblox-Client-Tracker/tree/roblox/scripts/PlayerScripts/StarterPlayerScripts) but modified if needed at the time of writing this
- Direct calls like game.Players/such are modified to use :GetService instead so renaming services will not break the module
- Classic, CameraToggle, Follow are supported, Orbital camera is removed/similar.
- Removed some useless functions of default PlayerModule
- Default PlayerModule tends to use some deprecated methods so this uses the latest non-deprecated methods mostly as of writing this
- Mobile jump button will always be visible
> [!TIP]
> Adding Collection Tag "ExcludeFromCamera" to any Model/such will allow the camera to go fully through it. Popper has been improved for such.

> [!NOTE]
> [MouseDeltaSensitivity](https://create.roblox.com/docs/reference/engine/classes/UserInputService#MouseDeltaSensitivity) will apply to most platforms for each PlayerModule in this repo, not only computer.

#### R6 Shiftlock:
- ButtonX (Gamepad) will trigger MouseLock
- Mobile shiftlock button next to jump button, so mobile users can use shiftlock too.
- Setting Workspace Attribute "ShiftlockEnabled" to false via script or so will forcefully disable Shiftlock, Setting the value to anything that is positive or NIL will allow the user to use Shiftlock again.
> [!NOTE]
> If you do not plan to use the "ShiftlockEnabled" attribute you can set the value of "ShiftlockAttributeListener" which is in the ShiftLockController Module to nil or false to disable the listener.

Click to see video of it:  
[![Video showcase](https://img.youtube.com/vi/GtK6XaZDUxA/hqdefault.jpg)](https://www.youtube.com/watch?v=GtK6XaZDUxA)

#### R6 MouseLock removed:
- Mouse lock is completely removed

Click to see video of it:  
[![Video showcase](https://img.youtube.com/vi/V9uib6tPmI4/hqdefault.jpg)](https://www.youtube.com/watch?v=V9uib6tPmI4)

#### R6 but with part camera collision:
Almost same to the R6 with Shiftlock Removed but:
- If BasePart has "CameraNoNoclip" attribute which value is true, it will prevent the Camera from going through the BasePart, regardless of its visibility/such.

Click to see video of it:  
[![Video showcase](https://img.youtube.com/vi/e5f2zsIBwic/hqdefault.jpg)](https://www.youtube.com/watch?v=e5f2zsIBwic)

#### R15 PlayerModule:
- R15 is only supported, not R6
- No ShiftLock

#### R15 Shiftlock:
- Pretty much same to R6 Shiftlock but instead only supporting R15

> [!NOTE]
> For any module that has ShiftLock removed, if you are to use it, you should probably disable the regular ShiftLock option in the roblox menu so users are not confused why shift lock isnt working, To disable:
> 1. Find StarterPlayer Service
> 2. Set "EnableMouseLockOption" to false

## How to install?
1. Download the wanted module from this repo, make sure to read information about it here to understand it better.
2. Import the rbxm file into the wanted game (Can Drag&Drop and such)
3. Place both scripts into StarterPlayerScripts which is located in StarterPlayer service
> [!TIP]
> If you use this module, i recommend you to turn on notifications for Releases for this repo so you can know when an update is available for the modules/such:  
> <img width="128" height="74" alt="image" src="https://github.com/user-attachments/assets/4247330e-b281-4247-baa6-906201a0384c" />  
> <img width="327" height="326" alt="image" src="https://github.com/user-attachments/assets/0eb7b91e-0a5f-4cc5-912a-d7b9ccc7b3cd" />  
> <img width="436" height="361" alt="image" src="https://github.com/user-attachments/assets/bbc73faa-b7a7-442b-8b5c-c910fa87d1d8" />

### What are some games adudu21 is using this for?
https://www.roblox.com/games/108235899254530/Sniper-Tag  
https://www.roblox.com/games/112582089018099/Launch-a-Fruit

There are more though i do not think it is needed to list them all here.
