Easy CS:GO Linux Game Server 
===================================================================
Simple deployment and management of a Counter Strike: Global Offensive Linux dedicated server.

Features
========
 * Server installer (using SteamCMD)
 * Start/Stop/Restart server
 * Server updater (using SteamCMD)
 * Server Console

Installation
============
Prerequisites
-------------
Before installing, please ensure you have all the dependencies required to run the script.

 `sudo dpkg --add-architecture i386; sudo apt update; sudo apt install wget tar tmux lib32gcc1`

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
