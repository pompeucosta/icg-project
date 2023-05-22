# Simple adventure game
## ICG project
This is a small game for a university project (introdução à computação gráfica / introduction to computer graphics). Initially the idea was to be an adventure game however due to the lack of time and js skills, it turned out to be more of a fighting game.

## Assets
I do not own any of the assets used!

Below is a table with all the models (models include textures) and their source.

|               Model               |    Source   |                                           Additional Info                                           |
|:---------------------------------:|:-----------:|:---------------------------------------------------------------------------------------------------:|
|         Monster character         |    mixamo   |                                       character name is mutant                                      |
|          Human character          |    mixamo   |                                       character name is brute                                       |
|               House               | Unity store |          https://assetstore.unity.com/packages/3d/environments/fantasy/mushroom-house-61027         |
| Trees, Mushrooms and other plants | Unity store |       https://assetstore.unity.com/packages/3d/environments/hand-painted-nature-kit-lite-69220      |
|       House ground mushrooms      | Unity store | https://assetstore.unity.com/packages/3d/environments/landscapes/free-low-poly-nature-forest-205742 |
|             Mountains             | Unity store |   https://assetstore.unity.com/packages/3d/environments/landscapes/lowpoly-environment-pack-99479   |
|             Tiki torch            |  Sketchfab  |           https://sketchfab.com/3d-models/outdoor-torch-8f9ceeff9f264a2688e7280e0d379c3f            |

The ground is made of cubes with a texture.

Texture source: https://3dtextures.me/2020/08/28/grass-005/


All animations come from mixamo.

## Code
The whole code was written in javascript by me however I did some research and copied (and adapted) parts of code from some websites.

Below are links of sources that I used.

Three js related code: https://threejs.org/docs/index.html#manual/en/introduction/

Day/Night cycle: https://github.com/mrdoob/three.js/blob/master/examples/webgl_shaders_sky.html

Move in direction of the camera: https://stackoverflow.com/questions/38052621/moving-the-camera-in-the-direction-its-facing-with-threejs

Multiple views: https://github.com/mrdoob/three.js/blob/master/examples/webgl_multiple_views.html

Math to check if character is in front: https://stackoverflow.com/questions/71311304/three-js-check-if-position-is-behind-object (adapted to my case obviously)

For physics I used a js library called ammojs which is a port of a c++ physics library called bullet

Ammojs: https://github.com/kripken/ammo.js/

bullet: https://github.com/bulletphysics

For references about the physics I used the bullet documentation

Documentation: https://pybullet.org/Bullet/BulletFull/

## The game
The game is very simple.

It's a coop (2 player), split screen, game in which both players just fight.

There is no set in stone objective, just fight.

Below you can find an image of the game.

![Game image](./game.png "game image")


As for the controls, they might be a bit confused but it's what I came up with.

Below is a table with all the controls. You can also find them in game by clicking in the blue cogwheel in the top right.

|                    | Human | Monster     |
|:------------------:|:-----:|-------------|
| action             | key   | key         |
| move forward       | w     | arrow up    |
| attack             | q     | 0           |
| rotate camera up   | e     | page up     |
| rotate camera down | r     | page down   |
| rotate left        | a     | arrow left  |
| rotate right       | d     | arrow right |
