# csgoserver
Easy CS:GO Linux Game Server 
===================================================================

Features
========
 * Server installer (using SteamCMD)
 * Start/Stop/Restart server
 * Server updater (using SteamCMD)
 * Server Console
 * Server Status

Installation
============
Prerequisites
-------------
Before installing, please ensure you have all the dependencies required to run the script.

 `apt-get install wget curl tar tmux`

64 Bit reuqirements
-------------------

 `apt-get install ia32-libs-gtk`

Install
-------
Add a new user since the script will not run on the root user!

`adduser csgouser`

`passwd csgouser`
(use a more secure password!)

`su - csgouser`


Download the script and make it executable:

`wget https://raw.githubusercontent.com/lkrumpak/csgoserver/master/csgoserver && chmod +x csgoserver`

Run the installer and follow the instructions

`./csgoserver install`
