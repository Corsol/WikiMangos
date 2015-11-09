[![](/wiki/icons/home.gif)](/wiki/Home.md) 
[![](/wiki/icons/back.gif)](/wiki/Installation%20Guides/Installation%20Guides.md)

----------

##How to Setup a MaNGOS Server
 
(without using repacks)

This document will explain how to setup a MaNGOS World of Warcraft Server with MaNGOS Universal Installer tool on Windows and Linux systems.

Supported cores:
* MaNGOS Zero (WoW 1.12.1)
* MaNGOS One (WoW 2.3.4)
* MaNGOS Two (WoW 3.3.5)
* MaNGOS Three (when the develop21 release will be done) (WoW 4.3.4)

###Obtain the MaNGOS Universal Installer tool

First of all you need to download the latest MaNGOS Universal Installer version from repository.
You can download the zip with files ready to use from [MaNGOS UI zip](https://github.com/Corsol/MaNGOSUI/archive/master.zip) or from git (if already installed) from [MaNGOS UI repository](https://github.com/Corsol/MaNGOSUI)

When the folder with MaNGOSUI.jar file is ready you can run it with .bat or .sh batch (for Windows or Linux systems) and start the setup operation.
Thoose batch will work only if your environment java installation is greater or equals to 1.7 update 79 (32 or 64 bits).
If you have multiple JAVA version installed you can edit the batch file and specify the path for correct java home.

**Note**: To download a new JAVA version look on [Latest JAVA](https://www.java.com/download/).
**Note**: The folder where MaNGOSUI.jar file will be placed will become the root for downloads, configuration and setups. The MaNGOS server install folder can be different from this one and can be specified on setup steps.

###Server configuration

Before start every setup activity MaNGOS UI will check if your system have every dependency installed like MySQL, OpenSSL, CMake, Git, etc...
On Linux systems you can start setup steps without pre-install dependencies and let MaNGOS UI to install it for you. On Windows systems MaNGOS UI show links to every dependency need to be downloaded and installed manually.

**Note**: To run MaNGOS UI you do not need every dependencies installed, but you will be able to use only some feature (that has dependency installed).

###Downloading and Importing the Database Data

First step to do is to download the source. Before start the download you need to select the MaNGOS core you want to configure and install.
There are two main and one optional sources:
* Database: sources with databases structure for server.
* Server: sources for server compilation and build.
* LUA scripts (optional): sourcce for additional scripts like game event, object event, and other...

From interface you can choose for every source to do a new download (wiping current data if present) or check the updates from main repository.
![Sources downloads](/database.png "Sources download")

##Compiling the MaNGOS source code

##Extracting Game Data

#Resolving Issues
