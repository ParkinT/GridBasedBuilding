# GridBasedBuilding
### Fortnite Building Remake

This  should be a remake of the Fortnite Building System.
This Project is discontinued.


Short Introduction :

- This is still a Prototype
- Lots of the Code is not commented (trying to do this)

- Like the name said, it is based on a 3D Grid
- Each Grid Node stores some information
   - Like Neighbors which I split into __Static__ and __Dynamic__ Neighbors
     - __Static__ Neighbors is the Neighbor in World Position so it is always the same
     - __Dynamic__ Neighbors is based on the rotation/direction of the custom Gizmo
- Simple Terrain/Ground Collision Check


I did not find a good way to solve the tons of conditions which are needed for the Wall, Ramp, Floor Placement.
Also for the chain destruction I considered saving all required Neighbors which was the wrong way of doing it.

Take a look in the `GridNode.cs` for more Information :D have fun to see some horror code

About the GridNode Recognition; it uses cardinal points mixing Y and Z Axis Rotation.

If you want to modify the KeyPress(es) used look at `BuildHandler`, in the Inspector and open __Buildable Object__.  In each item (e.g. Floor, Ramp, Wall) you will see the __Input Key__ selection.

Have Fun =D

https://youtu.be/KEdmQQ63Uto
