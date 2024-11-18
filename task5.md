# Task 5

Create the following scenario to make an adventure game

You have an adventure game where the player must:
 Manage your own situation (such as energy, weapons, and position).
 Decide whether to attack the enemy, run away from the enemy, or seek resources.
 According to the specific conditions, he has different enemies in front of him.

Exercise details:

Step 1: Initial settings

Create a new script named AdventureGame and define the following variables:
 Player variables:

 int health (health level, initial value 50)
 int energy (Energy amount, initial value 30)
 bool hasWeapon (Does the player have a weapon? Initial value false)
 bool isEnemyVisible (is the enemy visible? initial value true)

 Enemy Variables:

 string enemyType (type of enemy: Goblin, Orc, Dragon)
 int enemyHealth (enemy health, initial value 70)

Step 2: Implement the conditions

 Conditions for attacking the enemy:
 If the player has a weapon and his energy is greater than 20:
 If the enemy type is Goblin, reduce the amount of damage dealt to the enemy by 30 units.
 If the enemy type is Orc, reduce the amount of damage dealt to the enemy by 20 units.
 If the enemy type is Dragon, reduce the amount of damage dealt to the enemy by 10 units.
 If the enemy is defeated (enemyHealth <= 0), the message "Enemy defeated!" be printed
 If the player does not have a weapon, the message "You cannot attack without a weapon!" be printed

 Escape conditions:

 If the player can see the enemy (isEnemyVisible) and his energy is less than 20:
 If the enemy is a Dragon, the player cannot escape and the message "You cannot escape from the Dragon!" be printed
 Otherwise, the message "You escaped successfully!" be printed

 Search conditions for sources:

 If the enemy is not visible (!isEnemyVisible), and the energy is less than 10, the message "You found an energy potion!" be printed and the amount of energy of the player will increase by 20 units.

 Using switch for the enemy:
 
 In the attack section, use the switch to select the type of enemy (enemyType).