# TANWindowMgr

When working with multiple screens you'll often find that windows don't stay where you put them when you move between monitor changes or even awaking from sleep. This small program allows you to save the location and size of selected windows so you can easily restore their location later. Simply place a shortcut to the program in your startup folder so it runs at boot. Open all the programs you want to save and place them where you want. Right-click the TAN Window Manager icon that will be in your tray and click 'Save Window Locations'. In the popup check the windows you want to save and click 'Save'. Now you can use the 'Restore Window Locations' button to magically move your saved windows back to where you placed them.

## Command Line Arguments

`-saveall`   Save all open windows to the configuration file  
`-restore`  Restore layout found in the configuration file  
`-autoexit`  Don't keep TANWindowManager active in the tray. |Useful with the above 2 switches.

### Examples
`TANWindowMgr.exe -saveall -autoexit`  
`TANWindowMgr.exe -restore -autoexit`

## Known Limitations
Does not reliably handle situations where you have multiple instances of the same program open.

## Getting Started

### Run the Pre-Built Binary

In the Releases section in the right-hand sidebar, click Version 1.2 and from 
there download TANWindowMgr.exe.

### Build it Yourself

1. Download Visual Studio Community 2019 from 
   https://visualstudio.microsoft.com/downloads/
2. During install, select at least the .NET desktop development
   tools.
3. Open the TANWindowMgr\TANWindowMgr.sln
4. Build | Build Solution or Ctrl+Shift+B
5. The .exe file will be created in the folder
   TANWindowMgr\TANWindowMgr\bin\Debug\TANWindowMgr.exe

## Author
Todd Nelson  
todd@toddnelson.net  
https://toddnelson.net
