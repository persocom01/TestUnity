# Creating a sprite

To create a sprite, Unity must be supplied with a **texture**. A sprite may be created in several ways.

1. Right clicking project assets>create>sprites.

2. Dragging a standard image into the assets region of Unity.

3. Downloading a free asset from: https://assetstore.unity.com/top-assets/top-free

In my case, I got https://assetstore.unity.com/packages/3d/characters/unity-chan-model-18705

Download and import the package into the project, then go to assets>unity-chan!>unity-chan! model>art>models and drag unitychan into the hierarchy.

## Modifying a sprite

On the top left of the interface are a bunch of buttons. The hand has already been introduced in 01_interface.md. Before starting, any changes can be undone using ctrl+z.

1. Move tool.
When in move tool mode, clicking an object will allow one to modify its position along the 3 axes. Simply click one of the axes and drag the object. Clicking on the box in the middle allows movement in a 2d plane.
2. Rotate tool.
By default, one can freely rotate the object like a ball. Clicking on the axis lines allows rotation along an axis.
3. Scale tool.
Lets you stretch an object along an axis. To size up the whole object, click the box in the middle.
4. Rect tool.
Often used on UI elements, it allows an element to be resized and rotated relative to a parent canvas, such as a large rectangle. If this parent is rescaled, the child element will be scaled with it.
