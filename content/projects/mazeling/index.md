---
linux: mazeling_linux.zip
macos: mazeling_macos.zip
title: Mazeling
windows: mazeling_windows.zip
youtube: A6cGXkVrQxg
date: 2017-09-10 12:00:00
---

For the Game Prototyping course at ITU Games Technology we were given the task to design a Spectable game.

The requirements were

- Design a Spectable game
- Must have a digital component
- Either infinite play, or rounds <2 min.
- 2 players

Mazeling is a spectatable shooter game, in which two players compete in a randomly generated maze.

**Game Objective**
The goal of the game is to kill one another, using rocket launchers (bazooka like). 

**Gameplay**
Players view the maze from a first-person perspective in splitscreen mode, limiting the amount of information available to them. This is designed, to add an element of suspense from the players’ perspective. 

Spectators are able to see the game from both the players’ perspective and a top-down view of the maze as well, giving them a more complete picture of what is going on. 
 
We have also implemented “betting” mechanism, in which spectators are able to bet on players in real time (visible to other spectators and the player being upvoted). This  encourages audience participation that they are  actively engaged, by making them feel as if they have a personal stake in the game. 

This is done using a website, which the spectators can access using a browser on ex. their Smartphone while the game is running.

**Design**
One of of the key challenges with designing the Game, was how we could let players navigate the Maze without knowing where each other are. By creating a very “bland” environment with no distinctive features, the players can not identify their opponents location easily. 
But, by using a pillar in the middle, the players are able to know where the center is thus creating reference point, which gives them sense of where they are (within the maze).
Later on we added destructable walls in order for to make it faster to find one another throughout the game. And a powerup in the middle for the players to strive for.

**Controls**
The game is played using 

- WASD + Left Ctrl for Left Player (Red) and 
- Arrow keys + Right Ctrl for Right Player (Blue). 

It can be played on a single display (Without spectator view) or with another display connected in Extended mode for Spectator view.