# CS1666 Team EXAMPLE

## Team Members
* Random Level Generation sub-team
	* Dylan Miao
		* Pitt ID: dtm32
		* GitHuber username: dtm32
	* Brendan Marani
		* Pitt ID: bdm58
		* GitHuber username: BrendanMarani
	* Evan McEllhenney
		* Pitt ID: ecm53
		* GitHuber username: evanmce
* Networking sub-team
	* Jakob Strobl
		* Pitt ID: jps132
		* GitHuber username: Jakob-Strobl
	* Adam Ibrahim
		* Pitt ID: adi11
		* GitHuber username: ayoo324
	* Alec Cantor
		* Pitt ID: apc47
		* GitHuber username: apc47
* AI sub-team
	* Danny Phan
		* Pitt ID: dap167
		* GitHuber username: dap167
	* Alex Clewell
		* Pitt ID: alc261
		* GitHuber username: aclewell3
	* Nate Lyman
		* Pitt ID: njl26
		* GitHuber username: nlyman9

## Game Description

Similar to the original Wii tanks minigame, top down game where the user is a tank and has to defeat all other tanks in the arena. All tanks are able to shoot projectiles that bounce off of walls, and can also set bombs to blow up terrain or other tanks. The enemy tanks would use an AI to choose what objective to take, path around blocks, destroy the blocks with a bomb or angle a trajectory to attack the player. The levels themselves would be randomly generated with random terrain. An additional game mode willbe added as a versus mode between two players with networked multiplayer.

## Specific Milestones

* Will implement three unique enemy types
* Will implement two game modes: player versus player and single player versus the computer
* Will only implement one type of map with randomly generated obstacles
* Player will be able to control their own tank and no others
* Level is won when the player clears all the enemies
* Level is lost if time runs out or the enemy kills the player

## Advanced topics

* Random Level Generation
	* Build a unique layout of obstacles inside the static course
	* Ensure every level is winnable
	* Uniquely place enemies each new round
* Networking
	* Allow 2 players to connect to a single game instance and play the game as a lag-free experience
* AI
	* Computer controlled enemies decide between destroying destructable terrain, taking a shot at the player, moving around the map, and avoiding player attacks
