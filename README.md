# F4SEPlugins

Fallout 4 Script Extender:

http://f4se.silverlock.org/

Fallout 4 Engine Extender (F4EE) is used by LooksMenu:

http://www.nexusmods.com/fallout4/mods/12631/?

HUDExtension is used by Floating Healthbars:

http://www.nexusmods.com/fallout4/mods/21636/?

Achievements:

http://www.nexusmods.com/fallout4/mods/12465/?

Survival Unlocker:

http://www.nexusmods.com/fallout4/mods/23197/?

## F4EE Build Instructions

1. Make sure jsoncpp is installed ``vcpkg install jsoncpp --triplet x64-windows-static``
2. If Visual Studio doesn't pick it up then run the following in an administrator context ``vcpkg integrate install``
3. Build the f4ee project in Visual Studio (You'll need Desktop Development with C++ installed from the Visual Studio Installer)
