# Light Regions
Additional info for Light Regions.

### What is Light Regions?

Light Regions is a powerful optimization tool for real-time lights.

### How does it work?

There are two systems in Light Regions that can be used seperately or together.

### Baked Light Occlusion by region.
All of the lights inside of a region are ran through a ray-tracing test to calculate the visibility of other regions. This data is then stored in the region component and used to disable the other regions that are not in view.
This feature works best in large interiors but can be used for exteriors as well.

### Baked Light Influence
Each light that is managed by a region will have an optimized influence mesh generated. This mesh is used to switch between real-time shadows and static shadows.
This feature can make a big difference in more complex scenes with very detailed shadow geometry.
