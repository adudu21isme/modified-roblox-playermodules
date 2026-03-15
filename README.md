# modified-roblox-playermodules
Modified versions of the default roblox PlayerModule in StarterPlayerScripts

This repo is in W.I.P, check back later.

UNFINISHED CURRENT INFORMATION:
# Modified Roblox PlayerModule
## This is my modified version of the roblox default PlayerModule (StarterPlayerScripts/PlayerModule, non-server authority one)

The modified PlayerModules in this are designed for games i develop for.

Note for each:
- InvisCamera is removed
- Click to move is removed
- Roblox FFlags/such live values (https://clientsettingscdn.roblox.com/v2/settings/application/PCDesktopClient) will not affect the provided modules
- Original source is old but has been updated to most of latest changes of Roblox
- Direct index like game.Players/such has been changed to using :GetService so renaming services will not break the module
- Classic, CameraToggle, Follow are supported, Orbital camera is removed/similar.

Ones with MouseLock enabled will show a mobile MouseLock option which directly controls the MouseLock feature (ShiftLock)

R6 Shiftlock:
- ButtonX on console will trigger MouseLock
- Setting Workspace Attribute "ShiftlockEnabled" to false will disable ShiftLock, Setting it to any positive value or nil will enable it
