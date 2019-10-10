# Jump Higher

Author: Benjamin Huang

Design: A game where your character's animation sequence actually interacts with the world and affects gameplay.

Screen Shot:

![Screen Shot](screenshot.png)

How To Play:

I haven't got time this weekend to implement it, but the game would have run as such: a doodle-jump-esque game but in 3D-ish taking place around a central solid cylinder. The platforms spiral upwards around the cylinder. a human character controlled by the player has a number of poses - curling up into a ball, stretching out into a long narrow cylinder, and arms and legs spread in an X. For each of these, the collision meshes would be a sphere, cylinder and cuboid (with corners at limbs) respectively. However! It takes time to switch between the poses. As the character bounces up the platforms and off the solid cylinder, you can collide in a halfway pose - in which case the player mesh in the current animation is used for your collision instead, wrecking all sorts of (good) havoc.

Sources:

My idea, and doodle jump for inspiration.

This game was built with [NEST](NEST.md).
