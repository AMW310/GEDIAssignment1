# Assignment1
Alexander Macharia Waiganjo
100% of work done by myself
For this assignment, I incorporated the observer command, Singleton and factory design pattern to create a game where you control the actions of enemies after entering an area that they are occupying. For Singleton, I used this for the manager. for the observer pattern, I had the enemy behavior script and the game manager script, observing the detection script to see when the player entered the enemies area. For the command pattern, I have three different commands that determine the steering behaviors of the enemies. These commands are seeking, fleeing, and wandering. Finally for the factory design pattern, I have the enemies spawning randomly in the area of their zone using a factory script with an enemy spawner script.

The goal for this game project that I developed was to continue off of a project that I worked on last year, which was a recreation of a level in little nightmares 2. After seeing how the game played out, I realized that the scene itself didn’t really reflect the gameplay that I started setting up and ended up removing the original scene from the scene. It’s more just like a sandbox area where the players are able to interact with the enemies. The only aspect taken from my previous game was how the camera would function and the seeking of the play, which also behaves differently in this version.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Course Project
Alexander Macharia Waiganjo
For the course project my main goal was to optimize the spawning and creation of enemies in the factory. I wanted to have dynamic spawning where the detection zone can be placed anywhere on the map and the enemies would still behave the same, responding to the commands of the player regardless of where they spawn. I improved on the singleton and observer, by implementing more uses that were more significant for the game, the singleton being used to set the spawn point for enemies and the zone they would be moving around in. The observer pattern remained the same for at least what scripts are subscribing to, but the spawner now is subscribed as well and spawns enemies only after the player enters a certain zone. Factory now handles all the aspects of creating the enemy, where before they did not calculate the spawn position of the enemies, and they create enemies for the object pool to store. 
All Contributions were made by myself
