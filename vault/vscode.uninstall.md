---
id: YKHNItiNpEZdCeWDrVnNW
title: VSCode Uninstall
desc: ''
updated: 1637226463292
created: 1637225098897
---

# VSCode Uninstallation

When you uninstall VSCode, the extensions, settings, fodlers and many other things are not deleted alongside. Causing the issue of automatically picking up all of those settings, extensions etc making it a re-install process instead of fresh-install process.

In this the necessary steps required to fully delete the VSCode from you pc is explained. Follow the steps to make sure nothing is present in your pc after uninstalling the VSCode.

## 1. Uninstall VSCode

- First you need to run the VSCode uninstall programm.
* That can be located at
```
%LocalAppData%\Programs\Microsoft VS Code
```
* Paste this command in Run `Win+R` and hit enter.
* VSCode default installation directory should open up.
* Run the `unins000.exe` from that folder.
* Follow the simple instructions to uninstall the VSCode from your windows.

## 2. Removing extra folders

### a. AppData Folder

* Simply go to this location
```
C:\Users\UserName\AppData\Roaming
```
* Locate the folder called `Code`
* Delete that folder

### a. User Folder

* Simply go to this location
```
C:\Users\UserName\
```
* Locate the folder called `.vscode`
* Delete that folder


> 🗑️ Now `VSCode` has been fully removed from your pc alongside it's files.