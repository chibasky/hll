- Source
	- [[Steam]]:
		- https://store.steampowered.com/news/app/686810/view/2609223645230578579
- Animation
	- FPP
		- Our entire first person perspective animations have been overhauled in two ways - first in all the underlying systems, and then in the way the specific animations look. You can read more about this in the specific [[Developer Briefing]] [here](https://steamcommunity.com/games/686810/announcements/detail/2536038699697837955?snr=1_2108_9__2107).
	- TPP
		- All TPP animations have been overhauled at a systems level in order to make them procedural, as well as at an asset level - to incorporate the use of [[Motion capture]] movements. You can read more about this in the specific [[Developer Briefing]] [here](https://steamcommunity.com/games/686810/announcements/detail/2609223645216778362?snr=1_2108_9__2107).
	- Sound
		- All TPP and FPP firearms sounds have been overhauled. The full details can be read here, in [our sound-specific Developer Briefing](https://steamcommunity.com/games/686810/announcements/detail/2609223645216778362?snr=1_2108_9__2107).
- [[Carentan]] (including [[Warfare mode]] and [[Offensive mode]] for [[US]])
	- Carentan is our first majority-urban map.  You can read more about Carentan the specific [Developer Briefing](https://steamcommunity.com/games/686810/announcements/detail/2536038699672860181?snr=1_2108_9__2107).
	- The sheer density of the map has been a huge challenge to optimise, and while we have made many large scale improvements to the performance, there are key aspects of optimisation that we are now working to improve. Over the course of [[Early Access]] Carentan will receive the same continued attention as all other maps as we seek to improve frame rates across the board.
- [[Foy]] Overhaul
	- Both Foy game modes have received a photoreal lighting pass, including a change to all atmospherics.
	- Foy itself has had nearly every [[Strongpoint]] assessed and revised based on [[Feedback]] and player experience within the game. All are overhauled - to provide either a visual upgrade, fix collision bugs or improve gameplay.
	- We’re working to create variation of experience in each location across the map, as well as maintaining open fields for [[Vehicle]] movement. Cover density has hugely increased too, while map flow has been revised to allow for better armored encounters and easier placement of [[Spawn]] points.
- [[Omaha Beach]] Partial Overhaul
	- While more work is still to be done on Omaha, many locations - including [[Vierville]] and outlying [[Strongpoint]]s - have had a significant rework to include new assets - including more optimised and gameplay friendly [[Structure]]s and layouts.
	- Omaha has also been re-lit to better build the mood of the fated morning.
	- More work will be done to Omaha during the course of Early Access.
- [[Metagame]] Changes
	- We’ve listened to all the feedback regarding [[Garrison]] bombing and the dissatisfaction with the metagame. Our design policy is to gently move the meta back into line with the outcomes we desire.
	- [[Garrison]]s cannot be placed on [[Neutral territory]] or [[Enemy territory]].
	- We are delineating the usage of [[Garrison]]s to be positions behind the front that are designed to feed attacks and defensive locations, as opposed to functioning as a “bomb” or the tip of the spear in the assault. To this end, [[Outpost]] s will now function as they are intended - as faster forward spawns used by assault units. Our desire here is to encourage more intentional offensive and defensive behaviour around a defined front line, as opposed to just dropping a Garrison and flooding the point. We feel this will make defending far easier as it is less likely that a defensive unit will be attacked from any direction.
	- [[Enemy]] [[Garrison]]s now take 5 [[Second]]s to be dismantled
		- This replaces the proximity takedown, as the opportunity cost of removing a Garrison was too easy and low previously. To counter any [[spawn]] camping this may encourage, we’ve made additional changes below.
	- Players cannot spawn on a [[Garrison]] if an [[Enemy]] player is within 15 [[Metres]]
		- Garrisons now lock spawning if an enemy is within close range and moving to dismantle it. This will reduce mass [[Spawn]] -killing, as well as incentivise the attacking player to close the distance to remove the Garrison.
	- Minimum distance between friendly [[Garrison]]s is now 100 [[Metres]]
		- This change is to enable more even placement behind the [[Front line]] and give more contingency should a key Garrison go down.
	- [[Outpost]] cooldown has been reduced to 120 [[Second]]s in order to allow players to maintain them
		- In order to effectively assault into [[Enemy territory]], OPs are now able to be placed far more frequently.
	- Sector [[Capture time]] is now reduced to 120 [[Second]]s
		- In order to create more decisive conflicts on the point, we’ve slightly lowered the total time to capture the point. We found that in [[Offensive mode]] particularly, the contested nature of flags as well as the total time needed to capture them meant that games could run well over 2 hours (7200 [[Second]]s), resulting in tedious gameplay and lack any decisive [[Victory]] or [[Defeat]].
	- As always, we’ll be monitoring all of these changes and the way they affect the flow of the gameplay. We are currently preparing two significant meta-changing new features: [[Transport vehicle]]s and [[Support]]/ [[Engineer]] changes and are keen to make these adjustments before these hit the battlefield. We’ve also added the new "[[Airhead]]" [[Commander ability]] (details below) in order to enable each force better strategic ability to mitigate [[Breakthrough]]s or strike into [[Enemy territory]].
- [[Teamkill]]s
	- Team Kill penalties now stack. Additional TKs will extend your next redeploy time by 10 [[Second]]s for each teamkill.
- [[Redeploy]]
	- Using the Redeploy function on the In-Game [[Menu]] now has a 20 [[Second]]s redeploy time
	- All self-inflicted [[Damage]] that leads to death, now gives a redeploy time of 20 [[Second]]s
- New [[Commander ability]]
	- [[Airhead]]
		- A bridgehead established by aerial drops - often into enemy territory. In Hell Let Loose, an Airhead can be established by the [[Commander]] at any location of their choice.
		- After using the ability, your [[Team]]-specific supply [[Plane]] will drop a temporary Airhead spawn point at the target location.
		- [[Cost]]: 75 [[Manpower]]
		- [[Cooldown]]: 600 [[Second]]s
		- All [[Infantry squad]] and [[Recon squad]] players can spawn on it.
		- Players can [[Spawn]] on it every 30 seconds for 120 [[Second]]s minutes (approximately four spawn waves).
		- Be careful when dropping the Airhead into [[Enemy territory]] - as enemy presence can destroy it immediately - rendering it useless.
		- Unlike the new [[Garrison]] changes, the Airhead is destroyed by enemy proximity.
		- Recommended Uses:
			- Use with coordinated Units to effectively flank and deep strike into [[Enemy territory]] .
			- Use to save a collapsing front line.
- Patch Changelist
	- Gameplay
		- Introduced the ability to use your mouse and turn your head in vehicle viewports. We have parented hull machine-guns to this movement to enable a smooth firing/looking experience. Please note that viewports will be overhauled to re-introduce both depth of field effects and much higher texture detail.
		- We will also be changing the hull and coaxial MGs in vehicles to use the ballistics system now that we’ve profiled performance costs.
		- MG’s can now be deployed while the player is still moving, instead of requiring the player to stop moving first.
		- The M1 Garand can now be reloaded mid-clip.
		- Hovering on any Unit Officers on the map highlights all of their Unit members.
		- Vehicle name plates to only show when pointed.
		- We now show the health status of Unit members in the member list on the HUD: Unit members appear white when alive in-game, grey when dead/in the deployment menu, and Red when in critical state in all listed locations.
		- Every weapon now has a recoil pattern that can be mastered.
		- Introduced new ways for experience to be gained. Eg. experience is rewarded for placing the ammo box, as well as for each time the ammo box is used by another player.
		- Added gameplay option to hide vote kick notifications
		- Unit list automatically expands in the deploy menu when you join or create a Unit.
		- Implemented an autosprint. Players can autosprint by double tapping the W key. We will refine and expand this functionality for U8.
		- When a player is crouched, enable the pressing of the space bar to stand them up.
		- Force dominance to going ADS while crawling.
		- When pressing jump while prone, transition the player to crouch.
	- [[Performance]]
		- Continual performance updates across all aspects of the title.
		- Lowered dead body despawn rate to 30 seconds as default.
		- Please note: we have many aspects of [[Optimisation]]s still to come. Now that U7 has been released, we will be focusing our efforts on this in the near future.
	- SFX
		- Introduced Sound Mix Modifiers for different Seats in a vehicle. This will allow us to give each vehicle seat a different audio treatment.
		- Number of Audio Channels exposed as a game option. Default value increased from 32 to 128.
		- Fixed: No click SFX when interacting with the 'Invite Players to Unit' UI
		- Fixed: The SFX for bandaging will play in its entirety if the user cancels the bandaging animation
		- Fixed: Body hit sound. (NOTE: depending on feedback will allow you the ability to disable this in the sound settings).
		- Fixed: Quickly traversing the cursor over the buttons within the frontend menus restarts the frontend's SFX and music
		- Fixed: [Omaha] Ocean audio abruptly stops at a certain point of the map.
		- Fixed: When firing and leaning right, the shell casings sound can be heard in the left ear.
		- Fixed: The player can hear the water SFX after they have drowned
		- Fixed: Heavy breathing audio can be heard if the player is wounded and underwater
		- Fixed: The audio cue for confirming a new marker will play even if the marker is not placed.
	- HUD/UI
		- Fixed: Multiple [[Spawn]] points can be highlighted by clicking on a new spawn point as the animation for the previously selected spawn plays
		- Recon marks now pulse and are darker red to better enable them to be seen on the map. They also layer correctly in the context of the other icons on the map.
		- Visual overhaul for [[Early Access]] Disclaimer when launching title for the first time.
		- Changed the red skull icon for a revivable player to a morphine icon - to better signal to new medics that the player is revivable.
		- Fixed: Sector names on the map will flash blue once the map is viewed for the first time during the player's life
		- Fixed: No tooltip available for Light tanks when hovering the mouse cursor over the map key for deployment menus and overview map
		- Fixed: Visual inconsistency between the [[Commander]] player icon on the key and in-game
		- Fixed: The "x" icon for kicking players from the Unit is missing a tooltip
		- Fixed:Inconsistent font and spacing in the 'Vehicles', 'Deployment', and 'Overview Map' sub-menus of the Field Manual.
		- Fixed: US wrist watch icon is present on the German HUD instead of the pocket watch icon
		- Fixed: [Omaha] When a strong point is nearly captured, the strong point emblem will appear full when it has not been captured yet
		- Fixed: Inconsistency in HUD element's design during the 'Loading' and 'Loaded' stages on the artillery
		- Fixed: Tank icons appear to be of a lower resolution than the map itself
		- Fixed: [Map] Missing tooltips for the Repair and Resupply stations at the spawn points
		- Fixed: On the scoreboard, there are no tooltips present when the Resource icons are hovered over
		- Fixed: Red mist effect overlaps the ‘You were wounded by ???’ pop up.
		- Fixed: There is no bandage icon shown when being healed by another player.
		- Fixed: [UI] Multiple UI elements are overlapping when using certain screen resolutions
		- Fixed:  [[Purple Heart Lane]]  The map title text is offset when viewing Purple Heart Lane on the Vote for Map screen
		- Fixed: There is no red blur effect on the 'Equip Bandage' button prompt
		- Fixed: Outpost icons are inconsistent on the Deployment Screen and In-Game Map
		- Fixed: Long server messages set via the [[RCon]] 's broadcast tool do not wrap, and will go off-screen as a result
		- Fixed: On the Deployment Screen, the tooltip for hovering over an Outpost or Garrison icon inconsistently displays "Enemy Near" when an enemy is within 50m of the spawn points
		- Fixed: Visible blank space on Commander order tooltips
		- Fixed: The thumbnails shown for creating the 3 unit types are incorrectly scaled when not selected
		- Fixed:  [[Purple Heart Lane]]  Strong point and underwater HUD elements can overlap
		- Fixed: Loadout descriptions have inconsistent text size
		- Fixed: The [[Artillery]] UI icons is difficult for the player to observe in the in-game environment.
		- Fixed: Multiple Loadout icons appear squashed in-game.
		- Fixed: Missing HUD icon for anti-tank gun
		- Fixed: In the [[Field Manual]] , the Maps section is missing images for all maps
		- Fixed: [PT] Tanks' Gunner seat is missing a "Zoom out/in" prompt
		- Fixed: [Foy-O] Inconsistency between the ingame HUD timer and the Scoreboard timer when entering Overtime.
		- Fixed: Fix issue where the unit letter isn't showing on the voip notify.
		- Fixed: Turning the 'HUD Display Mode' to 'Always On' after joining a server results in the HUD to fade out as the user loads into gameplay
		- Fixed: Cooldown timers for commander orders will be removed when the order is no longer in effect.
		- Fixed: Various issues where tooltips and cosmetic preview heads do not update when the item is embedded in a sub-menu.
	- Visual Improvements
		- [[Suppression]] has been reworked to optimise the visual effects, make the blur far less ugly while still maintaining the intended effect. Previously, it was very difficult to determine whether you had been wounded as the suppression would darken your screen. We’ve worked hard to distinguish these two states.
		- The “bloody screen” wounded overlay is now far more distinct and obvious. As your wounds become more severe and stay untreated, the pumping heartbeat sound will pulse with the overlay and become faster and faster.
		- When killed by small-arms, your player [[Camera]] will tumble much faster to the ground in line with the momentum of your body. Previously it would float down to the ground.
		- Overhauled [[Camera]] shakes when firing weapons to be calibre-specific
		- Overhauled [[Camera]] shakes when explosions occur nearby (including while in a tank).
		- Reworked [[Gore]] and dismemberment. Many features were not working as intended - including blood trails, fx and better visuals. This has all been fixed.
		- Fixed: The Colt M1911 and Luger P08 will display a bullet model inside the chamber even though the gun is currently empty
		- Fixed: No rotating animation present on the player in the second seat of the artillery
		- Temporarily disabled map vote function as it was non-functional and visually irritating. We will be introducing a much nicer end-of-round map vote function in [[Update 8]].
		- We have set traditional TAA to be the default game [[Anti-aliasing]], as this looks better in video footage. However, Clarity TAA and all exposed AA settings are still available.
	- Customisation
		- Introduced the new Fallschirmjäger uniform for [[Germany]] forces, including the Fallschirmjäger helmet.
		- Introduced the 1942 Airborne uniforms for the [[US]] forces.
		- Overhauled Barracks to use photoreal lighting.
		- Introduced the ability to zoom into the upper portion of the character using the [[Mouse]] wheel.
		- Fixed: The Albert head model's neck slightly clips with multiple uniforms
		- Fixed: Clipping visible on the character shoulder when equipping the Paul head on the Heer summer and Winter uniforms
		- Fixed: Multiple Winter Heads are missing "Winter" on their icon tooltip
		- Fixed: The Winter Wolfgang head icon is not in the correct icon order
		- Fixed: Visible clipping issues on the back of all [[Germany]] Winter head variants while crouched.
		- Fixed: Winter Erich and Winter Alfred head variants cause clipping issues with certain German Helmets.
		- Fixed: The Heer Panzer Cap is not properly aligned with the character head
	- Bug Fixes
		- Opened up collision on the drystone wall gaps
		- Fixed: [[Commander ability]] tooltip cooldown timers start when the user joins the server
		- Fixed: Supplies from [[Supply drop]]s that land in high altitude assets may fall through the ground.
		- Fixed: The [[Audio]] cue for confirming a new marker from the radial menu will play even though the marker is not placed onto the battlefield
		- Fixed: All active sectors are briefly shown as neutral when first entering the deployment menu.
		- Fixed: [[Supply drop]] s can be placed in the out of bounds area
		- Fixed: Karabiner 98k - sometimes will not shoot a bullet when fired
		- Fixed: Player death is counted as a team kill after bleeding out from damage caused by their own grenade.
		- Fixed: The player's [[Helmet]] will pop off of their corpse when they 'Let go'
		- Fixed: Being killed by a teammate that is currently on the deployment screen does not show the 'You were killed by teammate...' message
		- Fixed: Tooltip Cooldown timers for the Commander orders will be removed when the order is not longer in effect
		- Fixed: German Recon vehicle can be spawned on top of Players on all maps.
		- Fixed: Shooting dead bodies with a sniper rifle causes unrealistic movement
		- Fixed: The 'Head' list will not reset back to the initial roster of heads if the user leaves the 'Barracks' with the head variants list open
		- Fixed: [TPP] Various [[US]] [[Helmet]]s fall under the map when dying
		- Fixed: Opacity settings don't affect friendly tank crew icons and names
		- Fixed: Causing a teammate to enter Critical State and them "Letting Go" does not penalize the teamkiller's Death Screen Timer
		- Fixed: Attempting to join a server that has available spaces but is currently in the post-match screen will place the user in the server queue
		- Fixed: Accepting a [[Steam]] invite while Hell Let Loose is running will send the Player to a random server.
		- Fixed: Cannot Deploy here message stops player being able to use mouse
		- Fixed: ‘Match is over’ error message was displayed in German after a failed attempt to join a German server when the game had been booted up in English
		- Fixed: Aiming down sights immediately after entering or leaving the prone position results in the player's camera zooming in before the iron sights are brought up to the player's POV
		- Fixed: When a server is full, only the first attempt at joining a friend's game through [[Steam]] places the user in the server's queue
		- Fixed: The HUD element 'Strong Point' will show for the attacking team if they are standing within a locked [[Strongpoint]]
		- Fixed: Player will die if they exit the German Heavy tank while it is moving in 2nd gear or higher.
		- Fixed: The 'Cancel' button on the 'Connecting...' notification will become defunct shortly before the loading screen is shown
		- Fixed: All players that are unable to be invited to a unit will appear greyed out on the 'Invite Players to Unit' list
		- Fixed: The user cannot find servers for nearly 120 [[Second]]s after losing [[Internet]] connection within a server
		- Fixed: Unable to open the [[Map]] after using a [[Smoke grenade]]
		- Fixed: Inconsistent appearance of locked [[Strongpoint]]s between [[Warfare mode]] and [[Offensive mode]]
		- Fixed: Bullet decals can be produced inside the Greyhound Recon vehicle
		- Fixed: Player crashed after unplugging their monitor and opening the pause menu.
		- Fixed: Clicking 'Confirm' multiple times when entering a password for a server will produce a 'Join Failed' message and the user will be removed from the server when loaded in
		- Fixed: The "Can't deploy at that location" prompt is displayed on screen if the spawn point is destroyed just before deploying into active gameplay.
		- Fixed: Nothing happens when the player opts to deploy when the previous [[Outpost]] has recently been moved
		- Fixed: The player will receive two 'Can't deploy at location' error messages if they select an Outpost that is later moved
		- Fixed: The 'Fullscreen Mode' option will reset to the previously applied setting when changing the 'Master Quality'
		- Fixed: Using a [[Steam]] direct link to join a server will connect to an incorrect server
		- Fixed: Some servers may not update their map rotation list after a Patch/Update
		- Fixed: Users may appear falling under the map and get disconnected during map transitions on a specific community server
		- Fixed: Creating a Unit causes all other different Unit types to not be visible in the Deployment Screen.
		- Fixed: [[Vehicle]] trail fx are kicking out far in front of the vehicle.
		- Fixed: Manual bolt cycling.
		- Fixed: Shadows are removed from the frontend (Barracks) when the user leaves a server.
		- Fixed: Blood and Gore Decals not visible and causing SSAO/Lighting issues.
	- Armoured Gameplay
		- We have begun taking a look at the armoured gameplay ahead of introducing new [[Vehicle]]s into the game. We will continue to work on more improvements as we iterate.
		- Reduced the [[Damage]] that carries over from the tracks/wheels to the hull, so body shots are more effective and efficient than repeatedly shooting the tracks/wheels.
	- [[RCon]]
		- Exposed weapon player is killed with.
		- Added ability to identify players in chat log.
		- Fixed: The server broadcast message will not show correctly if it has been edited via the internal Rcon
		- Fixed: Internal Rcon cannot be accessed while on the scoreboard
		- Fixed: An inconsistency of the current map can occur between external RCon tool and the Enlist screen if the user changes map twice in quick succession
	- [[Purple Heart Lane]]
		- Fixed: Possible exploit locations because of no collision.
		- Fixed: Confirming a Fuel order on the middle [[US]] [[HQ]] [[Spawn]] will block the main path for tanks
		- Fixed:  [[Offensive mode]]  There is no "turn back" boundary that prevents Defenders from reaching the Attacker's initial [[HQ]]
		- Fixed 18 minor collision issues.
	- [[Sainte-Marie-du-Mont]]
		- Fixed: The [[US]] [[Commander]] cannot place Fuel Abilities on the mid HQ.
		- Fixed: Placeholder text is present when [[Loading]] into the map.
		- Fixed 10 minor collision issues.
	- [[Foy]]
		- Fixed: [Foy][C10] The Greyhound Recon vehicle can become stuck if the player drives over the snow mound directly in front of the Fuel Order spawn
		- Fixed: [[Foy]]  [[Offensive mode]] The attacking [[Germany]] team does not have any [[Tank]]s available at the start of the game on the left or right [[HQ]]s.
		- Inconsistent sector names between [[Offensive mode]] and [[Warfare mode]]. Both points are now referred to as [[Flak Battery]].
		- Fixed 56 minor collision and visual issues.
	- [[Utah Beach]]
		- Fixed 6 minor collision and visual issues.
	- [[Hill 400]]
		- The [[US]] Top HQ Heavy [[Tank]] [[Spawn]] location has the exact same spawn point as the [[Commander]]'s Fuel abilities spawn location.
		- Fixed 25 minor collision issues.
	- [[Omaha Beach]]
		- Fixed: ‘Out of Bounds’ area overlaps all [[US]] [[HQ]] sector strongpoints.
		- Fixed 13 minor collision issues.
	- [[Sainte-Mère-Église]]
		- Fixed: [SME-W][A6] Player is unable to exit the top two [[Germany]] [[Artillery]].
		- Fixed: [SME-O]  [[Germany]] [[Resupply station]]s are present in the [[US]] [[HQ]]s.
		- Fixed: [[Sainte-Mère-Église]]  Observing the [[Sun]] at a specific angle creates a powerful lens flare.
		- Fixed 22 minor collision issues.
	-
	- Known Issues
		- Some HLOD issues exist in [[Carentan]] (the buildings that appear to be “melted ice-cream”) and some other maps. We’ll be focusing on addressing these issues shortly.
		- Some collision issues exist in [[Carentan]] - we will be fixing these shortly.
		- We’re aware of some bugs causing small ditches in specific locations of [[Omaha Beach]] .
		- The blurring effect during [[Suppression]] is currently at an unintended low intensity, and will be increased back to normal levels shortly. This was introduced accidentally when reworking the suppression visual effects.
		- The [[Zeroing]] on many weapons currently sits at 0m. We will be fixing this shortly.
		- We temporarily needed to remove the player’s own FPP shadow as it was continuously casting shadow on the player rig no matter the angle or orientation. We’ll be revisiting this.
		- We’re aware of the [[FPS]] “hitch” that can occur every couple of minutes for some players. We have a fairly good idea of what is causing this and will be giving it a lot of attention moving forward.
		- As with all huge infrastructure changes, we do expect both server and client [[Crash]]es to increase in frequency. We are committed to isolating and fixing these as soon as possible, and are very thankful with your patience as we iron these out.
	- Currently Working On (in no specific order)
		- [[Engineer]] functionality - including building useful defensive locations.
		- [[Support]] functionality.
		- [[Tank]] and [[Vehicle]] [[Physics]] and functionality revisit - from collision in maps to potentially introducing turning out.
		- Investigating [[Freelook]] implementation.
		- Investigating ways of allowing players more control over which [[Uniform]] is automatically applied per [[Map]] .
		- Investigating “Historic” setting in options menu for players who only want the historically accurate [[Uniform]] per [[Map]] . This would be a non-default client-side setting that would not be mandatory for all players.
		- [[Tank crewman]] functionality.
		- Continued refinement of TPP animation systems (to iron out any issues presented in U7, and to build in greater procedural cycles).
		- Overhauling [[Ammo box]] and supply types - including the [[Support]] and [[Logistics]] gameplay loop.
		- New [[Commander ability]]s.
		- Overhauling [[Sainte-Mère-Église]], [[Sainte-Marie-du-Mont]], and [[Hürtgen Forest]], as well as continued work on [[Utah Beach]], [[Omaha Beach]] and [[Purple Heart Lane]] .
		- Transport vehicles and supply vehicles.
		- Investigating melee implementation.
		- New weapons for new loadouts (FG-42 and more).
		- 3 new unannounced maps.
		- New customisations.
		- A new front.