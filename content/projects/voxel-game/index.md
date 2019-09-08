---
title: Voxel Game
date: 2017-12-11 12:00:00
windows: voxe-game_windows.zip
youtube: 3t8JtOKxXeU
---

First Semester of Msc. Games Technology in Game Programming we were given final assignement to make a game using the [Simple Render Engine](https://github.com/mortennobel/SimpleRenderEngineProject/) (SRE).
Our group deciced to create a basic Minecraft-clone, with the main interesting of working on a proper voxel data structure together with chunk manangement.

The final result is a simple game with the same mechanics as Minecraft: You can mine blocks and place them. We added some extra small functions like flying and added a few details for particle systems together with textures but the big thing is that we achived a stable 60FPS gameplay with 262,144 voxels loaded.

The primary big challanges was of course optimisation, mesh generation and getting the data structure right. But most of our lecturing had also been focused on 2D together with SRE being target towards 2D, so making a game in 3D graphics have of course added to the complexity. But also most of the engine supports [Box2D](box2d.org/) for physics. In our cases we implemented [Bullet Physics](http://bulletphysics.org/) which also added a layer of complexity due to none of us having experience with the tool and no lecture based on the library. The game can be found right below together with a technical report.

The project was made together with [Mads Engberg](http://www.itu.dk/people/engb/) and [Sven Santema](http://sven.whalefall.nl/).