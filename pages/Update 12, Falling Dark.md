- Vehicles
	- Added new US “M4A3 75w” medium tank
	- Added Machine guns to Half-tracks (M2 Browning, MG42)
	- Reimplemented the German “Panther” as a heavy tank with updated [[Smart materials]]
	- Updated [[Tiger]] with new camo pattern
	- Updated [[Panzer IV]] with new camo pattern
	- Updated [[Luchs]] with new camo pattern
- Weapons
	- Added [[Flare gun]]s (LP-42, SPSh-42, AN-M8)
- Loadouts
	- Added [[Flare gun]] to Spotter lvl 3 “Scout” loadout
	- Moved Ammo Crate from Spotter lvl 3 “Scout” to Spotter lvl 1 “Standard Issue” loadout
- Cosmetics
	- Added 2 new DLC uniforms for the [[Commander]] role
		- [[Upper Echelon]]
		- [[Red Marshall]]
- Gameplay/Features
	- Added the following new [[Commander]] Abilities:
		- [[Precision Strike]]
		- [[Germany]] : Stuka Dive Bomb
		- [[US]]: x2 P-47 Bombs
		- [[Soviet]] : IL-2 Rocket Strafe
		- Ammo Drop
- Improved animations for the strafing run Commander Ability
- Added separate volume controls for Proximity, Unit and Leadership VOIP channels
- Added gore models for the Soviet faction (previously used US models)
- Primary Weapons are now displayed on the player’s back while not equipped
- Added the ability to interrupt weapon reloads
- Fortifications can now be snapped together using the default “LEFT ALT” keybinding
- Adjusted MG deployment logic to prevent players from hiding their model inside objects
- Updated Personal Stats screen with new stats and an organized layout
- Tank crews are now notified when the gunner destroys an OP
- Vehicle wrecks can now be destroyed using tank shells, AT-guns, rockets and satchels
- Increased AT-Gun deploy timer from 3 to 8 seconds
- Reduced AT-Gun damage from 600 to 350
- Added the following new [[Achievement]]s:
	- Not a bridge too far!
	  
	  MG goes BRRRR!
	  
	  You can run, but you can't hide!
	  
	  I don't need no Nightvision Goggles!
	  
	  Soldier of the Month
	  
	  Commend and Conquer!
	  
	  War Hero
	  
	  Deputy of Death
	  
	  Do Svidaniya!
	  
	  I spy, I spy, with my little eye...
	  
	  Cleanup down isle 3
	  
	  Geneva Genocide!
	  
	  There can only be one!
	  
	  One with the shadow...
	  
	  Spot On!
	  
	  Medal of Honor
	  
	  Iron Cross
	  
	  Hero of the Soviet Union
	  
	  Breaking the Geneva Convention
	  
	  Its over two thousand!
	  
	  Humble lifestyle
	  
	  Its like fashion week!
	  
	  Rock, Paper, Tank!
	  
	  And so it begins...
	  
	  Rain Hell
	  
	  Beat the DEV (Medic)
- Maps
	- Added new [[Remagen]] map:
		- [[Warfare mode]]
		- Warfare Night
		- Offensive GER
		- Offensive US
	- Added Night maps:
		- [[Foy]] Warfare Night
		- [[Purple Heart Lane]] Warfare Night
		- [[Hurtgen Forest]] Warfare Night
		- [[Kursk]] Warfare Night
	- Added additional [[Omaha Beach]] map variants:
		- [[Warfare mode]]
		- [[Offensive mode]] for [[Germany]]
- Reworked HQs on Kursk to provide additional cover for each faction
- HUD/UI
	- Improved legibility of Enemy Recon Markings on the Tactical Map
- Audio Effects
	- Shortened incoming [[Artillery]] whistle SFX
	- Adjusted bullet crack SFX for the MG42
	- Adjusted [[Foy]] map ambience
	- Balanced volume of grenade throw SFX
	- Added sound occlusion to explosion SFX
	- Balanced end of round music volume
	- Adjusted flesh impact SFX
	- Adjusted wood impact SFX
	- Adjusted smoke grenade SFX
	- Additional minor sound tweaks and improvements
- Visual Effects
	- Updated TPP Blood Hit FX
	- Added lighting to the following in-game FX for better visuals on night maps:
		- Muzzle Flashes
		- Artillery cannons
		- Tank cannons
		- Panzerschreck/Bazooka rockets
	- Adjusted artillery impact and vehicle explosion FXs
- Server Administration
	- Added ‘Aim Laser’ to indicate where a player is aiming
	- [Fixed] The prompt displayed when the player is banned via Votekick mentions that the ban is from the administrator
- Bug Fixes
	- [Fixed] Unusual camera stuttering when vaulting over an object while the server/player has a high ping
	- [Fixed] Disconnecting and Reconnecting from VoIP while making Microphone check will cause VoIP to permanently stop working.
	- [Fixed] [[Soviet]] Recon Tank doesn't trigger any SFX when entering the vehicle or switching positions.
	- [Fixed] [[Panzer IV]] has incorrect armour collision
	- [Fixed] The player cannot be heard if they switch very fast between the VOIP channels
	- [Fixed] Players are unable to hear enemy Half-track SFX
	- [Fixed] M97 Trench Gun cannot penetrate any materials.
	- [Fixed] Outpost can be placed next to downed enemy but is instantly destroyed.
	- [Fixed] Bullet Crack Sound Plays when leaving Mounted Prone with PTRS-41.
	- [Fixed] Typing Y/N in chat will accept or deny UI requests
	- [Fixed] Deployable explosives can't be placed in an area around garrisons and airheads.
	- [Fixed] The player model can clip through certain building roofs by deploying LMG’s.
	- [Fixed] LMGs camera will lose its input when being deployed in another player
	- [Fixed] Some Personal Stats are not saved when the player exits and reenters a server
	- [Fixed] Offensive mode initial Deploy Timer counts down before any players have joined the server
	- [Fixed] [[VOIP]] may not work immediately after creating a unit for 20-30 seconds
	- [Fixed] Career and Role EXP may not correctly display in change role menu if gained just before a match ends.
	- [Fixed] Two players can trigger the bandaging animation if the bandage is used at the same time
	- [Fixed] Players do not get suppressed from bombing run fire when in artillery reload seat
	  
	  [Fixed] Players do not get suppressed from strafing run fire when in artillery reload seat
	- [Fixed] Deploying an LMG on a wooden beam of a specific barn causes graphical issue and un-deploys the LMG.
	- [Fixed] Half-Track spawn icon appears when the engine is on in Locked enemy territory
	- [Fixed] During idle animation the left hand is misaligned and clips through the weapon while holding any Rifle or Sniper Rifle
	- [Fixed] The player is unable to deploy or to enter the Change Role menu in certain scenarios after they've been switched to the other team via RCon during the last 3 seconds of deployment
	- [Fixed] The Anti-Tank gun turret will collide with vehicles, potentially causing collision/physics issues
	- [Fixed] Missing glass in [[Opel Blitz]] asset
	- [Fixed] [[Eastern Wood Peewee]] can be heard in [[Hurtgen Forest]] Map
	- [Fixed] Rebinding W A S or D in Infantry, Driver and Admin tabs will allow two bindings on one key.
	- [Fixed] Rebinding W A S or D to common and relaunching the title will rebind in Infantry, Driver and Admin Tabs.
	- [Fixed] [[Garrison]]s and [[Outpost]]s render distances vary based on map
	  
	  [Fixed] [[Airhead]] is destroyed by friendly grenades
	- [Fixed] The Damaged Engine Fire PFX always face directly toward the player
	- [Fixed] When a player quickly switches between [[VOIP]] channels, the nametag of the player will not show up or will show up for a brief period of time
	- [Fixed] Gear change animation plays twice in Soviet vehicles
	- [Fixed] Occasions where nametags appeared in Streamer Mode
	- [Fixed] Poor network conditions will cause bolt action rifles to not fire when inputting.
	- [Fixed] [[FG42]] bullets land higher than the crosshair
	- [Fixed] [[Soviet]] Half-Track have no SFX while being repaired at a repair station
	- [Fixed] The map images on the 'Maps' section of the Field Manual are low resolution
	- [Fixed] There is a corrupted texture in the viewports of certain tanks
	- [Fixed] Outside parts of the [[Panzer IV]] is present in the viewport at FoV higher than 90
	- [Fixed] [[Airhead]]s will deploy faster than the icon indicates
	- [Fixed] The prompt that appears after a player is kicked appears in [[German]]
	- [Fixed] [[Steam]] invites will bring a player into the last server the inviter was in if they're on the Front End
- [[Kursk]]
	- [Fixed] Increased height of certain foxholes to provide improved cover
	- [Fixed] Multiple instances of floating or misaligned assets
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- [[Stalingrad]]
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- [[Foy]]
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- [[Hill 400]]
	- [Fixed] Visual issue with some riverbanks
	- [Fixed] Multiple instances of floating or misaligned assets
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- [[Hurtgen Forest]]
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- SME
	- [Fixed] Some instances where the player could not deploy their MG on an asset
	- [Fixed] Multiple instances of floating or misaligned assets
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- [[Purple Heart Lane]]
	- [Fixed] Multiple instances of floating or misaligned assets
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- [[Omaha Beach]]
	- [Fixed] Multiple instances of floating or misaligned assets
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- [[Remagen]]
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- [[Carentan]]
	- [Fixed] Adjustments to player collision across a number of assets
	- [Fixed] Adjustments to LoD settings across a number of assets
- Known Key Issues
	- Ammo Drop ability description mentions x5 rearms instead of x12
	- Specific assets appear to LoD aggressively on some maps (notably Omaha)