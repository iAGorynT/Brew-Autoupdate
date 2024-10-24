# Brew Autoupdate
 Autoupdate zsh scripts and files used with Launchd, Launchctl, and other utilities on an Apple Mac Computer.
 
 **Installation:**
*  Copy Launchd Folder and it's contents to user's $HOME folder.
*  Copy bin folder and it's contents to user's $HOME folder.
*  Add $HOME/bin to $PATH (if not already there).
*  Add an alias command for Brewautom2.sh (Brew Autoupdate Manager).

**Other Files**
* BrewitLaunchd.sh: A zsh script used by Launchd to run the Brew Autoupdate User Agent.
* Launchd.plist: A Launchd plist template containing Key-Values used to generate a "User Specific" Launchd User Agent plist file.
 
 Modified: 10/24/2024 14:13
