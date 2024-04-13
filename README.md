# ![trophy](./images/trophy-small.png "trophy") winning-at-windows

Windows 11 software and tweaks that *I* find useful. The list is (intentionally) personal and is not meant to be a comprehensive database of all programs of this kind. While the software mentioned below has proven useful to me, not all carbon-based life forms  share the same workflow or tastes. Consider yourself warned.

Software previously listed that I have taken out of rotation is [here](deprecated.md).

## "Ricing" (appearance customization)

* [Stardock software](https://www.stardock.com/): Several tools for Windows customization, such as [IconPackager](https://www.stardock.com/products/iconpackager/) (replaces the most common system icons), [WindowFX](https://www.stardock.com/products/windowfx/) (adds effects when opening, closing, minimizing, moving windows), [TouchTasks](https://www.stardock.com/products/touchtasks/) (triggers actions by touching certain screen corners), and [Start11](https://www.stardock.com/products/start11/) (alternative start menu layouts).

* Fans of alternative start menus will also want to check out [StartAllBack](https://www.startallback.com/) and [Open-Shell](https://github.com/Open-Shell/Open-Shell-Menu).

* [MyDockFinder](https://store.steampowered.com/app/1787090/MyDockFinder/): Mac-like dock and Finder bar. Pro-tip: To get a weather status icon on the finder bar, also set up [Tray Weather](https://github.com/FelixdelasPozas/TrayWeather).

* [WinDynamicDesktop](https://github.com/t1m0thyj/WinDynamicDesktop): wallpaper that changes with the time of day, a la MacOS.

* for animated wallpapers, check out [Wallpaper Engine](https://www.wallpaperengine.io/en) or (an open source alternative) [Lively Wallpaper](https://www.rocksdanister.com/lively/)

* [ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica): Adds a background blur effect to Explorer windows.

* [TranslucentFlyouts](https://github.com/ALTaleX531/TranslucentFlyouts): Adds a background blur effect to context menus.

* [RoundedTB](https://github.com/RoundedTB/RoundedTB): Add margins and/or rounded corners to the taskbar.

* [WinPaletter](https://github.com/Abdelrhman-AK/WinPaletter): Originally began as a tool to customize Windows accent colors(useful for tweaking the titlebar appearance, for instance). Now does much more, allowing one to manage everything from sounds to icons to fonts!

* [ModernFlyouts](https://modernflyouts-community.github.io/): Modern-looking pop-up indicators for changing volume, brightness, toggling caps-lock, etc. 

* [filetypesman](https://www.nirsoft.net/utils/file_types_manager.html): tool for managing filetype icons and associations. A useful alternative is [types](https://ystr.github.io/types/). The latter hasn't been updated in several years but seems to work OK on Windows 11; in fact, unlike filetypesman it doesn't seem to stop responding for unknown reasons.

* [Resource Hacker](https://angusj.com/resourcehacker/): view and edit resources in EXE, DLL, and related files. Essential tool for changing stubborn icons. To gain permissions to customize icons built in to Windows, you will want to run Resource Hacker with something like [NSudo](https://github.com/M2Team/NSudo). Windows keeps many (but not all) of its icons in **\Windows\SystemResources\shell32.dll.mun** and **\Windows\SystemResources\imageres.dll.mun**.

  * Sample usage: On Windows 11, IconPackager does not change the icon for nonempty folders. For this, one should replace Icon Group 162 in imageres.dll.mun.
  * On Win11 22H2 or above, to disable folder thumbnail previews, overwrite Icon Group 6 in imageres.dll.mun with your generic folder icon. To change the Home icon in the File Explorer sidebar, overwrite Icon Group 51380 in shell32.dll.mun. (But Windows can be finicky about granting permissions; a simpler solution is to [remove the home icon altogether](https://www.elevenforum.com/t/add-or-remove-home-in-navigation-pane-of-file-explorer-in-windows-11.2449/)!)

* [namazso/SecureUxTheme: A secure boot compatible in-memory UxTheme patcher (github.com)](https://github.com/namazso/SecureUxTheme): allows one to apply custom themes without modifying system files, and without rebooting (!)

* [Rainmeter](https://www.rainmeter.net/): tool for displaying desktop widgets. An endless number of Rainmeter skins are on deviantArt (but beware that many, especially ones that are older, do not play nice with modern high DPI displays). If you use a tablet or frequently change screen resolutions for any other reason, grab [RainRez](https://forum.rainmeter.net/viewtopic.php?f=18&t=10471&hilit=rainrez) as well.

  * [Droptop](https://github.com/Droptop-Four): Rainmeter skin providing a highly customizable menu bar at the top of the screen (think MacOS). Even better when used with [Yaron's System Monitor](https://github.com/Yaron2334/SystemMonitor/) app (requires [HWiNFO](https://www.hwinfo.com/)).

  * [Omnimo](https://omnimo.info/), [Big Sur](https://www.deviantart.com/fediafedia/art/Big-Sur-1-0-BETA-for-Rainmeter-846882462?comment=1%3A846882462%3A4964685064), and [Longhorn Sidebar](https://www.deviantart.com/fediafedia/art/Longhorn-Sidebar-for-Rainmeter-947066452): (deservedly) popular skin suites for Rainmeter, by [fediafedia](https://fediafedia.com/). If you like Mac-style widgets, see also [MontereyRainmeter](https://github.com/creewick/MontereyRainmeter) by creewick.

  * Jax enjoys [pushing the limits of what one would think is possible with Rainmeter](https://jaxcore.app/). For example, [YourFlyouts](https://www.deviantart.com/jaxoriginals/art/919259685) is a pretty great ModernFlyouts alternative.

* prettify Explorer by adding thumbnail previews for more filetypes: for many common filetypes, see the links under "image thumbnails" [here](https://www.zabkat.com/x2plugins.htm). Also: [DJVU](https://www.cuminas.jp/en/downloads), [SVG](https://github.com/EtheaDev/SVGShellExtensions). For PDF, one can use the shell extension built into [Sumatra](https://www.sumatrapdfreader.org/free-pdf-reader) (worth having around for many other reasons!).

* [No!! Meiryo UI](https://github.com/Tatsu-syo/noMeiryoUI):  Change Windows system fonts. Allows more fine-grained control than (say) WinAeroTweaker.

* [Sound Manager](https://github.com/ORelio/Sound-Manager): "Sound schemes" are back, for those old enough to remember and shameless enough to admit it. The only way I know to set a custom startup chime on Windows 11. (Even modifying imageres.dll.mun didn't work for me.)

* Sure, you don't need a screen saver these days, but don't you want one? [Screensavers Planet](https://www.screensaversplanet.com/) has a ton, including retro classics like [Flying Toasters](https://www.screensaversplanet.com/screensavers/after-dark-flying-toasters-1153/) and [Johnny Castaway](https://www.screensaversplanet.com/screensavers/johnny-castaway-237/).

* Firefox extensions:
  * [Edge-style vertical tabs](https://github.com/ranmaru22/firefox-vertical-tabs) for Firefox
  * [Stylus](https://github.com/openstyles/stylus): Browser extension that can customize the appearance of websites via injected CSS, with a [large database of prebuilt scripts](https://userstyles.world/). (One can also use [scripts for the competing, sketchier extension Stylish](https://userstyles.org).)
  * [Wikiwand](https://www.wikiwand.com/): Modernizes the Wikipedia UI; customizable.
  * [Tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/): More userscript goodness.
  * [Bonjourr](https://addons.mozilla.org/en-US/firefox/addon/bonjourr-startpage/): my preferred minimalist startpage.

## System maintenance and optimization


* [Process Explorer](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer): Task Manager on steroids. Useful for searching handles and DLL processes.

* [Chocolatey](https://chocolatey.org/): package manager for Windows, through powershell. Slowly being replaced in my life by [winget](https://winget.run/).

* [Autoruns for Windows](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns): comprehensive startup process manager.

* [WizTree](https://diskanalyzer.com/): shows, visually, which files are taking up space on your drive.  Very fast on NTFS-formatted drives. A (paid) alternative with a nicer UI is [FolderSizes](https://www.foldersizes.com/).

* [Bulk Crap Uninstaller](https://www.bcuninstaller.com/): Thorough uninstall tool. Advanced detection capabilities (e.g., knows about programs installed through chocolatey) as well as leftover detection features. A less thorough but much faster-to-start program in the same vein is [geek uninstaller](https://geekuninstaller.com/).

* [O&O RegEditor](https://www.oo-software.com/en/ooregeditor): User-friendly registry editor. Far superior search functions vs the built in RegEdit.

* [Compactor](https://github.com/Freaky/Compactor): GUI to Windows' built in file and folder compression tools. Useful especially (but not only) for games.

* [FileOptimizer](https://nikkhokkho.sourceforge.io/static.php?page=FileOptimizer): Lossless file size reduction for many different file formats. Saved me about 0.87 GB when run on roughly 10 GB worth of PDFs (~ 600 files).

* [czkawka](https://github.com/qarmin/czkawka): comprehensive tool for finding unnecessary files (empty files and directories, duplicate music/videos/images, etc.). Useful for bringing in after the "usual suspects" have been obliterated with a surface-level cleaner such as [BleachBit](https://www.bleachbit.org/).

* [Mp3tag](https://www.mp3tag.de/en/): easily edit audio files' metadata. Useful when you notice that only half of an album's MP3s are displaying the correct cover art.

* [Veeam Agent](https://www.veeam.com/agent-for-windows-community-edition.html): totally painless way to manage incremental backups of your entire system. Free!


## Usability/Quality of life enhancements

* [Microsoft PowerToys](https://github.com/microsoft/PowerToys): Microsoft's own collection of quality-of-life enhancements for Windows. Favorites of mine are 
  * Always on Top: self explanatory,
  * Awake: prevents your PC from going to sleep,
  * Color Picker: mouseover a pixel to get the color code,
  * FancyZones: snap windows into preset configurations,
  * File Locksmith: determines which processes are using a file or folder and offers you the option of terminating them,
  * Text Extractor: OCRs a selected region of your screen and places the resulting text in your clipboard.

  I use [XnShell](https://www.xnview.com/en/xnshell/) instead of Image Resizer.

* [Listary](https://www.listary.com/pro): Terrific search bar for Windows. Adds the ability to quickly find and open files from any "open file" dialogue. No more navigating seas of directories: truly a killer feature!

* [WinSetView](https://github.com/LesFerch/WinSetView): Easily set your default view in Windows File Explorer --- for example, to always show details. 

* [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher): restores functionality from Windows 10 that was removed in the "upgrade" to Windows 11 (and does much else besides). I like the clean-looking Alt-Tab replacement that the author built in as well as the taskbar weather widget.

* [Everything](https://www.voidtools.com/) and [EverythingToolbar](https://github.com/srwi/EverythingToolbar): Instant search by filename. I have had strange seeming search results with Fluent Search as it comes out of the box; Everything, without trying to be as clever, often gets me directly where I want to go, and it can be configured as the Fluent Search indexing engine. EverythingToolbar seamlessly integrates Everything into the Windows taskbar.

* [DragDropConfirm](https://github.com/broken-e/DragDropConfirm): Adds a confirm dialogue when dragging/dropping to move files in Explorer. Useful for those with touchscreen devices and wandering fingers.

* [Winaero Tweaker](https://winaero.com/winaero-tweaker/): adjust many (!) "secret" Windows settings. For example, you can modify which folders show up under This PC, and you change the Quick Access icon in the navigation pane (though for me this always results in a duplicate navigation pane icon; seems better to avoid WinAeroTweaker for this and just directly edit the registry key `HKEY_CLASSES_ROOT\CLSID\{679f85cb-0220-4080-b29b-5540cc05aab6}\DefaultIcon`).

* [EarTrumpet](https://github.com/File-New-Project/EarTrumpet): Replacement for the Windows system tray audio control widget. Much more functional, e.g., including per-app volume control.

* [ExtractNow](https://extractnow.com/): archive handler. Allows one to unzip/unrar/etc. by double clicking the archive. Quite customizable.

* [SnipDo](https://snipdo-app.com/): Formerly known as PantherBar. Whenever you select text, pops up a menu with possible ``quick actions'' (such as copy, cut, search in Google, run through Google Translate).

* [Snipaste](https://www.snipaste.com/): full-featured and customizable screen snipping tool. Can auto-detect certain portions of the screen that are natural candidates for capture.

* [QuickLook](https://github.com/QL-Win/QuickLook) or [Seer](http://1218.io): instant file preview in File Explorer, upon pressing the space bar (as in MacOS).

* [Ditto](https://ditto-cp.sourceforge.io/): good looking clipboard manager for Windows.

* [AltSnap](https://github.com/RamonUnch/AltSnap): Reposition Windows by pressing Alt and left-clicking, from anywhere (no need to grab a Window edge). Resize by pressing Alt and right-clicking. Put Windows always on top (or roll them up, close, minimize, ...) by pressing Alt and middle-clicking.

* [JDownloader](https://jdownloader.org/): Download manager. Not the prettiest, but feature rich. Quite useful for bulk downloading. A bit ad-ridden by default, but [this can be tweaked](https://superuser.com/questions/1297098/how-to-disable-ads-in-jdownloader).

* [ShareDrop](https://www.sharedrop.io/): Easy between-device file sharing, even between devices on different networks.

* [windows-terminal-quake](https://github.com/flyingpie/windows-terminal-quake): Quake mode for Windows Terminal.  Yes, Windows Terminal already has a built in Quake-mode, but the devs are still working out some kinks (see, e.g., [this issue](https://github.com/microsoft/terminal/issues/9996)). For now I prefer this.

* [BatteryInfoView](https://www.nirsoft.net/utils/battery_information_view.html): Displays information on your battery (e.g., charging status/rate and wear level).

* Alternative battery widgets
  
  * [BatteryBar](https://batterybarpro.com/): good-looking battery meter capable of displaying calibrated runtime estimates. Can be floating or (if you use something like ExplorerPatcher) pinned as a toolbar to the standard taskbar.
  * [BatteryMode](https://github.com/tarcode-apps/BatteryMode): similar to the standard tray widget, but with built in functionality to change the power plan and with more customization options (e.g., the ability bring back the Windows 7 battery tray icon).
  * [CircleBattery](http://rebelvalkyrie.com/?page=circle-battery): tray widget where remaining battery power is displayed in a glowing circular arc. A press in the middle prevents your computer from locking or going to sleep.

* [OnTopReplica](https://github.com/LorenzCK/OnTopReplica): generates a resizable, always on-top-replica of a window or window region. Lets you roll your own PIP mode for programs lacking native support (looking at you, [Stremio](https://www.stremio.com/)).

* [MiniBin](https://download.cnet.com/minibin/3000-2094_4-75451640.html): open and empty the recycle bin from the system tray. Themeable.

* [SuperF4](https://stefansundin.github.io/superf4/): when Alt-F4 isn't good enough. Forcefully kill foreground apps with Ctrl-Alt-F4. Endorsed by Bowser.

* [ShellExView](https://www.nirsoft.net/utils/shexview.html), [ShellMenuView](https://www.nirsoft.net/utils/shell_menu_view.html), [ShellMenuNew](https://www.nirsoft.net/utils/shell_menu_new.html), and [OpenWithView](https://www.nirsoft.net/utils/open_with_view.html): Remove unwanted entries from Explorer's (old school) right-click context menu.  

* [Incipitor](https://www.dcmembers.com/bgmcoder/download/incipitor/): automates the process of adding shortcuts to the Windows start menu.

* [Desktop Media](https://www.softpedia.com/get/Desktop-Enhancements/Other-Desktop-Enhancements/Desktop-Media.shtml): add icons for available drives to the Windows desktop.

* [notepad-replacer](https://github.com/olohmann/notepad-replacer): redirects calls to `notepad.exe` to your favorite text editor (e.g., [Notepad++](https://notepad-plus-plus.org/)).

## Apps for minimalists

* [nomacs](https://github.com/nomacs): image viewer that is simultaneously minimal and feature-rich.

* [mupdf](https://mupdf.com/): hyperminimal PDF viewer. (No, really. More minimal than even  [Sumatra](https://www.sumatrapdfreader.org/free-pdf-reader).) Also check out [Sioyek](http://sioyek.info/) if you don't need touchscreen scrolling or zooming.

## Icons and other art

* [deviantart](https://www.deviantart.com/): So much to see here! Some of my favorites include (but are not limited to)...
  
  * anything by [Niivu](https://www.deviantart.com/niivu), especially [his Windows themes (now on github!)](https://github.com/niivu/Windows-11-themes)
  * the  `iconic creations' of [Octaviotti](https://www.deviantart.com/octaviotti)
  * [Mnemo 'n' icons by hechiceroo on DeviantArt](https://www.deviantart.com/hechiceroo/art/Mnemo-n-icons-413224458): gorgeous filetype icons
  * the cursor icon themes by vladsukhetskyi, such as [VS Cursor 11.0 Premium](https://www.deviantart.com/vladsukhetskyi/art/VS-Cursor-11-0-Premium-900146070)

* [atomcorp](https://github.com/atomcorp) has collected [many Windows Terminal themes](https://windowsterminalthemes.dev/) in an easy to navigate website

* [dpcdpc11](https://dpcdpc11.gumroad.com/) over on [gumroad](https://gumroad.com/) has several pretty themes, wallpapers, and cursor sets for sale

* searching [dribbble](https://dribbble.com/) for "[icon replacement](https://dribbble.com/search/icon-replacement)" turns up a number of gorgeous icon designs, though almost none are ready-to-use. (One solution: Take a screenshot and grab the actual icon using the "select subject" tool in Photoshop. One gets somewhat more reliable results by instead running the screenshot through [remove.bg](https://www.remove.bg/).) A favorite artist of mine is [Sandor](https://dribbble.com/sandor).

* [500px](https://500px.com): brilliant way to discover photos, many of which make excellent wallpapers.

* [wallhaven](https://wallhaven.cc): large database of wallpapers.

* Google photo albums of all [Windows wallpapers](https://photos.app.goo.gl/7xH7UuhLAjLZdtrs5) and [Windows beta wallpapers](https://photos.app.goo.gl/r8BMfQhc3vDW8Ehq5), all [MacOS wallpapers](https://goo.gl/photos/HjY1hmo6p3jfFz8a7), and all [iOS wallpapers](https://goo.gl/photos/ZVpabTtcezd35XBa9).

* [IconArchive](https://iconarchive.com/): Remarkably extensive collection of icons. Plug in a keyword and look for something in a style that suits you.

* [macOSicons](https://macosicons.com) has a MacOS-style icon for almost everything.

* those who appreciate the Windows 10/11 icon design language will want to check out the [Fluency collection](https://icons8.com/icons/fluency) at [icons8](https://icons8.com). See also [this repository](https://github.com/icon11-community/Folder11) and [this one](https://github.com/sameerasw/folder-icons) for folder icons.

* there are an endless number of different styles of Linux icons; I am partial to  elementaryOS. Many icons in that style are collected [here](https://github.com/Macintosh98/elementosh-icons).

* I subscribe to the philosophy that emulators for retro-gaming should have retro-styled icons,  such as the [Antiseptic icons by starvingartist](https://www.deviantart.com/starvingartist/art/Antiseptic-Videogame-Systems-23217105), those found in [Ruckage's Snes Mini EmulationStation theme for Retropie](https://github.com/ruckage/es-theme-snes-mini), [ClusterM's hakchi2](https://github.com/ClusterM/hakchi2), [Faustbear's Additional Icon Pack 2.1 for Hakchi/CE/NESC/SNESC](https://imgur.com/gallery/09qQibS) and [JaffaCakeLover's Pixel Gaming Machine Icons](https://www.deviantart.com/jaffacakelover/art/Pixel-Gaming-Machine-Icons-413704203). For WiiU, see also Taurosa's icons [here](https://www.deviantart.com/eriaciaite/art/Basic-WiiU-Icon-326889848) and [here](https://www.deviantart.com/taurosa/art/Deluxe-WiiU-Icon-326889969).  

## Windows settings and Hacks

* Add items to the (classic) right-click context menu. Here is an example of adding a command to trim margins from PDF files (using [pdfCropMargins](https://github.com/abarker/pdfCropMargins)), in a form ready to be saved as a reg file and imported via regedit.

  ```

  Windows Registry Editor Version 5.00

  [HKEY_LOCAL_MACHINE\SOFTWARE\Classes\MuPDF\shell]

  [HKEY_LOCAL_MACHINE\SOFTWARE\Classes\MuPDF\shell\Trim margins]
  "Icon"="\"C:\\Users\\anon\\Insync\\OneDrive\\Pictures\\Custom taskbar icons\\crop.ico\""

  [HKEY_LOCAL_MACHINE\SOFTWARE\Classes\MuPDF\shell\Trim margins\command]
  @="C:\\Python310\\Scripts\\pdf-crop-margins.exe \"%1\""

  ```

  To operate on files other than PDF, open the extension in [Types](https://ystr.github.io/types/); "MuPDF" in the above should be replaced with whatever you see in the "Class" field. Of course, the above icon path and command names (both the name "Trim margins" and the actual command to be executed in the final line) also need to be tailored to your application.

* Disable UAC and open all apps as administrator (registry hack) `REG ADD HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /f /v EnableLUA /t REG_DWORD /d 0`

  *Warning*: This breaks installation of the [Google Play store version of the Windows Subsystem for Android](https://github.com/creative-builds/WSA-Magisk/releases/). Temporarily disable this hack (change the 0 to a 1 at the end of the last command) before attempting an install. 

* Change taskbar icons of pinned UWP apps. One needs [Win7AppId1.1](https://code.google.com/archive/p/win7appid/downloads). Get the AppID of the desired app by running `get-StartApps | Format-Table | Out-String -width 9999` in PowerShell. Create a custom shortcut  to `explorer.exe shell:appsFolder\YOURAPPID`. Back in Powershell, run `Win7AppId1.1 "YourAppShortcut.lnk" "YOURAPPID"`. Change the icon of the shortcut to whatever you desire, then pin the icon to the taskbar. (Thanks to dpcdpc11 for making me aware of [this method](https://dpcdpc11.com/custom-taskbar-icons-guide/)!)

* One can change the Windows 11 Settings app icon by replacing files in `C:\Windows\ImmersiveControlPanel\images`. To change the taskbar icon, relace the `logo.targetsize*` pngs with images of the same size.

* [Remove the time and date from the Windows taskbar.](https://www.thewindowsclub.com/hide-clock-and-date-from-taskbar-windows-10)

* Refresh icon cache without restarting Windows. Run (Win+R): `cmd /c taskkill /f /im explorer.exe & del /a %userprofile%\AppData\Local\IconCache.db & start explorer`. You can also create a shortcut with this command as the target. (Taken from [this post](https://superuser.com/a/1300573).)

* Rebind built-in hotkeys. For example, I prefer Win-S to open Everything search vs. Windows' built-in search. For this, I set Everything to open with the obscure hotkey combination Ctrl-Alt-U. Then I run the one-line [AutoHotkey](https://www.autohotkey.com/) script `#S::SendInput ^!u`.

* Windows 11's implementation of widgets doesn't allow you to hide the news feed. One can at least [remove or disable Widgets](https://winaero.com/remove-and-uninstall-widgets-from-windows-11/#:~:text=In%20the%20Local%20Group%20Policy,Click%20Apply%20and%20OK.) entirely.

## Other resources

* [Scott Hanselman's list of tools for power users](http://hanselman.com/tools)

* retrial's [Windows Ultimate Collection Guides](https://xdaforums.com/t/windows-ultimate-collection-guides.4507867/) (curated software lists) at the XDA forums

* [mydigitallife forums](https://forums.mydigitallife.net/): These folks are serious about Windows. See, e.g., th is very large list of [Windows 11 tweaks, fixes, and modifications](https://forums.mydigitallife.net/threads/windows-11-tweaks-fixes-and-modifications-overview.83744/). Forum registration required.

* [elevenforum](https://www.elevenforum.com/): Another venue for community discussions of Windows customization.  See also [tenforums](https://www.tenforums.com/). The tutorials ([Windows 10](https://www.tenforums.com/tutorials/1977-windows-10-tutorial-index.html), [Windows 11](https://www.elevenforum.com/tutorials/)) are particularly valuable.

* [Courage-1984](https://github.com/Courage-1984/Windows-Ricing-Privacy-Customization-Optimization) has put together a useful list, similar in spirit to this one, but including a focus on security and privacy.

***

<a href="https://www.flaticon.com/free-icons/trophy" title="trophy icons">Trophy icon created by Freepik - Flaticon</a>
