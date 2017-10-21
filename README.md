# 04_BattleTank
Open World Head to Head tank fight with simple AI, terrain, and advanded control system in Unreal 4.

#Battle Tanks GDD
#Concept: A tank game where the player faces off against an AI controlled tank to see who can destroy the other. The battle will take place in varied terrain and the tanks will be forced to aim in order to do damage to the enemy. There will also be mortars for the enemies that the player will either need to destroy or avoid in order to defeat the enemy tank.
#Rules:
*	Tanks are able to move forwards, backwards, left, and right. 
*	Tanks can only move up or down if the terrain is also moving in that direction.
*	The first tank to reach run out of health loses. 
*	After firing a shot there is a cooldown period for the tank. 
*	Mortars will fire at the tanks current position.
#Requirements:
##A functioning tank:
*	Tank with treads that can be controlled independently
*	Turret on tank can be moved independently from the wheels
*	Tank is able to fire shots
*	Tank will have ammo
*	Ammo is depleted when the tank fires a shot
*	Tank will take damage when hit by a shot
*	Delay when firing the next shot
## Effects for the tank:
*	Tank tracks moving
*	Visual for tank firing a shot
*	Turret moving
*	Sound effect for the tank firing a shot
## Sound effect for the explosions:
*	BOOM!
## Explosion effect:
*	Smoke
*	Fire
*	Disappears quickly 
## Battle Music:
*	Simple song playing during the battle
## AI Controlled Tank:
*	Copy of the tank that is controlled by AI
*	Follow the same rules and limits the player tank does
## Mortars: 
*	Gets and fires at the enemy position
*	Delay between firing times
*	Explosion for when rounds hit the ground
# Effects for the mortar:
*	Mortar firing a shot
*	Sound effect for the mortar firing a shot
