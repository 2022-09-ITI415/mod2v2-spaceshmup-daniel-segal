# 05-Space-SHMUP

[Initial Values of System Variables]
Enemy Spawn Per Second: 0.5
Blaster Velocity: 50
Blaster Damage On Hit: 1
Spread Velocity : 50
Spread Damage On Hit: 1
Hero Speed: 30



[Tuned Values of System Variables]
Enemy Spawn Per Second: 0.8
Blaster Velocity: 60
Blaster Damage On Hit: 2
Spread Velocity: 60
Spread Damage On Hit: 2
Hero Speed: 40



[Descriptions of effect of tuned variables on gameplay experience]

Enemy Spawn Per Second: Increased to have a faster gameplay experience with less time waiting for enemies to spawn.

Blaster and Spread Velocity and damage: Increase to account for the faster enemy spawn rates creating an overall faster gameplay experience allowing the player to kill enemies faster, however they spawn faster

Hero Speed: Helps speed up player movement to account for the increased enemy spawn rates and weapon damage.

[Added Features]
Two Shot Weapon: Fires two projectiles at once
Laser Weapon: attempted to have a laser using a line render however has issues with collisions and snapping to the center of screen
Phaser Weapon : attempted to make projectiles fire in a sine wave however, ended up just firing projectiles in random directions
UI: Added a counter to show the player how many ships they have destroyed during a given playthrough

