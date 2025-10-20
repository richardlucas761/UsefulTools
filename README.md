# UsefulTools
A README file listing some useful tools and tweaks.

## O&O ShutUp10++: Free antispy tool for Windows 10 and 11

https://www.oo-software.com/en/shutup10

## O&O AppBuster: Free uninstaller for unwanted apps

https://www.oo-software.com/en/ooappbuster

## Fix Slow Startup App Delay on Windows 11

https://github.com/GeovaniRgz/windows11-disable-startup-delay

## Restore old Right-click Context menu in Windows 11

https://learn.microsoft.com/en-gb/answers/questions/2287432/(article)-restore-old-right-click-context-menu-in

### Add

```
reg.exe add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve
```

### Remove

```
reg.exe delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f
```
