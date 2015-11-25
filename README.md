NPP-PRO
=======================

<div style="text-align:center"><img src="http://www.vonox.fr/wp-content/uploads/2015/11/logo-npp.png" alt="npp-logo" width="150" style="margin-right:60px"><img src="http://www.vonox.fr/wp-content/uploads/2015/11/PTC_RGB_LOGOTYPE_GRAY.png" alt="ptc-logo" width="150"></div>

General Information
-------------
npp-pro is a collection of UDL[^1] files for [notepad++](https://notepad-plus-plus.org) text editor.

The goal is to highlight and auto-complete the config files for PTC© Pro/Engineer and Creo Parametric / Simulate.

The following files are supported:
* `.pro` 
* `.sup` ( same as .pro but for Creo or Pro/Engineer it is loaded last at startup )
* `.dtl` ( Drawing options )

Installation
-------------

1. Highlighting

* Download the file correspond to your version of Creo or Pro/Engineer ( WF4_XXX_highlight.xml for Wildfire 4 )
* In Notepad++, choose *`Language`* and then *`Define your language`* in the menu.
* In the dialog which is opened then, choose the button *`Import`* and then the appropriate XML file.

2. Auto Completion

* Download the file correspond to your version of Creo or Pro/Engineer ( WF4_XXX_autocompletion.xml for Wildfire 4 )
* **Important!** The name of this file must match the name of the UDL[^1].
* Then move this file in the `.\plugins\APIs` folder of your Notepad++ installation location, by default this is `C:\Program Files (x86)\Notepad++\plugins\APIs`.

> Repeat operations for each extensions you want to add in Notepadd++ ( `.pro` `.sup` `.dtl` )

Credits
-------------
* All data is extracted from a **great site** for all cad admin,  [proesite.com](http://www.proesite.com). Thanks to [Olaf Corten](https://www.ptcusercommunity.com/people/ocorten) for sharing his experience and works to community.
* Thanks to [Domenic Laritz](https://www.ptcusercommunity.com/people/DomenicLaritz) for this new base repo, you can see [the post on ptcusercommunity.org](https://www.ptcusercommunity.com/docs/DOC-7865)

[^1]: [User Defined Languages](http://docs.notepad-plus-plus.org/index.php/User_Defined_Languages)