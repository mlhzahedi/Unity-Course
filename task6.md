# Task 6

The game of searching for lost objects

General description:

In this exercise, you design a game in which the player must find missing objects. These objects are in a predefined list. By entering the names of the objects, the player tries to find them, but the number of attempts is limited. You have to design this game using loops and bets.

Player Duties:

 Search for objects:
 The player must enter the name of an object.
 The program checks if this object is in the list of missing objects or not.

 Managing Efforts:
 The player has a limited number of attempts (eg 5 attempts).
 If the player runs out of attempts and there are still missing objects, the game ends.

 Manage found objects:
 Each time the player finds an object, the number of found objects increases.
 If the player finds all the objects, the game ends and the player wins.

The list of missing items includes the following:
 Key, Book, Phone, Wallet

The methods you should use:

1. while loop:
 To manage the number of player attempts and continue the game until:
 The player has remaining attempts.
 All lost objects are not found.

2. foreach loop:
 To check if the player entry is in the missing objects list.
 The loop iterates over all objects in the list, comparing the player's input to each item.