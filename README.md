# Brew Autoupdate
 Autoupdate zsh scripts and files used with Launchd, Launchctl, and other utilities on an Apple Mac Computer.
 
 **Installation:**
* Copy BrewautoInstaller.sh to your home folder and run it.
* A $HOME/Launchd and $HOME/bin Folder will be created and populated with necessary scripts and files.
* Add an alias command to your .zshrc file for Brewautom2.sh (Brew Autoupdate Manager).
* Add $HOME/bin to your $PATH.

**Installed Files:**
* Brewautom2.sh:  Brew Autoupdate Manager.
* BrewitLaunchd.sh: Used by Launchd to run the Brew Autoupdate User Agent.
* Launchd.plist: A Launchd plist template containing Key-Values used to generate a "User Specific" Launchd User Agent plist file.
 
 Modified: 11/5/2024 18:31
