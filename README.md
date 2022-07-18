# ![trophy](./images/trophy-small.png "trophy") winning-at-windows 

Windows 11 software and tweaks that *I* find useful. The list is (intentionally) personal and is not meant to be a comprehensive database of all programs of this kind. While the software mentioned below has proven useful to me, not all carbon-based life forms  share the same workflow or tastes. Consider yourself warned.

## "Ricing" (appearance customization)

* [Stardock software](https://www.stardock.com/): Several tools for Windows customization, such as [IconPackager](https://www.stardock.com/products/iconpackager/) (replaces the most common system icons), [WindowFX](https://www.stardock.com/products/windowfx/) (adds effects when opening, closing, minimizing, moving windows), [TouchTasks](https://www.stardock.com/products/touchtasks/) (triggers actions by touching certain screen corners), and [Start11](https://www.stardock.com/products/start11/) (alternative start menu layouts). 

* Fans of alternative start menus will also want to check out [StartAllBack](https://www.startallback.com/) and [Open-Shell](https://github.com/Open-Shell/Open-Shell-Menu).

* [MyDockFinder](https://store.steampowered.com/app/1787090/MyDockFinder/): Mac-like dock and Finder bar. Pro-tip: To get a weather status icon on the finder bar, also set up [Tray Weather](https://github.com/FelixdelasPozas/TrayWeather).

* [WinDynamicDesktop](https://github.com/t1m0thyj/WinDynamicDesktop): wallpaper that changes with the time of day, a la MacOS.

* for animated wallpapers, check out [Wallpaper Engine](https://www.wallpaperengine.io/en) or (an open source alternative) [Lively Wallpaper](https://rocksdanister.github.io/lively/)

* [Mica For Everyone](https://github.com/MicaForEveryone/MicaForEveryone): Apply the Windows 11 Mica transparency effect to win32 apps. Does wonders for Explorer.

* [RoundedTB](https://github.com/torchgm/RoundedTB): Add margins and/or rounded corners to the taskbar.

* [WinPaletter](https://github.com/Abdelrhman-AK/WinPaletter): Easily customize Windows accent colors. Useful for tweaking the titlebar appearance, for instance. 

* [OldNewExplorer](https://m.majorgeeks.com/files/details/oldnewexplorer.html): Allows one to return to the good old days when cats were cats, dogs were dogs, and File Explorer was less ornate and cluttered.

* [ModernFlyouts](https://modernflyouts-community.github.io/): Modern-looking pop-up indicators for changing volume, brightness, toggling caps-lock, etc.

* [filetypesman](https://www.nirsoft.net/utils/file_types_manager.html): tool for managing filetype icons and associations. A useful alternative is [types](https://ystr.github.io/types/). The latter hasn't been updated in several years but seems to work OK on Windows 11; in fact, unlike filetypesman it doesn't seem to stop responding for unknown reasons.

* [CustomizerGod](https://www.door2windows.com/customizergod/): User-friendly way to replace certain Windows system icons. Was never updated for Windows 11 (or even later builds of Windows 10), so handle with care.

* [Resource Hacker](http://www.angusj.com/resourcehacker/): view and edit resources in EXE, DLL, and related files. Essential tool for changing stubborn icons. To gain permissions to customize icons built in to Windows, you will want to run Resource Hacker with something like [NSudo](https://github.com/M2Team/NSudo). Windows keeps many (but not all) of its icons in **\Windows\SystemResources\shell32.dll.mun** and **\Windows\SystemResources\imageres.dll.mun**.

* [namazso/SecureUxTheme: A secure boot compatible in-memory UxTheme patcher (github.com)](https://github.com/namazso/SecureUxTheme): allows one to apply custom themes without modifying system files, and without rebooting (!) 

* [Rainmeter](https://www.rainmeter.net/): tool for displaying desktop widgets. An endless number of Rainmeter skins are on deviantArt (but beware that many, especially ones that are older, do not play nice with modern high DPI displays). If you use a tablet or frequently change screen resolutions for any other reason, grab [RainRez](https://forum.rainmeter.net/viewtopic.php?f=18&t=10471&hilit=rainrez) as well. 

* [Droptop](https://github.com/Droptop-Four/Basic-Version/releases/tag/Current-Stable): Rainmeter skin providing a highly customizable menu bar at the top of the screen (think MacOS). Even better when used with [Yaron's System Monitor](https://github.com/Yaron2334/SystemMonitor/) app (interfaces with [HWiNFO](https://www.hwinfo.com/)).

* [Omnimo](https://omnimo.info/) and [Big Sur](https://www.deviantart.com/fediafedia/art/Big-Sur-1-0-BETA-for-Rainmeter-846882462?comment=1%3A846882462%3A4964685064): two of the most popular (deservedly) skin suites for Rainmeter, by [fediafedia](https://fediafedia.com/).

* prettify Explorer by adding thumbnail previews for more filetypes: for many common filetypes, see the links under "image thumbnails" [here](https://www.zabkat.com/x2plugins.htm). Also: [DJVU](https://www.cuminas.jp/en/downloads), [SVG](https://github.com/EtheaDev/SVGShellExtensions). For PDF, one can use the shell extension built into [Sumatra](https://www.sumatrapdfreader.org/free-pdf-reader) (worth having around for many other reasons!). 

*  [No!! Meiryo UI](https://github.com/Tatsu-syo/noMeiryoUI):  Change Windows system fonts. Allows more fine-grained control than (say) WinAeroTweaker. 

* [Stylus](https://github.com/openstyles/stylus): Not a Windows app, but still deserving of mention. A browser extension that can customize the appearance of websites via injected CSS, with a [large database of prebuilt scripts](https://userstyles.world/). (One can also use [scripts for the competing, sketchier extension Stylish](https://userstyles.org).) I use this to force dark mode on Duolingo and Wikipedia.

## System maintenance and optimization
* [SUMo](https://www.kcsoftwares.com/?sumo): Software Update MOnitor. Scans through your installed software to find applications which can be upgraded to a newer version.

* [Process Hacker](https://github.com/processhacker/processhacker): Task Manager replacement. The [nightly versions](https://processhacker.sourceforge.io/nightly.php) have dark mode support.

* [Chocolatey](https://chocolatey.org/): package manager for Windows, through powershell.

* [Autoruns for Windows](https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns): comprehensive startup process manager.

* [WizTree](https://diskanalyzer.com/): shows, visually, which files are taking up space on your drive.  Very fast on NTFS-formatted drives. A (paid) alternative with a nicer UI is [FolderSizes](https://www.foldersizes.com/).

* [Bulk Crap Uninstaller](https://www.bcuninstaller.com/): Thorough uninstall tool. Advanced detection capabilities (e.g., knows about programs installed through chocolatey) as well as leftover detection features. A less thorough but much faster-to-start program in the same vein is [geek uninstaller](https://geekuninstaller.com/).

* [O&O RegEditor](https://www.oo-software.com/en/ooregeditor): User-friendly registry editor. Much better search functions than the built in RegEdit.

* [Compactor](https://github.com/Freaky/Compactor): GUI to Windows' built in file and folder compression tools. Useful especially (but not only) for games.

* [FileOptimizer](https://nikkhokkho.sourceforge.io/static.php?page=FileOptimizer): Lossless file size reduction for many different file formats. Saved me about 0.87 GB when run on roughly 10 GB worth of PDFs (~ 600 files).

* [Mp3tag](https://www.mp3tag.de/en/): easily edit audio files' metadata. Useful when you notice that only half of an album's MP3s are displaying the correct cover art.

* [Veeam Agent](https://www.veeam.com/windows-endpoint-server-backup-free.html): totally painless way to manage incremental backups of your entire system. Free!

## Usability/Quality of life enhancements

* [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher): restores functionality from Windows 10 that was removed in the "upgrade" to Windows 11 (and does much else besides). I like the clean-looking Alt-Tab replacement that the author built in as well as the taskbar weather widget.

* [Fluent Search](https://www.fluentsearch.net/): Full featured search bar for Windows. The killer feature (for me) is the ability to find a file and drag and drop it from the search window into one of Windows' "open file" dialogue boxes. Huge timesaver.

* [Everything](https://www.voidtools.com/) and [EverythingToolbar](https://github.com/stnkl/EverythingToolbar): Instant search by filename. I have had strange seeming search results with Fluent Search as it comes out of the box; Everything, without trying to be as clever, often gets me directly where I want to go, and it can be configured as the Fluent Search indexing engine. EverythingToolbar seamlessly integrates Everything into the Windows taskbar.

* [DragDropConfirm](https://github.com/broken-e/DragDropConfirm): Adds a confirm dialogue when dragging/dropping to move files in Explorer. Useful for those with touchscreen devices and wandering fingers.

* [Winaero Tweaker](https://winaero.com/winaero-tweaker/): adjust many (!) "secret" Windows settings. For example, you can modify which folders show up under This PC, and you change the Quick Access icon in the navigation pane (though for me this always results in a duplicate navigation pane icon; seems better to avoid WinAeroTweaker for this and just directly edit the registry key `HKEY_CLASSES_ROOT\CLSID\{679f85cb-0220-4080-b29b-5540cc05aab6}\DefaultIcon`).

* [EarTrumpet](https://github.com/File-New-Project/EarTrumpet): Replacement for the Windows system tray audio control widget. Much more functional, e.g., including per-app volume control.

* [BatteryInfoView](https://www.nirsoft.net/utils/battery_information_view.html): Displays information on your battery (e.g., charging status/rate and wear level). 

* [ExtractNow](https://www.extractnow.com/#/home): archive handler. Allows one to unzip/unrar/etc. by double clicking the archive. Quite customizable. 

* [SnipDo](https://snipdo-app.com/): Formerly known as PantherBar. Whenever you select text, pops up a menu with possible ``quick actions'' (such as copy, cut, search in Google, run through Google Translate). 

* [Snipaste](https://www.snipaste.com/): full-featured and customizable screen snipping tool. Can auto-detect certain portions of the screen that are natural candidates for capture.

* [QuickLook](https://github.com/QL-Win/QuickLook) or [Seer](http://1218.io): instant file preview in File Explorer, upon pressing the space bar (as in MacOS).

* [Ditto](https://ditto-cp.sourceforge.io/): good looking clipboard manager for Windows.

* [AltSnap](https://github.com/RamonUnch/AltSnap): Reposition Windows by pressing Alt and left-clicking, from anywhere (no need to grab a Window edge). Resize by pressing Alt and right-clicking. Put Windows always on top (or roll them up, close, minimize, ...) by pressing Alt and middle-clicking.

* [ShareDrop](https://www.sharedrop.io/): Easy between-device file sharing, even between devices on different networks.

* Alternative battery widgets
  
  - [BatteryBar](https://batterybarpro.com/): good-looking battery meter capable of displaying calibrated runtime estimates. Can be floating or (if you use something like ExplorerPatcher) pinned as a toolbar to the standard taskbar.
  - [BatteryMode](https://github.com/tarcode-apps/BatteryMode): similar to the standard tray widget, but with built in functionality to change the power plan and with more customization options (e.g., the ability bring back the Windows 7 battery tray icon).
  - [CircleBattery](http://rebelvalkyrie.com/?page=circle-battery): tray widget where remaining battery power is displayed in a glowing circular arc. A press in the middle prevents your computer from locking or going to sleep.

* [OnTopReplica](https://github.com/LorenzCK/OnTopReplica): generates a resizable, always on-top-replica of a window or window region. Useful for rolling your own PIP mode for programs without built-in-support (looking at you, [Stremio](https://www.stremio.com/)).

* [MiniBin](https://e-sushi.net/): open and empty the recycle bin from the system tray. Themeable.

* [SuperF4](https://stefansundin.github.io/superf4/): when Alt-F4 isn't good enough. Forcefully kill foreground apps with Ctrl-Alt-F4. Endorsed by Bowser.

* [File Unlocker](https://github.com/marianpekar/file-unlocker-for-windows): Easily find and kill processes that are locking a file or folder.

* [Incipitor](https://www.dcmembers.com/bgmcoder/download/incipitor/): automates the process of adding shortcuts to the Windows start menu.

* [Desktop Media](https://www.softpedia.com/get/Desktop-Enhancements/Other-Desktop-Enhancements/Desktop-Media.shtml): add icons for available drives to the Windows desktop.

* [TaskbarControl](https://www.thefreewindows.com/3252/hide-completely-the-windows-taskbar-using-a-hotkey-and-unhide-it-with-taskbar-control/): assign a hotkey to toggle autohiding  the taskbar. Useful for touchscreen devices in combination with Stardock's TouchTasks.

## Apps for minimalists

* [nomacs](https://nomacs.org/): image viewer that is simultaneously minimal and feature-rich. 

* [mupdf](https://mupdf.com/): hyperminimal PDF viewer. (No, really. More minimal than even  [Sumatra](https://www.sumatrapdfreader.org/free-pdf-reader).)

* [xmplay](https://www.un4seen.com/):  ridiculously lightweight music player. Skinnable. But could use better high dpi support... See also [AIMP](https://www.aimp.ru/).

* [Ferdium](https://ferdium.org/): centralized portal for webapps. I use this to unite several different chat apps (Google Messages, Hangouts, Discord). The Facebook Messenger portal doesn't play nice with video calling, so I use [Caprine](https://sindresorhus.com/caprine/) for that.

## Icons and other art

* [deviantart](https://www.deviantart.com/): So much to see here! Some of my favorites include (but are not limited to)...
  
  * anything by [Niivu](https://www.deviantart.com/niivu), especially [his Windows themes (now on github!)](https://github.com/niivu/Windows-11-themes)
  * the  `iconic creations' of [Octaviotti](https://www.deviantart.com/octaviotti)
  * [Mnemo 'n' icons by hechiceroo on DeviantArt](https://www.deviantart.com/hechiceroo/art/Mnemo-n-icons-413224458): gorgeous filetype icons
  * the cursor icon themes by vladsukhetskyi, such as [VS Cursor 11.0 Premium](https://www.deviantart.com/vladsukhetskyi/art/VS-Cursor-11-0-Premium-900146070) 

* [atomcorp](https://github.com/atomcorp) has collected [many Windows Terminal themes](https://windowsterminalthemes.dev/) in an easy to navigate website

* [dpcdpc11](https://dpcdpc11.gumroad.com/) over on [gumroad](https://gumroad.com/) creates nice themes, wallpapers, and cursor sets

* searching [dribbble](https://dribbble.com/) for "[icon replacement](https://dribbble.com/search/icon-replacement)" turns up a number of gorgeous icon designs, though almost none are ready-to-use. (One solution: Take a screenshot and grab the actual icon using the "select subject" tool in Photoshop. Alternatvely, one can run the screenshot through [remove.bg](https://remove.bg).) A favorite artist of mine is [Sandor](https://dribbble.com/sandor).

* [500px](https://500px.com): brilliant way to discover photos, many of which make excellent wallpapers.

* [wallhaven](https://wallhaven.cc): large database of wallpapers.

* Google photo albums of all [Windows wallpapers](https://photos.app.goo.gl/7xH7UuhLAjLZdtrs5) and [Windows beta wallpapers](https://photos.app.goo.gl/r8BMfQhc3vDW8Ehq5), all [MacOS wallpapers](https://goo.gl/photos/HjY1hmo6p3jfFz8a7), and all [iOS wallpapers](https://goo.gl/photos/ZVpabTtcezd35XBa9).

* [IconArchive](https://iconarchive.com/): Remarkably extensive collection of icons. Plug in a keyword and look for something in a style that suits you.

* [macOSicons](https://macosicons.com) has a MacOS-style icon for almost everything.

* those who appreciate the Windows 10/11 icon design language will want to check out the [Fluency collection](https://icons8.com/icons/fluency) at [icons8](https://icons8.com). See also [this repository](https://github.com/icon11-community/Folder11) for folder icons.

* there are an endless number of different styles of Linux icons; I am partial to  elementaryOS. Many icons in that style are collected [here](https://github.com/Macintosh98/elementosh-icons). 

* I subscribe to the philosophy that emulators for retro-gaming should have retro-styled icons,  such as the [Antiseptic icons by starvingartist](https://www.deviantart.com/starvingartist/art/Antiseptic-Videogame-Systems-23217105), those found in [Ruckage's Snes Mini EmulationStation theme for Retropie](https://github.com/ruckage/es-theme-snes-mini), [ClusterM's hakchi2](https://github.com/ClusterM/hakchi2), [Faustbear's Additional Icon Pack 2.1 for Hakchi/CE/NESC/SNESC](https://imgur.com/gallery/09qQibS) and [JaffaCakeLover's Pixel Gaming Machine Icons](https://www.deviantart.com/jaffacakelover/art/Pixel-Gaming-Machine-Icons-413704203). For WiiU, see also Taurosa's icons [here](https://www.deviantart.com/taurosa/art/Basic-WiiU-Icon-326889848) and [here](https://www.deviantart.com/taurosa/art/Deluxe-WiiU-Icon-326889969).  

## Windows settings and Hacks

* Disable UAC and open all apps as administrator (registry hack) `REG ADD HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /f /v EnableLUA /t REG_DWORD /d 0`

* Change taskbar icons of pinned UWP apps. One needs [Win7AppId1.1](https://code.google.com/archive/p/win7appid/downloads). Get the AppID of the desired app by running `get-StartApps | Format-Table | Out-String -width 9999` in PowerShell. Create a custom shortcut  to `explorer.exe shell:appsFolder\YOURAPPID`. Back in Powershell, run `Win7AppId1.1 "YourAppShortcut.lnk" "YOURAPPID"`. Change the icon of the shortcut to whatever you desire, then pin the icon to the taskbar. (Thanks to dpcdpc11 for making me aware of [this method](https://dpcdpc11.com/custom-taskbar-icons-guide/)!)

* One can change the Windows 11 Settings app icon by replacing files in `C:\Windows\ImmersiveControlPanel\images`. To change the taskbar icon, relace the `logo.targetsize*` pngs with images of the same size. 

* Refresh icon cache without restarting Windows. Run (Win+R): `cmd /c taskkill /f /im explorer.exe & del /a %userprofile%\AppData\Local\IconCache.db & start explorer`. You can also create a shortcut with this command as the target. (Taken from [this post](https://superuser.com/a/1300573).)

* Configure Stardock TouchTasks to open Task View. In Windows 10, swiping from the left edge opened the task view panel. In Windows 11, this action has been remapped to the widgets panel (boo!). While I don't know how to get the old swipe gesture back, one can at least map the task view panel to a tap on the middle left edge. First, [remove or disable Widgets](https://winaero.com/remove-and-uninstall-widgets-from-windows-11/#:~:text=In%20the%20Local%20Group%20Policy,Click%20Apply%20and%20OK.). Then install [nircmd](https://www.nirsoft.net/utils/nircmd.html) and create a shortcut to `C:\nircmd-x64\nircmd.exe sendkeypress lwin+tab` (replacing the location of nircmd appropriately). Then use TouchTasks to assign the shortcut link to a touchpoint. By default, TouchTasks looks for .exe files, but if you first enter *.lnk in the file dialogue and **then** select your shorcut, it gets properly assigned.

## Other resources

* [Scott Hanselman's list of tools for power users](http://hanselman.com/tools)

* [mydigitallife forums](https://forums.mydigitallife.net/): These folks are serious about Windows. See, e.g., this very large list of [Windows 11 tweaks, fixes, and modifications](https://forums.mydigitallife.net/threads/windows-11-tweaks-fixes-and-modifications-overview.83744/page-20#post-1687577). Forum registration required.

* [elevenforum](https://www.elevenforum.com/): Another venue for community discussions of Windows customization.  See also [tenforums](https://www.tenforums.com/). The tutorials ([Windows 10](https://www.tenforums.com/tutorials/1977-windows-10-tutorial-index.html), [Windows 11](https://www.elevenforum.com/tutorials/)) are particularly valuable.

***

[Trophy icon created by Freepik - Flaticon](https://www.flaticon.com/free-icons/trophy)
