## FreeCad part 1
[&larr;](index.html "back")

Note: I use the blender interface for freecad (as I’m using blender regularly). Just right-click in the main window and select navigation-style> blender (shown in the 2nd video).

| Functionality | Shortcut      |
| :------------- |:-------------|
| 3D rotation   |middle mouse botton + move the mouse |
| Move the view |shift + middel mouse button + move the mouse |
| Scale         |mouse wheel or ctrl + middle mouse button + move the mouse |


### 0. Get Freecad

Freecad provides appImages / binaries for Win / Mac / Linux. Just download and execute it. We will base this tutorial on the current stable release 0.18
<br>[Video – 0](https://youtu.be/aXOwi4yDWuY)

### 1. Getting started: prepare for body creation
We will open part design and create a sketch (which is a 2D drawing, allowing for constraints etc.) which will then be the basis for the 3D body
<br>[Video -1](https://youtu.be/uvMJVKm25mM)

### 2.  Sketch a square, using constraints, extrude to body
[Video -2](https://youtu.be/NsnNnIFMbkQ)

### 3. Adapt the geometry

[Video -3](https://youtu.be/oMFNh4hp3A8) shows how to use the underlying sketch (the constraints therein) to adapt the body geometry. This illustrates a basic design feature I like in freecad: all the steps build on oneanother (its like filters / adaptors applied in sequence). You can adapt almost all of them later on an the result will be adapted.

### 4. Making a pocket

You can easily match a sketch on a face of a 3d body, do some 2d design and use it as the basis of 3D body modification.
<br>[Video – 4](https://youtu.be/FBp4xR3D_J4)

### 5. Add an island

[Video – 5](https://youtu.be/SoJ363wfyG8)

### 6. Configure the path workbench, create the pocketing operation

[Video -6](https://youtu.be/1RDEcL7GOIQ)

### 7. Visualize and correct the finishing allowance
In the last video we generated the pocketing operation; checking the visualization we recognize that we had used the wrong sing for the finish allowance and correct it here
<br>[Video – 7](https://youtu.be/3qmyA0SOTy8)


### 8. Export gcode

[Video – 8](https://youtu.be/Hlzd1YXwUFM)

 
### Open points
+ check if we could have holding tabs generated: thanks to @edwardvmills: holding tabs are called ‘tags’ and are available as a ‘Dressup’ on an operation. tutorial tbd.
+ we use 5mm in z. add a short video to show how to use a plunge angle and smaller milling depth per pass
+ 3d milling

<br>
Feel free to dicuss your questions in the [related discussion thread](https://www.v1engineering.com/forum/topic/foss-milling-toolchain-freecad-gbrl-on-ramps-discussion/) 

[&larr;](index.html "back")