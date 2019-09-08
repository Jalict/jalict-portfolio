---
linux: icehopping_linux.zip
macos: icehopping_macos.zip
title: Ice Hopping
date: 2017-11-05 12:00:00
windows: icehopping_windows.zip
---

Ice hopping is a vertical jumping game in which a single player controls a
penguin and attempts to navigate across a sea of icebergs without falling off
and becoming submerged in freezing water. Inspired by the game "Island
Hopping", the penguin constantly moves forward at a constant velocity, with
the player limited to controlling the penguin by turning left or right and
by jumping (as well as double jumping). All movement is controlled via the
mouse.

Levels are procedurally generated in chunks, with each chunk consisting of
islands procedurally generated islands randomly chosen from a pool of five
different models. Each island also has a randomized color assigned to it --
either white, gray or black. Landing on a platform will mark that platformed
as already landed on by changing its color to green. Furthermore, landing on
multiple platforms in a row will increment a combo counter, which will
increase the number of points the player gains when landing on the next
island. This starts at 1 point, and is incremented by 1 for each combo.
Breaking the combo will reset the number of points awarded to 1. Upon
touching the water the player is returned to the main menu and the current
high score is displayed. Being procedurally generated, The level continues
indefinitely until the player dies.

Thematically the level is set in an an arctic-like landscape, with the snow
particle effects contributing to the setting. Also contributing are the
penguin model, the water shader, the music (made by Alex Rymark Vorm), and the water
shader sourced from the Suimono Unity plugin. Overall, these elements work
together to produce a play experience which manages to be visually
consistent and feature high amounts of replayability, especially given the
limited scope of the game.

The game was made together with August Almgren, [Sven Santema](http://sven.whalefall.nl/), [Alex Rymark Vorm](https://soundcloud.com/alex-vorm)