# Brew Autoupdate
 Autoupdate zsh scripts and files used with Launchd, Launchctl, and other utilities on an Apple Mac Computer.
 
 **Installation:**
* Copy BrewautoInstaller.sh from the GitHub Repo. bin folder to your home folder and run it.
* A $HOME/Launchd and $HOME/bin Folder will be created and will contain necessary scripts and files.
* A "ShellScripts" Symbolic Link will be created in your home folder.
* Add an alias command to your .zshrc file for Brewautom2.sh (Brew Autoupdate Manager).
* Add $HOME/bin to your $PATH.

**Installed Files:**
* Brewautom2.sh: Brew Autoupdate Manager.
* BrewitLaunchd.sh: Used by Launchd to run the Brew Autoupdate User Agent.
* FLibFormatEcho.sh: Text formatting library for zsh scripts.
* Launchd.plist: A Launchd plist template containing Key-Values used to generate a "User Specific" Launchd User Agent plist file.
 
 Modified: 02/09/2025 13:03
