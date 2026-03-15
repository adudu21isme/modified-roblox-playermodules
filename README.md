# The information is unfinished, check back in a day.

# Modified Roblox PlayerModule
## This is my modified version of the roblox default PlayerModule (StarterPlayerScripts/PlayerModule, non-server authority one)

The modified PlayerModules in this are designed for games i develop for.

Note for each:
- InvisCamera is removed
- Click to move is removed
- Roblox FFlags/[such live values](https://clientsettingscdn.roblox.com/v2/settings/application/PCDesktopClient) will not affect the modules in this repo
- Original source is old but has been updated to most of latest changes of Roblox
- Direct calls like game.Players/such are modified to use :GetService instead so renaming services will not break the module
- Classic, CameraToggle, Follow are supported, Orbital camera is removed/similar.

R6 Shiftlock:
- ButtonX on console will trigger MouseLock
- Mobile shiftlock button next to jump button, so mobile users can use shiftlock too.
- Setting Workspace Attribute "ShiftlockEnabled" to false will disable ShiftLock, Setting it to any positive value or nil will enable it
