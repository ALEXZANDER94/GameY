# GameY
Game Y is a personal project that I've created to showcase my understanding of custom data structures, random number generation, and the workflow of game development. 

As a solo project, I am not privileged with Experts in Animation, Graphics, or Textures. Therefore, I did not put much time into the graphical aesthetics of the game. 

The game does include an extensive grid-based room generator that is designed to ensure no game is repeated and will grow linearly as the play progresses into more floors. Many aspects of the game are generated randomly to keep the user playing to experience all of the different executions of the game.

Level Generator
No game is the same. The level structure is different every time, but the game is equipped with an intricate mapping system to ensure the player does not get lost.
  Random rooms
  Derived from Djikstra's Shortest Path Algorith
  Uses custom Blueprint Structure

Power Up Generation
Power Ups are generated at random for the level. So no two games can likely be generated and the phenomena of "Luck of the Draw" is experienced
  Randomly generated per level
  Custom Enumerated value 
  
 Enemy Generation
The number of enemies and types of enemies are different for each room that is entered. This is a promise to keep the user engaged and alert that danger could very well be around every corner.
  Chasers - chase you around the room
  Spitters - attack you with a projectile; run away if you get too close
  Brutes - slowly move toward you; much larger and stronger; rush in the forward direction dealing massive damage on contact
