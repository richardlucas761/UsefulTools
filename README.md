# UsefulTools

A README file listing useful  tools and tweaks.

## Windows

### O&O ShutUp10++: Free antispy tool for Windows 10 and 11

<https://www.oo-software.com/en/shutup10>

### O&O AppBuster: Free uninstaller for unwanted apps

<https://www.oo-software.com/en/ooappbuster>

### Fix Slow Startup App Delay on Windows 11

<https://github.com/GeovaniRgz/windows11-disable-startup-delay>

### Restore old Right-click Context menu in Windows 11

<https://learn.microsoft.com/en-gb/answers/questions/2287432/(article)-restore-old-right-click-context-menu-in>

#### Add

```
reg.exe add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve
```

#### Remove

```
reg.exe delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f
```

### Open-Shell

"A collection of utilities bringing back classic features to Windows."

<https://open-shell.github.io/Open-Shell-Menu/>

### Pathping

For example ```pathping google.com```

Because "Ping is not the best tool to be used to test the availability of a remote network."

See <https://superuser.com/questions/549617/no-reply-for-ping-command-what-does-this-mean>

### Test-netconnection

<https://learn.microsoft.com/en-us/powershell/module/nettcpip/test-netconnection?view=windowsserver2025-ps>

## Linux

### The Odin Project

<https://www.theodinproject.com/>

High quality coding education maintained by an open source community.

### Split a PDF into single pages

```qpdf Ticket_1.pdf --split-pages output.pdf```

### Cinnamon : add a coloured border to windows

Adds a subtle border for windows on Cinnamon. (Not all applications respect this setting).

Create a new file with this content called ```~/.config/gtk-3.0/gtk.css```.

Restart Cinnamon ```Ctrl+Alt+Esc```.

```CSS
headerbar {
  border: 3px solid #32435d;
  border-bottom-style: none;
}

decoration {
  border: 3px solid #32435d;
  background: #32435d;
}
```

<https://forums.linuxmint.com/viewtopic.php?p=2565965&sid=8b5fc99fc26a0f69ec5a42fccb42bc52#p2565965>

*When using a dark theme windows tend to blur into each other and this helps a little.*
