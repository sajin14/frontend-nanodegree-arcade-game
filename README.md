#Arcade Game Clone
  This game mainly featuring a boy and his enemies. The requirement is that boy has reach water without colliding with the enemies.

##How to Play
  Use arrow key to move the boy. The boy must not collide with the Enemy and have to reach the water to win the game.

 #Game Implementation
  *Two objects are used : **Enemy** and **Player**. Prototype objects are created for both the objects. 
  *The constructor initializes the initial position for both the objects.
  *time variable dt is multiplied with the enemy's position inorder sync the movement speed across different machines.
  *The position of boy and enemy is resetted when boy reaches water.

  **Collission detection**
  *A method is used to find out whether boy collided with the enemy. 
  *If collission is detected the boy's and enemy's positions are resetted.




