# qb-dildo

Im still working on this so please give me time but the basics are here.

A dildo to use as a weapon.


**Manual**
1. Place qb-dildo in you're server recources folder and add it to the server config.cfg

2. Add this line below to: qb-core\shared\items	
	
		['weapon_dildo'] 		         = {['name'] = 'weapon_dildo', 		        	['label'] = 'dildo', 	                ['weight'] = 1000, 		['type'] = 'weapon',   	['ammotype'] = nil,						['image'] = 'weapon_dildo.png',           ['unique'] = true,      ['useable'] = false, 	['description'] = 'Dildo'},
	
3. Add this line below to: qb-core\shared\weapons

			[`weapon_dildo`] 			     = {['name'] = 'weapon_dildo', 			['label'] = 'dildo', 				['ammotype'] = nil,	['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},


4. Add the image (weapon_dildo.png) to qb-inventory/html/images

5. Start/Restart you're server


Original mod https://www.gta5-mods.com/weapons/dildo
