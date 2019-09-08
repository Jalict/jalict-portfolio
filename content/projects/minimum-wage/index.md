---
linux: minimum-wage_linux.zip
macos: minimum-wage_macos.zip
title: Minimum Wage
date: 2017-10-08 12:00:00
windows: minimum-wage_windows.zip
---

For the Game Prototyping course at ITU Games Technology we were given the task to create a game where we split up the different game loops.
The requirements were
* Single Player
* Competitive

You play as a newly hired employee in a Warehouse. Your job is to unload and sort the crates. So we had those two types of game loops being **sorting** and **unloading**.
For *unloading* you have to get crates out of a truck, before the truck departures again.
For *sorting* you have to get the crates to the right conveyor belt.

Both loops can be done wrong and punishes the player and rewards when done right, this is done with simple negative/positive scoring system.

Each loop is time dependend so you have to do the taskes in a certain amount of time.

The loop have also been incorporated into the universe, being that you are a worked and have 2 days to learn the whole the job. So on Day 1 you do unloading and on Day 2 you do sorting. Lastly we have Day 3 where both a combined to show the whole full game loop.

The game is controlled using Arrow keys. You pick up crates by pressing Space.