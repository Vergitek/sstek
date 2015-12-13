### Introduction ###
**_ssTek_** is a name derived from "_SetupS Technologies_" and all the tools using that technology.

**_SetupS_**, meaning "_Setup Silently_", is the central tool responsible for the install and setup of certain deployment packages. These deployment packages have file extensions that SetupS automatically recognizes and can be installed simply by double clicking on those deployment package files. One can also use the context-menu "Sendto" option to install these packages or to install an entire folder of them.

Although not an installer itself but rather a "wrapper" for other installers, the main feature and advantage of SetupS is its advanced ability to customize an install for nearly any application or game and to do that install without user interaction. This is sometimes also called an _unattended_ install.

Another ssTek tool is **_ssWPI_** -- a highly modded (W)indows (P)ost (I)nstaller that works in conjunction with SetupS; and hence the name. ssWPI presents the user with a list of available deployment packages each with their own descriptions and screenshot/previews. The user can then select from any number of these items to install... all in one sitting... all without requiring any further interaction from the user.

Included with the SetupS suite is another application called SetupS Editor, or **_ssEditor_**, that can create these deployment packages for ssWPI or SetupS.

ssTek has several types of deployment packages available:

  * installer based apps, installed silently or unattended (_ssApp_)
  * a portable and permanent application (_ppApp_) and
  * a portable and permanent game (_ppGame_).

An advantage of ppApps or ppGames is that they can be located anywhere on any drive (i.e., _portable_) -- for example, "D:\ppApps" or "D:\ppGames". Another is that as long as they remain on a different drive than the operating system (OS) then even after a new OS is re-installed, these apps or games can then be "brought back to life" and reused exactly as they were before (i.e., they're also _permanent_). This recovery can be accomplished by means of another ssTek tool called **_ssRegenerator_**.

With ssTek a user can also opt for an _advanced startmenu_ structure that allows SetupS to automatically sort these apps or games while it is installing them or while they are being "regenerated". Of course the user can also opt for the _standard startmenu_ structure if that is preferred. The ssTek tool that does this is called the SetupS Control Panel, or **_ssControlPanel_**. And for cleaning dud shortcuts from the _advanced startmenus_ is **_ssCleaner_**, which can be accessed via the ssControlPanel.

Each ss/ppApp contains a file with an .app extension (or .ppg for ppGames). It is a text-file which contains all the essential install information, startmenu sorting, and shortcut options, etc. This SetupS-file basically tells SetupS how to install the app or game. It can also contain many other bits of information pertaining to the app or game.

There are also many other SetupS-recognized files a typical ssTek deployment package might use. Installers (in the case of ssApps), or archives (in the case of ppApps); and various graphics files not essential to the apps' installations, but are added to provide other fun things ssTek tools can do. For example, screenshots of the apps or games when used through ssWPI.

SetupS works with all the popular "NT-based" Windows, such as 7 / Vista / XP / 2008 / 2003 / 2000.<sup>1</sup> And best of all, ssTek tools are licensed under the open-source GNU GPL v3. For details, please see http://www.gnu.org/licenses/.

---

<sup>1</sup>_Disclaimer:_ Because of the many fundamental changes to the OS experience by Windows 8 and 2012 -- and although technically SetupS should work with them -- there is _NO GUARANTEE_ that all features will be functional or without some bugs. In other words, use of ssTek and all its tools with Windows 8 and 2012 is purely _AT ONE'S OWN RISK_.