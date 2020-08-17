# Object parenting

In unity, objects follow a Hierarchy system. In this system, objects can become "parents" of other objects. Being a child of a object means your transforms will be relative to your parent.

For instance, the turret of a tank is always positioned on top of the tanks's main body. In this case the body of the tank is the parent and the turret is the child. This not only applies to position transforms, but also to scale.

# Creating a parent child relationship

We will use internal assets to demonstrate the parent child relationship between objects.

1. Right click project assets>create>sprites>square.

2. Right click project assets>create>sprites>triangle.

3. Now drag the square into the scene.

4. Drag the triangle onto the square.

The triangle is now the child of the square. Transforms on the triable are now relative to the square. Shift the triangle out of the square and then shift the square around. You'll observe that the triangle follows the square around.
