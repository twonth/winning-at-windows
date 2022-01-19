# winning-at-windows
A list of Windows 11 software and tweaks that this carbon-based lifeform finds useful

## "Ricing" (appearance customization)

* [Stardock software](https://www.stardock.com/): Several tools for Windows customization, such as IconPackager (replaces the most common system icons), WindowFX (adds effects when opening, closing, minizing, moving windows), TouchTasks (triggers actions by touching certain screen corners), and Start 11 (alternative start menu layouts). 

* Fans of alternative start menus will also want to check out [StartAllBack](https://www.startallback.com/).

* [MyDockFinder](https://store.steampowered.com/app/1787090/MyDockFinder/): a Maclike dock.

* [WinDynamicDesktop](https://github.com/t1m0thyj/WinDynamicDesktop): wallpaper that changes with the time of day, a la MacOS.

* for animated wallpapers, check out [Wallpaper Engine](https://www.wallpaperengine.io/en) or (an open source alternative) [Lively Wallpaper](https://rocksdanister.github.io/lively/)

* [RoundedTB](https://github.com/torchgm/RoundedTB): Add margins and/or rounded corners to the taskbar.

* [OldNewExplorer](https://m.majorgeeks.com/files/details/oldnewexplorer.html): Allows one to return to the good old days when cats were cats, dogs were dogs, and File Explorer was less ornate and cluttered.

* [ModernFlyouts](https://modernflyouts-community.github.io/): Modern-looking pop-up indicators for changing volume, brightness, toggling caps-lock, etc.

* [filetypesman](https://www.nirsoft.net/utils/file_types_manager.html): tool for managing filetype icons

* [CustomizerGod](https://www.door2windows.com/customizergod/): User-friendly way to replace certain Windows system icons. Was never updated for Windows 11 (or even later builds of Windows 10), but still functional if handled with care.

* [Resource Hacker](http://www.angusj.com/resourcehacker/): view and edit resources in EXE, DLL files. Useful for changing certain stubborn program icons.

* [namazso/SecureUxTheme: A secure boot compatible in-memory UxTheme patcher (github.com)](https://github.com/namazso/SecureUxTheme): allows one to apply custom themes without modifying system files, and without rebooting (!) 

* [Rainmeter](https://www.rainmeter.net/): tool for displaying desktop widgets. An endless number of Rainmeter skins are on deviantArt (but beware that many, especially ones that are older, do not play nice with modern high DPI displays).

* [Droptop](https://github.com/Droptop-Four/Basic-Version/releases/tag/Current-Stable): Rainmeter skin providing a highly customizable menu bar at the top of the screen (think MacOS).

* [WeatherBar](https://weatherbarapp.com/): weather in your Windows system tray. 


## System maintenance and optimization

* [SUMo](https://www.kcsoftwares.com/?sumo): Software Update MOnitor. Scans through your installed software to find applications which can be upgraded to a newer version.

* [BatteryInfoView](https://www.nirsoft.net/utils/battery_information_view.html): Displays information on your battery (e.g., charging status/rate and wear level). An alternative, which can be pinned to the taskbar (on Windows 10, or on Windows 11 if you use something like ExplorerPatcher) is [BatteryBar](https://batterybarpro.com/).

* [Process Hacker](https://github.com/processhacker/processhacker): Task Manager replacement. The nightly versions have dark mode support.

* [Chocolatey](https://chocolatey.org/): package manager for Windows, through powershell.

* [Nativeifier](https://github.com/nativefier/nativefier): Wrapper to turn webapps into standalone applications.

* [Autoruns for Windows](https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns): comprehensive startup process manager.

* [WizTree](https://diskanalyzer.com/): shows, visually, which files are taking up space on your drive.  Very fast on NTFS-formatted drives.

## Usability enhancements


* [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher): restores much of the missing functionality of Windows 11 (and much else besides). I like the clean-looking Alt-Tab replacement that the author built in .

* [Fluent Search](https://www.fluentsearch.net/): Full featured search bar for Windows. The killer feature (for me) is the ability to find a file and drag and drop it from the search window into one of Windows' "open file" dialogue boxes. Huge timesaver.

* [Winaero Tweaker](https://winaero.com/winaero-tweaker/): adjust "secret" Windows settings. I use it, e.g., to change the Quick Access icon in the navigation pane, though this results in a duplicate icon for some reason; the fix is [here](https://www.tenforums.com/customization/157112-duplicate-quick-access-navigation-pane.html).

* [EarTrumpet](https://github.com/File-New-Project/EarTrumpet): Replacement for the Windows system tray audio control widget. Much more functional, e.g., including per-app volume control.

* [BatteryMode](https://github.com/tarcode-apps/BatteryMode): Alternative battery system tray widget. More information than the default widget more customization options too (e.g., bring back the Windows 7 icon).

* [ExtractNow](https://www.extractnow.com/#/home): archive handler. Allows one to unzip/unrar/etc. by double clicking the archive. Quite customizable. 

* [Pantherbar](https://pantherbar-app.com/): Whenever you select text, pops up a menu with possible ``quick actions'' (such as copy, cut, search in Google, run through Google Translate).

* [Incipitor](https://www.dcmembers.com/bgmcoder/download/incipitor/): automates the process of adding shortcuts to the Windows start menu

* [Snipaste](https://www.snipaste.com/): full-featured and customizable screen snipping tool. Can auto-detect certain portions of the screen that are natural candidates for capture.

* [Ditto](https://ditto-cp.sourceforge.io/): good looking clipboard manager for Windows.

* [DragDropConfirm](https://github.com/broken-e/DragDropConfirm): shell extension that adds a confirmation dialogue before moving files in File Explorer. Essential for those with touchscreen devices and slippery fingers.


## Icons and other art

* [deviantart](https://www.deviantart.com/): So much to see here! Some of my favorites include (but are not limited to)...
    * anything by [Niivu](https://www.deviantart.com/niivu), especially his Windows themes
    * the  `iconic creations' of [Octaviotti](https://www.deviantart.com/octaviotti)
    * [Mnemo 'n' icons by hechiceroo on DeviantArt](https://www.deviantart.com/hechiceroo/art/Mnemo-n-icons-413224458): gorgeous filetype icons. 

* [500px](https://500px.com): brilliant way to discover photos, many of which make excellent wallpapers.

* [wallhaven](https://wallhaven.cc): large database of wallpapers.

## Low-level "hacks"

* Open all apps as administrator (registry hack) `REG ADD HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /f /v EnableLUA /t REG_DWORD /d 0/`

* Change taskbar icons of pinned UWP apps. One needs [Win7AppId1.1](https://code.google.com/archive/p/win7appid/downloads). Get the AppID of the desired app by running `get-StartApps | Format-Table | Out-String -width 9999` in PowerShell. Create a custom shortcut  to `explorer.exe shell:appsFolder\YOURAPPID`. Back in Powershell, run `Win7AppId1.1 "YourAppShortcut.lnk" "YOURAPPID"`. Change the icon of the shortcut to whatever you desire, then pin the icon to the taskbar. (Thanks to dpcdpc11 for making me aware of [this method](https://dpcdpc11.com/custom-taskbar-icons-guide/)!)

* [mydigitallife forums](https://forums.mydigitallife.net/): These folks are serious about tweaking Windows.

* [elevenforum](https://www.elevenforum.com/): Another venue for community discussions of Windows customization.  See also [tenforums](https://www.tenforums.com/).










