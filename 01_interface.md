# Interface

The interface is split into 4 sections:
1. Main window in the center.
You may see the scene of the game here. Of note is the hand icon at the top left of the interface, which allows one to freely move around the scene by dragging the left mouse button without adjusting angle of view.
2. Object inspector on the right.
3. Scene hierarchy on the left.
It lists all objects in the currently open scene, as well as their parent-child relationships.
4. Project assets at the bottom.

# Camera

A new scene in unity will have a camera object called "Main Camera" by default. By selecting it, one may see the **viewport**, which is the area in which objects are visible to the camera.

# Objects

A scene is made out of objects, called **GameObjects** (for simplicity simply called objects hereafter). Objects have a set of components attached to them, which describe how they behave and react to others in the scene.

## Components

1. Transform.
The most important component, which determines the position, rotation and scale of the object.
2. Renderer.
Makes objects visible.
3. Collider.
Define collision boundaries for objects.
4. Rigidbody.
Gives an object real time physics properties.
5. Audio source.
Allows the object to store and play sound.
6. Audio listener.
Allows the object to hear audio and output it to the player's speakers. The main camera has this component by default.
7. Animator.
Allows access to animation system.
8. Light.
Makes and object a light source.
