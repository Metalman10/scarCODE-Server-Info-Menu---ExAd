scarCODE-Server-Info-Menu---ExAd

** I DO NOT TAKE CREDIT FOR MAKING THE MENU OR EXAD **

INSTALL
1. Go to your Config.cpp (Inside your mission file (Exile.Altis) and find class CfgXM8. Then Add this to your class CfgXM8..
class CfgXM8
{
	extraApps[] = {"scarCode"};
	
	class scarCode
	{
		title = "Server Info Menu";
		controlID = 66000;			
		logo = "ExadClient\XM8\Apps\scarCODE_Info\Icon.paa";
		onLoad = "ExAdClient\XM8\Apps\scarCODE_Info\onLoad.sqf";
		onOpen = "ExAdClient\XM8\Apps\scarCODE_Info\onOpen.sqf";
		onClose = "ExAdClient\XM8\Apps\scarCODE_Info\onClose.sqf";
	};
}; 

3. Drag and drop the scarCode folder into the root of your mission file. (Exile.Altis)

4. Go to your Description.ext located inside your mission file. And paste this at the bottom of your description.ext.

#include "scarCODE\ServerInfoMenu\hpp\CfgServerInfoMenu.hpp"
#include "scarCODE\ServerInfoMenu\hpp\RscDisplayServerInfoMenu.hpp"

5. Go to Exile.Altis\ExAdClient\XM8\Apps and drag and drop the ServerInfoMenu folder in the apps folder.

DONE!!

/////////////////////
//CONFIGURATON//////
///////////////////

Now head over to Exile.Altis\scarCODE\ServerInfoMenu\hpp\CfgServerInfoMenu.hpp to customize whatever you want!


---	CREDIT	----
Original Code - IT07
ExAd - Janski
Thanks John for helping me!
