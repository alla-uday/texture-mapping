Assignment 3: Texture Mapping

Uday Shankar Alla

Implememnted all the requirements -
-Loaded two square images into texture maps. 

 - Applied entire first texture image onto each face of a cube (cube #1) that has dimensions 2x2x2. Filtering set to use nearest neighbor.  

- Created a second cube  with dimension 2x2x2 where the second texture image is applied to each face but is zoomed out by 50% . Enabled Mip Mapping for the zoomed texture using tri-linear filtering. 

- Positioned both cubes side by side within the view of your starting camera view – both cubes have dimensions of 2x2x2. Center of cube #1 positioned at (-4,0,0) and the center of cube #2 at (4,0,0). Horizontal FOV set to 50 degrees. ‘i’ and ‘o’  move the camera nearer or farther away, along the z-axis.

- the key ‘r’ starts and stops the rotation of both cubes. The cube #1 rotates around its Y-axis at a rate of 20 rpm. Cube #2  rotates around that cube’s X-axis at a rate of 30 rpm. 