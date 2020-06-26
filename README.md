# Exile-Australia-mission.pbo
This is a custom mission file for your exile server. For the Australia Map

I did not create these files. i have had them for about 4 years on my old pc.
All i did was rebuild the mission.pbo and made it work with Exile 1.0.41.
i also rebuilt the Mission.sqm file and redone all the traders.

REQUIRED MODS!!!
@Australia         https://forums.bohemia.net/forums/topic/182043-australia-version-509-release/
@PLPMarkers        https://steamcommunity.com/sharedfiles/filedetails/?id=495275491




INSTALLATION!!!!

Step 1.  Install a exile server like usual.

Step 2.  Place my Exile.Australia.pbo file in your << mpmissions >> folder.
  
Step 3.  Open your << @ExileServer >> folder and open your << config.cfg >> file and at the bottom of that file you need to change it like example below.


EXAMPLE!!! BEFORE.. 

class Missions
{
	class Exile
	{
		template = Exile.Malden;  // Exile.Namalsk, Exile.Altis, Exile.Tanoa, ExileEscape.Altis, ExileEscape.Tanoa
----------------------------------------------------------------------------------------------------------------------------
EXAMPLE!!! AFTER..

class Missions
{
	class Exile
	{
		template = Exile.Australia;  // Exile.Namalsk, Exile.Altis, Exile.Tanoa, ExileEscape.Altis, ExileEscape.Tanoa
-------------------------------------------------------------------------------------------------------------------------------

Step 4.  Add >>> @Exile;@ExileServer;@Australia;@PLPMarkers; <<< to your server start perameters.

Enjoy it should work.

If you experience any problems please leave a comment here.

Edit it how you want. this is just the basic australia mission.
