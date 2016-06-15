RK Launcher 0.5 Beta - Nightly Build

Requirements

    OS: Windows Vista/7/8/10

    Notes: This software does not work in Windows 95/98/Me/NT.
           Might work on Windows XP/2000 (Not tested).

Copyright


    The author (RaduKing) owns the full copyright to RK Launcher.

    I choose to allow the use of RK Launcher but only under the assumption that 
    the contents of this archive are not changed or altered in any way, and it's 
    contents are intact. For any reproduction, distribution, etc... written 
    approval from the owner (RaduKing) must be obtained.

    Default Icon set created by Philipp Antoni

    You are not allowed to distribute the included icons in any modified
    form or without RK Launcher

    The author assumes no responsibility, or gives any sort of guarantees for
    damages that may occur from using this software.

Download:

    

Contact:

    rklauncher@gmail.com

Note:

    since this is a nightly build some of the features may not work or are disabled

---------------------------------------
What's new in version 0.5 Beta:

- all files are built with Visual Studio 2013

RKLauncher.exe

- runs on Windows 10

---------------------------------------
What's new in version 0.41 Beta:

- all files are built with Visual Studio 2005
- switched from MFC to ATL/WTL

RKLauncher.exe

- fixed several OD docklets bugs
- added restore windows support
- added minimize position, new applications position settings
- fixed minimize problem with Firefox 1.5
- fixed RK Launcher accessing the HDD every second
- added minimized window menus
- fixed OD docklets sometimes crashing on removing
- fixed draging files onto items when dock locked
- added language support (language files in the 'lang' directory)
- added show minimized window icon option
- added Menu tab in Settings
- added "Show in Explorer" option for folders (click+Hold)
- added some more options to the folder view
- smooth item move
- updated Position settings
- fixed shortcuts for Office, WLM, etc...
- added Alt+Tab support for restoring minimized windows
- all "conf" files are now Unicode UTF-16 LE

---------------------------------------
What's new in version 0.4 Beta:

RKLauncher.exe

- themes and backgrounds changed completely
- added exclusions for apps/windows
- cannot drag excluded apps to dock
- Y'z Docklet support improved
- icons from any folder (added Browse button)
- browse for application in dock item properties
- hide label
- label transparency
- saves changes on windows restart
- saves items on change
- fixed wrong appearance of OD docklet in add docklets dlg
- fixed save on change for add docklet
- changed 'application' to 'docklet_yz' or 'docklet_od' in itemlist.conf
- added Hide Taskbar option
- added Hotspot for dock showing up when the mouse goes to margin
- added Import Y'z Dock background
- settings are saved when the Settings dialog closes
- fixed DockletSetImageFile not setting the right image
- added Hide Indicators
- added Hide Poofs
- ObjectDock Docklet support improved (still missing some features)
- added void DockletSetIndicator(HWND, BOOL) that's missing in OD Docklet SDK
- docklet settings are saved via OnSave in itemlist.conf
- added effect when a new item is shown in dock
- RK Launcher can go up to 200fps now
- opened applications now receive focus
- added *.ico files to icon browse dialog
- excluded items moved to 'excluded.conf' file
- added detection of fullscreen windows
- plugins support API modified
- added folder contents context menu on-hold folder items
- added hotspot delay
- added attention animation for minimized windows
- messenger windows jump on attention when minimized to dock
- added autohide delay
- added full margin hotspot
- added folder view on click+hold
- added drag to RecycleBin

YzDocklet.dll

- fixed YzDockletGetFolderPath unicode result
- fixed YzDockletGetRect giving client coords instead of screen coords
- fixed YzDockletGetInt not returning the default value (Tasks docklet)
- changed icon loading
- fixed some docklets not letting RK Launcher close
- no Y'z Docklet API can be called after RK Launcher is closing

---------------------------------------
What's new in version 0.3 Beta:

- first non alpha stable release
