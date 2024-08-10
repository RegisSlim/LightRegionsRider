# Light Regions
Additional info for Light Regions.

## What is Light Regions?

Light Regions is a powerful optimization tool for real-time lights.

## How does it work?

There are two systems in Light Regions that can be used seperately or together.

### Baked Light Occlusion by region.
All of the lights inside of a region are ran through a ray-tracing test to calculate the visibility of other regions.

### Baked Light Influence
Each light that is managed by a region will have an optimized influence mesh generated. This mesh is used to switch between real-time shadows and static shadows.

## What it can do:
It can provide some serious performance gains and enable you to utilize real-time lighting to a higher degree than before. I originally made this tool for a horror game we've been working on in HDRP and it simply can't run without it. It's a multiplayer game that takes place in a hotel with 30 rooms and an average of 3-4 lights per room. With Light Regions it becomes a playable scene by disabling all of those unseen lights all the while maintaining clear sight lines (Lights and all) from one end of the hotel to the other if need be. It was important to use real-time lighting because every light is on a switch and can be turned on and off by the players.

## What it can't do:
It will not auto-generate all of your regions. While the package offers tools to help you fit them quickly it still takes some manual placement. The auto-generator is in closed-beta and isn't yet stable enough for me to package but I assure you we are working on it.
Lights managed by Light Regions aren't intended to be moved, although in some cases it won't affect anything.

## What comes with your purchase?
Dedicated support, perfomance gains, and the satisfaction of helping a tiny (And oh so grateful) dev team along the way.
