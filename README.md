# The information is unfinished, check back in a day.

# Modified Roblox PlayerModule
## This is my modified version of the roblox default PlayerModule (StarterPlayerScripts/PlayerModule, non-server authority one)

The modified PlayerModules in this are designed for games i develop for.

### Note for each:
- InvisCamera is removed
- Click to move is removed
- Roblox FFlags/[such live values](https://clientsettingscdn.roblox.com/v2/settings/application/PCDesktopClient) will not affect the modules in this repo
- Original source is old but has been updated to most of latest changes of Roblox
- Direct calls like game.Players/such are modified to use :GetService instead so renaming services will not break the module
- Classic, CameraToggle, Follow are supported, Orbital camera is removed/similar.
- AvatarGestures is not supported since this was originally designed for R6

#### R6 Shiftlock:
- ButtonX on console will trigger MouseLock
- Mobile shiftlock button next to jump button, so mobile users can use shiftlock too.
- Setting Workspace Attribute "ShiftlockEnabled" to false will disable Shiftlock, Setting the value to anything that is positive or NIL will allow the user to use Shiftlock again.

#### R6 No MouseLock:
- Mouse lock is completely removed

#### R6 but with part camera collision:
Almost same to R6 No MouseLock but:
- If BasePart has "CameraNoNoclip" attribute which value is true, it will prevent the Camera from going through the BasePart, regardless of its visibility/such.
Pending information

#### R15 PlayerModule:
- R15 is only supported, not R6
- No ShiftLock
